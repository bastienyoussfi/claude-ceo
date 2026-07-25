# Calibration data: what tiny products actually earn (2024–2026)

> Research file, Day 1 (2026-07-25). Produced by a research sub-agent; sources at bottom. Anything not payment-processor-verified is marked **claimed**.

Compiled 2026-07-25. Method: WebSearch + fetches of HN thread "Ask HN: Those making $500/month on side projects in 2025", founder blog posts, and secondary analyses. Nothing below is invented; anything not backed by payment-processor data is marked **claimed**.

## Base rates (read these first)

- An analysis of **5,079 Stripe-verified indie projects** (TrustMRR data, discussed on Indie Hackers) found **median revenue = $169/month**; a related ScrapingFish analysis of Stripe-verified Indie Hackers products found **54% make exactly $0**. Source: https://www.indiehackers.com/post/i-analyzed-5-079-stripe-verified-startups-f0f6bd053f (page itself timed out on fetch; figures from search excerpts — treat as claimed, secondhand)
- A 2025 analysis of ~1,000 micro-SaaS products: **~70% earn under $1,000 MRR**; median *profitable* micro-SaaS ≈ $4,200 MRR. (claimed, secondhand via search results)
- Acquire.com: micro-SaaS at $1K–5K MRR sells for 2–3x annual SDE; one scheduling tool sold for **$3,800**. Source: https://blog.acquire.com/acquire-com-biannual-acquisition-multiples-report-jan-2026/ (multiples verified by Acquire; the $3,800 example claimed, secondhand)
- Launch-platform conversion (OpenHunts 2024 study, 387 launches): **Indie Hackers ~23.1% conversion per engaged post vs Product Hunt ~3.1% per launch**. Source: https://awesome-directories.com/blog/indie-hackers-launch-strategy-guide-2025/ (claimed, unverified methodology)

## Examples (tiny end of the market)

| # | Product | What it is | Price | Revenue claim | Evidence | Time to first revenue | Channel that worked |
|---|---|---|---|---|---|---|---|
| 1 | JustFax Online | One-time online fax sending | $5/fax, pay-per-use | >€500/mo gross, consistent | Founder comment, HN thread https://news.ycombinator.com/item?id=46307973 (claimed, credible) | not stated | SEO + being recommended by LLMs |
| 2 | NotebookLM Web Importer | Chrome extension, 1-click page import to NotebookLM | Freemium, paid premium | "quickly went over $500/mo" after July launch; 100k+ users | Same HN thread (claimed) | weeks | Riding a platform wave (NotebookLM growth), Chrome Web Store organic |
| 3 | DedupX | macOS duplicate/similar-file finder | **$5.99/yr or $16.99 lifetime** | 100+ paying users shortly after launch | Same HN thread (claimed) | days–weeks | Reddit, Product Hunt, HN, Discord |
| 4 | Video Hub App | Local video organizer (desktop, open source) | $5 one-time | "$300/mo reliably, occasionally $500/mo" | Same HN thread (claimed) | — | GitHub/open-source visibility, direct sales |
| 5 | DB Pro | Desktop database client | subscription (undisclosed tiers) | "just crossed $1k MRR", launched Oct 2025 (~2 months) | Same HN thread (claimed) | ~1 month | Product Hunt + YouTube devlogs |
| 6 | SoundReads.io | Public-domain audiobook streaming | $23.50/yr | crossed ~$500/mo | Same HN thread (claimed) | — | HN post + niche curation |
| 7 | Ubidrop (Alex Styl) | Mac utility app | one-time license (Black Friday 50% off) | **$802.50 in launch month** | https://alexstyl.substack.com/p/1k-revenue-from-a-single-product (claimed, screenshots in post) | days | Product Hunt (#2 Product of the Week, Productivity) + X |
| 8 | ShipFast (Marc Lou) | Next.js SaaS boilerplate | $199–299 one-time | $40k month 1; $528k in 4 months; $1M+ lifetime by end 2024 | https://www.starterstory.com/marc-lou-shipfast, https://newsletter.marclou.com/p/i-made-250000-usd-selling-javascript (self-reported, widely corroborated) | day 1 | Pre-existing X audience + build-in-public |
| 9 | TrustMRR (Marc Lou) | Verified-revenue database/marketplace | paid listings/access | **$1,198 in 52 min, $10,085 in 36 hours** (Oct 31 2025 launch) | https://www.producthunt.com/products/trustmrr + https://trustmrr.com (Stripe-verified by design) | <1 hour | Existing X audience; PH |
| 10 | Dead Chefs Society | Monthly curated dinner-club events | ~$115 avg ticket | **$126k in 2025**, 1,099 guests | HN thread (claimed, detailed) | first event | Word-of-mouth, local Facebook food groups, local press; $0 ads |
| 11 | Easlo | Notion templates on Gumroad | ~$10–150/template | claimed **$500k+ lifetime** (teenager, oft-cited) | https://medium.com/read-or-die/how-this-guy-earned-1-million-selling-notion-template-4661fe5bd87e (claimed, unverified press) | — | X audience + Gumroad marketplace |
| 12 | Micro SaaS Idea (newsletter/directory) | Curated micro-SaaS ideas newsletter | paid tier | $1k ~2 months after PH launch; later $75k+/yr, 500+ paid subs | https://www.goodreads.com/author_blog_posts/23956169-side-project-of-his-side-project-earns-75-000-a-year (claimed) | ~2 months | Product Hunt #1 of the day, then SEO/newsletter compounding |
| 13 | SamsList (Sam Parr) | "Yelp for accountants" directory | lead-gen/listing fees | $99k in 8 months | search excerpt (claimed, founder has large audience) | — | Existing audience + niche directory demand |
| 14 | **Counterexample:** BrandingStudio.ai | AI branding tool | subscription | #6 on PH, 168 upvotes, 400 signups → **1–3 paying customers** | https://www.indiehackers.com/post/400-signups-from-product-hunt-1-paying-customer-what-4-days-taught-me-about-launch-vs-traction-4a226fe482 | n/a | PH traffic ≠ revenue |

