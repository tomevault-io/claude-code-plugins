# monorepo

> Monorepo conventions and tooling

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/monorepo/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Monorepo Conventions

## Package Manager

- Always use `pnpm`, never `npm` or `yarn`.
- Use `pnpm install` to install dependencies.
- Use `pnpm turbo run <task>` to run tasks across packages.

## Code Style

- TypeScript is used throughout. Prefer `unknown` over `any` when possible. Try avoid using `any` types unless absolutely necessary.
- Use ES module syntax (`import`/`export`), not CommonJS (`require`/`module.exports`).
- Run `check-types`, `lint` tasks (see per package.json) afterward to ensure types and coding styles match the rule.

### React

- Prefer `PropsWithChildren` instead of manually specifying `children` type.

---
> Source: [ecp-eth/comments-monorepo](https://github.com/ecp-eth/comments-monorepo) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-21 -->
