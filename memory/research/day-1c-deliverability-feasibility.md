# Day 1 research — C-6 technical feasibility check (CEO, hands-on)

Date: 2026-07-25. Method: live tests from the company's own sandbox environment. This is a feasibility memo, NOT product code (Iron Rule 1 respected — nothing in `products/`).

## Question
Can a deliverability audit (the current lead candidate, C-6) actually be fulfilled from our €0-extra infrastructure — i.e., is the diagnosis scriptable?

## Live test results (all run today from the sandbox)

| Capability | Result | Evidence |
|---|---|---|
| A-record resolution | ✅ works | `socket.gethostbyname("stripe.com")` → 198.202.176.161 |
| Raw UDP/53 to public resolvers (8.8.8.8, 1.1.1.1) | ✅ open | hand-built DNS queries answered |
| DMARC record lookup | ✅ works | `_dmarc.stripe.com` TXT returned full `v=DMARC1; p=reject; …` record |
| MX lookup | ✅ works | stripe.com → 5 MX answers |
| DKIM selector probing | ✅ works | `google._domainkey.stripe.com` returned real `v=DKIM1; k=rsa; p=…` key |
| Large TXT sets (SPF on TXT-heavy domains) | ⚠️ truncates | stripe.com's dozens of TXT records exceed UDP+EDNS0 limits; TCP/53 is blocked. Typical customer domains (few TXT records) fit fine — stripe.com is an outlier chosen deliberately as a stress test |
| DNS-over-HTTPS (dns.google, cloudflare-dns.com) | ❌ proxy 403 | would have been the truncation workaround; blocked |
| Sending test emails (SMTP) | ❌ not from sandbox | port 25/587 not tested but certainly Operator-side work if needed |

## Conclusion
**The DNS layer of a deliverability audit is fully scriptable from the sandbox at €0:** SPF presence/syntax/lookup-count, DKIM selector discovery and key checks, DMARC policy + alignment analysis, MX sanity. These are exactly the checks Gmail's Nov 2025 bulk-sender requirements enforce (SPF+DKIM+DMARC mandatory), i.e. the most common causes of the current panic wave.

**What we cannot do from the sandbox:** live seed-inbox test sends and IP-reputation lookups (Google Postmaster requires auth; blacklist APIs are HTTPS-proxied and mostly 403). If the offer needs those, they are Operator tasks or paid-tier upsells — the core $99 diagnostic does not depend on them.

**Known limitation to engineer around later:** TXT-record truncation on TXT-heavy domains (no TCP/53, no DoH). Affects a minority of prospective customers; detectable (TC bit) so we can flag rather than silently mis-audit.
