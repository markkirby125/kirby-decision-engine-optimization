# Module 5: LLM-Optimized Proposal & RFP Structuring

*Source: LLM Mastery — "Advanced LLM Visibility Hacks" (2026), extended with document-parseability doctrine.*

When the buyer pastes your PDF into an LLM, the model does not "read" it like a human — it extracts. Structure documents so the extraction is unambiguous and the comparison resolves in your favor.

## 5.1 The Extraction Standard

1. **Machine-readable source format:** submit text-layer PDFs or Markdown exports — never image-only scans (the model sees nothing). Verify: text selects/copies from the final export.
2. **BLUF per section:** each section opens with its conclusion ("Total fixed price: £9,850. Delivery: 6 weeks. Penalty-backed."), then supports it (front-loading law, `kirby-aiseo-skill` §2.1).
3. **One fact per labeled line:** prices, timelines, guarantees, and coverage amounts live in labeled table rows — `"Public Liability Insurance | £5,000,000 | Certificate on request"` — never buried in prose.
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
* **Consistency rule:** figures in the proposal must match the website, review-summary domain (Module 4), and registry entries (Module 3) exactly — cross-document mismatches are the cheapest disqualification an LLM can find.
* **Price-gating boundary:** `kirby-text-first-cro` §12 gates prices in *marketing* title tags and hero copy; tender/proposal documents are the opposite context — buyers demand exact figures, and withholding them is a disqualification. Do not apply §12 here.
