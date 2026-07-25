# C-10 native-coverage check — Operator challenge, Day 2 evening (2026-07-26)

> Trigger: the Operator asked, mid-Day-2, whether Copilot can't natively add token limits/alerts, and whether C-10 really has demand and an ICP. Verified same session via WebSearch + GitHub docs. This partially fires D-004's pre-registered risk ("gap closes / native alerts ship") — logged here so Day 3+ sessions weigh it with eyes open.

## What GitHub ships natively (verified 2026-07-26)
- **Budgets on metered products (incl. Copilot AI credits)** with alerts at **75% / 90% / 100%** — email + GitHub banner, to owners/billing managers, additional recipients addable. ([docs: budgets-and-alerts](https://docs.github.com/en/billing/concepts/budgets-and-alerts), [set-up-budgets](https://docs.github.com/en/billing/how-tos/set-up-budgets))
- **User-scoped budgets, Copilot-AI-credits-only** (universal / cost-center / individual scopes) that can **hard-stop an individual user** when exhausted. GitHub's own docs: *"Alerting for user-level budgets is not consistently available in all scenarios."* Docs frame them around enterprise cost centers; org-plan availability not clearly stated.
- Since 2026-07-20: individuals can see their own credits per billing cycle in settings.

## Honest impact on C-10
The Day-1 research framing ("no threshold alert, no budget control") was **stale — the original 534-comment rage predates/ignores controls GitHub has since shipped or improved.** The wedge narrows to what native verifiably does NOT do:
1. **Delivery:** email-to-billing-admins only. No Slack/webhook.
2. **Timing model:** fixed %-crossed thresholds, no burn-rate **pace projection** ("out of credits by the 20th").
3. **Audience:** billing admins, not eng managers/team leads; per-user alerting unreliable per GitHub's own docs.
4. **Failure mode:** the native per-user control is a hard cutoff mid-sprint, not an early warning.

## ICP, restated more honestly
Eng managers / team leads at Copilot Business/Enterprise orgs who (a) are not billing managers, (b) live in Slack, (c) own the "why is Copilot stopping for my devs / why is the bill 4x" conversation. Narrower than Day 1's framing. Whether they pay ~€19/mo for a convenience layer over free native controls is **exactly what the D-004 gate tests** — the rage thread proves anger, not willingness to pay a third party.

## Actions taken same session (execution, no new decision)
- `docs/copilot-alerts.html` rewritten: added a "what GitHub already ships — use it first" section, hero/meta overclaims removed, features reframed to pace-alerts + lead-digest only.
- GH-discussion comment draft caveat updated to state native budgets/user-caps exist and should be configured first.
- D-004 unchanged: same gate (≥10 weighted signals by 2026-08-02), same fallback (C-12). The narrower wedge makes the gate MORE likely to fail — fine; that is the gate doing its job at €0 build cost. If Day 3 session judges the wedge dead on arrival, killing early costs one decision.
