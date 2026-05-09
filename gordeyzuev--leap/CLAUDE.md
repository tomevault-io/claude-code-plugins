# engineering-principles

> KISS, DRY, YAGNI and readability expectations for all project work

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/engineering-principles/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Engineering principles

- **KISS** — prefer the simplest design that solves the problem.
- **DRY** — no duplicated logic without reason; extract when repetition hurts maintenance.
- **YAGNI** — do not build features or abstractions until they are needed.
- **Readability** — optimize for the next reader; avoid speculative “future-proofing.”

These apply to **code, APIs, and docs**. Tooling-specific rules (Ruff, `ty`, pytest) live in `python-code-quality.mdc` and `testing.mdc`.

---
> Source: [GordeyZuev/LEAP](https://github.com/GordeyZuev/LEAP) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-04 -->
