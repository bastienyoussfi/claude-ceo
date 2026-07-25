# SOP — Order to Delivery (F-1 DFY Job-Search Materials)

> **STATUS: DRAFT — nothing here is live. Pending Day 3 GO decision.**
> This is the per-order operating procedure. The AI executes every step it can; the Operator presses send on Fiverr messages and deliveries. No step in this SOP ever touches a buyer's login, password, or account — that is the product's core trust promise and a hard rule (see feasibility file, LinkedIn/Indeed ToS).

---

## 0. Tier table (draft prices — confirm against OQ-006 package-table check before publishing)

| | Basic | Standard | Premium |
|---|---|---|---|
| Roles covered | 3 | 10 | 30 |
| Draft price (Fiverr lists USD) | $15 | $35 | $75 |
| Net after 20% commission | $12 | $28 | $60 |
| Delivery window (buyer-facing) | 2 days | 3 days | 5 days |
| Internal delivery target | 24h | 48h | 72h |
| Revisions included | 1 | 2 | 3 |
| Role swaps allowed within revisions | 0 | up to 2 roles | up to 5 roles |
| **Operator (human) time cap per order** | **15 min** | **35 min** | **70 min** |
| Implied human hourly at cap | ~$48/h | ~$48/h | ~$51/h |

The human time cap is the profitability line, not the AI wall-clock. AI generation time is effectively free; Operator minutes are the scarce resource. If an order is trending past its cap, stop and check §9 (escalation) before spending more.

---

## 1. Order received — first response (within 1 hour, always)

Fiverr's delivery countdown starts when the buyer submits gig requirements, and response time is a ranking signal. The moment an order lands, Operator sends:

> Hi [buyer first name], thanks for your order! I'm reviewing your CV and target roles right now. If everything's complete I'll confirm within a few hours and get to work — if I need anything I'll ask in one single message so we don't lose time. Quick reminder of how this works: I never ask for any passwords or account logins. You'll receive tailored materials for every role plus a tracker, and you stay in full control of pressing "apply."

Then run intake validation (§2) immediately.

---

## 2. Intake validation

An order is **complete** when all of the following are true:

- [ ] Master CV file received and it opens (.docx, .pdf, or Google Docs link set to public view)
- [ ] CV contains: name, contact method, at least one dated work experience entry
- [ ] Job links: count matches tier (3 / 10 / 30), **or** buyer chose "you find the roles" mode and gave target titles + locations + seniority
- [ ] Every provided link resolves to a live posting (check all of them NOW, not at delivery — dead links found late blow the schedule)
- [ ] Work-authorization answer present (which countries they can legally work in without sponsorship)
- [ ] Tone preference and off-limits answers present (blank is acceptable — treat blank as "professional tone, nothing off-limits")

### 2a. If requirements are incomplete — exact messages

Send **one** consolidated message. Never drip questions. Pick the applicable blocks:

**Missing/unreadable CV:**
> Hi [name], I'm ready to start but the CV file didn't come through readable on my end ([describe: file is empty / password-protected / the link needs public sharing enabled]). Could you re-upload it as a .docx or PDF? The delivery clock is running, so the sooner it arrives the sooner your materials do.

**Fewer links than the tier includes:**
> Hi [name], your [Premium] order covers [30] roles but I received [22] links. Three options — just reply with a number: (1) send me [8] more links, (2) tell me your target role/location and I'll find [8] matching fresh openings myself at no extra cost, or (3) I deliver the [22] now and the remaining [8] as soon as you send links. Any of these works; option 2 is fastest if you're short on time.

**Dead or expired links (report them all at once, with replacements offered):**
> Hi [name], quick heads-up: [3] of your links no longer work — the postings appear to have closed ([list them]). Would you like to send replacements, or shall I find [3] equivalent live openings matching the same role and location? No extra charge either way.

**No links and no usable role description:**
> Hi [name], to find the right openings for you I need a little more direction. Could you reply with: (1) 1–3 job titles you're targeting, (2) locations that work for you (or "remote only"), and (3) your minimum acceptable salary if you have one? With those I can start immediately.

