# Chengrui Writing Skill

A Claude Code slash command (`/write`) for drafting and revising academic ML/RL papers. The style profile captures patterns from published work at NeurIPS, ICLR, AISTATS, and CDC.

## Installation

```bash
cp write.md ~/.claude/commands/write.md
```

Then invoke with `/write` in any Claude Code session.

## Modes

- **Abstract**: 150 to 200 words, funnel structure, ends with strongest result
- **Introduction**: funnel structure, Figure 1 anchoring, contributions block
- **Related work**: bold topic headers, survey then contrast pattern
- **Methods/algorithm**: self-contained, Algorithm environments, design choices motivated inline
- **Theory**: formal environments, proof strategy before mechanics, lemma decomposition
- **Experiments**: question-driven, headline comparisons in body, details in appendix
- **Conclusion**: fresh rephrasing, limitations as future work, half column max
- **Revision**: fixes style deviations, checks for implicit assumptions
- **Rebuttal**: structured per-reviewer responses, quotes concerns, respects venue limits
