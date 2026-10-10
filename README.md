# Kirby Decision Engine Optimization (DEO)

[![Kirby Skills Collection](https://img.shields.io/badge/Kirby_Skills-Collection-blue?style=flat-square&logo=github)](https://github.com/markkirby125/kirby-skills-collection)

Every AI SEO skill optimizes **discovery** — citations, impressions, rankings. This one optimizes the **decision stage**: the moment your prospect pastes four competing quotes (or an RFP PDF) into ChatGPT or Claude and asks *"Which one provides the best value? Who should I place the order with?"*

That answer is decided by what the LLM can extract and verify: exact insurance figures, accreditations, entity status, review proof, and document structure. `kirby-decision-engine-optimization` engineers all five.

## What's Inside

- **Module 1 — Adversarial Reverse-Audit:** run the elimination prompts ("give me 3 reasons NOT to choose Company A") against yourself and competitors; patch every surfaced gap.
- **Module 2 — Procurement Micro-Disclosures:** "£3M Public Liability", "Constructionline Gold", "ISO 9001:2015" — exact, certificate-backed figures that LLMs can actually weigh.
- **Module 3 — Knowledge Graph Gating:** enterprise AI procurement filters disqualify unverified entities; KG ID / Knowledge Panel doctrine (self-contained twin of `kirby-aiseo-skill` §2.42).
- **Module 4 — Review Summary Ecosystems:** `[Brand]Reviews.com` architectures segmented by buyer persona (self-contained twin of `kirby-local-seo` §3.17).
- **Module 5 — LLM-Optimized Proposals & RFPs:** the extraction standard for quotes and tender responses that must survive both LLM parsing and human scrutiny.

## 🪄 The Magic Prompt

Copy and paste this directly to your AI (Cursor, Windsurf, Claude Code, Antigravity):

```markdown
@agent Please install the kirby-decision-engine-optimization skill into this workspace.
1. Read the `SKILL.md` file and `references/` directory from this repository: https://github.com/markkirby125/kirby-decision-engine-optimization
2. Identify the correct rules system for our current environment (e.g., `.cursor/rules/` for Cursor, `.windsurfrules` for Windsurf, `.clinerules` for Cline, or `~/.agents/skills/` for Antigravity).
3. Save the contents appropriately. If our environment supports multi-file dispatcher skills, clone the directory structure exactly.
4. Confirm when the installation is complete.
```

## Manual Installation

- **Cursor**: Save `SKILL.md` to `.cursor/rules/kirby-decision-engine-optimization.mdc` and copy `references/`
- **Windsurf**: Save `SKILL.md` to `.windsurfrules` and copy `references/`
- **Antigravity**: Clone this repository directly into `~/.agents/skills/kirby-decision-engine-optimization`
