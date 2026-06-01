# package-manager-conventions

> description: Use Yarn only, never npm/pnpm

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/package-manager-conventions/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

---
description: Use Yarn only, never npm/pnpm
globs: package.json, yarn.lock
alwaysApply: true
---

# Package Manager Rules

- Use Yarn v1.22.22 only - never use npm or pnpm
- Never manually edit yarn.lock
- Keep yarn.lock changes minimal when adding deps
- Registry must be https://registry.yarnpkg.com

---
> Source: [microsoft/data-formulator](https://github.com/microsoft/data-formulator) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-01 -->