**Missing work-authorization answer:**
> One quick question before I tailor anything: which country/countries can you work in without visa sponsorship? This changes which roles are worth your time, so I never skip it.

**Buyer offers or asks to use their LinkedIn/Indeed/job-board login (decline, always, no exceptions):**
> I appreciate the trust, but I never log into anyone's accounts — that's a firm policy, and it protects you: LinkedIn and Indeed's terms treat shared logins as grounds for restricting *your* account, right when you need it most. My service is built so you never take that risk: I prepare everything (tailored CV, cover letter, direct application link, outreach messages) and you press submit in about two minutes per role. You lose nothing except the risk.

If the buyer insists login-based application is the only thing they want, offer a mutual cancellation politely (a cancellation hurts our stats, but delivering a ToS-violating order can end the account — cancellation is the lesser cost):
> If done-for-you submission using your accounts is essential for you, I'm genuinely not the right seller — no hard feelings, and I'd rather cancel cleanly than deliver something different from what you want. If you'd like to try the no-login version, I'm confident you'll find it does 95% of the work. Your call!

### 2b. Requirements-complete confirmation

> All set — everything I need is here. You'll receive: a tailored CV + cover letter for each of your [N] roles, an application tracker, and outreach message drafts, by [date]. I'll message you the moment it's delivered.

---

## 3. Role verification & sourcing

**Link mode (buyer provided links):** for each link capture into the working folder: company name, exact job title string, location, posting date if shown, full job-description text, and the direct apply URL (prefer the company career page / ATS URL — Greenhouse, Lever, Workday, Ashby — over an aggregator repost when both exist).

**Sourcing mode (we find the roles):** rules for every role we pick:
- Posting is live and ≤14 days old (or has a future deadline)
- Direct company-page or ATS apply link — never "easy apply only" aggregator duplicates when a direct link exists
- Matches buyer's title/seniority/location/authorization constraints — a role the buyer can't legally take is a wasted slot and looks careless
- No duplicate companies within an order unless buyer asked
- Record where it was found and the date, in the tracker's Notes column

**Budget warning:** sourcing mode costs 4–8 minutes per role even with AI search assistance (finding, freshness-checking, de-duplicating, constraint-matching). On a Premium order that is 2–4 hours — it is the single most likely step to blow the time budget. Controls: (a) source in one batch, never interleaved with tailoring; (b) at 20 minutes in, if fewer than 25% of needed roles are found, message the buyer to narrow or broaden criteria rather than grinding; (c) sourcing mode on Premium is capped at 15 roles sourced + 15 buyer links in gig copy if this proves unprofitable in the first three orders — flag to CEO via operator-queue if the cap needs activating.

---

## 4. Per-role tailoring (the actual product)

For each role, AI produces one tailored CV + one cover letter from: master CV + intake answers + the captured job description.

### 4a. Extract from the posting
- Exact job title string (as written, including seniority qualifiers)
- The 8–12 hard requirements (tools, methods, certifications, years, domains)
- Keyword surface forms — the JD's exact spelling wins: "PostgreSQL" not "Postgres", "search engine optimization (SEO)" not just "SEO", "B2B SaaS" not "software"
- 2–3 soft-skill/culture phrases (e.g. "thrives in ambiguity", "cross-functional")
- 1–2 company facts usable in the cover letter (product, market, recent launch — from the JD or the company's own site only; no speculation)
- Disqualifiers to respect (clearance, license, on-site days, language)

### 4b. Mirror in the tailored CV
- Headline/summary rewritten toward this role's title — **only if truthful** (a marketing coordinator may be headlined "Marketing Coordinator — Email & Lifecycle" for an email role; never "Marketing Manager" if they never held it)
- Reorder experience bullets so the most JD-relevant achievements come first in each job entry
- Rewrite bullets to use the JD's keyword surface forms where the underlying fact already supports them
- Skills section reordered and trimmed: JD-matching skills first, irrelevant ones cut (cutting is honest; adding is not)
- Quantify using only numbers the buyer supplied (master CV or intake Q8). A missing number is asked for or omitted — never estimated on the buyer's behalf

### 4c. HARD RULE — never fabricate
**We never invent experience, employers, job titles, dates, degrees, certifications, skills, or metrics. We never stretch employment dates to close a gap. We never add a skill the buyer hasn't claimed. Rephrasing, reordering, emphasizing, and cutting are the entire toolbox.** A CV that lies fails the buyer at the first interview question and fails us at the first Fiverr dispute.

**When a buyer asks us to lie** ("say I have a degree", "change the dates so there's no gap", "add 2 years at a company"), the behavior is fixed: **decline that item, deliver everything else, explain why — warmly, once, without lecturing.** Exact message:

> Happy to do almost anything to make your CV stronger — reframe, reorder, emphasize, quantify — but I can't add [a degree you don't hold / employment dates that didn't happen / experience at a company you didn't work for]. It's not just principle: recruiters verify exactly these things, and a caught fabrication ends a candidacy instantly, sometimes years later. What I *can* do: [concrete honest alternative — e.g. "list your coursework toward the degree as 'in progress'", "present the gap with a one-line honest framing (career break, freelancing, caregiving) — recruiters in 2026 barely blink at gaps", "surface the equivalent experience you DO have from [X]"]. Everything else in your order is unaffected and on schedule.

