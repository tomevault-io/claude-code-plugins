# 144

> - Build: `npm run build`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/144/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Guidelines

## Commands
- Build: `npm run build`
- Dev/Watch: `npm run dev`
- Lint: `npm run build` (ESLint via [[.eslintrc]])
- Test: Manual testing only.

## Code Style
- Language: [[TypeScript]]
- Formatting: Adhere to [[.eslintrc]] rules.
- Imports: Top of file.
- Types: Explicit, `strictNullChecks` enabled ([[tsconfig.json]]).
- Naming: `camelCase` (vars/funcs), `PascalCase` (classes/interfaces).
- Error Handling: Use [[Obsidian Notice]] for user feedback; `try-catch` for critical ops.
- General: Avoid [[Unused Variables]] (`@typescript-eslint/no-unused-vars`).

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/angelwingscomms)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/angelwingscomms)
<!-- tomevault:4.0:claude_md:2026-04-08 -->
