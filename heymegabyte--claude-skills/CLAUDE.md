# emdash-skills

> Emdash Skills — 14-category product-building OS for Windsurf.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/emdash-skills/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Emdash Skills for Windsurf

Load CONVENTIONS.md for stack defaults. Load _router.md for skill routing.
14 categories (01-14), 94 reference docs, 18 agents.

## Stack

CF Workers+Hono | Angular 21+Ionic 8+PrimeNG 21 | D1/Neon | Drizzle v1 | Clerk | Stripe | Inngest | Resend | Bun | Playwright v1.59+ | PostHog | Sentry

## Rules

- TypeScript strict, never `any`, prefer `interface` over `type`
- Hono inline handlers for RPC type inference
- Zod validation on all inputs
- TDD: failing test first, Playwright 6 breakpoints
- Dark-first design, #060610 bg, #00E5FF accent
- Deploy to CF Workers, purge CDN after every deploy

See CONVENTIONS.md for full patterns.

---
> Source: [heymegabyte/claude-skills](https://github.com/heymegabyte/claude-skills) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-15 -->
