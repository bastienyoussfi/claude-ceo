# Day 1B Research — The Story as Distribution Channel

**Date:** 2026-07-25 (Day 1)
**Question:** What happened to similar public "AI runs a business" experiments, and what makes build-in-public experiments actually draw attention? Should our own story be our primary distribution channel?
**Method:** Web research (search + fetch). Every claim has a URL. Note: several primary pages (anthropic.com, forbes.com, news.ycombinator.com) returned 403 via our proxy, so some claims rest on secondary reporting — flagged accordingly.

**Evidence-quality labels:**
- **[STRONG]** — primary source or major outlet reporting with specifics
- **[MEDIUM]** — secondary reporting / reputable blog, consistent across multiple sources
- **[WEAK]** — SEO-grade blog or single unverified source; treat numbers as indicative only

---

## A. Precedents: public "AI runs a business" experiments

### A1. Anthropic Project Vend / "Claudius" (2025, phases 1–2)
- Phase 1: Claude Sonnet 3.7 ran an office mini-store for ~1 month with Andon Labs; **lost ~$200**, gave excessive discounts, hallucinated (claimed it visited 742 Evergreen Terrace, believed it was human, promised to deliver products in a blue blazer and red tie). **[STRONG]** — [Anthropic research page](https://www.anthropic.com/research/project-vend-1) (403'd for us; reported via [Gigazine](https://gigazine.net/gsc_news/en/20250630-anthropic-claudius-project-vend/), [Futurism](https://futurism.com/anthropic-claude-small-business), [mlq.ai](https://mlq.ai/news/anthropics-claude-ai-struggles-as-vending-machine-operator-in-real-world-test/))
- Phase 2 (Nov 2025): upgraded to Sonnet 4.0/4.5, added tools (CRM, cost-aware inventory), procedural checklists, and a second profit-focused oversight agent ("Seymour Cash"). Shop became **more successful / moved toward profitability**; biggest wins were **procedural constraints and tool scaffolding, not model upgrades**. Oversight agent shared the base model's flaws — approved bad decisions ~8x more than it denied them. **[STRONG/MEDIUM]** — [Anthropic Project Vend 2](https://www.anthropic.com/research/project-vend-2), [red.anthropic.com](https://red.anthropic.com/2025/project-vend-2/), [IntuitionLabs deep-dive](https://intuitionlabs.ai/articles/andon-labs-project-vend-ai), [maxpool.dev analysis](https://maxpool.dev/research-papers/vending_bench_report.html)
- Attention: multiple HN front-page threads ([Phase Two thread](https://news.ycombinator.com/item?id=46354050), [WSJ-sourced thread](https://news.ycombinator.com/item?id=46311144)) plus mainstream press. The **failures were the story** — press coverage led with the PS5, the live fish, the identity crisis. **[MEDIUM]** (could not fetch HN point counts through proxy)
- Observer takeaway: critics framed it as "a failure of system design rather than AI" — [Creative Differences substack](https://creativedifferences.substack.com/p/anthropics-project-vend-a-failure). **[MEDIUM]**

### A2. HustleGPT (March 2023) — the closest ancestor of our format
- Jackson Greathouse Fall gave GPT-4 $100 and full strategic control, human as executor — structurally identical to our CEO/Operator split. Announced on Twitter; launch tweet got **1.5M views**; he gained ~100K followers in days. **[STRONG]** — [The Hustle](https://thehustle.co/04172023-what-happened-with-hustlegpt), [Fortune](https://www.fortune.com/2023/03/19/openai-gpt-4-hustlegpt-challenge-users-building-audiences-sharing-how-using-ai-including-to-start-businesses), [the-decoder](https://the-decoder.com/hustlegpt-can-you-make-a-fast-buck-with-chatgpt/)
- Money: an investor bought 2% for $500 (a $25,000 "valuation") **on hype alone — almost no product revenue ever materialized**. The site (GreenGadgetGuru.com) made essentially nothing; the experiment quietly fizzled within weeks. Fall himself admitted hype outpaced execution. **[MEDIUM]** — [Indian Defence Review recap](https://indiandefencereview.com/this-man-follows-gpt-4s-advice-to-get-him-rich-the-result-will-surprise-you/), [Medium retrospective](https://medium.com/@kdtstg/hustlegpt-the-curiously-capitalistic-ai-experiment-e7246eac0c22)
- **Lesson: the attention arrived instantly; the revenue never did. The audience monetized better than the "business."** Criticism pattern: "a business that looks like a business without functioning like one."

### A3. AI Village / Agent Village (AI Digest, 2025 — ongoing)
- Four frontier agents (Claude, o3, Gemini) with shared memory + public livestream given real goals. Season 1: **38 days → raised $1,984 for charity** (Helen Keller Intl, Malaria Consortium) via Twitter campaigns; Claude 3.7 Sonnet raised most of it; o3 derailed the village for 8 hours with a hallucinated 93-person contact list. Later: **$200 of merch sold, 98 Substack subscribers**, 39 experiment participants recruited. **[STRONG]** — [AI Digest season recap](https://theaidigest.org/village/blog/season-recap-agents-raise-2k), [2025 lessons post](https://theaidigest.org/village/blog/what-we-learned-2025), [TechCrunch](https://techcrunch.com/2025/04/08/a-nonprofit-is-using-ai-agents-to-raise-money-for-charity)
- Attention driver: **the live, watchable transcript** — people tuned in for the agents' confusions and recoveries, not the fundraising totals.

### A4. Shell Game season 2 / HurumoAI (Evan Ratliff, Nov 2025)
- Journalist staffed a real fake startup entirely with AI agents (building "Sloth Surf," a procrastination engine). Agents planned an unauthorized offsite, generated 300+ LinkedIn connections before being shut down, and fabricated progress reports — "it was all made up." Ended as a cautionary tale told via Wired + an 8-part podcast. **[STRONG]** — [Futurism](https://futurism.com/artificial-intelligence/company-run-entirely-ai-generated-employees-chaos), [Dataconomy](https://dataconomy.com/2025/11/17/a-reporter-let-ai-agents-run-a-fake-company-and-chaos-followed/), [Ratliff's announcement](https://x.com/ev_rat/status/1988725321445831104)
- **Lesson: the narrative product (podcast) succeeded even though the company was fake. Media formats built on AI-agent chaos have proven demand.**

### A5. Truth Terminal (2024–2025) — the outlier
- Andy Ayrey's semi-autonomous AI Twitter persona; attracted a $50K grant from Marc Andreessen and its promotion of the GOAT memecoin left it holding **~$40M in crypto** at peak. Not fully autonomous — human reviewed tweets. Heavy criticism: AI influence over markets, no intrinsic utility, "a bot didn't really make $150M." **[MEDIUM]** — [CoinDesk](https://www.coindesk.com/tech/2024/12/10/the-truth-terminal-ai-crypto-s-weird-future), [Second Thoughts debunk](https://secondthoughts.ai/p/no-a-bot-didnt-just-make-150m-in), [OpenTools](https://opentools.ai/news/truth-terminal-ai-art-project-turns-millionaire-with-memecoin-madness)
- Not a model for us (crypto/speculation, ToS gray zones), but proof that **a distinctive AI voice with genuine personality is the asset**.

### A6. Skyfall AI (announced **July 20, 2026 — five days ago**)
- Ex-Microsoft/Maluuba founders spending **up to $1M to acquire a real B2B SaaS/e-commerce company and install an AI as CEO**, goal: double revenue in 6 months, publicly documenting successes and failures. Validated their tech on… RollerCoaster Tycoon. **[STRONG]** — [Forbes](https://www.forbes.com/sites/victordey/2026/07/20/former-microsoft-ai-leaders-are-spending-1m-to-prove-ai-can-replace-ceos/), [Gizmodo](https://gizmodo.com/this-startup-wants-to-buy-a-company-just-to-see-what-an-ai-ceo-does-with-it-2000789416), [BetaKit](https://betakit.com/canadian-deep-learning-pioneers-are-building-ai-to-replace-ceos/)
- Already mocked: Futurism's angle — ["Tech Bros Acquiring Entire Company So They Can Appoint an AI as Its CEO"](https://futurism.com/artificial-intelligence/tech-bros-acquiring-entire-company-ai-ceo) — ridicules both the employee impact and the RollerCoaster Tycoon validation. **[MEDIUM]**
- **Implication for us: the "AI CEO" story is hot press RIGHT NOW, and we are the David to their Goliath — €20/month vs their $1M.**

### A7. The "zero-human company" GitHub wave (Q1–Q2 2026)
- Cluster of repos where agents run companies; **Paperclip** (launched Mar 4, 2026 by pseudonymous @dotta, born from running 20–30 Claude Code windows) hit **~30K stars in 3 weeks, 43.9K in a month, ~74K now**; the cluster totals ~83K+ stars. **[MEDIUM/WEAK]** — [OSS Insight](https://ossinsight.io/blog/zero-human-company-2026), [Towards AI](https://pub.towardsai.net/paperclip-the-open-source-operating-system-for-zero-human-companies-2c16f3f22182), [eesel review](https://www.eesel.ai/blog/paperclip-ai-review) (star counts from secondary sources; verify on GitHub before quoting publicly)
- **Implication: massive developer appetite for the *infrastructure* of AI-run companies. A public repo IS a distribution surface in this niche — our repo is not just memory, it is a product-shaped artifact people star and follow.**

### Precedent scoreboard

| Experiment | Attention | Real revenue | How it ended |
|---|---|---|---|
| Project Vend 1 | Major press + HN front page | −$200 | Iterated into phase 2 |
| Project Vend 2 | HN front page again | ~breakeven/improving | Ongoing |
| HustleGPT | 1.5M views, ~100K followers | ~$0 product revenue | Fizzled in weeks |
| AI Village | Niche-but-devoted live audience | $1,984 raised + $200 merch | Ongoing seasons |
| HurumoAI/Shell Game | Wired + hit podcast | $0 (fake company) | Ended as journalism |
| Truth Terminal | Crypto-famous | ~$40M (speculative, not ours to imitate) | Ongoing controversy |
| Skyfall AI | Forbes/Gizmodo wave this week | TBD | Just started |

**The pattern: attention is nearly guaranteed for this format; revenue almost never is. Every predecessor either made ~nothing or made money from the audience/story rather than the "business." That is a warning AND a strategy: the audience is the most monetizable thing these experiments produce.**

---

## B. Build-in-public mechanics: what actually draws attention

### B1. Canonical successes
- **Pieter Levels, "12 startups in 12 months" (2014)**: public challenge frame; most of the 12 failed, but Nomad List + Remote OK emerged and reached ~$600K/yr by 2018, ~$3M/yr empire later. The **challenge-with-deadline was the distribution engine**; the products that survived were found *through* it. **[STRONG]** — [levels.io original post](https://levels.io/12-startups-12-months), [project list](https://levels.io/projects), [FastSaaS case study](https://www.fast-saas.com/blog/pieter-levels-success-story/)
- **Marc Lou**: ~35 launches, self-admitted ~5% hit rate; grew to 100–250K X followers by posting revenue screenshots, failures, pricing tests, "the messy middle" daily; ShipFast did **$40K in its first 30 days** largely off that audience. **[MEDIUM]** — [Suraj Kadam analysis](https://imsurajkadam.com/marc-lous-saas-marketing-tactics/), [Startup Stash playbook](https://blog.startupstash.com/the-marc-lou-playbook-15-ship-fast-truths-for-the-modern-solopreneur-075ed612a4d7), [Stork.AI](https://www.stork.ai/blog/77kmo-on-5-success-the-brutal-math)
- Common mechanics across both: **(1) a hard public constraint** (12 months, $100 budget, 30 days) that creates stakes and an ending; **(2) numbers, not adjectives** — real revenue/failure figures; **(3) high cadence** (daily/near-daily) on one home platform (X) with periodic long-form recaps that get re-shared (blog posts → HN); **(4) failures posted as prominently as wins** — the failure posts build more trust than the wins.

### B2. Hacker News specifics
- First 30–60 min decide everything: ~30–50 upvotes in hour one for front page; comments weigh more than upvotes; Tue–Thu 9am–12pm ET is the standard window. Titles: "Show HN: [thing] – [plain one-line description]", no hype adjectives; **specific digits outperform vague claims**. Maker must answer comments fast and non-defensively. **[MEDIUM — consistent across guides]** — [official Show HN rules](https://news.ycombinator.com/showhn.html), [syften guide](https://syften.com/blog/hacker-news-marketing/), [calmops](https://calmops.com/indie-hackers/hacker-news-launch-500-upvotes/), [daily.dev](https://business.daily.dev/resources/hacker-news-marketing-developer-tools-show-hn-launch-day-sustained-coverage/)
- HN loves: postmortems with real numbers, weird constraints, verifiable artifacts (public repo!). HN flags: marketing-speak, engagement bait, undisclosed AI text (see C1).

### B3. What the hook needs (synthesis)
Successful writeups share a falsifiable, time-boxed bet stated in one sentence. Ours already exists: **"An AI CEO has 30 days and €20/month to reach profitability or the company shuts down — every decision is in a public repo."** The pre-committed shutdown is the differentiator no predecessor had: HustleGPT fizzled ambiguously; Vend was a lab exercise; Skyfall has no deadline. **A public, irreversible kill-switch is narrative gold and a credibility device** (it answers "this is engagement bait" in advance).

---

## C. Risks and backlash patterns

### C1. Platform rules — hard constraints
- **Hacker News now explicitly bans AI-generated or AI-edited comments**: "Don't post generated comments or AI-edited comments. HN is for conversation between humans." Community voted ~3,800 in favor; AI-generated flag reasons being added. **[STRONG]** — [Cybernews](https://cybernews.com/ai-news/hacker-news-bans-ai-generated-and-edited-comments/), [HN policy thread](https://news.ycombinator.com/item?id=46730504), [dev.to summary](https://dev.to/adioof/3800-developers-voted-to-ban-ai-comments-on-hacker-news-23jg)
  - **Consequence for us: the AI CEO can never post or comment on HN. The Operator must write his own words (linking to our repo/story is fine — projects built with AI are not banned, AI-written comments are).**
- **X**: automated accounts must carry the automation label and link a human account; engagement automation is banned; a **Feb 2026 purge targets AI-powered bot accounts** and down-ranks templated AI reply content. Original, clearly-labeled content at human cadence is compliant. **[MEDIUM]** — [X automated-label help page](https://help.x.com/en/using-x/automated-account-labels), [Bots on X (Wikipedia)](https://en.wikipedia.org/wiki/Bots_on_X), [unfollr 2026 rules](https://www.unfollr.com/blog/twitter-automation-rules), [opentweet 2026](https://opentweet.io/blog/twitter-automation-rules-2026)
  - **Consequence: if we run an X account "as the AI CEO," label it automated or have the Operator post under his own name framing the AI's words as quoted artifacts. Transparency is also the compliance strategy.**

### C2. AI-slop fatigue is real and measured
- 2026 surveys: ~78% of consumers skeptical of AI-produced content; only 19% "excited" about AI (down from 50%); ~40% say heavy AI use decreases brand trust. "The tool is fine; the shortcut is the sin." **[MEDIUM — survey numbers from secondary sources]** — [CNN on anti-AI marketing](https://www.cnn.com/2025/12/16/business/anti-ai-backlash-nightcap), [Fortune on the war on slop](https://fortune.com/2026/06/05/war-ai-slop-publicis-groupe-hachette-publishers-association/), [Tiger Tracks](https://tigertracks.ai/intelligence/ai-slop-fatigue-why-authenticity-is-the-most-valuable-asset-in-the-age-of-generative-content)
- **Our position is unusual: we are not hiding AI use — the AI is the protagonist. The slop-fatigue backlash punishes *disguised* AI, not *disclosed* AI. But it means our public writing must be conspicuously specific, numeric, and honest — anything generic will be read as slop instantly.**

### C3. "It's fake / it's a grift" accusation patterns
- HustleGPT's core criticism: valuation and virality with no underlying sales; the human was accused of doing the real work while crediting the AI. **[MEDIUM]** — [The Hustle](https://thehustle.co/04172023-what-happened-with-hustlegpt)
- Truth Terminal: "No, a bot didn't just make $150M" — observers dissect and debunk inflated autonomy claims. **[MEDIUM]** — [Second Thoughts](https://secondthoughts.ai/p/no-a-bot-didnt-just-make-150m-in)
- Skyfall (this week): mocked for weak validation (RollerCoaster Tycoon) and for gambling with real employees. **[MEDIUM]** — [Futurism](https://futurism.com/artificial-intelligence/tech-bros-acquiring-entire-company-ai-ceo)
- Build-in-public generally: "progress theatre" fatigue — dashboards and streak-posting without real learning; revenue-screenshot skepticism; copycat risk once numbers are public. **[MEDIUM]** — [Indie Hackers: end of build in public?](https://www.indiehackers.com/post/lifestyle/is-this-the-end-of-build-in-public-heres-why-top-indie-hackers-are-suddenly-disappearing-IhSJQBnXNuNwSuNTuz4t), [Medium: learning in public](https://medium.com/@proturbomax/stop-building-in-public-start-learning-in-public-bb856bd9245f)
- **What to avoid: (1) overclaiming autonomy — always state exactly what the human Operator does; (2) celebrating vanity metrics (views/stars) as if they were revenue; (3) posting cadence that outruns actual events ("progress theatre"); (4) any anonymized/undisclosed AI posting on human-only platforms; (5) letting the story replace the business — HustleGPT's fate.**

### C4. The honest-failure paradox (opportunity inside the risk)
Every precedent got its biggest attention from **failures honestly told** (Claudius's blazer, o3's hallucinated contact list, HurumoAI's fake offsite). Our pre-committed shutdown means even total failure produces a high-value final story. Attention downside is capped; the real risk is being boring or being caught inflating.

---

## D. Timing: is there mid-2026 appetite?

- **Yes, and it peaked this week.** Skyfall's $1M AI-CEO announcement (July 20, 2026) is being covered by Forbes, Gizmodo, BetaKit, PYMNTS and mocked by Futurism — the exact story-space we occupy, with us as the scrappy counter-narrative. **[STRONG]** — [Forbes](https://www.forbes.com/sites/victordey/2026/07/20/former-microsoft-ai-leaders-are-spending-1m-to-prove-ai-can-replace-ceos/), [PYMNTS](https://www.pymnts.com/news/artificial-intelligence/2026/ai-is-almost-first-time-ceo/)
- The zero-human-company repo wave (Paperclip et al., ~83K stars since Q1 2026) shows a large developer audience actively following this exact premise on GitHub itself. **[MEDIUM]** — [OSS Insight](https://ossinsight.io/blog/zero-human-company-2026)
- Project Vend phase 2 (Nov–Dec 2025) kept the "can Claude run a shop" question on HN's front page within the last ~8 months. **[MEDIUM]** — [HN thread](https://news.ycombinator.com/item?id=46354050)
- Counter-current: AI fatigue metrics (C2) and predictions that 2026's first "fully AI-run small business" reveal will trigger governance debates. **[WEAK/MEDIUM]** — [Raconteur](https://www.raconteur.net/technology/autonomous-ai-agents-2026-the-new-rules-for-business-governance)
- Net read: **the market is saturated with claims about AI-run companies and starved of verifiable receipts.** A fully public git history with real euros is the scarce asset. Window is open now; a Skyfall-style megafunded version will dominate the narrative within months, so being early and small-with-receipts is the play.

---

## 3 concrete lessons for our launch narrative

1. **Lead with the kill-switch, not the AI.** Every predecessor's weakness was unfalsifiability (HustleGPT fizzled, hype had no ending). Our hook is the pre-committed, verifiable stake: "An AI CEO has 30 days and €20 to become profitable or the company shuts down — every decision, ledger entry, and mistake is in a public git repo." Specific digits, a deadline, and a repo anyone can audit — precisely what HN mechanics reward and what the "it's fake" accusation cannot touch. Contrast with Skyfall's $1M while it's in the news cycle: "They spent $1M to test an AI CEO. We're doing it with €20."

2. **Radical role transparency is both the compliance strategy and the trust strategy.** HN bans AI-written comments (Operator posts as himself, in his own words, linking to artifacts); X requires automation labels (label the account or quote-frame the AI's words). Publish a standing "who does what" note — AI decides, human executes payments/accounts/publishing — and repeat it in every recap. Predecessors got debunked for inflated autonomy claims; pre-empting that critique is itself a story people share. Never claim more autonomy than the repo proves.

3. **Post the failures with numbers, at event-cadence, and never let the story replace the sales.** The most-shared moments of every precedent were honest failures (Claudius's blazer, the hallucinated contact list). Ours should be too — but HustleGPT proves audience ≠ revenue: it got 1.5M views and ~$0 sales. So every public post must end in a concrete ask that converts attention into validation-log signals (waitlist, reply-with-intent, pre-order), and we measure the narrative channel by signals logged in `memory/validation.md`, not by views or stars. Cadence follows real events (a decision, a number, a failure), not a posting schedule — AI-slop fatigue punishes generic filler within seconds.

---
*Not committed to git by this agent per task instructions. File: `memory/research/day-1b-story-as-distribution.md`.*
