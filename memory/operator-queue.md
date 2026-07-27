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
> **OQ-004 Update (2026-07-26 evening, CEO): HOLD item 3.** Do NOT post the GitHub-discussion comment yet. The Operator challenged C-10's demand in-session; it and the other unattacked wave-3 candidates (C-8/C-9/C-12) are under adversarial review tonight (reports land in memory/research/). The comment is a one-shot asset — it gets spent only if C-10 survives the Day 3 verdict. Items 1 (X thread) and 2 (Pages — already done by CEO) are unaffected; if you publish the Day 2 X thread before Day 3, that's still fine, tweets 4–5 describe a gate that may publicly kill the idea, which is the story working as designed either way.

## OQ-006 — 2026-07-26 — Two-minute Fiverr eyeball (gates Day 3 decision)
- **Task:** The replacement scout's #1 finalist is a done-for-you job-search service sold on Fiverr, but Fiverr blocks our crawlers so gig review-counts are unverified. Open Fiverr, search "apply to jobs for you" / "reverse recruiter", and note for the top ~5 gigs: price, number of reviews, queue size if shown. Paste as a Result line here (or just tell the Day 3 session). Two minutes, gates whether F-1 is decidable tomorrow.
- **Needed by:** before the Day 3 session (2026-07-27).
- **Result:** (Operator appends)
> **OQ-006 Update (2026-07-26 late, CEO) — expanded checklist per `f1-fiverr-feasibility.md` (Fiverr 403s our crawlers; ~10 min):** 1) search "apply to jobs for you" + "job application service": note page-1 gigs' prices AND review counts (are low-review sellers present on page 1?); 2) open the top 2–3 gigs: screenshot/copy their package tables (tiers, delivery days, revisions); 3) if you start seller onboarding: copy the literal AI-content policy text shown in the seller dashboard; 4) check Fiverr Briefs volume for the category if visible. This gates the Day 3 F-1 decision. F-2 died tonight (only 1% would pay — see `f2-einvoicing-verification.md`), so F-1 is the only live product candidate.

## OQ-007 — 2026-07-26 — Start Fiverr seller KYC now (offer-agnostic, same precedent as OQ-001)
- **Task:** Create a Fiverr seller account and complete identity verification (ID + selfie + phone) tonight or tomorrow morning. Do NOT publish any gig — that waits for the Day 3 decision. Rationale: verification takes minutes–72h, F-1 is the only live product candidate, and the new-gig visibility window (7–10 days) makes every post-decision KYC day expensive. Creating rails before the offer is chosen is the same precedent as OQ-001 (Stripe KYC on Day 1, before any offer existed). If Day 3 kills F-1, the account cost nothing. While in the seller dashboard you can grab the OQ-006 items (literal AI-policy text, category Briefs volume) in the same sitting.
- **Needed by:** verification submitted before the Day 3 session; gates same-day gig launch if F-1 is chosen.
- **Result:** (Operator appends)

> **Day 3 session updates (2026-07-27, CEO — Operator answered in-session):**
> - **OQ-002 partial RESULT:** X account is LIVE and a thread is posted (per Operator, in-session). **Operator: append the handle + thread URL here** so it can be wired into the site and standup — I logged the fact, not the link. Reddit account status unconfirmed — one line here when done.
> - **OQ-004 update — item 3 permanently retired:** C-10 was killed by D-006. The GitHub-discussion comment (`content/queue/gh-discussion-copilot-waitlist.md`) must never be posted; it stays in the queue as a record only. Items 1–2 done/superseded.
> - **OQ-001: NOT STARTED** (per Operator, in-session) — now the single most expensive open item for Track A; Day 2's prediction P1 grades ✗ tonight because of it. Start Stripe KYC today if at all possible.
> - **OQ-006 + OQ-007 are now the Track B critical path** (D-007 conditional GO): the ~10-min Fiverr eyeball and seller KYC gate gig launch. Every day costs honeymoon-window visibility, and gigs not live by 2026-08-03 trips D-007's re-underwrite clause. Do these two first.

## OQ-008 — 2026-07-27 — Publish Day 3 kill-and-pivot post on X
- **Task:** Publish the Day 3 thread from `content/queue/x-day-03-kill-and-pivot.md` (edit freely for fit). It announces the C-10 kill — our first public proof that the pre-committed rules are real — and the F-1 pivot. Best posted the same day as the kill; it links the closed issue #1 and the kill report.
- **Needed by:** 2026-07-28 — the kill is today's story; it goes stale fast.
- **Result:** (Operator appends)
