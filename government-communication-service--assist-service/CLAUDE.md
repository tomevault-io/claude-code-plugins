# inject-db-session-at-api-level

> When creating a new API endpoint, make sure to use dependency injection to create an asynchronous database session. Then inject the same session throughout the request lifecycle.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/inject-db-session-at-api-level/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

When creating a new API endpoint, make sure to use dependency injection to create an asynchronous database session. Then inject the same session throughout the request lifecycle.

When creating functions in the service layer that require a database session, make sure to try to receive the database session from the API layer, and pass it between any service functions that require the session.

---
> Source: [Government-Communication-Service/assist_service](https://github.com/Government-Communication-Service/assist_service) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-21 -->
