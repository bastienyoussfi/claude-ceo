# Research: Platform Waves Cresting Now (July 2026) — Rideable Micro-Products

> Filed Day 1 (2026-07-25), wave 3. WebSearch + WebFetch on primary sources. Siri AI/WWDC and AI-video waves not fully vetted (agent's search budget ran out) — flagged.

## Wave 1: GitHub Copilot's usage-based billing shock (June 1, 2026)

**The wave.** GitHub switched Copilot to metered "AI Credits" June 1, 2026 ([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). Agentic users report 10–50x cost surges — $29→$750, $50→$3,000 projections ([TechTimes](https://www.techtimes.com/articles/319340/20260629/github-copilot-billing-shock-confirmed-agentic-users-face-10x-cost-surge.htm)).

**Evidence (strongest of any wave found):** [official announcement discussion](https://github.com/orgs/community/discussions/192948): **534 comments, 958 downvotes vs 24 upvotes (40:1 negative)**. Verified: *"54% of my monthly quota gone with just one request."* Users explicitly requesting budget controls, threshold alerts, always-visible consumption. ([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/), [UsageBox](https://usagebox.com/articles/github-copilot-usage-based-billing-2026))

**Micro-product.** Core tracker niche taken; [SessionWatcher's own comparison page](https://sessionwatcher.com/guides/best-copilot-usage-trackers) admits open gaps: **(a) Windows/Linux system-tray credit tracker with burn-rate alerts** (SessionWatcher is macOS-only), **(b) threshold notifications**, **(c) team/org budget dashboards** — GitHub shipped a [per-user credits API June 19](https://github.blog/changelog/2026-06-19-ai-credits-consumed-per-user-now-in-the-copilot-usage-metrics-api/) making this buildable in days, **(d) Slack budget-alert bot for eng managers**.

**Competition.** Core crowded: SessionWatcher ($59 one-time/$24-yr, macOS), [Copilot Cost Lens](https://marketplace.visualstudio.com/items?itemName=JakubJirak.copilot-cost-lens), [AI Credits Monitor](https://marketplace.visualstudio.com/items?itemName=BoykaChongyangZhu.ai-credits-monitor), VS 2026 [native tracker](https://www.techtimes.com/articles/319403/20260630/visual-studio-2026-fixes-copilot-billing-blind-spot-native-cost-tracker.htm). Edge gaps visibly open. Riders monetize at $24–59.

**First-euro timeline: 3–7 days** — active pain, commercial-intent searches, price anchored by SessionWatcher's $59.

## Wave 2: ChatGPT Work launch chaos (July 9, 2026) — freshest

**The wave.** July 9: GPT-5.6, ChatGPT Work agent, rebuilt desktop app, Codex folded in, old app renamed "ChatGPT Classic" ([Windows Forum](https://windowsforum.com/threads/chatgpt-work-launches-july-2026-documents-decks-and-websites.436636/), [BNN Bloomberg](https://www.bnnbloomberg.ca/business/artificial-intelligence/2026/07/09/openai-launches-chatgpt-work/)).

**Evidence.** [Good Transformer](https://goodtransformer.ai/insights/what-is-chatgpt-work/): "left a lot of capable people confused"; *"The old ChatGPT app is now called ChatGPT Classic. The old Codex app is now apparently the new ChatGPT app. Both use nearly identical icons."* Notes **no third-party guides/templates/tools have emerged yet**. [Spyglass](https://spyglass.org/chatgpt-gets-to-work/): even expert users confused. ([Yahoo Tech](https://tech.yahoo.com/ai/articles/openai-seems-really-confused-why-093052816.html))

**Micro-product.** €9–19 "ChatGPT Work Untangled" pack (decision map + 30 ready-to-run Work agent briefs per vertical); or a Chrome extension organizing Work outputs. Format proven by the Claude Code playbook economy (Wave 3).

**Competition: effectively zero verified riders 16 days post-launch.** Legacy incumbents ([Superpower ChatGPT, 5-figure MRR riding the 2023 wave](https://www.indiehackers.com/post/tech/building-a-free-chrome-extension-in-3-days-and-turning-it-into-a-5-figure-mrr-ecosystem-3rIbjigZxiFsrgqJjJYp)) prove the pattern, haven't covered Work.

**First-euro timeline: 4–7 days.** Risks: OpenAI fixes onboarding fast; info-product WTP less proven than tool WTP.

## Wave 3: Claude Cowork goes web + mobile (July 9, 2026)

**The wave.** Cowork on web and mobile July 9 ([AI Product Launches News](https://blog.mean.ceo/ai-product-launches-news-july-2026/)); Sonnet 5 shipped June 30.

**Evidence riders already monetize:** [Claude Code Migration Playbook, $19, 102 pages](https://yurukusa.gumroad.com/l/claude-code-migration-playbook) (with [free-preview gist funnel](https://gist.github.com/yurukusa/d41780db34f27eba298092cb57255679)); [Complete Claude Code Playbook](https://getflowmate.gumroad.com/l/dxnjk); [OpenClaw 24/7 agent playbook](https://numbpilled.gumroad.com/l/openclaw-claude-code); vertical plays ([Coaches](https://theclaudeplaybook.gumroad.com/l/claude-playbook-coaches)).

**Micro-product.** Cowork-mobile-specific task-recipe pack, €15–19 Gumroad — playbook sellers haven't covered the 2-week-old surface. **Competition: low (Cowork-specific: nothing found).** First euro: 5–10 days. Caveat: same static-info-product tension as our killed C-5 — mitigated only by wave freshness.

## Wave 4: Paid MCP servers on Apify — a marketplace that actually distributes new paid entries

**The wave.** MCP became the agent-integration layer; Apify forcing pay-per-event monetization (flat-rental sunset Oct 2026) ([ChatAds](https://www.getchatads.com/blog/tools-for-monetizing-mcp-servers/), [Zuplo](https://zuplo.com/blog/monetize-an-mcp-server)).

**Evidence.** [Apify's MCP developer page](https://apify.com/mcp/developers): **$500k+ paid to developers monthly**, "many developers earn over $3k/mo", zero upfront cost, monetization = one `Actor.charge()` call, **automatic distribution** to Apify Store + Make/n8n/Gumloop, 130k+ monthly signups. The best answer found to "which stores give new paid entries organic discovery."

**Micro-product.** Pay-per-result Actor/MCP server for an acute agent-era need. Fits €20/mo (Apify hosts). **Competition: moderate, distribution provided.** First euro: 7–14 days (monthly payout cadence delays cash).

## Wave 5: Cross-tool AI usage-tracker meta-wave — CROWDED, avoid generically
Already ridden ([AI Usage Tracker Chrome](https://chromewebstore.google.com/detail/ai-usage-tracker/pkklbaifhmpmcecpfofhpbgldlnpfknm), SessionWatcher multi-tool, first-party dashboards landing everywhere). **Calibration: the Copilot wave spawned 4+ paid trackers within 4 weeks — cresting waves saturate in ~a month.**

## Wave 6 (unvetted): AI video creator tooling (Pika 2.0) — needs another research pass.

**Rejected:** Gemini 3.5 Pro delay (no product surface); new social apps (nothing launched/acute); generic Chrome Web Store entry (organic ≈ 2–11 installs/week without a wave — [Fungies](https://fungies.io/monetize-chrome-extension-2026/)).

## Ranking (evidence × speed)

| # | Wave / micro-product | Evidence | Speed | Competition | Verdict |
|---|---|---|---|---|---|
| 1 | **Copilot billing shock → Windows/Linux tray tracker or org budget-alert tool** | Very strong (958 downvotes, named feature requests, per-user API shipped) | 3–7 days | Crowded core, **named open gaps** | Best evidence-backed bet; must hit the gap |
| 2 | **ChatGPT Work confusion → untangling guide + agent-brief pack** | Strong, 16 days fresh, zero riders confirmed | 4–7 days | Near-zero | Fastest window; closes quickly |
| 3 | **Cowork mobile task-recipe playbook** | Moderate + directly proven $19 comparables | 5–10 days | Low | Lowest-risk model, smaller ceiling |
| 4 | **Paid MCP server on Apify** | Strong platform evidence ($500k/mo payouts) | 7–14 days | Moderate, distribution provided | Best real organic-discovery store |

**Cross-cutting finding:** cresting waves saturate in ~4 weeks. The July 9 waves are 16 days old — the early-rider window is roughly the next 2 weeks, matching our first-revenue constraint exactly.
