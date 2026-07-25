# npmgraph

> Always run `npm run fix` before committing changes. This runs ESLint with `--fix` and Prettier in parallel to ensure code is properly linted and formatted.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/npmgraph/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Copilot Agent Instructions

## Before Committing

Always run `npm run fix` before committing changes. This runs ESLint with `--fix` and Prettier in parallel to ensure code is properly linted and formatted.

```sh
npm run fix
```

Note: `npm run lint` requires Node.js 24 (`Object.groupBy` is unavailable in older versions). Run `npm run types` for TypeScript checks, which work on all supported versions.

---
> Source: [npmgraph/npmgraph](https://github.com/npmgraph/npmgraph) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-24 -->