If the buyer makes fabrication a condition of accepting delivery, offer mutual cancellation with the same calm framing as §2a. Log the event in the order notes.

### 4d. Cover letters
Use the skeleton in `template-deliverable-package.md`. One page maximum, 180–280 words, three paragraphs, at least two role-specific facts (from §4a extraction) and one candidate-specific achievement per letter. No letter may be reusable for a different company by swapping the name — that is the per-order customization bar.

---

## 5. QA checklist before delivery (mandatory, every order — this is the Fiverr AI-policy compliance step)

Fiverr's AI-content standard requires output customized per order. This checklist is how we prove it to ourselves before every single delivery. Operator (or AI with Operator spot-check) verifies:

**Customization (the policy-critical block):**
- [ ] Each tailored CV differs from the master in: headline/summary, bullet order, at least 3 rewritten bullets, and skills block
- [ ] Each tailored CV differs from every *other* tailored CV in the same order (spot-check any 2 side by side)
- [ ] Each cover letter names the right company and role, contains ≥2 facts specific to that posting, and could not be sent to a different company as-is

**Honesty:**
- [ ] Every claim in every tailored CV traces to the master CV or the buyer's intake answers (diff pass: anything new that isn't a rephrasing is a defect)
- [ ] All dates identical to master CV
- [ ] Nothing the buyer marked off-limits appears anywhere

**Cross-contamination (the reputation-killer class):**
- [ ] No file contains another company's name (search each cover letter for every OTHER company name in the order)
- [ ] Buyer's name spelled identically everywhere, contact info matches master CV
- [ ] File names match the convention and the right file is in the right role's folder

**Format (ATS-safe, per package template):**
- [ ] Single column, no tables/text boxes/images/icons, standard font, .docx
- [ ] Opens clean in Word AND Google Docs (both, every time — formatting drift between them is common)
- [ ] CV ≤2 pages, cover letter ≤1 page

**Freshness:**
- [ ] Every job link re-verified live on delivery day (a link that died mid-order → note it in delivery message and offer a free replacement role)

**Tracker & extras:**
- [ ] One tracker row per role, all pre-fillable columns filled, Status = "Materials ready"
- [ ] Outreach kit present for every role (Standard/Premium) or the included roles (Basic: all 3)

Any failed box: fix before delivery. Never deliver with a known defect and a promise to patch it in revision — revisions are for the buyer's preferences, not our misses.

---

## 6. Delivery

Deliver as one .zip through the Fiverr order page (never off-platform), structured per `template-deliverable-package.md`. Delivery message:

> [Buyer first name], your application kit is ready — delivered ahead of schedule. 🎯
>
> **What's inside:**
> - **START-HERE.pdf** — 2-minute guide to using everything
> - **One folder per role** ([N] total): tailored CV + matching cover letter, both .docx so you can tweak freely
> - **Application tracker** (spreadsheet): every role, direct apply link, deadline, and follow-up dates pre-filled — this becomes your mission control
> - **Outreach kit per role**: a recruiter message, a hiring-manager message, and two follow-up drafts, ready to paste
>
> **Your move:** open the tracker, start at row 1, click the apply link, upload that role's CV + letter, hit submit. Two minutes per role — the tedious 95% is done.
>
> Every CV was individually tailored to its posting — reworded and reordered around what each employer asks for, using only your real experience. Nothing invented, ever.
>
> If anything needs adjusting, tell me — your order includes [X] revision(s) and I turn them around fast. Good hunting! 🚀

