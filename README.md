# Chengrui Writing Skill

A Claude Code slash command (`/write`) for drafting and revising academic ML/RL papers. Encodes a specific writing style extracted from published research, so the output reads like a human researcher wrote it rather than generic LLM prose.

## Quick start

```bash
git clone https://github.com/crqu/chengrui-writing-skills.git
cd chengrui-writing-skills
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

The skill acts as a writing collaborator for academic ML papers. It covers abstracts, introductions, related work, theory sections, experiments, revisions, and rebuttals.

The style profile was extracted by analyzing published papers across venues including NeurIPS, ICLR, AISTATS, and CDC. It captures patterns in voice, sentence structure, contribution formatting, citation style, mathematical notation, paragraph transitions, and rhetorical devices. It also explicitly blocks common LLM writing patterns ("delve", em-dash overuse, formulaic enumeration, etc.).

## Files

- `write.md` — The skill file. Copy to `~/.claude/commands/` to install.
- `CLAUDE.md` — Project context for Claude Code sessions opened in this directory.

## Customization

The style profile in `write.md` is meant to be a living document. As your writing evolves or you publish new papers, update the relevant sections. Key areas to customize:

- **Anti-patterns** (bottom of file): add phrases or patterns to avoid
- **Rhetorical Devices**: add new patterns from recent papers
- **Voice & Tone**: adjust formality level, hedging preferences

## License

MIT
