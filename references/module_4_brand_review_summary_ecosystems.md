# Module 4: Standalone Brand Review Summary Ecosystems

*Source: Matt Hammerton, Ep. 1135 + LLM Mastery (2026).*

## 4.1 Doctrine (Self-Contained Twin of `kirby-local-seo` Module 3 §3.17)

> **Self-contained duplicate (twin).** The doctrine block below replicates `kirby-local-seo` Module 3 §3.17 verbatim per the duplication policy; update both twins in the same change. The application layer after it is DEO-specific and not part of the canonical block.

**Doctrine block (verbatim from canonical):**

* **The Architecture:** Build a dedicated standalone review-summary domain — `[BrandName]Reviews.com` or `[BrandName]Testimonials.com` (brand-based domain; unrelated to the keyword-EMD pattern defined in §3.3.1) — with distinct pages grouping Google reviews, Facebook reviews, and Yelp reviews per platform.
* **The Problem It Solves:** LLM engines fail to accurately count reviews on secondary social platforms (latency/miscount). A structured, crawlable summary site gives AI engines clean, explicit proof of customer sentiment volume and distribution. The aggregated customer reviews, linked back to their originals, are the corroboration (entity trinity, `kirby-aiseo-skill` Module 2 §2.42 doctrine); the site itself is brand-owned and disclosed as such, so it is not itself third-party evidence.
* **Disclosure Rule (16 CFR §465.6):** A brand-owned review site must be identified as brand-owned and must not selectively include or omit reviews; it is not independent third-party corroboration.
* **Sourcing Rule:** Aggregate only **genuine, verifiable reviews that already exist on-platform**. Summarize with attribution and link back to originals rather than republishing full text where platform ToS restrict reproduction (Google Maps/Yelp content terms). Fabricating or padding summary content classifies the whole domain as astroturfing and jeopardizes the linked platforms' trust.
* **Copy Rule:** Any paraphrased review text must satisfy the §3.11E unique-copy standard (≥50% unique copy per page); do not mirror review text verbatim at scale.
* **Caution:** Domain + maintenance overhead per brand; keep the site technically minimal (static HTML) and refresh counts on the Module 6 recurring maintenance loop.

## 4.2 Application Layer — Buyer-Persona Segmentation

* **Reference note:** `§3.3.1`, `§3.11E`, and "the Module 6 recurring maintenance loop" inside the doctrine block above are `kirby-local-seo` internal references (respectively: the *GBP Configuration Hygiene & Rolling Maintenance Protocol* section containing the EMD-to-DBA pipeline; sub-block E of §3.11 *Secondary-City Arbitrage* containing the ≥50% unique-copy "Net New Local Data Test"; and local-seo Module 6's GBP maintenance loop).
* **Ownership disclosure (FTC 16 CFR Part 465 territory):** every page of the brand-owned summary domain carries a prominent "Operated by [Brand]" disclosure. An undisclosed affiliated review site is the review-platform equivalent of astroturfing; disclosure preserves the aggregation's legitimacy without discounting the counts (the reviews remain genuine, on-platform, and linked).
* **Persona pages (buyer personas, not author personas), not one pile:** decision-stage buyers ask persona-scoped questions ("reliable commercial roofing contractor for schools"). Segment the summary site by buyer persona — one page per persona (e.g., `/schools/`, `/housing-associations/`, `/retail-fit-out/`) — each aggregating that persona's genuine reviews plus the persona-relevant Module 2 accreditation row.
* **Machine-readable counts (Plain HTML Only — Strict Ban on `AggregateRating` / `Review` JSON-LD):** State review counts, average rating, and platform per persona page in plain HTML text and labeled `<table>` rows with direct outbound links to the live platform profiles, so miscount-prone secondary platforms stop being the LLM's only source. **Strict Structured-Data Ban:** **Never** inject `AggregateRating` or `Review` JSON-LD on a brand-owned review summary domain, `/trust` hub, or first-party commercial page aggregating third-party reviews. Self-serving and third-party-aggregated `AggregateRating` markup violates Google's review snippet guidelines and triggers manual-action / rich-result suppression penalties — LLMs extract plain-text tables and outbound links directly without schema risk (see `../../kirby-technical-aeo/SKILL.md` Phase 4).
* **Maintenance note:** in a DEO-only deployment, refresh counts quarterly, aligned to the Module 1 re-audit.
* **Astroturfing boundary:** the Sourcing Rule above is absolute — self-owned does not mean self-written. The domain aggregates proof; it never manufactures it.
