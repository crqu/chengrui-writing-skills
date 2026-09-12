# Chenrui Writing Skill

A Claude Code slash command (`/write`) that drafts and revises academic papers in Chengrui Qu's writing style.

## Quick start

```bash
# Clone this repo
git clone <repo-url>
cd "Chenrui Writing Skill"

# Install the skill
cp write.md ~/.claude/commands/write.md
```

Then in any Claude Code session:

```
/write abstract for our new paper on distributionally robust MARL
/write revise this introduction: [paste text]
/write related work section covering sim-to-real transfer and value factorization
/write rebuttal to reviewer 2 who says our assumption is too strong
```

## What it does

The skill acts as a writing collaborator calibrated to Chengrui's exact academic voice. It covers abstracts, introductions, related work, theory sections, experiments, revisions, and rebuttals.

The style profile was extracted by analyzing 5 published papers across venues including NeurIPS, ICLR, AISTATS, and CDC. It captures patterns in voice, sentence structure, contribution formatting, citation style, mathematical notation, paragraph transitions, and rhetorical devices.

## Files

- `write.md` — The skill file. Copy this to `~/.claude/commands/` to install.
- `CLAUDE.md` — Project context for Claude Code sessions opened in this directory.

## Customization

The style profile in `write.md` is meant to be a living document. As your writing evolves or you publish new papers, update the relevant sections. Key areas to customize:

- **Research Context** (line ~97): update your active research areas and collaborators
- **Anti-patterns** (line ~136): add any additional phrases or patterns to avoid
- **Rhetorical Devices** (line ~89): add new patterns from recent papers

## License

Personal use.
