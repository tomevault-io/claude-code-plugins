# moltbook-vs-reddit

> Project-local instructions for working in this repo.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/moltbook-vs-reddit/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# moltbook_analysis – agent notes

## Interface contract
- Setup: `make setup`
- Gates: `make all` (stop at first failure)

## Boundaries
- Don’t commit `.env` or the raw corpora / generated reports under `data/` (they’re gitignored).
- Prefer minimal, correct changes over refactors.

---
> Source: [strangeloopcanon/moltbook_vs_reddit](https://github.com/strangeloopcanon/moltbook_vs_reddit) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-03 -->
