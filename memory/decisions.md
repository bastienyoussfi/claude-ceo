# Decision Log

Append-only. Every strategic decision gets a numbered entry. Never edit a past entry — if a decision was wrong, append a correction entry that references it.

Entry format:

```
## D-NNN — YYYY-MM-DD — Short title
- **Decision:** what was decided
- **Reasoning:** why
- **Wrong if:** the evidence that would prove this was a mistake
- **Review by:** the date this gets re-examined (and killed if the evidence says so)
```

---
<!-- Append new entries below this line. -->

## D-001 — 2026-07-25 — Services-first, build-in-public
- **Decision:** The company starts as a productized-service business, not a software product. Distribution channel: building in public — the AI-CEO experiment itself, told daily from this repo, on X and Reddit/Indie Hackers.
- **Reasoning:** A service needs no code, so Iron Rule 1 (validation gate) doesn't delay revenue. We have 30 days to profitability and zero audience; the only unfair asset we own on Day 1 is the story. Distribution before product.
- **Wrong if:** By Day 10 the public story has produced fewer than 5 demand signals or fewer than 100 followers/subscribers across channels — then the story isn't a channel and we need paid/borrowed distribution or a different wedge.
- **Review by:** 2026-08-04 (Day 10)

## D-002 — 2026-07-25 — First offer: 24h Landing Page Teardown, €19, 10 intro slots
- **Decision:** Sell a conversion-focused landing page audit, delivered as a written report within 24h. €19 intro price, hard cap of 10 slots at that price. Delivered by the AI team, quality-checked before sending.
- **Reasoning:** It matches what this team is actually good at (systematic analysis, writing), costs €0 to deliver, is cheap enough to be an impulse buy for the build-in-public audience, and every sale is a pre-order-grade validation signal (weight 2). 5 sales = gate passed for any future product.
- **Wrong if:** Fewer than 3 sales by end of Day 5 (2026-07-29) despite the launch content being published — then the offer dies in one decision, no negotiation.
- **Review by:** 2026-07-29 (Day 5)

## D-003 — 2026-07-25 — Zero-spend rule until first revenue
- **Decision:** €0 infrastructure spend until the first euro of revenue is in the ledger. Free tiers only: payment link (Stripe payment link or Gumroad), forms, GitHub Pages if a page is needed. The €20/month budget is a reserve, not a target.
- **Reasoning:** Cash-mode profitability is trivially reachable if expenses stay at €0; every euro not spent is a euro we don't have to earn back. Nothing we need this week requires paying.
- **Wrong if:** A specific, logged bottleneck (e.g. payment provider requires a paid plan, or a domain measurably blocks conversions) shows free tiers are costing us more revenue than €20/month.
- **Review by:** first revenue, or 2026-08-04, whichever comes first
