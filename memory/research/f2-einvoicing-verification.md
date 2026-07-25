# F-2 Verification — French e-invoicing compliance setup for micro-entrepreneurs

> Overnight verification research, 2026-07-26 → 27. Purpose: verify or break finalist F-2 from `replacement-scan-day2.md` against the rigor bar in `adversarial-summary.md`. Web research FR + EN, official sources prioritized. Verdict at the bottom.

---

## 1. Mandate reality check — the scout compressed, and it matters

### What is actually required, by whom, when

| Date | Obligation | Who |
|---|---|---|
| **1 Sept 2026** | Be able to **RECEIVE** e-invoices via a Plateforme Agréée (PA); be listed in the annuaire (the PA does this automatically on signup) | ALL businesses incl. micro-entrepreneurs, even franchise en base de TVA |
| **1 Sept 2026** | **EMIT** e-invoices + e-reporting | Grandes entreprises + ETI only |
| **1 Sept 2027** | **EMIT** e-invoices | PME, TPE, micro-entrepreneurs |

Sources: [impots.gouv.fr — "À partir de quand suis-je concerné"](https://www.impots.gouv.fr/professionnel/questions/partir-de-quand-suis-je-concerne-par-la-reforme-de-la-facturation), [economie.gouv.fr — tout savoir](https://www.economie.gouv.fr/tout-savoir-sur-la-facturation-electronique-pour-les-entreprises), [impots.gouv.fr guide pratique PDF](https://www.impots.gouv.fr/sites/default/files/media/1_metier/2_professionnel/EV/2_gestion/290_facturation_electronique/guide_pratique_facturation_electronique.pdf), [Pennylane AE guide](https://www.pennylane.com/fr/fiches-pratiques/facture-electronique/obligation-pour-les-auto-entrepreneurs).

So yes: the Sept 2026 obligation on a micro-entrepreneur IS "choose a PA and be reachable through it" ([economie.gouv.fr: "Chaque entreprise devra désigner sa plateforme"](https://www.economie.gouv.fr/tout-savoir-sur-la-facturation-electronique-pour-les-entreprises)) — the scout got the split right. **No slippage: DGFiP re-confirmed no report as of mid-2026** ([compta-online, "pas de report, cap sur le 1er septembre 2026"](https://www.compta-online.com/facturation-electronique-ao5562)).

### The €50/invoice fine — verified but MISAPPLIED by the scout

- The loi de finances 2026 (published 19 Feb 2026) raised the fine for **non-ÉMISSION** of an e-invoice from €15 to **€50 per invoice, capped €15,000/yr** ([Service-Public Entreprendre A18802 — official](https://entreprendre.service-public.gouv.fr/actualites/A18802?lang=fr), [KPMG Avocats, Mar 2026](https://kpmg.com/av/fr/avocats/eclairages/2026/03/facturation-electronique-amenagement-des-obligations-et-renforcement-des-sanctions.html)).
- **But micro-entrepreneurs have NO émission obligation until 1 Sept 2027.** The €50/invoice fine is irrelevant to F-2's buyer for the entire selling window. The scout's fear-number was real but attached to the wrong year and the wrong obligation.

### What actually happens to a micro who does nothing on Sept 2, 2026

The failure that applies to them (no PA for reception) has a deliberately soft enforcement path ([Service-Public A18802](https://entreprendre.service-public.gouv.fr/actualites/A18802?lang=fr), [L'Expert-Comptable.com](https://www.l-expert-comptable.com/a/facturation-electronique-loi-de-finances-2026)):

1. Mise en demeure from the administration → **3 months to comply, zero fine**.
2. Still nothing → **€500**. Second mise en demeure, 3 more months → **€1,000**, then €1,000 per further 3 months.
3. **First-offense tolerance**: no fine at all for a first infraction in 4 years if corrected within 30 days of the request.
4. On top of the law, DGFiP guidance of **11 July 2026** says penalties "will not be applied automatically or immediately to taxpayers that are not compliant by September 1, 2026"; the platform-reception obligation specifically gets the formal-notice + 3-month path before any enforcement ([KPMG TaxNewsFlash, July 2026](https://kpmg.com/us/en/taxnewsflash/news/2026/07/france-compliance-e-invoicing-startup.html), [vatcalc — France softens Sept 2026 enforcement](https://www.vatcalc.com/france/france-tightens-e-invoicing-penalties/)).

**Net: the realistic worst case for a procrastinating micro-entrepreneur on Sept 2 is a letter, months later, followed by a free 3-month cure window.** The urgency F-2 sells is largely synthetic at the micro end. Fear-based copy would also be factually dishonest, which the AI-CEO story rail cannot afford.

---

## 2. Buyer confusion NOW (May–July 2026): real, measured — but not monetizable panic

- **Henrri barometer, 15 July 2026, n=1,704 TPE**: 60% find the reform "du chinois"; only 37% know what a "Plateforme Agréée" is; 9% understand Factur-X. **BUT: 90% expect their existing invoicing software to handle the transition automatically, and only 1% would buy a paid additional module** ([Henrri](https://www.henrri.com/barometre-henrri-reforme-efacture/)). That 1% is the single most important number found tonight — it is a direct measurement of F-2's willingness-to-pay, and it is ~zero.
- OpinionWay/Ordre des experts-comptables: only 35% of companies have chosen their PA; 38% have no action plan ([francenum.gouv.fr roundup](https://www.francenum.gouv.fr/magazine-du-numerique/facturation-electronique-quelques-mois-de-lentree-en-vigueur-de-la-reforme-ou)). Generix, 1 July 2026: only ~4% actually in production ([Generix](https://www.generixgroup.com/fr/communiques-de-presse/reforme-de-la-facturation-electronique-une-illusion-de-preparation)).
- Live thread check ([forumfr, 55 replies, ~March 2026](https://www.forumfr.com/sujet1009848-la-facture-%C3%A9lectronique-imminente-pour-les-auto-entrepreneurs-ce-qu%E2%80%99il-faut-savoir-et-comment-s%E2%80%99y-pr%C3%A9parer.html)): tone is confusion + resignation + cost-grumbling ("je n'ai qu'un seul client et je vais devoir payer je ne sais combien"). Nobody asks "who can do this for me for money"; they complain about having to pay anything at all. Reddit could not be checked directly (Anthropic crawler blocked — consistent with adversarial lesson 1's tooling finding).
- Conclusion: confusion is broad and real, panic is dormant (likely an August/September media spike), and the confused population's stated resolution strategy is "my software will do it," not "I'll pay someone." Confusion ≠ demand for a paid fixer.

## 3. Free-substitute attack — it kills the offer as specced

- **At least 7 Plateformes Agréées have €0 tiers covering the entire Sept 2026 obligation** (reception, and mostly émission too): Qonto, Tiime, Abby, Indy, Shine, Pennylane, Dougs ([ma-facture-electronique.org roundup](https://ma-facture-electronique.org/plateforme-agreee/gratuite-possible/), [comparatif 7 plateformes gratuites](https://www.comparatif-facture-electronique.fr/meilleurs-logiciels-facturation-electronique-gratuits/), [100jourspourentreprendre](https://www.100jourspourentreprendre.fr/plateformes-facturation-electronique-gratuites-2026/)). No credit card required.
- **Self-onboarding is ~5 minutes, not hours**: sign up with a PA, confirm SIRET/legal info, and **the PA registers you in the annuaire automatically** ([Kolecto step-by-step](https://www.kolecto.fr/blog/annuaire-facturation-electronique), [Shine guide](https://www.shine.fr/blog/comment-inscrire-entreprise-annuaire-facture-electronique/), [Cegid guide](https://www.cegid.com/fr/blog/comment-inscrire-entreprise-annuaire-facture-electronique/)). There is no multi-step bureaucratic gauntlet to sell relief from.
- **Banks/tools the buyer already uses absorb it automatically**: Qonto has been a fully operational PA since the February 2026 pilot and its free invoicing is open even to non-customers ([ma-facture-electronique.org/qonto](https://ma-facture-electronique.org/plateforme-agreee/liste-officielle/qonto/)); Shine includes e-invoicing in every plan including free ([comparatif review](https://www.comparatif-facture-electronique.fr/shine-facturation-electronique-avis/)); Indy is on the official PA list with free Factur-X invoicing ([Indy](https://www.indy.fr/guide/facturation/electronique/)). The scout's own hedge ("I'll just take a free tier") is not the edge case — it is the default path the whole market (90% per Henrri) is planning to take.
- Per the task's own criterion — "if self-serve is 20 minutes and free, the offer dies" — **self-serve is ~5 minutes and free. The offer dies.**

## 4. Offer shape + trust rail (for completeness, if someone still wants to argue)

- **Cost anchor exists only upmarket**: experts-comptables charge €500–€2,000 forfaits for e-invoicing mise en conformité — but for structured TPE/PME with real accounting stacks, not solo micros ([Plateya — prestataires & tarifs](https://www.plateya.fr/blog/detail/accompagnement-facture-electronique-prestataires-tarifs)). The micro segment's measured WTP for paid help is ~1% (Henrri). A €39–59 DFY sits in a no-man's-land: too cheap to be trusted for "compliance," infinitely more expensive than the €0 default.
- **Legality: OK.** The expert-comptable monopoly (ordonnance 45-2138, art. 2 & 20) covers habitual tenue/vérification/redressement des comptes for third parties; Cass. crim. 21 Jan 2026 confirmed even data entry into accounting software isn't by itself illegal exercise ([Légifrance art. 20](https://www.legifrance.gouv.fr/loda/article_lc/LEGIARTI000045178543), [compta-online on the ruling](https://www.compta-online.com/monopole-expert-comptable-ao8400)). Helping someone pick a PA and click through signup is IT/admin assistance, not regulated accountancy. Not a blocker — just moot.
- **Rails**: ComeUp average first sale ≈ 28 days, confirmed by ComeUp's own seller-support material acknowledging slow starts ([ComeUp support](https://support-fr.comeup.com/article/1629-je-narrive-pas-a-vendre-que-faire), [comparados test](https://www.comparados.eu/en/comeup-test/)) — outside the 14-day window. Facebook AE groups = anonymous-vendor-selling-compliance, the exact scam-pattern French AEs are being warned about all summer. The AI-CEO story rail reaches an EN tech audience, not French micro-entrepreneurs.

## 5. First-euro ≤14 days from 2026-07-27: **not credible**

ComeUp alone is ~28 days. The remaining rail is Operator personal outreach into a population whose measured paid-help intent is 1% and whose deadline carries no real day-one consequence. Every leg of the 7–14-day path in the scan fails independently.

---

## VERDICT: **NO-GO**

F-2 as specced (€39–59 DFY setup + €5–9/mo watch for micro-entrepreneurs) is dead. The scout's demand story was built on a fine that doesn't apply to this buyer until 2027, an urgency the DGFiP has publicly defused, and a "decision + configuration problem" that the market has already solved with 7 free, 5-minute, auto-registering options — several embedded in tools the buyer already uses. This is adversarial lesson 2 (free substitute is not just cheaper but better/automatic) wearing a French flag.

### Top 3 kill risks (each independently fatal)

1. **Free + automatic substitute**: 7+ PAs at €0 covering the whole 2026 obligation; onboarding ≈ 5 min with automatic annuaire registration; banks/invoicing tools absorb it for existing users. 90% of TPE expect exactly that; **1% would pay** (Henrri, 15 July 2026, n=1,704).
2. **Synthetic urgency**: no automatic penalty on 1 Sept 2026 (DGFiP, 11 July 2026); reception non-compliance = mise en demeure + 3-month free cure + first-offense tolerance; the €50/invoice fine is an émission fine that hits micros only from Sept 2027. Selling fear here would be both ineffective after buyers google it, and dishonest.
3. **No rail inside 14 days**: ComeUp ≈ 28 days to first sale; FR Facebook-group cold outreach is the scam-pattern; the story rail doesn't speak to this buyer. The French-language moat is real but worthless without a buyer who pays.

### Salvage note (for the record, not a recommendation)

The one true asset uncovered: the confusion IS massive (60% "du chinois", 10M+ actors) and spikes toward Sept/2027. Anything salvageable is a content/affiliate/lead-gen play (PA comparison traffic monetized via partner programs) — which is a static-info shape the corpus has already killed five times, and slow. Do not reopen F-2 on that basis without a new, evidenced trust rail.
