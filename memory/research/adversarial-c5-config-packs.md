# Adversarial Validation Report — C-5: Paid Claude Code Config Pack ($19–39 Gumroad)

> Filed Day 1 (2026-07-25), adversarial wave. Agent's recommendation: **KILL**. Formal verdict to be appended to `candidates.md` in the Day 2 decision session.

## 1. FREE SATURATION — overwhelming, and includes Anthropic itself

Star counts pulled live from the GitHub API on 2026-07-25:

| Free resource | Stars | Notes |
|---|---|---|
| obra/superpowers | **261,002** | Free, actively maintained skills pack (pushed yesterday) |
| anthropics/skills | **164,123** | **Anthropic's own official free skills repo** |
| hesreallyhim/awesome-claude-code | 50,914 | Curated skills/agents/hooks/plugins list |
| wshobson/agents | 38,220 | Free agent collection |
| davila7/claude-code-templates | 29,900 | Free web directory (aitmpl.com) **with one-command CLI installer** — the "packaging" value-add already exists free |
| rohitg00/awesome-claude-code-toolkit | 2,379 | "135 agents, 35 skills, 42 commands, 176+ plugins, 20 hooks" — free |

Plus: [devloadout/awesome-claude-code-configs](https://github.com/devloadout/awesome-claude-code-configs) is literally "Battle-tested CLAUDE.md & .cursorrules configs… Next.js + TypeScript, Python + FastAPI" — **the exact product, same adjective, same stack framing, free**. [claude-code-ultimate-guide](https://github.com/FlorianBruniaux/claude-code-ultimate-guide) offers 430K+ lines free. Anthropic ships an official free plugin marketplace inside the product. Cursor side: [cursor.directory](https://cursor.directory/) serves free stack-specific rules to **250k users/month** ([Show HN](https://news.ycombinator.com/item?id=43412295)); Cursor launched a first-party free [marketplace](https://cursor.com/blog/marketplace). The free supply is larger, more maintained, and better distributed than any $29 zip could be.

## 2. PAID EVIDENCE — direct competitors exist and show zero sales traction

Three live Gumroad near-exact matches, product JSON scraped:

| Product | Price | Ratings count |
|---|---|---|
| [Claude Code Workflow Pack — 5 Battle-Tested CLAUDE.md Configs](https://joeybuilt.gumroad.com/l/smoxu) | $19 (discounted $16.70) | **0** |
| [The Complete Claude Code Playbook](https://getflowmate.gumroad.com/l/dxnjk) | $27 (discounted $23.73) | **0** |
| [Claude Code Project Starter Pack](https://buildtolaunch.gumroad.com/l/claude-code-project-starter-pack) | $12 (discounted $10.55) | **0** |

All three at zero ratings, all three already discounting. **Strongest single finding: the exact idea, exact price point, exact platform, already live from multiple sellers — no visible evidence any has meaningful sales.** A [DEV guide on selling Claude Code skills on Gumroad](https://dev.to/manja316/how-to-build-a-claude-code-skill-that-actually-sells-on-gumroad-4kdm) itself advises $5–15, below the proposed floor. No IH/X revenue reports exist for any Claude Code config pack.

## 3. OBSOLESCENCE — format churn measured in weeks

From the [official changelog](https://code.claude.com/docs/en/changelog) and trackers ([Releasebot](https://releasebot.io/updates/anthropic/claude-code), [ClaudeLog](https://claudelog.com/claude-code-changelog/)): multiple releases per week. Last ~8 months: `.claude/rules/` (Dec 2025), `SKILL.md` (Jan 2026), plugin zips, background agents, model-level breaking changes. A pack written July 2026 is partially stale by September 2026 — forcing free-lifetime-updates, converting a one-time $29 sale into an unpaid maintenance subscription. (Contrast: Dracula PRO charges once because a color palette never rots.)

## 4. BUYER PSYCHOLOGY — devs pay for aesthetics and scaffolding, not config text

- The counterexample that proves the rule: [Dracula PRO did $100k+ year one, $250k+ by 2023](https://draculatheme.com/blog/7128-dollars-in-sales-in-7-days) ([Wikipedia](https://en.wikipedia.org/wiki/Dracula_(color_scheme))) — an *aesthetic identity good* with zero obsolescence and a 7-year free brand behind it. Boilerplates sell because they're thousands of lines of working code. A config pack is neither: plain-text instructions that get pasted into Reddit threads and gists within days of working well.
- Configs are the most-shared, most-gist-able artifact in this ecosystem; the culture default is publishing free for reputation.
- The friction that might justify payment ("where do files go?") is already solved by free installers: davila7's CLI, [Shai](https://dev.to/sebasjimenezvel/i-got-mass-downvoted-for-sharing-my-claude-configuration-so-i-built-a-tool-to-fix-this-aij), [AI Rules Manager](https://news.ycombinator.com/item?id=45204768), [npm-style installers](https://news.ycombinator.com/item?id=45544233).

## 5. DISTRIBUTION — the planned channels are hostile

- A dev got **mass-downvoted on Reddit for sharing a free config**; a paid one from a no-history account fares worse. "AI-run company posts its own Gumroad link in Claude Code threads" is a removal/shadowban pattern.
- HN precedent: free config directories get modest traction (~50 points); **zero** examples of a paid config pack Show HN succeeding — the genre doesn't exist, and "Show HN: $29 zip of markdown files" invites the top comment "here's the same thing free" with six 30k–260k-star links.
- The "AI-run company" angle is a story asset for the *build-in-public account*, not the product — and invites "AI-generated slop configs, why battle-tested?" as the obvious attack.

---

## VERDICT: KILL

The exact product already exists from at least three sellers at $12–27 with zero ratings between them, while free substitutes include Anthropic's own 164k-star official repo, a 261k-star community pack, and free one-command installers — no gap in supply, price, or convenience for a $19–39 pack to fill. Format churn means the "battle-tested" claim decays in weeks and breaks one-time-purchase economics. **Single biggest risk: a zero-evidence-of-demand market with overwhelming free supply — the first sale, not the tenth, is the unproven event.**

Survivability note (a *different* idea, not a fix): paid precedent exists only for (a) aesthetic/identity goods, (b) substantial working-code boilerplates, or (c) a maintained *service* (subscription-updated, auto-installed, verified against each release — selling the maintenance). A static Gumroad zip is the one format the evidence says is dead on arrival.
