# core-types

> Editing the domain shapes or provider interfaces.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/core-types/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


The purpose-named modules under `src/core/types/` are the source of truth for domain shapes and the five provider interfaces (`BuildEngine` / `StorageProvider` / `CredentialsProvider` / `Submitter` / `ComputeHost`).

- Add or change a shape in its matching purpose-named module and import it directly. Do not create an internal barrel.
- Normalized App Store resource/query shapes live in `src/core/types/appleCatalog.ts`; generated Apple wire types stay in `src/apple/generated/schema.ts`.
- Google Play wire/resource DTOs currently live beside the transport in `src/google/playClient.ts` and `src/google/playReporting.ts`; move them into a resource module only as part of that API mirror cleanup.

---
> Source: [YosefHayim/launch-store](https://github.com/YosefHayim/launch-store) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-01 -->
