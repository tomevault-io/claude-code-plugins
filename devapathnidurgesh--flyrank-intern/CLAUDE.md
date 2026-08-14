# flyrank-intern

> Before any task in this repo: **read `skills/README.md`** — it is the router.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/flyrank-intern/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent instructions

Before any task in this repo: **read `skills/README.md`** — it is the router.
Find the task in its table and load exactly **one** skill (plus `skills/flyrank/flyrank-data/SKILL.md`
whenever the task touches the data). Do not load every skill; keep context small.

Ground rules for this repo:
- Search the repo before assuming something is missing or not implemented.
- One task per conversation; finish and verify before starting the next.
- Never commit datasets (CI blocks them). Never print private data, client names, or raw queries.
- The intern validates your output — end each task by running the notebook top to bottom.

---
> Source: [DEVAPATHNIDURGESH/flyrank-intern](https://github.com/DEVAPATHNIDURGESH/flyrank-intern) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-13 -->
