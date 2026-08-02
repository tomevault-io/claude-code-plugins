# shad-expo-studio

> This Expo shell lives in a pnpm + Turbo monorepo. Keep it lightweight so designers can focus on UI.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/shad-expo-studio/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Expo App Guide

This Expo shell lives in a pnpm + Turbo monorepo. Keep it lightweight so designers can focus on UI.

How to work on `apps/expo`
- Use pnpm only: `pnpm --filter expo-app <cmd>`.
- Quality checks: `pnpm --filter expo-app lint`, `typecheck`, `test`, `format`.
- UI-first: no backend SDKs unless absolutely required for a design demo.
- Imports: use the `@/*` alias (set in Babel/Metro) for local files.
- Testing: `pnpm --filter expo-app test` (Jest). `test:watch` is local-only.
- Dependencies: prefer workspace packages; avoid adding extra lockfiles or package managers.

---
> Source: [Ge-limin/shad-expo-studio](https://github.com/Ge-limin/shad-expo-studio) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-22 -->
