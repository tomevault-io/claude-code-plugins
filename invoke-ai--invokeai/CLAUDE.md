# invokeai

> Change legacy UI only when explicitly requested or required for shared compatibility. Ordinary frontend work belongs in `../webv2/`; read its guidance.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/invokeai/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Legacy frontend

Change legacy UI only when explicitly requested or required for shared compatibility. Ordinary frontend work belongs in `../webv2/`; read its guidance.

Shared OpenAPI/type artifacts and generation tooling belong to [../api/AGENTS.md](../api/AGENTS.md). This package consumes those types through `src/services/api/schema.ts`; keep that type-only compatibility import path.

## Commands

Run from this directory with this package's lockfile:

- `pnpm lint`: legacy TypeScript, dependency-cycle, ESLint, Prettier, and unused-dependency checks.
- `pnpm test:no-watch`: legacy Vitest; colocate tests following existing conventions.
- `pnpm build`: legacy production build.
- Regenerate shared contracts from `../api/` using its commands and lockfile.

Use root Ruff/pytest for Python changes. Do not apply webv2's Chakra version, @dnd-kit APIs, Oxc commands, or browser-test assumptions here. Preserve existing persisted-state migrations when changing legacy state.

---
> Source: [invoke-ai/InvokeAI](https://github.com/invoke-ai/InvokeAI) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-06 -->
