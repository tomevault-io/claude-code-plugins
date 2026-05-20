# sentry

> Sentry observability conventions — capture funnel and direct-call rule

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/sentry/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Sentry Rules

@docs/sentry.md

- Do not attach raw user data to Sentry events. If an `Err.*` context includes `email`, `phone`, `phoneNumber`, `name`,
  `firstName`, `lastName`, `displayName`, `username`, `bio`, `file`, `user`, raw Pubky keys, or Pubky URLs, verify
  `src/libs/observability/sentry.ts` redacts it before merge.

---
> Source: [pubky/pubky-app](https://github.com/pubky/pubky-app) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-19 -->
