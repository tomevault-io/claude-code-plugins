# spool

> description: Defines the recommended state management strategies for Next.js 15 applications, including server and client contexts.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/spool/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

---
description: Defines the recommended state management strategies for Next.js 15 applications, including server and client contexts.
globs: app/**/*
---
- Use `useActionState` instead of deprecated `useFormState`.
- Leverage enhanced `useFormStatus` with new properties (data, method, action).
- Implement URL state management with 'nuqs'.
- Minimize client-side state.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/G2-Spool) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
