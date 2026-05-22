# typescript

> - Strict mode. Avoid `any`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/typescript/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# TypeScript Rules

## TypeScript & Syntax

- Strict mode. Avoid `any`.
- Use optional chaining, union types (no enums).

## tRPC Routers

- **enabled**: as needed
- Routers in `src/lib/api/routers`, compose in `src/lib/api/root.ts`.
- `publicProcedure` or `protectedProcedure` with Zod.
- Access from React via `@/lib/trpc/react`. # TypeScript Rules

## TypeScript & Syntax

- Strict mode. Avoid `any`.
- Use optional chaining, union types (no enums).

## tRPC Routers

- **enabled**: as needed
- Routers in `src/lib/api/routers`, compose in `src/lib/api/root.ts`.
- `publicProcedure` or `protectedProcedure` with Zod.
- Access from React via `@/lib/trpc/react`. 

---
> Source: [manta-digital/manta-templates](https://github.com/manta-digital/manta-templates) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-22 -->
