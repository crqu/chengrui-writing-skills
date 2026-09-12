# Chengrui Writing Skill

A Claude Code slash command (`/write`) for drafting and revising academic ML/RL papers. The style profile captures patterns from published work at NeurIPS, ICLR, AISTATS, and CDC.

## Installation

```bash
cp write.md ~/.claude/commands/write.md
```

Then invoke with `/write` in any Claude Code session.

## Modes

- **Abstract**: 150 to 200 words, funnel structure, ends with strongest result
- **Introduction**: broad context, narrows to gap, explicit question, contributions block
- **Related work**: bold topic headers, survey then contrast pattern
- **Theory**: formal environments, assumptions contextualized, Remark blocks
- **Experiments**: question-driven, precise metrics, inline figure/table references
- **Revision**: fixes style deviations while preserving arguments
- **Rebuttal**: direct, factual, assertive
