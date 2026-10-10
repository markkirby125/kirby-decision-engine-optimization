# Module 3: Knowledge Graph Procurement Gating

*Source: LLM Mastery — "Advanced LLM Visibility Hacks" (2026).*

## 3.1 The Enterprise Filter

Enterprise procurement increasingly routes vendor pools through AI-assisted screening before human review. These filters disqualify **unverified entities**: a vendor the model cannot resolve to a Knowledge Graph ID or corroborated entity record is filtered as a risk, regardless of quote quality. In tenders, entity verification functions as a *gating* criterion (pass/fail) that precedes any value comparison — which is why this module sits first in the patch order even though its work is slow.

## 3.2 Doctrine (Self-Contained Twin of `kirby-aiseo-skill` Module 2 §2.42)

> **Self-contained duplicate (twin).** The doctrine block below replicates `kirby-aiseo-skill` Module 2 §2.42 verbatim per the duplication policy; update both twins in the same change. The application layer after it is DEO-specific and not part of the canonical block.

**Doctrine block (verbatim from canonical):**

* **Who You Are:** Unambiguous entity identity — Knowledge Graph ID (KG ID), Knowledge Panel presence, and consistent NAP-equivalent identifiers.
* **What You Do:** Specific products/services explicitly coupled with the brand as semantic triples (`<Brand> — provides — <Service>`), never vague category labels.
* **Why You're Brilliant:** Third-party corroboration — awards, client case studies, verifiable reviews. First-party claims in this slot are discounted.
* **Day-1 Standardization:** Create an identical 1–2 sentence entity definition and propagate it across every property (website, X, LinkedIn, Yelp, Google Maps) before any campaign work begins.
* **Caution:** KG ID / Knowledge Panel acquisition speed is path-dependent: the Wikipedia route is slow and outside direct control (notability bar — plan a quarterly horizon); the Google Books book-funnel route is deterministic and fast (reported 3–4 weeks). Plan entity work by route, not by one horizon.

## 3.3 Application Layer — Procurement Gating

* **Pre-tender entity audit:** before any tender submission, verify the brand resolves in Google's Knowledge Graph (search the brand; check the Knowledge Panel), Wikidata (QID exists), and Companies House/state registry (matching registered name). Any miss is a gating risk — start the §2.42 Day-1 standardization immediately; expect the KG horizon to be route-dependent per the Caution above — the Wikipedia route will exceed the tender clock; the Google Books book-funnel route (personal KG MID, reported 3–4 weeks) may fit inside it.
* **Tender-document entity fields:** every Module 5 document carries the registered entity name, registration number, and consistent brand string exactly as filed — entity mismatches between quote, website, and registry are themselves a filter trigger.
* **Primary-association discipline:** the entity's "What You Do" triple must match the tendered service precisely (`<Brand> — provides — <fire-risk assessments>`, not generic "safety services"); misclassification costs ~10x to reverse (lock-in doctrine, `kirby-zero-to-100-seo` §1.1).
