# egoverse

> to run commands in the interactive shell make sure to source emimic/bin/activate

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/egoverse/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repo Agent Rules

## Shell / Command Execution
to run commands in the interactive shell make sure to source emimic/bin/activate

Apply this before running project Python tooling (for example: `python`, `pytest`, `pip`).

## Model settings
use plan mode for anything except extremely simple tasks

## Slurm rules
If you're on a slurm cluster, request a GPU before running or testing training.
On sky1/sky2: salloc -p rl2-lab -A rl2-lab --gres=gpu:a40:1 -c 12 --mem=30G

---
> Source: [GaTech-RL2/EgoVerse](https://github.com/GaTech-RL2/EgoVerse) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
