# Deliverable Package Template (F-1)

> **STATUS: DRAFT — pending Day 3 GO decision.**
> This defines exactly what a buyer receives. Every real order is assembled to this spec; the QA checklist in `sop-order-to-delivery.md` §5 verifies against it. The quality bar is `sample-deliverable.md`.

---

## 1. Package structure (delivered as one .zip via the Fiverr order page)

```
Jane-Smith-Application-Kit/
├── START-HERE.pdf
├── Application-Tracker-Jane-Smith.xlsx        (+ .csv copy for Google Sheets import)
├── 01-Brightpath-Software-Marketing-Specialist/
│   ├── Jane-Smith-CV-Brightpath-Software.docx
│   ├── Jane-Smith-Cover-Letter-Brightpath-Software.docx
│   └── Outreach-Brightpath-Software.docx
├── 02-Nordwind-Outdoor-Email-Marketing-Coordinator/
│   ├── Jane-Smith-CV-Nordwind-Outdoor.docx
│   ├── Jane-Smith-Cover-Letter-Nordwind-Outdoor.docx
│   └── Outreach-Nordwind-Outdoor.docx
└── ... (one numbered folder per role, ordered to match tracker rows)
```

**File-naming rules:**
- `Firstname-Lastname-CV-Company.docx` — recruiters download these; the buyer's name must be in the filename (recruiters search their downloads folder by candidate name). Hyphens, no spaces, no underscores, no dates, no "v2", no "FINAL".
- Folder prefix `01-`, `02-`… matches the tracker row number exactly.
- If two roles share a company, append a short role slug: `Jane-Smith-CV-Brightpath-Growth.docx`.

