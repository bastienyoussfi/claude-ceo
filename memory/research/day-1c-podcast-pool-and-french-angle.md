# Day 1c — C-2 Buyer Pool Reality Check & the French/EU Angle

*2026-07-25, research wave 3. Research only, nothing posted. Companion to `day-1b-creator-offers-competition.md` (which set the C-2 wedge: "finished, voice-matched, zero-editing" show notes ~€25/episode for podcasters burned by Castmagic/Podsqueeze-type output).*

**Evidence-quality labels:**
- **[HIGH]** = official/government/platform first-party source
- **[MED]** = vendor first-party pricing, or multiple independent sources agreeing
- **[LOW]** = single blog/aggregator claim, search-engine-summarized, competitor writing about competitor, or my inference

---

## JOB 1 — Is there a reachable pool of podcasters who hate AI show-notes output?

### 1A. The complaint corpus: real but QUIETER than the wedge assumes

What I could actually find people saying, with sources:

- **"Generic without custom prompts"** — Castmagic reviews across aggregators: "the pre-defined content is generic; a custom prompt significantly enhances the output," "accuracy may decline with complex or technical subjects," transcript editing called "a major time-waster" [MED — multiple aggregators agree] https://tekpon.com/software/castmagic/reviews/, https://appsumo.com/products/castmagic/reviews/, https://hackceleration.com/labs/review/castmagic. One AppSumo review title: "A good beginning, but also trying to be everything" https://appsumo.com/products/castmagic/reviews/a-good-beginning-but-also-trying-to-be-343967/.
- **Voice mismatch acknowledged even by the tools' own ecosystem** — Descript's 2026 roundup of show-notes AI tools concedes machine output "risks sounding repetitive or generic… that personal spark gets lost" and recommends DIY Claude-with-transcript workflows "if you want your show notes to sound like you wrote them" [MED — category leader admitting the flaw] https://www.descript.com/blog/article/the-best-ai-tools-for-podcast-show-notes-reviewed.
- **Independent head-to-head testing exists as a genre** ("Show notes generators tested — which…") — dissatisfaction is a live topic [LOW] https://thepodcasttechstack.substack.com/p/show-notes-generators-tested-which.
- **What I could NOT find:** first-person Reddit/X threads saying "AI show notes wasted my time, I went back to writing my own." Multiple query formulations returned zero direct Reddit hits (Reddit also blocks unauthenticated fetch, so I could not read r/podcasting directly). **Honest read: the editing-burden pain is documented in reviews [MED] but it is not a loud, searchable, top-of-mind scream.** The words buyers actually use are *generic, accuracy, custom prompts, tweaking, time-waster* — not "I'd pay a human instead." That last leap is our hypothesis, not their words. [LOW for the leap]

### 1B. Where reachable podcasters concentrate

**Facebook groups (the big pools, all Operator-account-dependent):** [MED — Buzzsprout roundup + group pages]
- Podcast Movement Community: 32k–61k members (sources conflict; 32k older, 61.3k newer) https://www.facebook.com/groups/podcastmovement/, https://www.buzzsprout.com/blog/best-podcast-communities
- Buzzsprout Podcast Community: 44k+ members
- Podcasters' Support Group: 42k+ members
- She Podcasts: ~21k members
- Podcast Movement itself is now an events+media brand ("world's largest podcasting community") https://podcastmovement.com/ — its FB group is the practical entry point, not a forum.

**Reddit:** r/podcasting rules could not be verified first-party (fetch blocked). Secondary sources consistently describe promo as gated: participation history required, low-karma filtered, service promotion effectively banned outside designated threads [LOW–MED] https://dev.to/sh20raj/reddit-self-promotion-framework-how-to-post-smart-and-stay-unbanned-1kfg (consistent with day-1b findings via thepodcasthost.com). Treat Reddit as a listening channel, not a selling channel.

**Databases / list-building:**
- **Podchaser Pro** sells exactly the asset we want (RSS-extracted contact emails, 25+ filters, CSV bulk export) — but pricing is **$2.5k–5k/YEAR**, agency-grade, no self-serve tier [MED] https://features.podchaser.com/pro/contacts/, https://rephonic.com/blog/podchaser-pro-pricing/. Out of budget; its existence proves the outreach-to-podcasters market is monetized.
- **Listen Notes API**: 3.79M podcasts searchable, developer self-serve [MED] https://www.listennotes.com/api/. Combined with the Apify RSS scraper from day-1b, **DIY scraping of public RSS contact emails remains the accessible path** — with the day-1b caveat intact: hosts now hide emails because of exactly this spam (Transistor/RSS.com), so the channel is pre-poisoned.
- New-podcast lists with contact info: no free/cheap first-party source found; Podchaser/Rephonic paywall this. [MED absence]

### 1C. People currently PAYING humans for show notes (the anchor that matters)