Deliver at the internal target (§0), not at the deadline — early delivery is a review-quality lever and leaves slack for revisions inside the window.

---

## 7. Revisions

**Counts:** Basic 1, Standard 2, Premium 3. A "revision" = one batch of change requests, not one change.

**In scope (do cheerfully, fast):** tone/wording changes; re-emphasizing different experience; different bullet ordering; cover letter rewrite for an included role; formatting preference changes that stay ATS-safe; swapping roles within the tier's swap allowance (§0) when a posting closed or the buyer changed targets.

**Out of scope (polite redirect):** adding roles beyond tier count; fabrication requests (§4c protocol, doesn't consume a revision — it's a decline, not a change); rewriting the master CV from scratch (that's a different gig/extra); non-ATS formats ("make it a designed PDF with graphics") — explain once:
> I can absolutely restyle it, but a heads-up first: graphic/two-column layouts get scrambled by the applicant tracking systems most companies use to read CVs before a human does. That's why everything I deliver is deliberately plain. If you want a designed version *in addition* for networking/email use, I can add that as an extra — but for the actual application portals, plain wins.

**Out-of-scope volume, exact message:**
> Happy to help with that! It's beyond what the [Standard] package covers ([10] roles / [2] revisions), so the cleanest way is a gig extra — [e.g. "+5 additional roles for $15"]. Want me to send the offer? Everything already delivered stays yours regardless.

**If ATS-unsafe change is insisted on after the warning:** do it, note in the delivery message that it was done at buyer's request against our ATS recommendation. Buyer's CV, buyer's call.

---

## 8. Timing budget per order (the profitability spine)

Minutes are Operator human time; AI wall-clock runs in parallel and is not the constraint.

| Step | Basic (3) | Standard (10) | Premium (30) |
|---|---|---|---|
| First response + intake validation (§1–2) | 4 | 5 | 8 |
| Link verification (link mode) | 1 | 3 | 6 |
| Tailoring supervision (AI generates; human skims flags) | 2 | 6 | 12 |
| QA checklist (§5) — ~1 min per role spot-check pattern: full check on 100% Basic / 50% Standard / 33% Premium + all cross-contamination boxes always | 4 | 10 | 25 |
| Package assembly + delivery message | 3 | 5 | 7 |
| Revision reserve | 1 | 6 | 12 |
| **Total human minutes (cap from §0)** | **15** | **35** | **70** |

**Rules that keep Premium profitable at $75/$60 net:**
1. QA sampling, not exhaustive reading: cross-contamination and honesty boxes are checked on *every* file (they're fast, mechanical searches); deep line-reads are sampled per the ratios above. First 5 orders of the account: 100% deep-read regardless of tier (we're buying our quality bar and first reviews).
2. Sourcing mode consumes the revision reserve first, then triggers §3's controls. A Premium order that is 30 sourced roles at 6 min/role is unprofitable — the gig copy must price sourced-role Premium higher or cap sourced roles (Day 3 pricing decision input).
3. Any single order past 1.5× its human-time cap: finish it (never deliver late or thin), then log what blew the budget in the order notes and flag the pattern to CEO if it repeats twice.

---

## 9. Escalations → `memory/operator-queue.md` / CEO

- Buyer requests anything requiring an account, payment, or credential → Operator only, never AI
- Fabrication demand that persists after the §4c message → offer cancellation, log it
- Any Fiverr ToS ambiguity mid-order (e.g., buyer asks "did an AI write this?" → answer honestly per gig copy: AI-powered, human-reviewed — disclosure when asked is mandatory per the 2026 policy reading)
- Dispute/cancellation threat → Operator handles in own voice, AI drafts options
- Two orders in a row past time cap → CEO decision on pricing/tier structure before accepting the next Premium
