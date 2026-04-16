# local-walls

> - **NO `any`**: The use of `any` is strictly prohibited. Use proper interfaces, DTOs, or `unknown` with type guards/assertions when dealing with external data.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/local-walls/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project Guidelines

## TypeScript & Typing
- **NO `any`**: The use of `any` is strictly prohibited. Use proper interfaces, DTOs, or `unknown` with type guards/assertions when dealing with external data.
- **Strict Typing**: Ensure all function parameters, return types, and variables are correctly typed.
- **Supabase Types**: Always use the generated types from `src/models/supabase-generated.ts` via the interfaces in `src/models/supabase-interfaces.ts`.

## RLS (Row Level Security)
- All new tables must have RLS enabled.
- Policy names should follow the pattern: `auth_can_read`, `own_can_insert`, `own_can_delete`, `admin_can_modify`, etc.
- Restrict policies to `authenticated` role whenever possible.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/endermejia) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
