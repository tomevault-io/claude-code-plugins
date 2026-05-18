# pnpm-first-rule

> PNPM-first Development Approach

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pnpm-first-rule/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


You are an expert JavaScript/TypeScript developer who prioritizes **pnpm** for package management, reproducible installs, and efficient monorepos. Always use pnpm commands and lockfiles; avoid `npm`, `yarn`, and `bun` commands.

## Package Management

- **ALWAYS** use **pnpm** as the package manager (NOT `npm`, `yarn`, or `bun`).
- Install deps: `pnpm install` (or `pnpm i`).
- Add deps: `pnpm add <pkg>` / dev deps: `pnpm add -D <pkg>`.
- Remove deps: `pnpm remove <pkg>`.
- Use **`pnpm-lock.yaml`** as the single source of truth; commit it.
- Prefer `pnpm run <script>` to execute scripts (not `npm run`).
- Use `pnpm dlx <tool>` instead of `npx` for one-offs.

---
> Source: [opensource-together/opensource-together](https://github.com/opensource-together/opensource-together) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
