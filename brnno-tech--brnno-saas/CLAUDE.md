# brnno-saas

> description: Git branch policy — use main and dev only; never master

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/brnno-saas/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

---
description: Git branch policy — use main and dev only; never master
alwaysApply: true
---

# Git branches

- **Default branches:** Use **main** and **dev** only. There is no `master` branch.
- **Never** commit to or push to `master`. Do not create or reference a `master` branch.
- **Workflow:** Do work on `dev`; merge into `main` when ready. Push to `origin main` or `origin dev` as appropriate.
- When suggesting git commands, use `main` and `dev` only (e.g. `git push origin main`, `git checkout dev`).

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/BRNNO-Tech) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-10 -->
