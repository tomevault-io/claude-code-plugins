# gh-stars-classifier-skill

> Gemini CLI reads this file automatically. The actual workflow is defined in

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/gh-stars-classifier-skill/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# GitHub Stars Classifier — Gemini CLI entry

Gemini CLI reads this file automatically. The actual workflow is defined in
`AGENTS.md` and imported below — one source of truth across every supported
CLI agent.

@AGENTS.md

## Gemini-specific setup

Before invoking any bash command from the imported workflow, make sure the
root resolver can find the `scripts/` directory. The simplest path is to
`cd` into the clone first:

```bash
cd /path/to/gh-stars-classifier-skill
gemini          # opens with this directory as the working root
```

or export the variable explicitly:

```bash
export GH_STARS_CLASSIFIER_ROOT=/path/to/gh-stars-classifier-skill
```

Then ask Gemini to "organize my GitHub stars." It will execute the five-phase
workflow above, pausing at each **[CONFIRM]** checkpoint.

---
> Source: [catuscio/gh-stars-classifier-skill](https://github.com/catuscio/gh-stars-classifier-skill) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-22 -->
