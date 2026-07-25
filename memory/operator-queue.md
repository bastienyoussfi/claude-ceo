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
