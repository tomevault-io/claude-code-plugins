# repro-lens

> Keep one implementation of each rule in `src/repro_lens`; CLI, hooks and skills use it.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/repro-lens/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Working on Repro Lens

Keep one implementation of each rule in `src/repro_lens`; CLI, hooks and skills use it.
The checker must not import project code, execute notebook cells or start training.
Keep `review` findings separate from confirmed policy violations. Do not call a clean
static scan proof of reproducibility, or a two-run match proof of scientific validity.

Add positive and negative behavioral cases when changing a detection rule. Preserve
aliases, shadowed identifiers, configured exclusions and justified suppressions.
Never autofix a scientific choice by inserting seed 42 or relaxing a tolerance.

The template is a working user project: validate a generated copy, not just its text.
Keep generated data/models and local evidence out of source control except tiny
deliberately versioned fixtures. Document new limits alongside new capabilities.

Use `uv run pytest`, `uv run ruff check .` and `uv run ruff format --check .`.

---
> Source: [00200200/repro-lens](https://github.com/00200200/repro-lens) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-13 -->
