# Module 1: The Adversarial Competitor Reverse-Audit Protocol

*Source: LLM Mastery — "Advanced LLM Visibility Hacks" (2026).*

At the decision stage, buyers do not ask the LLM *"why should we choose X?"* — they ask it to **eliminate** vendors. Optimize for the elimination question.

## 1.0 The 26% Benchmark & The Billboard Doctrine (Economic Basis)

1. **Cold-Inquiry-to-Customer Conversion (Dooley/Floate — "Entity SEO for AI Search" V6, 2026; single 1.3M-inquiry study, directional):** AI-referred leads convert cold-inquiry-to-customer at **26%** — **3× web-search leads, 2 points above word-of-mouth** (1.3M inquiries, 850 industries, UTM-tracked from ChatGPT/AI search). Buyers arrive pre-sold on perceived AI neutrality. *Harmonization:* `kirby-off-page-seo` §4.21 reports 20–25% vs ~5% organic (Odys Global) for the same phenomenon — cite ranges with attribution; never blend sources into one number. Case evidence: Module 5 §5.4.
2. **GA4 Session-Level Telemetry & Post-GPT-5 Referral Decay (Marie Haynes, 2026; analyzed in Edward Sturm Ep. 1208, `10DT7t1RetI`):** Across 12 months of GA4 data on 100 websites (145M+ sessions; 55 tracking key events, 45 lacking conversion tracking), ChatGPT referral sessions equaled just **0.62%** of Google organic session volume (**0.73%** across all LLMs combined) and began declining after August 2025 (GPT-5 release) — even as ChatGPT's overall audience tripled over the 12-month window (speaker-reported in `10DT7t1RetI`; separately, Mike King's article reports ChatGPT reaching **1.2B weekly users, up from 900M in February**). When users did click through, ChatGPT sessions converted at **13.8% vs. 3.02% for Google organic (4.5× higher)**, though Google across all channels still drove **96.5% of total conversions** (and Google organic drove **27× more conversions** than all LLMs combined).
3. **The Mike King "Billboard" Doctrine (`ipullrank.com`, *"AI Search Is Not a Distraction, It's a Branding Channel"*, 10.22.26 / Ep. 1208):** Judging AI search on GA4 referral clicks is a category error—equivalent to telling a CMO that highway billboards are a distraction because nobody clicks a billboard. Over a billion users a week consult LLMs inside zero-click decision sessions. DEO optimizes the in-session vendor-selection and elimination judgment, not referral traffic volume.

## 1.1 The Core Prompts

Run these against the same LLMs your buyers use (ChatGPT, Claude, Gemini), with the client's and competitors' real **public** materials pasted in:

> **⚠️ Confidentiality rule:** never paste NDA-bound tender documents, unpublished quotes, or client-confidential material into consumer LLMs. Use (a) public materials only (websites, registries, published accreditations), or (b) an enterprise/contracted deployment whose DPA covers the material. When in doubt, redact pricing and identifiers and test structure, not specifics.

1. **The Head-to-Head Elimination:**
   > *"Company A and Company B both quote £10k. Give me 3 reasons why I should NOT choose Company A."*
   Run once with the client as Company A, once per competitor. Every returned reason is a **liability gap**.
2. **The Tender Grill:**
   > *"You are a risk-averse procurement officer. Rank these four quotes by risk of a bad outcome, and justify each ranking."*
   Surfaces the risk dimensions the model actually weights (insurance, accreditation, specificity, verifiability).
3. **The Missing-Information Probe:**
   > *"What information is missing from this quote that you would need to recommend it confidently?"*
   Every missing item is a Module 2 disclosure candidate or a Module 5 formatting gap.

## 1.2 The Patch Loop

1. Log every surfaced reason into a gap ledger: `Gap → Module (2/3/4/5) → Patch → Re-audit date`.
2. Patch each gap with the corresponding module's protocol (disclosure, entity work, review proof, or document restructuring).
3. **Re-run the same prompts after patching.** Stop condition (integrity floor): the loop closes only when the elimination prompts return reasons that are *factually inaccurate or fully remediated* — never when prompting tricks (keyword-stuffed quotes, sycophancy bait) merely flip the model's answer. A quote stuffed to win the audit fails the keyword-stuffing penalty doctrine (`kirby-aiseo-skill` Module 2 §2.2) and the Module 5 human-scrutiny rule.

## 1.3 Guardrails

* **Internal-use-only findings:** reverse-audit outputs are remediation intelligence. Publishing disparagement angles sourced from LLM audits (especially unverifiable or outdated claims about competitors) risks defamation exposure — external comparisons follow the comparison-page doctrine (`kirby-aiseo-skill` §2.40 caution: verifiable, current, attributed).
* **Model variance:** run each prompt across at least two engines; single-engine findings may reflect one model's weighting, not the market's.
* **Cadence:** re-audit quarterly and before every major tender — competitor disclosures change.
