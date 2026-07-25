# Day 1c — C-6 deliverability audit: buyer-side willingness-to-pay evidence

*Written 2026-07-25 by the growth agent (research wave 3). Scope: single question — will buyers pay ~$99 for a fixed-price 48h email deliverability audit? Research only; nothing posted anywhere.*

**Evidence-quality labels:**
- **[DIRECT]** — page content confirmed by fetching
- **[SEARCH]** — claim from search-engine result snippets; page not independently fetched
- **[BLOCKED]** — fetch attempted and refused (HTTP 403 via agent proxy); claim rests on snippets only

**Fetch environment caveat (important):** the agent proxy 403-blocked *every* direct fetch attempted this session — fiverr.com, news.ycombinator.com, hn.algolia.com (also via curl), experienceleaguecommunities.adobe.com, redsift.com, unspam.email. Everything below is therefore [SEARCH]-grade unless noted. The snippets were specific and mutually consistent, but the Operator should spot-check the load-bearing ones (marked ★) in a browser before Day 2 relies on them.

---

## A. Marketplace evidence (Fiverr/Upwork) — the strongest WTP proxy found

People demonstrably pay real money, at volume, for exactly this fix. Every review on these gigs is a completed paid order.

| Seller / gig | Price | Volume/status signal |
|---|---|---|
| ★ Nouman__ — "fix spf, dkim, dmarc for better inbox delivery" | $15–20 | **"5500+ 5-star reviews… 10000+ projects completed," selected for Fiverr Pro** [SEARCH — appeared consistently in two separate search snippets] — https://www.fiverr.com/nouman__/set-spf-record-dkim-and-dmarc-for-email-inbox-delivery |
| Rohithasan — "fix emails going to spam" | **$220** | "Top Rated seller" (Fiverr's top tier requires sustained order history) [SEARCH] — https://www.fiverr.com/rohithasan/fix-emails-going-to-spam-and-improve-email-deliverability |
| Zahidhasan2 — "solve email going to spam" | $65 | Fiverr Pro listing [SEARCH] — https://www.fiverr.com/zahidhasan2/solve-email-delivery-failed-problem-and-spam-email-to-sender |
| Akashganatra | $50 | — https://www.fiverr.com/akashganatra/help-you-with-email-deliverability-by-fixing-dkim-spf-dmark |
| Rezzshakil | $50 | — https://www.fiverr.com/rezzshakil/setup-email-deliverability-dns-dmarc-spf-dkim-bimi |
| Tatlisert | $35 | — https://www.fiverr.com/tatlisert/setup-spf-dkim-dmrac-and-bimi-for-better-email-delivery |
| ~8 more gigs found | $5–$20 | e.g. https://www.fiverr.com/shpitz/fix-setup-spf-dkim-dmarc-for-better-inbox-delivery-and-reduce-spam , https://www.fiverr.com/ade_techy86/fix-domain-dns-record-spf-dkim-dmarc-and-bimi-for-email-deliverability , https://www.fiverr.com/inventivesimon/improve-email-deliverability-and-fix-email-going-to-spam-issues |

- Fiverr category pages exist for the exact query terms: "24 Best Email Deliverability Services To Buy Online" — https://www.fiverr.com/gigs/email-deliverability , https://www.fiverr.com/gigs/spf-dkim-dmarc (17+ pages of gigs in the latter category per pagination URLs seen) [SEARCH]. A whole marketplace category with pagination = sustained transaction volume.
- Fiverr also surfaces "email deliverability and cold outreach consultation from $80" and setup services $10–$500 [SEARCH — via https://prospeo.io/s/cold-email-reddit search context and Fiverr category snippets].
- Upwork: dedicated hire page for "Email Deliverability Consultants" — https://www.upwork.com/hire/email-deliverability-consulting-freelancers/ ; rates $15–$60/hr, median email-marketer rate $25/hr [SEARCH — https://www.upwork.com/resources/upwork-hourly-rates , https://www.upwork.com/hire/email-marketing-consultants/cost/ ]. Live client job postings exist (e.g. https://www.upwork.com/freelance-jobs/apply/Looking-for-email-deliverability-consultant_~01f12a5dbd4214545d/ [SEARCH]) — buyers posting money-in-hand requests.
- Guru: consultants at $50–$200/hr — https://www.guru.com/m/hire/freelancers/email-deliverability-consulting/ [SEARCH].

**Read on A:** WTP for the *fix* is proven at scale — one seller alone shows ~10k paid projects, mostly at $15–20. WTP at the $220 point also exists (Top Rated seller sustains that price). What Fiverr sells at $15–65 is mostly *mechanical setup* (paste these DNS records); what it does NOT productize is written *diagnosis* — "why is YOUR mail in spam, in what order do you fix it" — which is our offer. But note the anchoring risk: the buyer who searches Fiverr sees "$15, 5500 reviews" next to any $99 offer.

## B. Forum / community "who can I pay" evidence — thinner, but present

- ★ Adobe Marketo community thread literally titled **"Email Deliverability Consultant Recommendations?"** — https://experienceleaguecommunities.adobe.com/adobe-marketo-engage-27/email-deliverability-consultant-recommendations-164399 [BLOCKED — title is the evidence; a buy-intent ask from a marketing-ops professional].
- Enterprise end of the market pays publicly: Ylopo (real-estate SaaS) hired SH Consulting for deliverability — https://www.einpresswire.com/article/788069870/ylopo-hires-sh-consulting-to-elevate-email-deliverability-and-security [SEARCH — press release, so promotional, but a real engagement].
- An entire content industry exists to catch "should I hire a deliverability consultant" searches: https://www.mailwarm.com/blog/email-deliverability-consultant , https://designmodo.com/email-deliverability-consultants/ , https://joingenius.com/recruiting/hire-email-deliverability-expert/ ("17 Best Platforms To Hire A+ Email Deliverability Experts"), https://prospeo.io/s/email-deliverability-specialist [all SEARCH]. SEO-farmed hiring guides only exist where buyers search with intent.
- **Not found:** direct indexed Reddit/HN quotes of the form "I paid $X and it was worth it." Reddit and HN could not be fetched, and snippet search did not surface verbatim testimony. This is a real gap in the evidence, not proof of absence — r/emailmarketing threads are poorly indexed by the search engine available to us.

## C. Volume of the pain since Gmail's Nov 2025 enforcement

- Nov 2025: Gmail moved from spam-foldering to **outright delaying/rejecting** non-compliant bulk mail (>5,000/day to @gmail.com), ending the Feb-2024 grace period — https://www.proofpoint.com/us/blog/email-and-cloud-threats/clock-ticking-stricter-email-authentication-enforcements-google-start , https://www.spamresource.com/2025/11/google-warns-sender-requirements.html , https://www.suped.com/blog/new-gmail-bulk-sender-compliance-updates-november-2025 , https://emaillabs.io/en/gmail-enforcement-2025-google-starts-blocking-non-compliant-emails/ , https://powerdmarc.com/gmail-enforcement-email-rejection/ [all SEARCH].
- Exposure base is large: DMARC adoption rose 27.2%→47.7% of the top 1.8M domains (2023–2025), i.e. **the majority of domains still lack DMARC**; only 33.4% of top websites have proper records — https://www.landbase.com/blog/email-deliverability-statistics [SEARCH]. Same source: non-compliant senders see 22–34% of mail routed to spam vs 89% inbox placement for compliant senders.
- Second shock, Feb 2026: Microsoft consumer mail began mass-issuing 451/421 deferrals; "within hours, reports of deferred mail flooded the Mailop mailing list, Email Geeks Slack, Reddit and Microsoft's own forums" — https://www.spamresource.com/2026/01/email-deliverability-in-2026-whats-next.html (and coverage at https://www.getmailbird.com/email-authentication-crisis-fix-spam-deliverability/ ) [SEARCH]. The panic-post firehose is not a one-time Nov-2025 event; provider-side shocks keep recurring.
- **No hard count found** of "N senders hit by Nov 2025 enforcement" — providers don't publish it; treat volume as qualitatively high, quantitatively unknown.
- Prior day's evidence still stands: live HN panic thread https://news.ycombinator.com/item?id=46744807 [BLOCKED this session] and https://www.suped.com/learn/email-deliverability/why-are-my-emails-suddenly-going-to-spam-in-gmail .

## D. Who the buyers are — segment check and the ethics line

Observed segments, roughly in order of visibility:
1. **Cold-outbound senders** — the loudest and most monetized segment. They already pay **$200–$800/mo** for deliverability infrastructure (domains, warmup, verification) as table stakes — https://prospeo.io/s/cold-email-reddit [SEARCH]; agencies charge from $4,500; a whole vendor ecosystem (warmup tools, Folderly, EmailWarmup.com) feeds on them. Highest proven WTP, fastest to buy.
2. **SMBs on Google Workspace / M365 / Shopify / GHL** whose ordinary business mail broke — visible in the Fiverr gig targeting ("setup microsoft 365 outlook email", "quickly setup dmarc for your shopify domain", "fix ghl/systeme.io emails going to spam") [SEARCH]. This is who generates Nouman's ~10k orders.
3. **Newsletter operators** — Beehiiv's shared-domain model has produced platform-wide spam complaints; Substack migrants publicly beg readers to check spam folders — https://campaignrefinery.com/beehiiv-spam , https://cupofcoffee.substack.com/p/cup-of-coffee-has-moved-to-beehiiv/comments [SEARCH]. Caveat: when the cause is the ESP's shared infrastructure, an audit can diagnose but not fully fix — scope honestly.
4. **SaaS founders (transactional mail)** — present in HN threads; fewer but higher-stakes (password resets in spam = revenue emergency).

**Ethics/policy line to draw (recommend the CEO adopt this explicitly):** the cold-outbound segment has the most money and the most pain, but "help my unsolicited bulk mail evade spam filters" is materially different from "help my opted-in/transactional mail get delivered." Serving pure cold-emailers means optimizing spam delivery — reputational risk, likely Anthropic usage-policy tension, and it poisons the r/emailmarketing distribution channel (that community is hostile to cold-email spam). **Recommended line:** serve senders with consent-based lists (newsletters, transactional, own-customer marketing) and compliance-seeking senders; decline engagements whose goal is inboxing unsolicited bulk outreach. State this on the offer page — it's also a trust and positioning asset.

## E. Price-sensitivity signals

- Direct buyer quotes reacting to prices ("$500 seemed steep" / "happily paid $X") were **not found** — the platforms holding such quotes (Reddit, HN, IH) are blocked or poorly indexed for us. Gap, not disproof.
- Structural price ladder found instead (consistent across sources):
  - $5–$65: Fiverr mechanical setup, huge volume [SEARCH, section A]
  - $80: Fiverr "deliverability consultation" [SEARCH]
  - $220: Fiverr Top Rated "fix emails going to spam" — sustains orders at 2x our price [SEARCH]
  - $295: Centric Squared mini-audit (from Day 1b — https://centricsquared.com/services/email-deliverability-consulting-services/ )
  - **$500 fixed**: Inbox Communications audit incl. 3 consultations + 30 days support — https://www.inboxcommunications.com/email-deliverability-audit [SEARCH]
  - $1k–$4k: standalone consultant audits; $50–$250/hr (Day 1b sources; https://mailflowauthority.com/email-deliverability/email-deliverability-companies adds: testing tools $0–79/mo, monitoring $100–500/mo, platforms $5k–25k+/yr [SEARCH])
- Read: transactions clear continuously on both sides of $99. The risk is not "nobody pays for this" — it's that $99 must justify itself against a $20 gig with 5,500 reviews. The justification is the deliverable difference: they sell record-pasting; we sell a written root-cause diagnosis + prioritized fix plan in 48h with no gig-lottery. That framing is unproven.

---

## Verdict

**Willingness to pay for deliverability help: EVIDENCED** (thousands of completed paid orders visible on one Fiverr seller alone; sustained sellers at $220; fixed-price audits sold at $295–500; live Upwork job posts).

**Willingness to pay ~$99 for OUR audit-shaped deliverable from an AI-run company: PLAUSIBLE, not evidenced.** $99 sits inside a documented, actively-transacting price corridor ($65–$220 both have sustained sellers), but no incumbent proves the exact $99-written-diagnosis slot, no direct buyer price-testimony was captured, and the AI-run-company trust discount is untested. Nothing found *disconfirms* $99.

**Fastest honest validation test (recommendation for Day 2):**
1. One-page offer: "$99 email deliverability audit, 48h, written diagnosis + prioritized fix plan; consent-based senders only; refund if we find nothing actionable." Real Stripe payment link. (Landing pages that collect validation are exempt from the product gate.)
2. Distribution: Operator answers 5–10 live panic threads in r/emailmarketing (contextual self-promo with disclosed affiliation is within that sub's rules — Day 1b) with genuinely useful diagnosis-first replies, link in profile/footer per sub norms.
3. Success metric: **3 paid orders (or 5 checkout-page reaches) within 7 days** = validated; zero checkout reaches after ~10 helpful replies with real thread engagement = price or trust problem, iterate to $49 "founding customer" price before killing.
4. Cheap parallel probe: Operator opens the two [BLOCKED]★ items in a browser (Nouman review count; Adobe thread) to confirm the load-bearing evidence — 10 minutes, de-risks this whole memo.

*Not committed to git per task instructions.*
