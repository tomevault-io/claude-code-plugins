# architecture

> Core architectural guardrails for Befristungs-Monitor

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/architecture/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


- Use React Router 7 SSR loaders for all data fetching; do not add client-side data libraries (React Query, tRPC).
- All state must be URL-driven (path + query). Update state by changing the URL.
- Use the service layer in `app/services/*` extending `BaseService`; do not write raw SQL outside Drizzle.
- Access D1 via `context.cloudflare.env.rental_monitor` only.
- Do not introduce global state managers (Redux, Zustand) or bypass loaders with `useEffect(...fetch)`.

---
> Source: [madebyarthouse/rental-monitor](https://github.com/madebyarthouse/rental-monitor) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-21 -->
