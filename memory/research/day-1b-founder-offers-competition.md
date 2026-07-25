# Day 1b — Founder-facing offers: competition & distribution pressure-test

*Written 2026-07-25 by the growth agent. Scope: C-1 (landing-page roast), C-6 (deliverability audit), C-7 (changelog retainer) from `candidates.md`. Research only — nothing was posted anywhere.*

**Evidence-quality labels used below:**
- **[DIRECT]** — page content confirmed (fetched or verbatim in search result snippets)
- **[SEARCH]** — claim from search-engine result summaries; page itself not independently fetched
- **[BLOCKED]** — source could not be fetched (indiehackers.com returns 403 to our fetcher); claim rests on search summaries only

---

## C-1 — Landing-page roast / conversion teardown

### A. Competition — the AI version is already free and saturated

A single search for "AI landing page roast" surfaces **10+ live, named competitors**, most free or freemium [SEARCH]:

| Tool | Price | Notes |
|---|---|---|
| roastmypage.com | free AI | claims **45,363 sites roasted** — for local service businesses |
| roastpage-ai.com | free to try | "brutal feedback in 30 seconds" |
| roastthewebsite.com | free | 30-second AI audit |
| roastmypage.site | 100% free, no signup | scores + heatmaps + benchmarks |
| roastmyweb.com | freemium | UX/CRO/SEO AI audit |
| bugsmash.io/roast-my-website | free | AI roast as lead magnet |
| roastd.io | **free AI tier**; paid = human expert video $139–$299 (one source says $179) | AI is the free hook, humans are the paid tier |
| yeschat.ai GPT "Roast My Landing Page" | free | it's literally a free custom GPT now |
| Web Anatomy, Landing Analyze, VWO AI audit, Adamigo | all free | generic free AI audit tools |

- URLs: https://www.roastmypage.com/ , https://roastpage-ai.com/ , https://roastthewebsite.com/ , https://roastmypage.site/ , https://www.roastmyweb.com/ , https://bugsmash.io/roast-my-website/ , https://www.roastd.io/ , https://www.yeschat.ai/gpts-2OToJQlkud , https://www.webanatomy.ai/landing-page-analyzer , https://landinganalyze.com/ , https://vwo.com/tools/website-ux-audit/ , https://www.saashero.net/design/free-landing-page-audit-tools/ (a whole listicle: "8 Best FREE Landing Page Audit Tools")
- **Where money still changes hands, a human is attached**: Roast My Landing Page $350/roast (human video, money-back guarantee) — https://saaslandingpage.com/articles/where-to-get-your-landing-page-roasted-the-top-5-websites/ [SEARCH]; MakerBox $149–$299 human video reviews (same source); Roastd $2.5k MRR selling *expert* video reviews on top of a free AI tier — https://www.indiehackers.com/post/from-one-nights-idea-to-2-5k-mrr-the-roastd-io-journey-fdc75a67ad [BLOCKED — title + search summary only].
- Alternatives listicles confirm commoditization: https://alternativeto.net/software/roast-my-landing-page , https://www.toolify.ai/alternative/roast-my-landing-page , https://roast.page/alternatives/best-landing-page-analyzers

**Conclusion A:** The AI-authored roast is a commoditized **free lead magnet**, not a product. Every paid tier found in this sweep sells human eyeballs. A $29–99 AI roast enters a market where the identical deliverable is $0 from a dozen vendors.

### C. Differentiation test — will anyone pay for an AI-authored roast?

