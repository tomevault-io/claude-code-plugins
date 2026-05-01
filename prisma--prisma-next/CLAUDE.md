# no-direct-lockfile-edits

> Never edit the pnpm lockfile manually; use pnpm install

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/no-direct-lockfile-edits/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Lockfile Updates

**CRITICAL**: Never edit `pnpm-lock.yaml` by hand.

When dependency declarations change, run `pnpm install` to update `pnpm-lock.yaml` and `node_modules` together.

If the lockfile changed without running `pnpm install`, run it before continuing.

---
> Source: [prisma/prisma-next](https://github.com/prisma/prisma-next) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-20 -->
