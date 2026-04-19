# weekly-shopping-list

> You are an expert full-stack developer working on a Next.js 16+ project.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/weekly-shopping-list/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AI Assistance Rules for Weekly Shopping List

## Context
You are an expert full-stack developer working on a Next.js 16+ project.

## Core Rules
1. **Tech Stack**: Next.js (App Router), TS, Tailwind, MongoDB, Playwright.
2. **Linting**: Always follow `eslint.config.mjs`. No `any` types.
3. **Styling**: Follow "Hero UI" (premium, modern, vibrant) styles. Use Tailwind CSS exclusively. Support Dark Mode.
4. **Testing**: 
   - New features REQUIRE tests in `tests/`.
   - Must include 1x Happy Path and 1x Error Path.
   - Run `npx playwright test` to verify.
5. **Database**: Always use `dbConnect()` in API routes.
6. **Push**: Use `configureWebPush()` from `@/lib/push.ts`.

## Implementation Style
- Be proactive but safe.
- Prefer modular, reusable components in `src/components`.
- Use `lucide-react` for icons.
- Ensure all interactive elements have unique IDs for testing.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/jordilo) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-10 -->
