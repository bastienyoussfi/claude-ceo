# Operator Queue

Tasks only the human Operator (Bastien) can do: accounts, payments, KYC, phone verification, publishing. The CEO appends tasks with exact instructions and never blocks a day waiting on them. The Operator appends a result line under a task when it's done — tasks are never deleted.

Task format:

```
## OQ-NNN — YYYY-MM-DD — Short title
- **Task:** exact instructions
- **Needed by:** date, and what it unblocks
- **Result:** (Operator appends: done/blocked, date, outcome, links)
```

---
<!-- Append new tasks below this line. -->

## OQ-001 — 2026-07-25 — Payment rails ready before the offer exists
- **Task:** Create accounts on BOTH (1) **Gumroad** and (2) **Lemon Squeezy** (or Polar if Lemon Squeezy KYC stalls). Both are merchant-of-record platforms: they handle EU VAT and don't require a registered company, which fits our constraints. Complete any identity/KYC verification immediately — that's the part with lead time. Do NOT create any product listing yet; the offer doesn't exist until Day 2 at the earliest. Also confirm: does either platform charge a fixed monthly fee (would hit our €20/month budget), or only per-sale fees? Append what you find as the Result.
- **Needed by:** 2026-07-27 (Day 3) — unblocks charging the first euro as soon as the Day 2 offer decision lands.
- **Result:** (Operator appends)

## OQ-002 — 2026-07-25 — Browser research the sandbox can't do
- **Task:** Three quick items needing a real browser (the sandbox proxy blocks Reddit, HN, hn.algolia.com, and most direct page loads):
  1. Open https://news.ycombinator.com/item?id=48045237 ("tasks you'd pay $10–20/mo to automate") and paste the 5–10 most concrete "I'd pay for X" comments into a Result line here — it's a live pool of stated willingness-to-pay.
  2. Spot-check that the top-3 candidate evidence links in `memory/research/candidates.md` (C-1, C-2, C-3) actually say what we claim — one line each: "checks out" or what's off.
  3. Optional, unlocks deeper research: connect a (free) TrustMRR account / API key to the TrustMRR MCP connector so the CEO can run authenticated queries on verified-revenue startups by category.
- **Needed by:** 2026-07-26 morning (Day 2) — feeds directly into the offer decision.
- **Result:** (Operator appends)

## OQ-003 — 2026-07-25 — Wave-3 browser verifications (10 min total)
- **Task:** All wave-3 numbers are search-snippet grade (proxy blocked direct page loads). Verify in a browser, one line each in Result:
  1. Fiverr seller "nouman__" email-deliverability gig: is the ~5,500 five-star reviews / $15–20 price real? (Strongest WTP anchor for C-6 — highest priority.)
  2. Centric Squared $295 / Inbox Communications $500 fixed deliverability audits still live at those prices?
  3. Only if C-4/C-1 get reconsidered: thinsky.com/saq3 $399 flat questionnaire service; Quilt free tier; the "€10 AI roast sold zero" IH claim.
- **Needed by:** 2026-07-26 (Day 2 session) — the offer decision leans on item 1–2.
- **Result:** (Operator appends)
