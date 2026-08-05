# ccblocks

> This is a deepsec scanning workspace. Each registered project has its

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ccblocks/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent setup

This is a deepsec scanning workspace. Each registered project has its
own setup prompt at `data/<id>/SETUP.md` — open the relevant one when
asked to set a project up.

## Common tasks

- **Set up a project for scanning**: read `data/<id>/SETUP.md` and
  follow it (read `node_modules/deepsec/SKILL.md`, then fill
  `data/<id>/INFO.md` from the target codebase).
- **Add a new project**: run `deepsec init-project <root>` — it
  scaffolds `data/<id>/` and prints/writes the setup prompt for the
  new project.
- **Write a custom matcher** (only after a real true-positive shows you
  a pattern worth keeping): read
  `node_modules/deepsec/dist/docs/writing-matchers.md`.

## Reference

The deepsec skill is at `node_modules/deepsec/SKILL.md` (after
`pnpm install`). The full docs ship at
`node_modules/deepsec/dist/docs/`.

---
> Source: [designorant/ccblocks](https://github.com/designorant/ccblocks) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-22 -->
