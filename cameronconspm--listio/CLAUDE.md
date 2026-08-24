# architecture

> Keep docs/ARCHITECTURE.md updated when app structure or data flow changes

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/architecture/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Architecture documentation

Canonical reference: [`docs/ARCHITECTURE.md`](../../docs/ARCHITECTURE.md)

Update when changing:

- App bootstrap gates or provider tree (`App.tsx`)
- Auth, bootstrap, or premium gate flow
- React Query keys, persistence, or bundle fetch patterns
- Service boundaries (client vs Edge Functions)
- Realtime, import, or sync behavior

Add a row to the **Changelog** section with the date and a one-line summary.

Cross-update [`docs/DATA_MODEL.md`](../../docs/DATA_MODEL.md) if entity relationships or RLS scope change.

---
> Source: [cameronconspm/Listio](https://github.com/cameronconspm/Listio) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-22 -->
