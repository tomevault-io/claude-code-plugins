# marlo

> - Always use `pnpm` instead of `npm`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/marlo/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Commands

- Always use `pnpm` instead of `npm`
- **Install**: `pnpm install`
- **Build**: `pnpm build`
- **Lint**: `pnpm check:lint`
- **Types**: `pnpm check:types`
- **Format**: `pnpm format`
- **Test**: `pnpm test`

## IMPORTANT

- This is a PNPM Monorepo with turbo, primarily TypeScript, React, and Astro.
- Remove development/debugging `console.log()` statements and `debugger` statements before merging
- Run `pnpm check` before committing to ensure lint/types pass

---
> Source: [withastro/marlo](https://github.com/withastro/marlo) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-16 -->
