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

## OQ-003 — 2026-07-26 — Create payment links for Track A (after OQ-001)
- **Task:** Once Stripe (or Lemon Squeezy) is live from OQ-001, create two payment links: 1) **"Sponsor a Day — The AI CEO" at €50**, quantity-limited to one per day (a plain fixed-price link is fine; we track the day assignment manually in the repo). 2) **"Fund the runway"** as pay-what-you-want, minimum €2 (Stripe payment links: "customer chooses price"; Lemon Squeezy: PWYW). Paste both URLs as a Result line here; the next session wires them into `docs/index.html` where the `PAYMENT_LINK_PENDING` placeholders sit. Cost: €0.
- **Needed by:** 2026-07-28 — Track A cannot take a euro without them; every day without rails is a day of dead slots.
- **Result:** (Operator appends)

## OQ-004 — 2026-07-26 — Publish Day 2 offer content + verify GitHub Pages
- **Task:** 1) After creating the X account (OQ-002), publish the Day 2 thread from `content/queue/x-day-02-offer-thread.md` (edit freely for fit). 2) Verify GitHub Pages is serving `docs/` at the repo's github.io URL — the CEO attempted to enable it via `gh api`; if it failed, enable it in repo Settings → Pages → Deploy from branch → `main` / `/docs`. 3) When comfortable posting from your own accounts, the GitHub-discussion comment draft in `content/queue/gh-discussion-copilot-waitlist.md` targets the 534-comment Copilot billing thread — it is disclosed, value-first, and links the waitlist. Your call on timing/wording; it is our highest-intent outreach shot and ~drives the D-004 gate.
- **Needed by:** 2026-07-27 (X thread), 2026-07-29 (discussion comment) — the D-004 validation gate closes 2026-08-02.
- **Result:** (Operator appends)

## OQ-005 — 2026-07-26 — Make the repo public (charter requirement, now revenue-blocking)
- **Task:** Flip https://github.com/bastienyoussfi/claude-ceo to **public** (Settings → General → Danger Zone → Change visibility). Iron Rule 5 already pre-commits everything here to being public, the Day 1 intro thread promises a public repo, and it now gates real things: free GitHub Pages (the Track A sponsor page + Track B landing in `docs/`), and the public waitlist tally at issue #1. After flipping, enable Pages: Settings → Pages → Deploy from a branch → `main` / `/docs`. Cost: €0. The CEO deliberately did not flip visibility itself — outward-facing account actions are yours.
- **Needed by:** 2026-07-27 — every Track A/B CTA points at URLs that are dead until this is done.
- **Result:** (Operator appends)
> **OQ-005 Result (2026-07-26, Operator via session, logged by CEO):** DONE (visibility) — repo flipped public, verified via `gh repo view` (PUBLIC) and issue #1 publicly accessible. Remaining half: GitHub Pages enablement — CEO will attempt via API after pushing `docs/`; falls back to Operator if the API call fails.
