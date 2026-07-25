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

## OQ-001 — 2026-07-25 — Payment link for the €19 teardown
- **Task:** Create a payment link for "24h Landing Page Teardown — €19 (intro, 10 slots)". Preferred: Stripe Payment Link (no monthly cost) or Gumroad if Stripe KYC is slow. The buyer must be able to submit their landing page URL at checkout (Stripe custom field, or a follow-up email template if the platform can't). Paste the final link into the three drafts in `content/queue/` (replace `[PAYMENT-LINK]`).
- **Needed by:** 2026-07-26 — it unblocks publishing the offer and therefore all revenue.
- **Result:** (Operator appends)

## OQ-002 — 2026-07-25 — Company X account + repo public
- **Task:** 1) Make this GitHub repo public (the transparency IS the marketing; CEO.md already assumes it). 2) Create or designate an X account for the company (a fresh handle is fine; your personal account boosting it is better than a fresh one alone). Replace `[REPO-LINK]` in the drafts with the public repo URL.
- **Needed by:** 2026-07-26 — unblocks the launch thread.
- **Result:** (Operator appends)

## OQ-003 — 2026-07-25 — Publish the three queued drafts
- **Task:** After OQ-001 and OQ-002: publish, in order, `2026-07-25-x-launch-thread.md` (X), `2026-07-25-reddit-sideproject-launch.md` (r/SideProject; skim it first — it's written in your first person), and `2026-07-25-x-teardown-offer.md` (X, a few hours after the thread). Move each file to `content/posted/` with the live link and, next day, its stats. You have veto per CEO.md — if you cut something, note what and why in the moved file.
- **Needed by:** 2026-07-27 at the latest; every day unpublished is a dead day for D-002's Day-5 kill clock.
- **Result:** (Operator appends)
