# GitHub discussion comment — Copilot usage-based billing thread (drafted by CEO, Operator publishes)

> **Platform:** GitHub — official discussion https://github.com/orgs/community/discussions/192948 (the 534-comment usage-based-billing thread)
> **Audience:** engineers and org admins angry/anxious about the June 1 move from premium requests to AI Credits

> **NOTE TO OPERATOR — your call entirely:**
> - Post from your own account, as yourself. Edit freely — this must sound like you, not like me.
> - Before posting, sanity-check the API facts against the June 19 changelog ("AI credits consumed per user now in the Copilot usage metrics API") — if anything drifted, fix it or skip.
> - If the thread's mood makes any product mention feel gross that day, cut the last paragraph and post only the useful part, or skip entirely. A helpful comment with no pitch still builds the account's standing. Skipping is a fine outcome.
> - One link only (the waitlist issue). Do not add the repo or site links here.

---

**Comment draft:**

For teams trying to get ahead of the new billing before finding out from the invoice — some of the visibility people are asking for in this thread is already scriptable today, since the June 19 changelog ("AI credits consumed per user now in the Copilot usage metrics API"):

**What exists now:**
- The user-level reports in the Copilot usage metrics API (`users-1-day` and `users-28-day`, org and enterprise level) now include an `ai_credits_used` field per user — total AI credits that user consumed that day.
- Since July 20, individual users can also see their own credits used per billing cycle in their settings.
- The enhanced billing platform supports budgets with automatic email notifications as spend crosses thresholds — worth setting up first if you haven't, it's the only native alerting there is.

**What a team can script today** (the standard pattern for any metered API):
1. Nightly scheduled GitHub Action pulls the `users-1-day` report for your org.
2. Accumulate per-user credits for the current billing cycle into a small store (a JSON file in a repo or a gist is honestly enough).
3. Compare each user against `monthly_budget × days_elapsed / days_in_cycle`; anyone tracking >N% over pace goes into a Slack webhook message with their number.
4. Weekly, post the top-10 consumers and the org total as a digest.

**Caveats worth knowing before you build it:** the `ai_credits_used` field is a metrics signal, not the billed total — reconcile against the billing usage report before treating it as money. It's also not broken down by feature or model yet, so you can see *who* is burning credits but not *on what*. And there's no native push alerting at the per-user level — budgets email your billing managers about aggregate spend, nothing tells a team lead "this dev will blow their allotment by the 20th."

Disclosure, since it's relevant: I'm running a public experiment where an AI acts as CEO of a real company, and the exact gap in that last caveat — per-user threshold alerts + an org burn-rate digest, delivered to Slack/email — is the one product idea it's currently validating. It will only get built if 10 teams sign up by Aug 2; otherwise it gets killed on that date, so it may well never exist. If it's the tool you'd want, the waitlist is here: https://github.com/bastienyoussfi/claude-ceo/issues/1 — and if not, everything above works fine without it.
