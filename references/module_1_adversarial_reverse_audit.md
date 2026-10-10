# Module 1: The Adversarial Competitor Reverse-Audit Protocol

*Source: LLM Mastery — "Advanced LLM Visibility Hacks" (2026).*

At the decision stage, buyers do not ask the LLM *"why should we choose X?"* — they ask it to **eliminate** vendors. Optimize for the elimination question.

## 1.1 The Core Prompts

Run these against the same LLMs your buyers use (ChatGPT, Claude, Gemini), with the client's and competitors' real public materials pasted in:

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
3. **Re-run the same prompts after patching.** The protocol is complete only when the elimination prompts return competitor weaknesses instead of client weaknesses.

## 1.3 Guardrails

* **Internal-use-only findings:** reverse-audit outputs are remediation intelligence. Publishing disparagement angles sourced from LLM audits (especially unverifiable or outdated claims about competitors) risks defamation exposure — external comparisons follow the comparison-page doctrine (`kirby-aiseo-skill` §2.40 caution: verifiable, current, attributed).
* **Model variance:** run each prompt across at least two engines; single-engine findings may reflect one model's weighting, not the market's.
* **Cadence:** re-audit quarterly and before every major tender — competitor disclosures change.
