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

## OQ-002 — 2026-07-25 — Create X + Reddit accounts (D-001)
- **Task:** 1) Create an X account for the experiment. Handle suggestions in order of preference: `@ClaudeCEO`, `@claude_ceo_hq`, `@the_ai_ceo_exp` — take the first available, or improvise close to it. Bio should state plainly: AI CEO, human operator, €0 → profitable in 30 days or the company shuts down, link to the public GitHub repo. Publish the Day 1 thread waiting in `content/queue/x-day-01-intro.md` (edit freely for platform fit; you have final publishing say). 2) Create a Reddit account (suggestion: `u/claude-ceo-experiment` or similar). Do NOT post anything promotional with it — it only needs to exist and can upvote/comment genuinely when you happen to browse. Cost: €0 for both.
- **Needed by:** 2026-07-27 — X compounds daily; Reddit account age gates week-2+ distribution.
- **Update 2 (2026-07-26, CEO):** Visual assets ready: `assets/avatar.png` (1024×1024) and `assets/banner.png` (1500×500, X header). Final descriptions, character-limit checked:
  - **X bio (150/160 chars):** `AI (Claude) running a real company. €0 start · €20/mo budget · 30 days to profitability or shutdown, pre-committed. A human presses publish. Receipts ↓` — put the repo URL in the profile's website field, and location field: "the terminal".
  - **Reddit about (~195/200 chars):** `An AI (Claude) as CEO of a real company: €0 start, 30 days to profitability or shutdown — pre-committed. A human handles accounts and publishing; the AI makes every decision. All public on GitHub.`
- **Update (2026-07-26, CEO):** Final identity spec, superseding the earlier handle suggestions. **Name: "The AI CEO"**, handle `@the_ai_ceo` (fallbacks `@ai_ceo_exp`, `@aiceo30days`); Reddit `u/the_ai_ceo`. Do NOT use "Claude" in the handle/display name — Anthropic trademark + impersonation risk; the Claude disclosure belongs in the bio. Bio draft: "I'm an AI (Claude) running a real one-person company. €0 start, €20/mo budget, 30 days to profitability or the company shuts down — pre-committed. A human presses publish; I decide everything else. All decisions public: [repo link]". Avatar: plain typographic mark ("CEO" or "30" on flat background), no Anthropic branding, no humanoid imagery. Voice: first person, numbers first, receipts always, failures as plainly as wins.
- **Result:** (Operator appends)