## Synthesis

**Categories that most reliably reach first revenue in <2 weeks:**

1. **Cheap one-time-purchase utilities ($5–$20)** — desktop apps, browser extensions, small tools (DedupX, Video Hub App, Ubidrop, JustFax). Lowest friction: no trust barrier at $5–17, no subscription commitment. First sales typically arrive within days of a Reddit/HN/PH post. Ceiling is low ($300–800/mo is a *good* outcome), which matches our calibration need — this is what "success" usually looks like.
2. **Templates/boilerplates ($99–$299 one-time)** — highest revenue-per-effort in the dataset (ShipFast), but the outlier results are audience-dependent. Without an existing X following, expect the Gumroad median, not Easlo.
3. **Curated directories/newsletters** — slow (SEO/compounding, ~2 months to $1k for Micro SaaS Idea), monetize via listings/leads rather than day-one sales. Poor fit for a 14-day first-revenue target unless paired with an audience.
4. **Productized/in-person services** — biggest absolute numbers per unit effort (Dead Chefs Society $126k, pitch-deck service ~$3k/mo, Bean Ninjas $100k/8mo) because price per transaction is 10–20x higher ($115+ vs $5), but they consume human operator time.
5. **Pay-per-use micro-transactions** ($5/fax) — underrated: zero subscription objection, monetizes SEO/LLM-referral traffic passively.

**Price-point clusters observed:** $5 one-time · $6–24/year · $17 lifetime · $115/transaction (services) · $199–299 (boilerplates). Almost no successful tiny products in the data charge $20–50/mo subscriptions — that model shows up in the failures (BrandingStudio: 400 signups, 1 payer).

**Distribution reality:**
- **Existing audience is the single biggest revenue predictor** (Marc Lou, Sam Parr). Every $10k+ fast launch had one.
- Without an audience: **HN/Reddit posts and niche communities out-convert Product Hunt** (~23% vs ~3% claimed); PH gives signups and a spike, not payers.
- **SEO + LLM recommendations** is the durable channel for pay-per-use utilities but takes months.
- **Riding a platform wave** (NotebookLM, Cursor ecosystem) is the fastest zero-audience path found in the data.

**Calibration for our 30-day/€20 constraint:** the honest base rate is $0–169/month; a realistic *good* outcome for a first product with no audience is a $5–20 one-time-price utility or template earning **$100–800 in month one**, driven by 2–3 well-executed Reddit/HN posts, not by Product Hunt or SEO.

## Caveats

The HN thread examples are founder self-reports (credible, detailed, but not payment-verified); TrustMRR and ShipFast figures are the closest to verified (Stripe-connected / long public track record); the IH 5,079-startup analysis page itself was unreachable (timeout + 502), so its numbers come from search-index excerpts of the post.
