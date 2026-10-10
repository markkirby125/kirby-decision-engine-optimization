# Module 5: LLM-Optimized Proposal & RFP Structuring

*Source: LLM Mastery — "Advanced LLM Visibility Hacks" (2026), extended with document-parseability doctrine.*

When the buyer pastes your PDF into an LLM, the model does not "read" it like a human — it extracts. Structure documents so the extraction is unambiguous and the comparison resolves in your favor.

## 5.1 The Extraction Standard

1. **Machine-readable source format:** submit text-layer PDFs or Markdown exports — never image-only scans (the model sees nothing). Verify: text selects/copies from the final export.
2. **BLUF per section:** each section opens with its conclusion ("Total fixed price: £9,850. Delivery: 6 weeks. Penalty-backed."), then supports it (front-loading law, `kirby-aiseo-skill` §2.1).
3. **One fact per labeled line:** prices, timelines, guarantees, and coverage amounts live in labeled table rows — `"Public Liability Insurance | £3,000,000 (example figure) | Certificate on request"` — never buried in prose. (Figures here are placeholders; real values come from Module 2's certificate-audited disclosures and must match them exactly.)
4. **Explicit comparison metrics:** where you beat a competitor on a checkable dimension, state the metric with its number and unit; the model can weigh "98% first-fix rate (12-month trailing, 417 jobs)" and cannot weigh "highest quality".
5. **Risk-mitigation block:** a dedicated section enumerating what happens if things go wrong (remedies, penalty clauses, escalation path) — LLMs performing risk ranking (Module 1's Tender Grill) reward vendors who pre-answer it.
6. **ROI guarantees as falsifiable claims:** "save 14 hrs/month per operator (measured onboarding baseline, 30-day exit if unmet)" beats "significant efficiency gains".

## 5.2 The RFP Response Skeleton

```
1. Executive answer       — the single recommendation + 3 falsifiable reasons
2. Compliance matrix      — RFP requirement | Our response | Evidence (module 2 disclosures)
3. Delivery plan          — milestones with dates and owners
4. Risk & remediation     — what-if table + penalty backing
5. Proof                  — persona-matched case studies + accreditation row
6. Pricing                — labeled table, exact figures, price-gating doctrine applies
                            to marketing copy only — tenders quote exact prices
```

## 5.3 Guardrails

* **Human scrutiny rule:** every claim must survive a human procurement officer reading the same document. Over-optimized keyword scaffolding that reads as machine-first triggers spam filters in procurement portals and destroys human trust — optimize extraction clarity, never keyword density.
* **Authority-to-commit rule:** penalty clauses, guarantees, and remedy terms enter a document only with the contractual authority to back them (sign-off from whoever owns delivery risk). An LLM-parseable penalty clause the business cannot honor is worse than none — it converts a marketing claim into a breach.
* **Template precedence:** where the tender mandates a response template, the extraction standard applies *within* the template's structure (labeled rows, BLUF per section) — never restructure a mandatory format.
* **Consistency rule:** figures in the proposal must match the website, review-summary domain (Module 4), and registry entries (Module 3) exactly — cross-document mismatches are the cheapest disqualification an LLM can find.
* **Price-gating boundary:** `kirby-text-first-cro` §12 gates prices in *marketing* title tags and hero copy; tender/proposal documents are the opposite context — buyers demand exact figures, and withholding them is a disqualification. Do not apply §12 here.

## 5.4 Case Studies (V6-G — Dooley/Floate, 2026; single-source, directional)

* **UniPlay (playground markings, UK):** won a **£24,000 contract while bidding £2,000 above** a £22,000 competitor. The client (a school headteacher) uploaded all three competing quotes into ChatGPT; it recommended UniPlay specifically because of its dominance of **comparison pages and value-focused listicles** emphasizing longevity and superior materials. The client confirmed she would have chosen the cheaper vendor without ChatGPT's intervention. *Doctrine link:* this is Modules 3+4 proof surfacing at the exact Module 1 elimination moment — and the comparison-page dominance is discovery-stage work (`kirby-aiseo-skill` §2.40, `kirby-off-page-seo` Module 18) that pays off here.
* **Caleb Texas agency (Lubbock, TX):** after a DEO audit and optimization for ChatGPT visibility, ChatGPT recommended the agency as **#1 for "best marketing agency in Lubbock"** with a personalized-fit endorsement; within two weeks a prospect called, bypassed the sales process, and paid a **$55,000 ARR contract upfront**.
* **Reading the cases:** both wins were decided *before* the sales conversation — the mechanism is retrieval dominance (comparison/commercial content the model trusts) plus verifiable entity proof, not persuasion. That is why this skill's patch order starts at entity gating (Module 3), not copywriting (Module 5).
