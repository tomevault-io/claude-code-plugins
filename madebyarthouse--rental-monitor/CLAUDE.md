# routing

> Route patterns and loader expectations

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/routing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


- Route patterns allowed: `/`, `/:state`, `/:state/:district`, `/inserate`, `/:state/inserate`, `/:state/:district/inserate`.
- Loaders must validate params, call services, and set appropriate cache headers.
- Components should rely on loader data; avoid client-side fetching.
- React router 7 generates type definitions for the routes. Use them to validate the params and query in the loader functions. Use `pnpm run rr:generate` to generate the type definitions when you change the routes.

---
> Source: [madebyarthouse/rental-monitor](https://github.com/madebyarthouse/rental-monitor) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-21 -->
