# Adversarial Validation Report — C-3 / C-6 / C-7 (AI-run productized services)

> Filed Day 1 (2026-07-25), adversarial wave. Agent's recommendations: C-3 **KILL**, C-6 **WOUNDED (best survivor)**, C-7 **WOUNDED (only via pivot ≈ kill as specced)**. Formal verdicts to be appended to `candidates.md` in the Day 2 decision session.

Method: web search + page fetches, July 2026. Fiverr and Etsy listing pages return 403 to direct fetch, so per-gig review counts could not be scraped directly; prices and gig density come from search-indexed pages. Flagged wherever evidence is indirect.

---

## C-3 — €5–10/batch "photos → 10 marketplace-ready listings" (death piles)

### 1. Fiverr/VA floor
- eBay description gigs from **$10** ([thewritequeen](https://www.fiverr.com/thewritequeen/write-an-awesome-ebay-description)); Fiverr's cost guide puts listing-optimization projects at ~$91 ([guide](https://www.fiverr.com/resources/guides/costs/ebay-listing-expert)).
- VA agencies do full eBay listing work at **$6.50–6.99/hr** ([vamasters](https://vamasters.com/ebay-marketplace-virtual-assistant/), [keachassistants](https://keachassistants.com/ebay-virtual-assistant-services/), [zenius](https://zenius.co/solutions/ebay-virtual-assistant/)). At €0.50–1/listing we'd price below Filipino VA agencies while offering less (they also upload).

### 2. DIY-with-AI substitute — the fatal one
- **eBay gives this exact product away free, in the app.** "Magical Listing": photo in → specifics, category, title, description out; **10M+ sellers, 100M+ AI-created listings** ([ebayinc](https://innovation.ebayinc.com/stories/magical-listing-tool-harnesses-the-power-of-ai-to-make-selling-on-ebay-faster-easier-and-more-accurate/), [retaildive](https://www.retaildive.com/news/ebay-ai-magical-listing-product-descriptions-listings/693185/)); bulk version too ([ebayinc](https://innovation.ebayinc.com/stories/magical-bulk-listing-tool-is-ebays-latest-ai-powered-time-saver-for-sellers/)).
- SaaS crowds the residual gap: FlowLister ([flowlister](https://flowlister.com/blog/ebay-listing-from-photo/)); Vendoo $14.99/mo with AI + PhotoRoom across 10+ marketplaces ([pricing](https://www.vendoo.co/pricing)).

### 3. Platform rules
- Delivering listing text violates nothing; Vinted discourages automated access — the customer still does the actual listing on the phone app ([selleraider](https://selleraider.com/vinted-terms-and-conditions-update/), [quicklistai](https://quicklistai.org/crosslisting-rules-by-platform/)).

### 4. Delivery friction — second fatal flaw
- A "marketplace-ready" listing needs what a photo cannot contain: measurements, weight, flaws, authentication, price research. Get them wrong and the *seller* eats the return/defect. eBay community consensus on outsourced listing: hires "list at the same speed as you, or slower"; consignment listers want **50%+ of sale price**; "not worth it" ([thread](https://community.ebay.com/t5/Selling/How-to-find-someone-to-list-items-for-me/m-p/34207590/highlight/true), [thread](https://community.ebay.com/t5/Selling/How-to-find-someone-to-help-me-list/m-p/34297186)). Per €5–10 order, collecting 10 items' details destroys unit economics of attention.

### 5. Transaction evidence
- Death piles are a real, named pain (eBay's own podcast covers it — [episode](https://community.ebay.com/t5/eBay-for-Business/Ep-276-Tackling-Your-Death-Piles/ba-p/34228469)) — but **zero evidence of anyone paying per-batch remote listing-drafting at this price**. The pain is monetized via consignment (30–50% rev share) or SaaS subscriptions, never €5 gigs.

### VERDICT: KILL
The platform ships this feature free to 10M sellers; the residual work is exactly the part a remote AI service cannot do; the price point is below the attention cost of collecting inputs.

---

## C-6 — €9–19 "your 10 best Etsy listings optimized" (tags/titles/descriptions)

### 1. Fiverr floor
- Direct incumbents at **$5–35**: [$5](https://www.fiverr.com/designer_rafy/etsy-description-etsy-seo-listing-etsy-title-etsy-tag-etsy-rank-etsy-rank-ca04), [$10](https://www.fiverr.com/webservices07/boost-your-shop-title-tags-writing-rewriting-create-content), [$15](https://www.fiverr.com/vadimthai/do-etsy-tags-and-title-seo), [$35](https://www.fiverr.com/sbdesign6/optimize-your-etsy-seo-by-writing-your-etsy-titles-and-tags). Identical delivery model. €9–19 sits inside an occupied band with zero differentiation as an anonymous vendor.

### 2. DIY-with-AI substitute
- Heavy: a Gumroad economy of "ChatGPT prompts for Etsy SEO" packs ([1](https://chatgptaihubcom.gumroad.com/l/ChatGPT-Prompts-for-Etsy-Listing), [2](https://overhauldesigns.gumroad.com/l/etsyprompts), [3](https://ehaven.gumroad.com/l/ChatGPTPrompts)) — people pay $5–15 for *prompts*, which cuts both ways: DIY intent is high, but paying for shortcuts is normalized. eRank/EtsyHunt/Marmalead are sub-$10/mo substitutes.

### 3. Platform rules — the one genuinely good finding
- The category is **scam-tainted** via DM/Fiverr cold pitches ([nifty.ai](https://nifty.ai/post/etsy-scams-for-sellers)) — anonymous cold outreach reads as scam.
- **BUT**: Etsy explicitly allows custom writing/design services as digital files and loosened its Services Policy in June 2025 ([policy](https://www.etsy.com/legal/policy/services/242665313101), [analysis](https://www.cindylouwho2.com/blog/2025/6/16/etsy-now-allows-shops-to-sell-services-that-the-site-used-to-prohibit)). Shop-critique/SEO-audit listings sell **on Etsy itself**, with reviews and "Etsy Pick" badges ([example](https://www.etsy.com/listing/1860559834/etsy-shop-critique-seo-review-expert), [example](https://www.etsy.com/listing/4307951184/etsy-shop-critique-2026-full-seo-audit), [market page](https://www.etsy.com/market/etsy_shop_audit)). Selling *on* Etsy solves the trust/distribution problem.

### 4. Delivery friction
- Lowest of the three: shop URL in (public), text/PDF out, no account access. Caveat: must disclaim "3–4 weeks before Etsy search reflects changes" — refund/1-star risk window on a platform where reviews are existential.

### 5. Transaction evidence
- Strongest of the three at the proposed price: visible purchases of $5–35 Fiverr gigs AND Etsy-native audit listings with accumulated reviews, both recent.

### VERDICT: WOUNDED — survivable with required changes
(1) Sell it *as an Etsy digital listing*, not cold outreach or a standalone site — the only trust wedge an anonymous vendor has; (2) price at the $19–29 audit+rewrite tier with before/after keyword-volume evidence, not the $9 tier where $5 incumbents with review moats live; (3) never promise rankings/sales.

---

## C-7 — €9–15/episode podcast show notes (+ titles + social posts)

### 1. Fiverr floor
- Occupied at **$5–20**: [$5](https://www.fiverr.com/estelwriters/write-podcast-description-and-show-notes), [$10 in 24h](https://www.fiverr.com/tess_paul/write-your-podcast-show-notes-in-24-hours), [$15](https://www.fiverr.com/anubhav3345/write-your-podcast-show-notes-in-less-than-48-hours), [$20](https://www.fiverr.com/edirito/write-your-podcast-show-notes); a whole category with 500+ results ([category](https://www.fiverr.com/categories/writing-translation/podcast/show-notes)). €9–15 is exactly the incumbent band.

### 2. DIY-with-AI substitute — structural squeeze
- Podsqueeze: show notes + timestamps + newsletters for **$12–24/month** (ALL episodes) ([site](https://podsqueeze.com/blog/how-to-choose-a-podcast-show-notes-service-actionable-tips/)); Castmagic similar.
- **Hosting platforms bundled it**: Buzzsprout's Cohost AI ($10–30/mo) produces titles, descriptions, chapters, transcript, blog post, and three social posts on upload — the entire C-7 deliverable inside the tool the podcaster already uses ([review](https://www.creatorstackclub.com/software/buzzsprout), [roundup](https://blog.podbean.com/best-podcast-platforms-ai-publishing-tools/)). A weekly podcaster at €12/episode pays ~€50/mo for what their host does at €10–30/mo.

### 3. Platform rules
- r/podcasting rules unverifiable (Reddit blocks fetch); assume standard hard anti-promo norms; distribution unproven.

### 4. Delivery friction
- Structurally best of the three: RSS/episode URL in (automatable), recurring by nature. Counterweight: podfade — most shows die young, so per-episode revenue churns with the shows.

### 5. Transaction evidence
- Real money at *other* price points: Fiverr $5–20 sells; B2B human writers and PodReacher charge **$50–150/episode** ([podreacher](https://podreacher.com/show-notes/), [story](https://dollarsprout.com/entrepreneur-success-stories-podreacher/)); podcast VAs $500–800/mo retainers. €9–15 is the worst place to stand: above free/bundled AI, below trusted humans, level with reviewed incumbents.

### VERDICT: WOUNDED — but the required change makes it a different business
As specced (€9–15/episode, anonymous): dead. The surviving variant is $49+/episode B2B podcast content repurposing (PodReacher's slot) — requiring editorial reputation, not an AI pipeline plus a Stripe link. If that pivot isn't on the table, treat as KILL.

---

## FINAL RANKING

1. **C-6 — WOUNDED, best survivor.** Strongest transaction evidence at the actual proposed price, lowest delivery friction, and uniquely a legitimate distribution wedge: Etsy's 2025 policy change permits selling it as a digital listing on Etsy, where trust and reviews accrue on-platform instead of starting from anonymous zero.
2. **C-7 — WOUNDED, only via pivot** to $49+ B2B content shop; not the stated idea.
3. **C-3 — KILL.** Free platform feature + margin-destroying input collection + zero transaction evidence at this shape/price.