- **Fiverr**: an active category ("24 Best Podcast Show Notes Services") with gigs at $5 (robertplank, 300 words per ≤90-min episode), $20 (edirito), $30 (script+notes) — reviews confirm repeat buyers ("received 5 show notes on time") [MED — first-party gig pages] https://www.fiverr.com/gigs/podcast-show-notes, https://www.fiverr.com/robertplank/listen-to-your-podcast-and-write-your-show-notes, https://www.fiverr.com/edirito/write-your-podcast-show-notes. Exact order counts weren't retrievable this session (would need page-level scraping) — flagging as follow-up. [LOW on volume]
- **Upwork**: dedicated "Podcast Show Notes Jobs" category exists https://www.upwork.com/freelance-jobs/podcast-show-notes/; writer median $40/hr (typical $30–59), podcast producers median $25/hr [MED] https://www.upwork.com/hire/writers/cost/, https://www.upwork.com/hire/podcasting-freelancers/cost/.
- **ZipRecruiter**: "Podcast Show Notes Writer" salaried/contract listings at **$23–70/hr** [MED] https://www.ziprecruiter.com/Jobs/Podcast-Show-Notes-Writer.

**Job 1 verdict:** Paying human-buyers exist at every tier ($5 Fiverr → $70/hr US jobs), so €25/episode sits inside a proven price band, and pools of tens of thousands of podcasters are one Facebook join away (Operator-dependent). But the "hates their AI tool" segment is documented mostly in reviews, not in loud community complaints — meaning we likely can't find them by listening; we'd have to *create* the comparison moment (free sample of their latest episode vs. their tool's output). That raises acquisition cost per customer above the day-1b estimate.

---

## JOB 2 — The French/EU angle (Operator is French; competitors are anglophone)

### 2A. French podcast market: big audience, small indie-creator buyer pool

- **Official volume (Arcom/Ministère de la Culture Observatoire des podcasts):** >100,000 francophone podcast series, >10M episodes, 25,000+ distinct publishers; offer grew +116% in 4 years [HIGH] https://www.arcom.fr/se-documenter/etudes-et-donnees/etudes-bilans-et-rapports-de-larcom/observatoire-des-podcasts-volume-et-caracteristiques-de-loffre-de-podcasts-francophones, https://www.culture.gouv.fr/content/download/375243/pdf_file/Observatoire%20des%20podcasts%20Axe2_VDEF.pdf
- **The catch: 86% of francophone episodes come from RADIO publishers** (Radio France etc.) who have in-house production — not buyers. The addressable pool is native/independent podcasters, a fraction of the 25k publishers (many of which are individuals/associations) [HIGH for the 86% figure, LOW for pool-size inference].
- Audience healthy and growing: ~47% of French people listen regularly in 2025 (44% 2024, 38% 2023) [MED] https://threeriversinstitute.org/chiffres-cles-podcast-2025/, https://lesmakers.fr/statistique-podcast/.

### 2B. French show-notes / post-production: higher human anchor, NO productized show-notes offer found

- French per-episode service prices: **rédaction/script €50–150; montage/post-production €150–400; full 30-min episode €450–740** [MED — French agency/blog aggregation] https://gopoddy.fr/prix-podcast/, https://blog.getasound.com/prix-creation-podcast/, https://www.aurevoircharlie.com/combien-coute-un-podcast-le-vrai-budget-poste-par-poste/, https://lafabriqueapodcast.com/nos-tarifs/. Malt freelance day rates for adjacent skills: €370–400/day [MED] https://www.malt.fr/t/barometre-tarifs.
- **I found no French-language productized "show notes only" service at any price** — the deliverable exists only bundled inside €400+ agency post-production [MED absence-of-evidence — searched in French]. A €25/épisode offer would be alone in its slot AND priced far under the French human anchor.
- **But the SaaS competitors are already localized:** Podsqueeze runs full French marketing pages (podsqueeze.com/fr/…, from $5.99/mo) and was covered by Blog du Modérateur; Castmagic has /fr/ blog content [MED] https://podsqueeze.com/fr/ai-podcast-generator/, https://www.blogdumoderateur.com/tools/podsqueeze/. So French is not competition-free — it's *service*-competition-free but not *tool*-competition-free. (AI output quality in French is plausibly worse than English — untested inference [LOW].)
- **French communities are small:** Podcastéo — ~2,000-member Facebook group (promo allowed Thursdays only), ~180-member Discord, association with directory + awards [MED] https://gensdinternet.fr/2019/03/06/podcasteo-lassociation-qui-veut-promouvoir-les-podcasts-independants/, http://podcasteo.fr/lecosysteme/. Versus 40k+ anglophone groups: the French pool is ~5% the size. Small enough that one Operator could genuinely become known in it; too small to support fast validation-signal collection.

### 2C. French deliverability: the strongest French finding of the day

- **The pain is officially large:** among active French domains, **SPF 69%, DKIM 40.7%, DMARC only 19.5%** — i.e. ~80% of French domains are non-compliant with the Gmail/Yahoo requirements enforced since Feb 2024, with Gmail escalating to outright rejections since Nov 2025 and **Microsoft joining in May 2025** (critical because French PME/ETI are heavily Microsoft 365) [MED — French ESP trade source] https://www.ediware.net/technique/regles-gmail-yahoo-2024-2025/, https://www.blaaaz.com/delivrabilite-email-2026-votre-newsletter-arrive-t-elle-vraiment/, https://www.itforbusiness.fr/dmarc-se-preparer-aux-nouvelles-exigences-authentification-emails-de-google-et-yahoo-72013.
- **The panic is visible in French SMB spaces:** WebRankInfo forum threads ("Problème de Délivrabilité Emails") [MED — live forum] https://www.webrankinfo.com/forum/t/probleme-de-delivrabilite-emails.182359/; a documented case of a Hauts-de-France PME blocked over missing SPF/DKIM/DMARC [LOW] https://www.blaaaz.com/delivrabilite-email-2026-votre-newsletter-arrive-t-elle-vraiment/; French how-to content mills exist (emailing.fr, custup.com, mo-jo.fr) but they sell content/consulting, not a cheap fix.
- **French-language help exists but is priced for mid-market, not SMBs:** Badsender (French emailing agency, deliverability practice) bills **€840/day or €120/hour HT** [MED — first-party] https://www.badsender.com/en/2023/01/03/why-agency-prices-always-seem-too-high/, https://www.badsender.com/en/agency/deliverability/; MailSoar is a French deliverability firm selling audits (pricing page blocked, quote-based) [MED] https://mailsoar.fr/nos-solutions-et-services/audit-de-delivrabilite/; Florence Consultant, MailGenius-fr similar consulting posture. **Nobody found selling a fixed-price "mise en conformité SPF/DKIM/DMARC pour PME" at, say, €150–300 one-time, in French** [MED absence-of-evidence]. That slot — below €840/day consulting, above free blog posts — appears empty.

### 2D. General "French = less competition" evidence

- Qualitative only: most micro-SaaS/productized tools are English-only; French B2B buyers are documented as slower, trust-driven, preferring long-term relationships and native-language dealings (Toubon law even mandates French for software marketing) [LOW–MED] https://superframeworks.com/articles/untapped-underserved-micro-saas-niches, https://www.magneticway.com/en/marketing-intelligence/france-vs-us-difference-b2b-marketing-practices/. No hard pricing data proving French services command better margins [none found]. Cuts both ways: less competition, but slower buying cycles and more skepticism of unknown vendors — which the Operator's French identity partially offsets.

---

## Closing assessment for the Day 2 decision

**Does the French angle strengthen any candidate enough to matter? Yes — the deliverability candidate, materially. Not C-2.**

1. **C-2 podcast show notes:** Job 1 confirms paying buyers exist ($5–70/hr human band; €25 sits comfortably inside it) and pools of 40k+ podcasters are reachable via Operator-joined Facebook groups. But the "hates their AI tool" segment is quiet — found in reviews, not in searchable complaints — so acquisition means manufacturing the comparison (free sample) one podcaster at a time. **The French sub-angle is neutral-to-weak for C-2:** no French productized competitor and a higher human anchor (€50–150 rédaction), but the indie buyer pool is ~5% the anglophone size, Podsqueeze already markets in French at $5.99/mo, and the main community (Podcastéo, 2k members, promo Thursdays) is too small for fast signal collection. If C-2 proceeds, run it anglophone with the French community as a bonus channel.
2. **Deliverability candidate:** the French angle changes its shape. ~80% of French domains lack DMARC, enforcement is escalating (Gmail Nov 2025 rejections, Microsoft May 2025), panic is visible on French SMB forums, and French-language supply is bimodal — free blog posts or €840/day agencies — with **no fixed-price SMB offer found in the gap.** A French Operator selling "mise en conformité e-mail, prix fixe" in French, into WebRankInfo-type forums and French LinkedIn, faces near-zero direct competition at that price point. This is the single strongest new fact from wave 3.
3. **Caveats on the French deliverability play:** absence-of-evidence searches are one session deep; MailSoar's quote-based pricing could reach down-market; French SMB sales cycles are slower and trust-driven [LOW–MED]. Verification task for Day 2: find 5 live French forum/LinkedIn threads under 60 days old showing the panic, and price-check MailSoar/2 competitors by direct inquiry (Operator).
4. **Scoring implication:** if Day 2 weighs "distribution channel where we have unfair advantage," the French Operator + empty French fixed-price deliverability slot should add meaningful points to the deliverability candidate; the French angle adds ~nothing to C-2/C-3/C-5.
