# Draft: Reddit launch post

- **Platform:** Reddit r/SideProject (also fits Indie Hackers as-is)
- **Intended audience:** side project builders, people who enjoy public experiments and will call out BS
- **Goal:** honest feedback on the experiment design, repo watchers, maybe 1-2 teardown sales without pushing
- **Notes for Operator:** replace [REPO-LINK] and [PAYMENT-LINK] before posting. Post as text post, no link post. Reply to every comment in the first few hours, including hostile ones; the CEO will draft replies if you paste the comments back. Do not repost the offer in comments unless someone asks.

---

**Title:** An AI is running my company as CEO. 30 days to get profitable, every decision public in a git repo. Tear the setup apart.

**Body:**

I set up an experiment and I'd genuinely like this sub to poke holes in it before it gets far enough to hurt.

The setup: an AI (Claude) is the CEO of a real company. I'm the only human involved. I handle the stuff that legally requires a person: payment accounts, KYC, and clicking "post" on content it writes. I don't make strategy. The AI decides what to sell, what to charge, what to kill. If I think a decision is bad, my only veto is for illegal / against ToS / harmful. Otherwise it ships.

The rules it operates under, all enforced through a public GitHub repo:

- **One session per day.** The CEO wakes up, reads its own files, runs a standup, goes back to sleep. No continuous running.
- **Max 3 decisions per day.** Anything that changes strategy, spends money, launches, kills or reprices something counts as a decision and gets logged with reasoning and a "what would prove me wrong" line.
- **Validation gate.** It is not allowed to build any product until 10 independent humans show real demand (signups, direct "I'd pay for this" replies, or pre-orders, which count double). Every signal gets logged with evidence.
- **Append-only memory.** The AI has no memory between sessions. The repo IS its memory: standups, decisions, a money ledger. Nothing in there can be edited after the fact. Wrong calls get corrected in new entries, never rewritten.
- **Public ledger.** Every euro in or out, same day, with source. Budget is €20/month infra, starting from €0 revenue. Target: profitable in 30 days. There's a hard mode where revenue also has to beat the AI's own API costs.

Repo, if you want to read the raw standups and decision log: [REPO-LINK]

What I'm actually asking this sub:

1. What's the most likely way this fails that I'm not seeing? My guess is "AI writes generic slop, nobody cares." Its guess, in yesterday's decision log, is "distribution, not quality."
2. Is append-only memory + 3 decisions/day enough structure, or does an LLM CEO just drift without a human strategist?
3. Would YOU trust a service delivered by an AI team if a human quality-checks it before sending? Honest no's are useful, that's the whole point of the validation gate.

For transparency since it's a real company and not just performance art: its first offer (its Day 1 decision, not mine) is a €19 landing page teardown delivered in 24h, first 10 slots, human-checked before sending. That's here if it's useful to anyone: [PAYMENT-LINK]. But comments telling me why this whole thing is broken are worth more to the experiment than a sale.
