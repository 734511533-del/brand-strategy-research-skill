# brand-strategy-research

An agent skill for generating deep brand development history and strategic analysis reports (深度品牌调研与品牌战略分析报告).

## What it does

Given a target brand, the skill guides an AI agent to:

1. Research the brand's founding story, funding history, product launches, marketing campaigns, leadership changes, crisis events, and competitive landscape.
2. Cross-verify brand stages against concrete business milestones.
3. Produce a structured 7-section strategic report:
   - Core Brand Identity & Summary (≤200 words)
   - Brand DNA & Founding Philosophy
   - Brand Evolution: Milestone Analysis (3-5 phases, table)
   - Product Line Brand Strategy Matrix (table)
   - Brand Communication System
   - Brand Competitive Landscape & Perception Gap
   - Conclusion: Brand Moat & Outlook

## Files

- `SKILL.md` — skill definition, workflow, output standards
- `references/report-template.md` — full 7-section report template with table formats

## Usage

Deploy as a skill in any agent environment that supports SKILL.md-style skills (e.g. Claude Skills, Kimi skills), or paste `SKILL.md` + the template into a system prompt. Trigger with requests like "品牌调研", "品牌分析", "brand strategy research".

All brand examples in the template are generic illustrative placeholders — no real client data included.
