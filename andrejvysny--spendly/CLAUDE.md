# react-typescript

> React/TypeScript and Inertia conventions for resources/js.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/react-typescript/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# React / TypeScript

- Prefer delegating to the `frontend` subagent for substantial frontend work.
- Use functional components and TypeScript interfaces for props.
- Imports: `@/components`, `@/lib/utils`, `@/hooks`, `@/types` (see tsconfig/vite aliases).
- Inertia: `Head`, `router`, `usePage` from `@inertiajs/react`; type page props from controller payload.
- Prettier: single quotes, tabWidth 4 — see .prettierrc.
- Reference: resources/js/pages/dashboard.tsx, resources/js/types/index.ts.

---
> Source: [andrejvysny/spendly](https://github.com/andrejvysny/spendly) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-19 -->