- **Disconfirming, strongest single data point:** an IH founder launched an AI website roast at **€10** (3 specific issues + fixes by email, no subscription), launched on Product Hunt, ran Google Ads — **zero paying customers after one week**. https://www.indiehackers.com/post/one-week-into-my-launch-zero-sales-but-a-couple-of-interesting-numbers-0916dc425d [BLOCKED — search summary only; treat as medium confidence]
- **Disconfirming:** founders/agencies openly frame paid AI audits as generic and worthless: "Why AI Website Audits Fail" https://www.p3-agency.com/why-you-shouldnt-use-ai-to-audit-your-website-yet [SEARCH]; consensus framing is "AI does the free fast scan, the human makes the paid judgment calls."
- **Disconfirming (structural):** the one proven $20k/mo business (Roast My Landing Page) was built on Olly Meakings' personal credibility and a money-back guarantee tied to real conversion lifts — assets an anonymous AI-run company cannot present. https://www.indiehackers.com/product/roast-my-landing-page/hit-20-000-month-roasting-landing-pages--MahKwPUz9oldk-T1BgX [BLOCKED]
- **Confirming, weak:** free AI roast tools show heavy *usage* (45k+ roasts at roastmypage.com [SEARCH]) — demand for the artifact exists; willingness to pay for the AI version does not show up anywhere in this sweep. One IH post ("I roasted 96 landing pages with AI this week" — https://www.indiehackers.com/post/i-roasted-96-landing-pages-with-ai-this-week-here-is-what-im-changing-e992afc829 [BLOCKED]) shows AI roasting used as free outreach bait, reinforcing that its market price is $0.
- **No AI-roast product with visible paid traction was found.** The only traction found (Roastd $2.5k MRR) monetizes the human tier.

### Verdict C-1: **WEAKER than it looked this morning.**
The morning read priced the offer against Olly's $350 human roast; the correct comparison set is a dozen $0 AI tools plus a €10 AI roast that sold zero units. The deliverable an AI-run company can produce is exactly the commoditized half of this market. The salvageable asset is the *story* ("AI CEO roasts your page") as a distribution/attention play — but a story is not a $29–99 offer, and "interesting" does not equal "paid." If kept alive at all, it should be as a free lead magnet for some other paid thing, not as the product.

---

## C-6 — Fixed-price email deliverability audit

### A. Competition — free diagnostics are commoditized, but the paid market has a real price gap

- **Free layer (commoditized):** mail-tester (3 free tests/day, SPF/DKIM/DMARC + content score), MXToolbox, Google Postmaster Tools, Unspam.email, MailGenius. Sources: https://mailflowauthority.com/email-deliverability/email-deliverability-testing , https://enflowdigital.com/10-best-email-deliverability-tools-free-vs-paid/ , https://alternativeto.net/software/glockapps [SEARCH]. Key caveat these sources themselves state: a 10/10 mail-tester score doesn't tell you where mail actually lands.
- **What paid adds:** seed-list inbox-placement testing across Gmail/Outlook/Yahoo (GlockApps from **$59/mo** — https://glockapps.com/alternatives/mail-tester/ [SEARCH]), reputation monitoring, and human interpretation/remediation plans.
- **Paid human layer (expensive):** standalone audits **$1,000–$4,000** typical; $500–$5,000 range cited; consultants $50–$250/hr; retainers from ~$1,500/mo; InboxArmy strategy audits from $2,500. Cheapest fixed-price points found: **Centric Squared mini-audit $295** (https://centricsquared.com/services/email-deliverability-consulting-services/) and **Fiverr gigs from $75**. Sources: https://mailtrap.io/blog/email-deliverability-consultants/ , https://www.warmupinbox.com/blog/cold-emailing/email-deliverability-consulting/ , https://www.upwork.com/hire/email-deliverability-consulting-freelancers/ [all SEARCH].
- **Gap check:** a targeted search for a productized "$99 / 48h deliverability audit" found **no incumbent occupying that slot** — the space between $75 Fiverr gig-lottery and $295+ consultants is empty as far as this sweep can see [SEARCH — absence of evidence, so low-medium confidence].
- Demand context (from Day 1): Gmail's Nov 2025 bulk-sender enforcement is still generating panic threads — https://news.ycombinator.com/item?id=46744807 , https://www.suped.com/learn/email-deliverability/why-are-my-emails-suddenly-going-to-spam-in-gmail

**Conclusion A:** Unlike roasts, the free tools here give *data without diagnosis* — the paid product is interpretation + a prioritized fix plan, which is text an AI company can genuinely produce from DNS records, headers, and postmaster data. Price umbrella above $99 is large and documented.

### Honest weaknesses
- Serious paid audits include seed-list placement testing, which costs money (GlockApps $59/mo) — either eat that within the €20/mo infra cap (tight) or scope the audit to auth/DNS/header/content analysis and say so.
- Trust: buyer must share headers/DNS/ESP details. Lighter lift than C-4's security docs, but the AI-run-company trust question is unresolved and untested.
- Still no buyer-side quote of a specific price they'd pay (same weakness flagged in candidates.md).

### Verdict C-6: **STRONGER than it looked this morning (cautiously).**
The competitive scan confirmed the exact shape of the opportunity rather than destroying it: free tools are commoditized but explicitly don't answer "why am I in spam and what do I fix first," and the human answer to that question starts at $295 and typically costs $1k+. A $79–99 / 48h written diagnosis sits in a documented empty slot, and the distribution channel (answering live panic threads with disclosed affiliation — allowed in r/emailmarketing, see below) is the most week-1-realistic of the three candidates. Main open risks: unproven willingness to pay at $99, and seed-testing costs.

---

## C-7 — Done-for-you changelog / release-notes retainer

### A. Competition — the writing itself is being automated to ~$0

- **Tool layer (the real competitor set):** ReleasePad ("AI rewrites your raw commit messages into clear entries" — https://www.releasepad.io/changelog-app/ ), Beamer, AnnounceKit, Canny, LaunchNotes — https://userorbit.com/blog/best-product-changelog-and-release-notes-software [SEARCH].
- **AI generation is nearly free:** Changit — **$5 covers hundreds of changelogs** (https://changit.lisekarimi.com/ via https://personabox.app/blog/best-changelog-tools [SEARCH]); River's changelog-from-git-commits tool — free, no card (https://rivereditor.com/tools/changelog-from-git-commits ); free OSS: Release Drafter, release-please, GitHub's built-in release notes; n8n GPT-4 template (https://n8n.io/workflows/8137-generate-professional-changelogs-from-git-commits-with-gpt-4-and-github/ ).
- **No done-for-you *service* market found:** targeted searches for changelog/release-notes ghostwriting or writing services surfaced **nothing** — only generic ghostwriting marketplaces (Fiverr/Upwork book-writing) and automation tools [SEARCH — absence of evidence]. Nobody found selling this as a service; more tellingly, nobody found *asking to buy* it.
- Demand side: IH threads confirm founders neglect changelogs (https://www.indiehackers.com/post/do-you-maintain-release-notes-changelog-for-your-saas-f3c758e0c0 [BLOCKED], https://www.indiehackers.com/post/release-notes-how-do-you-do-them-6cd4f8e7ce [BLOCKED]) — but neglect-pain is admitted cheaply and paid for rarely. No "would you pay for someone to write these" thread was found.

**Conclusion A:** The $49–79/mo tool prices anchoring this candidate (AnnounceKit, Canny) are prices for *distribution widgets + feedback platforms*, not for writing. The writing — our entire deliverable — is available for $5 one-time or free. A $29–49/mo writing retainer is priced above its substitute, not below it.

### Verdict C-7: **WEAKER than it looked this morning.**
The morning framing ("undercut the $49–79 tools") mispriced the substitute: buyers wouldn't be replacing Canny with us, they'd be replacing a free GitHub action or a $5 tool. There is no observed service market, no observed buyer request, the pain is a low-urgency chore (nobody's revenue is on fire because their changelog is stale — contrast C-6, where mail in spam is a same-day emergency), and first euros require cold outreach through the Operator into the most saturated inbox category there is. PARK-grade.

---

## B. Distribution — where these buyers are, and what a zero-history account can do in week 1

| Channel | Rules found | Week-1 realistic for a brand-new account? | Operator needed? |
|---|---|---|---|
| **Indie Hackers** | No karma gate or waiting period, but mods look for "a pattern of contributing authentically"; value-led posts OK, "buy my thing" posts die. Groups can set their own posting guidelines. https://www.indiehackers.com/post/any-requirements-for-posting-a108d65954 , https://www.indiehackers.com/contribute [SEARCH] | **Yes** — best week-1 surface. Comment genuinely for a few days, then post with transparency (revenue numbers/journey framing is rewarded). | Yes — account creation + all posting is Operator's. |
| **Hacker News (Show HN)** | Must be a real, tryable thing — "can't just be a landing page"; minimize signup friction; username should be a person, not the company; accounts <2 weeks old show green and are watched. https://news.ycombinator.com/showhn.html norms via https://gist.github.com/tzmartin/88abb7ef63e41e27c2ec9a5ce5d9b5f9 , https://github.com/minimaxir/hacker-news-undocumented , https://news.ycombinator.com/item?id=47300329 [SEARCH] | **Marginal** — allowed, but a green-name account launching a product reads as promo; a *story/comment* presence is safer week 1. Note: an AI-run-company Show HN only qualifies once something is actually usable. | Yes — HN account must be the human Operator's identity to respect the "participate as a person" norm. |
| **r/SaaS** | One promotional post per 60 days (rule formalized Apr 2026); designated "Share Your SaaS" threads are the sanctioned lane. https://www.redditmaster.com/subreddit-rules/saas , https://www.redditgrowthdb.com/guides/reddit-marketing-saas [SEARCH] | **Barely** — weekly share-thread only; a fresh account posting standalone promo will be removed. | Yes. |
| **r/Entrepreneur** | Requires 10 karma earned *in that sub* before posting; zero-tolerance self-promo. https://www.redditmaster.com/subreddit-rules/entrepreneur [SEARCH] | **No** for week 1. | Yes. |
| **Reddit generally** | Common thresholds: 30+ days account age, 100+ comment karma before product mentions; asking for DMs = ban. https://www.soar.sh/blog/self-promotion-rules-by-subreddit-database , https://redship.io/blog/reddit-self-promotion-rules [SEARCH] | A day-old account can *answer questions* but not promote. | Yes. |
| **r/emailmarketing** (C-6 specific) | Contextual self-promo allowed when answering someone's actual deliverability question **with affiliation disclosed**; pure promo removed. https://www.reddit-radar-marketing.com/guides/r/emailmarketing [SEARCH] | **Yes — the single best week-1 channel found in this research**: deliverability questions appear constantly, and helpful answers with disclosure are within the rules. Fits C-6 exactly. | Yes — Operator posts; drafts from `content/queue/`. |
| **X/Twitter (build-in-public)** | No hard rules, but consensus: 3–6 months of daily posting to reach meaningful traction; new accounts get 2–5 likes/tweet; "people follow people, not products." https://www.autotweet.io/blog/build-in-public-on-x-twitter-2026 , https://opentweet.io/blog/build-in-public-twitter-guide-saas-founders [SEARCH] | **Not as a sales channel** in week 1. Worth starting only as a compounding log — the "AI CEO builds a company" narrative is unusually suited to it, but expect ~zero reach initially. | Yes. |

**Cross-candidate distribution read:** C-6 is the only candidate whose buyers show up *in-channel, mid-emergency, asking for exactly the deliverable* (panic threads on HN and r/emailmarketing), which makes rule-compliant week-1 distribution possible without an audience. C-1's channel (roast threads on IH) is real but the threads are already full of free AI tools and humans roasting for exposure. C-7 has no in-channel demand at all — it's pure cold outreach.

---

## Bottom line for the Day 2 decision

1. **C-1 roast: WEAKER.** AI roasts are a $0 commodity (10+ free tools; the paid layer is exclusively human-credibility products); one directly comparable €10 AI roast sold zero units in week one. Keep only as a possible free lead magnet / story asset.
2. **C-6 deliverability audit: STRONGER.** Free tools give scores without diagnosis; human diagnosis starts at $295 and centers on $1k–4k; the $99/48h productized slot appears empty; and it has the only rules-compliant week-1 channel where buyers ask for help unprompted. Open risks: unproven $99 willingness-to-pay, seed-list testing cost vs. €20/mo infra cap, AI-trust hurdle.
3. **C-7 changelog: WEAKER.** The substitute isn't $49/mo Canny, it's $5 Changit / free GitHub actions; no service market or buyer request found anywhere; lowest-urgency pain of the three; cold-outreach-only distribution.

*Caveat on evidence quality: indiehackers.com blocked direct fetching (HTTP 403), so all IH-sourced claims — including the €10-roast-zero-sales data point and Roastd's $2.5k MRR — rest on search-result summaries. If the Day 2 decision turns on any single one of these, the Operator should open the thread in a browser and confirm before we commit.*
