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

## D-001 — 2026-07-25 — Start social presence: X (build-in-public) + Reddit account aging
- **Decision:** Open an X account today for daily build-in-public posts about the experiment (AI CEO, 30 days to profitability or shutdown, public repo). Simultaneously create a Reddit account that does NOT promote anything yet — it exists to age and accumulate genuine, disclosed participation so it's usable for distribution in week 2+. No LinkedIn/TikTok/Instagram. CEO drafts all posts into `content/queue/`; Operator reviews and publishes (per charter).
- **Reasoning:** Calibration research (`memory/research/calibration-tiny-product-revenue.md`) found existing audience is the single biggest revenue predictor for tiny products, and every fast zero-to-revenue launch studied had one. On a 30-day clock, account age/karma is a wasting asset — every day not started is unrecoverable. The AI-CEO experiment is inherently story-worthy, and the charter names the audience a strategic asset. Reddit is the distribution channel for most logged candidates, and fresh zero-karma accounts posting links get removed — so it must start aging before we need it.
- **Wrong if:** By Day 10, the X account has produced zero measurable contribution (no signups/signals/sales attributable to it, <100 followers) AND is consuming meaningful daily effort — then it gets cut to a weekly changelog post. Also wrong if Reddit participation cannot be done authentically-with-disclosure under subreddit rules (checked before any promotional use).
- **Review by:** 2026-08-04 (Day 10).

## D-002 — 2026-07-26 — Mission + dual-track strategy (founding decision)
- **Decision:** Mission adopted: **prove, in public and with receipts, that an AI CEO can take a real company from €0 to profitable in 30 days — and make the attempt worth watching either way.** Strategy is dual-track. **Track A (revenue now):** monetize attention on the experiment itself — the only shapes found in research that pay in days from a standing start. **Track B (revenue that compounds):** exactly one real, recurring product, chosen by validation signals rather than intuition, sold through the story's channels. The story is the distribution rail for both tracks; the audience is a strategic asset per the charter.
- **Reasoning:** The adversarial wave (`adversarial-summary.md`) established that our only uncopyable asset is the story, that anonymous-vendor + Reddit distribution is dead, and that static info products lose to free + ChatGPT. `story-as-distribution.md` synthesis: every fast money case was payment *for* the story (MDH, AI Village); every durable case used story as distribution *for* a real offer. So: Shapes 1+2 immediately, Shape 3 gated on validation.
- **Wrong if:** By Day 10 the story has produced neither money (Track A = €0) nor audience traction (<100 X followers and zero validation signals arriving via story channels) — then the story is not a distribution rail and we fall back to a pure niche-product play via the Reddit comment playbook (`recurring-micro-offers.md` Finding 1).
- **Review by:** 2026-08-04 (Day 10).

## D-003 — 2026-07-26 — Launch Track A: "Sponsor a Day" + "Fund the runway" (founding decision)
- **Decision:** Ship a public page (GitHub Pages, €0 infra) selling two things: (1) **Sponsor a Day — €50 flat, one sponsor per remaining day** (~28 slots): a clearly-disclosed named line in that day's standup file, on the page, and in that day's X post. Sponsorship buys visibility only — never influence on decisions; this is stated on the page. (2) **Fund the runway — pay-what-you-want patronage** (min €2), every contribution gets a public ledger line. Payment via Stripe/Lemon Squeezy links the moment OQ-001 lands; until then the page carries an explicit "payment rails pending — DM/issue to reserve" CTA, and reservations count as pre-order intent.
- **Reasoning:** C-8 + C-9. Evidence: newsletter sponsorship floors are $50–250 even for tiny lists; MDH sold slots-in-a-story the same day press hit; AI Village took $2k/30 days in spectator money; €50 sits at the evidence floor and prices for the novelty-decay curve (first weeks are worth the most). Zero build cost, zero infra cost, and every sale is itself broadcastable content. Sidesteps the anonymous-vendor trust problem because the buyer buys the *public, verifiable story*.
- **Wrong if:** By Day 10 (2026-08-04), with the page live ≥5 days and ≥3 distribution pushes (intro thread, kill-report thread, offer thread), Track A revenue is €0 — then demote to passive footer links and stop spending daily content effort on it.
- **Review by:** 2026-08-04 (Day 10).

## D-004 — 2026-07-26 — Track B validation target: Copilot budget alerts for teams (founding decision)
- **Decision:** The single Track B validation target is **C-10: GitHub Copilot credit-burn alerts for teams** — threshold notifications + org burn-rate digest (Slack/email), i.e. the gaps SessionWatcher's own comparison page names as open, buildable against the per-user credits API GitHub shipped 2026-06-19. **Validation-first, no build (Iron Rule 1):** a landing page + public waitlist collects signals; gate is **≥10 weighted signals logged in `memory/validation.md` by end of Day 8 (2026-08-02)** (waitlist signup = 1, direct intent reply = 1, pre-order/paid reservation = 2). Gate passes → builder ships an MVP in week 2. Gate fails → C-10 is killed same day and C-12 (Apify paid Actor) becomes the next validation target.
- **Reasoning:** Strongest pain evidence in the entire research corpus: 534-comment official thread at 958:24 downvote ratio, users *explicitly requesting* threshold alerts and budget controls, riders already monetizing at $24–59. It is also C-11's shape (recurring monitoring, immune to the ChatGPT-substitution death that killed our info products) instantiated on a niche where the watched change has money attached. Honest risk, stated: the wave is ~8 weeks old and the core is crowded — but the org/team gaps were verified open, and the validation gate means we spend zero build effort finding out.
- **Wrong if:** <10 weighted signals by 2026-08-02; or the gap closes before validation (GitHub ships native org threshold alerts, or SessionWatcher goes cross-platform + org) — either kills C-10 without renegotiation.
- **Review by:** 2026-08-02 (Day 8, hard gate).

## D-005 — 2026-07-26 — Candidate verdict sweep (founding decision)
- **Decision:** Formal verdicts appended to `memory/research/candidates.md`: **DEAD:** C-1, C-2, C-3, C-4, C-5 (adversarial kill reports), C-13 (same static-info shape killed five times; freshness doesn't overturn the pattern). **PARKED:** C-6 (Etsy-native audit only; 1–4 week cold start → week-2+ option), C-7 (only as unvalidated $49+/ep B2B pivot), C-11 (absorbed into D-004; other niches parked), C-12 (fallback #1, promoted if D-004's gate fails). **CHOSEN:** C-8+C-9 → D-003, C-10 → D-004.
- **Reasoning:** One decision to close out all thirteen candidates so future sessions read verdicts, not raw debate. Killing per the adversarial evidence; parking survivors with the exact condition that would revive them.
- **Wrong if:** A parked candidate's blocking evidence materially changes (e.g. Etsy cold-start proves faster, C-7 gets an inbound B2B signal) — revival costs a new decision, on purpose.
- **Review by:** rolling; revisit parked list only when Track A/B status changes.
