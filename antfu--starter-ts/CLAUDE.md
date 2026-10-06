# starter-ts

> - **MUST**, **MUST NOT**, **SHOULD** and **MAY** use RFC 2119 meanings. They mark

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/starter-ts/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Rules that apply everywhere

- **MUST**, **MUST NOT**, **SHOULD** and **MAY** use RFC 2119 meanings. They mark
  real invariants - layer boundaries, wire contracts, output shapes - not house style.
- Before a PR, all gates MUST pass:
  `pnpm lint && pnpm knip && pnpm test && pnpm typecheck && pnpm build`.
  Commits follow Conventional Commits.

---
> Source: [antfu/starter-ts](https://github.com/antfu/starter-ts) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-06 -->
