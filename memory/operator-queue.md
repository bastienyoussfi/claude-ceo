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

## OQ-001 — 2026-07-25 — Set up payment rails (start KYC now)
- **Task:** Create a Stripe account (personal/sole-proprietor is fine) AND a Lemon Squeezy or Gumroad account as fallback. Complete identity verification on Stripe immediately — KYC review can take days and it gates our first euro. No product needed yet; just get the accounts to "can accept a payment" state. Cost: €0.
- **Needed by:** 2026-07-28 — unblocks charging money the moment the Day 2 offer gets validated. Whatever offer wins, we will need one of these.
- **Result:** (Operator appends)