**START-HERE.pdf contents (one page):** how to use the kit in 4 steps (open tracker → row 1 → click link → upload that folder's CV + letter → submit → set Status to Applied), when to send each outreach message, the follow-up rhythm (day 5 and day 12), and one line restating: every file uses only your real experience, nothing was invented.

---

## 2. Tailored CV format conventions (ATS-safe — non-negotiable defaults)

- **Layout:** single column, top-to-bottom. No tables, no text boxes, no columns, no images, no icons, no charts, no photo. Nothing in the Word header/footer (ATS parsers frequently drop header/footer content — the candidate's name goes in the body).
- **Font:** Calibri 11pt body (Arial 11 or Georgia 11 acceptable alternates). Name at 16–18pt bold. Section headings 12–13pt bold, ALL CAPS or Title Case — consistent throughout.
- **File format:** .docx (primary — most ATS-friendly and buyer-editable). PDF only as an additional copy if the buyer requests it.
- **Length:** 1 page up to ~7 years' experience, 2 pages max ever.
- **Section order (mid-level default):**
  1. Name + contact line (city/country, phone, email, LinkedIn URL — no street address)
  2. PROFESSIONAL SUMMARY — 2–3 lines, rewritten per role (this is the highest-value tailoring slot)
  3. CORE SKILLS — one flat list or 2 plain-text rows, 8–12 items, JD-matched items first
  4. PROFESSIONAL EXPERIENCE — reverse chronological; per job: `Job Title — Company, City · MMM YYYY – MMM YYYY` then 3–5 bullets
  5. EDUCATION — degree, institution, year
  6. Optional: CERTIFICATIONS / LANGUAGES / TOOLS (only if load-bearing for the role)
- **Bullets:** start with a strong verb, one achievement per bullet, quantified only with the buyer's real numbers, ≤2 lines each. JD-relevant bullets first within each job.
- **Dates:** `MMM YYYY` format everywhere (`Mar 2022 – Present`). Identical to the master CV — dates are never altered in tailoring.
- **Keywords:** use the job posting's exact surface forms (see SOP §4b). Never white-text keyword stuffing, never a hidden keyword block — ATS vendors flag it and it is exactly the low-trust behavior we sell against.

---

## 3. Cover letter skeleton

One page, 180–280 words, 3 paragraphs + sign-off. `{{double-brace}}` marks a tailoring slot; every slot must be filled with role- or candidate-specific content — a letter where any slot could survive a company swap fails QA.

```
{{Candidate name}}
{{City, Country}} · {{email}} · {{phone}}

{{Date}}

Dear {{Named person if findable in ≤2 min, else "Hiring Team" — never "Sir/Madam"}},

[P1 — WHY THEM, 2–3 sentences] Open with the role by exact title and ONE
specific, verifiable thing about the company from the posting or the
company's own site ({{company fact}}), connected to why the candidate
wants THIS job — not a job. No "I am writing to apply for" openers;
the first sentence must already contain substance.

[P2 — WHY ME, 3–5 sentences] The candidate's strongest 1–2 achievements
({{achievement + real number}}) mapped explicitly onto the posting's top
requirements ({{requirement echo, JD's own vocabulary}}). This paragraph
is the CV's greatest hits ARGUED, not repeated — it says why those
results transfer to this employer's context.

[P3 — CLOSE, 2 sentences] One forward-looking line tying a candidate
strength to something the team is doing ({{second company/role fact}}),
then a plain, confident close: available for a conversation, thank you.
No "I hope", no begging, no "as seen on my resume".

Best regards,
{{Candidate name}}
```

---

## 4. Application tracker (the retention artifact — buyers keep using it after the order)

Delivered as .xlsx + .csv. Header row, one row per role, frozen top row, Status column with data-validation dropdown. Columns, in order:

| # | Column | Filled at delivery? | Notes |
|---|---|---|---|
| A | `#` | ✔ matches folder number | |
| B | `Role Title` | ✔ exact posting title | |
| C | `Company` | ✔ | |
| D | `Job Link` | ✔ direct apply URL, verified live on delivery day | |
| E | `Location / Remote` | ✔ | |
| F | `Salary (posted)` | ✔ if the posting states it, else `Not listed` | never our estimate |
| G | `Deadline` | ✔ if posted, else `Open until filled` | |
| H | `Materials` | ✔ folder name, e.g. `01-Brightpath…` | |
| I | `Date Applied` | buyer fills | |
| J | `Status` | ✔ pre-set to `Materials ready` | dropdown: Materials ready / Applied / Follow-up 1 sent / Follow-up 2 sent / Interview / Offer / Rejected / Closed |
| K | `Contact Name` | ✔ if findable from the posting in ≤2 min, else blank | public info only |
| L | `Contact Link/Email` | ✔ same rule | public info only — never scraped/guessed emails |
| M | `Outreach Sent` | buyer fills (date) | |
| N | `Follow-up 1 Due` | ✔ formula: Date Applied + 5 business days | |
| O | `Follow-up 2 Due` | ✔ formula: Follow-up 1 + 7 days | |
| P | `Notes` | ✔ sourcing note if we found the role; else blank | |

---

## 5. Outreach kit (one `Outreach-{{Company}}.docx` per role folder)

Four ready-to-paste messages per role. All in the candidate's voice, all using only real facts, none mention our service. Structure of the file:

**A. Recruiter LinkedIn message** — ≤300 characters including spaces (LinkedIn connection-note limit), pattern:
> Hi {{first name}} — I just applied for the {{role title}} opening at {{company}}. {{One-line strongest relevant credential}}. I'd love to be on your radar as you review candidates. Thanks!

**B. Hiring-manager LinkedIn message** — sent with or after connecting, 60–90 words: one sentence of genuine specific interest in the team's work ({{company fact}}), one sentence of the single most relevant achievement with its real number, one low-pressure close ("happy to share more if useful").

**C. Follow-up email 1** — send at `Follow-up 1 Due` (5 business days after applying), 70–100 words: subject `Following up — {{Role Title}} application, {{Candidate Name}}`; restate interest in one sentence, add ONE new piece of value not in the letter (a relevant result, link to portfolio/work), close with continued availability. Never "just checking in" as the substance.

**D. Follow-up email 2** — send at `Follow-up 2 Due`, 50–70 words: graceful final touch; states continued interest, invites a response either way, thanks them. After this, the tracker says stop — no third follow-up (that's the line between persistent and pest, and START-HERE says so).

---

## 6. Per-tier package contents

| Item | Basic (3) | Standard (10) | Premium (30) |
|---|---|---|---|
| START-HERE.pdf | ✔ | ✔ | ✔ |
| Tailored CV + cover letter per role | ✔ | ✔ | ✔ |
| Tracker | ✔ | ✔ | ✔ |
| Outreach kit per role | ✔ | ✔ | ✔ |
| Role sourcing ("you find the roles") | — | optional | optional (see SOP §3 budget warning) |

Everything is included at every tier; tiers differ on volume only. Simple to explain, simple to QA, and the $15 Basic is a full-quality sample of the Premium — deliberate: Basic's job is reviews and upgrades, not margin.
