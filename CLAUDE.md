# Chenrui Writing Skill

This project contains a Claude Code slash command that serves as an academic writing collaborator for Chengrui Qu. The skill is calibrated to match the writing style from published papers at ICML, NeurIPS, ICLR, AISTATS, and CDC.

## Installation

Copy `write.md` into your Claude Code commands directory:

```bash
cp write.md ~/.claude/commands/write.md
```

Then invoke with `/write` in any Claude Code session.

## What the skill does

When invoked, it produces or revises academic text matching Chengrui's style across these modes:

- **Abstract**: 150 to 200 words, funnel structure, ends with strongest result
- **Introduction**: broad context, narrows to gap, explicit question, contributions block
- **Related work**: bold topic headers, survey then contrast pattern
- **Theory**: formal environments, assumptions contextualized, Remark blocks
- **Experiments**: question-driven, precise metrics, inline figure/table references
- **Revision**: fixes style deviations while preserving arguments
- **Rebuttal**: direct, factual, assertive

## Style sources

The style profile was extracted from these papers:

1. Understanding Agent Scaling in LLM-Based Multi-Agent Systems via Diversity (2026)
2. Training Generalizable Collaborative Agents via Strategic Risk Aversion (2026)
3. Knowledge-Centric Self-Improvement (2026)
4. Hybrid Transfer Reinforcement Learning: Provable Sample Efficiency from Shifted-Dynamics Data (AISTATS 2025)
5. Distributionally Robust Cooperative Multi-agent RL with Value Factorization (ICLR 2026)
