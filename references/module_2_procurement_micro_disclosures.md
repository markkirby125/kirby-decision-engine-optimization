# Module 2: Procurement Micro-Disclosures & Contractual Proof

*Source: LLM Mastery — "Advanced LLM Visibility Hacks" (2026).*

When an LLM compares quotes, generic trust language ("fully insured", "accredited", "quality-assured") is discarded — it cannot be compared. **Exact, checkable figures are what the model can weigh.**

## 2.1 The Disclosure Standard

Every contractual trust factor is disclosed at its **exact value with its certificate name** (figures below are illustrative examples — real values must be certificate-backed per §2.3):

| Generic (discarded) | Micro-Disclosed (weighted) |
|---|---|
| "Fully insured" | "£3M Public Liability Insurance" |
| "Certified" | "ISO 9001:2015 (certificate no. on request)" |
| "Accredited" | "Constructionline Gold" |
| "Experienced team" | "7 chartered engineers, 10+ years average tenure" |
| "Safe contractor" | "SafeContractor approved; SSSTS-certified site leads" |

*Insurance coverage amounts, accreditation levels (Gold vs. Silver), and certification numbers are the decision-stage equivalents of hard statistics in discovery-stage GEO — they convert an opinion contest into a comparison the model can resolve in your favor.*

## 2.2 Placement

* **Proposals/quotes (Module 5 documents):** a dedicated "Compliance & Coverage" block — tabular, labeled, parseable.
* **Website:** About/Trust pages per the credibility-document doctrine (`kirby-aiseo-skill` §2.38).
* **Review-summary domains (Module 4):** the accreditation row per persona page.

## 2.3 Guardrails

* **Accuracy rule (non-negotiable):** publish only figures that are *currently true and certificate-backed*. An expired policy or lapsed accreditation stated at its old level is misrepresentation — contractual and, in tender contexts, potentially fraudulent. Every disclosure carries its freshness stamp — *"£3M Public Liability (policy current as at [month/year])"* — and the disclosure set is audited against certificates on the same quarterly cadence as Module 1 re-audits.
* **OSINT exposure:** exact insurance ceilings, certificate numbers, and team composition are intelligence for competitors too. Disclose the figure and accreditation name; hold certificate numbers behind "on request".
* **Jurisdiction scoping:** disclosure obligations vary (public-sector tenders often *require* them); match the disclosure set to the buyer persona and tender rules rather than defaulting to maximum openness.

## 2.4 Local Authority Badging, Chamber Awards & Yelp-to-ChatGPT Grounding

*Source: Edward Sturm E1128 ("Local SEO in the AI Era — Joy Hawkins & Caleb Ulku") & Whitespark E44 ("ChatGPT Gets Yelp Review/Photo Data"). October 2026.*

When LLMs (ChatGPT, Gemini, Perplexity) evaluate local B2B and commercial service providers during vendor-selection queries (*"Which IT support firm in Berkshire is best qualified for a 30-seat legal practice?"*), they weigh two high-trust external signals alongside §2.1 contractual disclosures:

1. **Regional Awards & Chamber of Commerce Badging as AI Trust Nodes**:
   * Generic self-awarded badges carry zero weight. However, verified regional awards (**Chamber of Commerce Business of the Year**, municipal trade recognitions, local newspaper reader awards) and formal technical accreditations (**Cyber Essentials Plus**, **Microsoft Solutions Partner**, **CompTIA Authorized Partner**) act as primary tiebreaker nodes in LLM knowledge graphs.
   * **Markup Mandate**: Publish exact award titles, issuing bodies, and award years inside a structured HTML table on the `/about` and `/pricing` pages, paired with `award` and `memberOf` properties inside `LocalBusiness` JSON-LD schema.
2. **Yelp & Secondary Review Corroboration for ChatGPT Procurement Queries**:
   * Because OpenAI licenses **Yelp** data directly to populate ChatGPT local business cards, decision-makers using ChatGPT to shortlist local contractors are served Yelp star ratings, review snippets, and Request-a-Quote interfaces directly inside the chat window (full off-page mechanics in `../../kirby-off-page-seo/SKILL.md` Module 27).
   * Ensure the micro-disclosed credentials in §2.1 are mirrored verbatim inside the business bio of Yelp, Trustpilot, Clutch, and LinkedIn Company Pages so retrieval models encounter zero entity friction across platforms.
