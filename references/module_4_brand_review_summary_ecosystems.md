# Module 4: Standalone Brand Review Summary Ecosystems

*Source: Matt Hammerton, Ep. 1135 + LLM Mastery (2026).*

## 4.1 Doctrine (Self-Contained Twin of `kirby-local-seo` Module 3 §3.17)

> **Self-contained duplicate (twin).** The doctrine block below replicates `kirby-local-seo` Module 3 §3.17 verbatim per the duplication policy; update both twins in the same change. The application layer after it is DEO-specific and not part of the canonical block.

**Doctrine block (verbatim from canonical):**

* **The Architecture:** Build a dedicated standalone review-summary domain — `[BrandName]Reviews.com` or `[BrandName]Testimonials.com` (brand-based domain; unrelated to the keyword-EMD pattern defined in §3.3.1) — with distinct pages grouping Google reviews, Facebook reviews, and Yelp reviews per platform.
* **The Problem It Solves:** LLM engines fail to accurately count reviews on secondary social platforms (latency/miscount). A structured, crawlable summary site gives AI engines clean, explicit proof of customer sentiment volume and distribution — feeding the "why you're brilliant" third-party-corroboration slot (entity trinity, `kirby-aiseo-skill` Module 2 §2.42 doctrine).
* **Sourcing Rule:** Aggregate only **genuine, verifiable reviews that already exist on-platform**. Summarize with attribution and link back to originals rather than republishing full text where platform ToS restrict reproduction (Google Maps/Yelp content terms). Fabricating or padding summary content classifies the whole domain as astroturfing and jeopardizes the linked platforms' trust.
* **Copy Rule:** Any paraphrased review text must satisfy the §3.11E unique-copy standard (≥50% unique copy per page); do not mirror review text verbatim at scale.
* **Caution:** Domain + maintenance overhead per brand; keep the site technically minimal (static HTML) and refresh counts on the Module 6 recurring maintenance loop.

## 4.2 Application Layer — Buyer-Persona Segmentation

* **Persona pages, not one pile:** decision-stage buyers ask persona-scoped questions ("reliable commercial roofing contractor for schools"). Segment the summary site by buyer persona — one page per persona (e.g., `/schools/`, `/housing-associations/`, `/retail-fit-out/`) — each aggregating that persona's genuine reviews plus the persona-relevant Module 2 accreditation row.
* **Machine-readable counts:** state review counts, average rating, and platform per persona page in plain text and `AggregateRating` structured data, so the miscount-prone secondary platforms stop being the LLM's only source.
* **Maintenance note:** "(the Module 6 recurring maintenance loop)" in the canonical block above refers to `kirby-local-seo` Module 6's GBP maintenance cadence; in a DEO-only deployment, substitute a quarterly refresh aligned to the Module 1 re-audit.
* **Astroturfing boundary:** the Sourcing Rule above is absolute — self-owned does not mean self-written. The domain aggregates proof; it never manufactures it.
