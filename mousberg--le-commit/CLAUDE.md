# ats-integration

> description: **Frontend ID Strategy**: All frontend components use `applicant_id` as the primary identifier for consistency. **Backend ID Mapping**: APIs accept `applicant_id` and internally join to `ashby_candidates` table to get `ashby_id` when needed for external API calls. **Separation of Concerns**: Frontend handles business logic with applicant entities, backend handles integration-specific identifiers. **Reusable Utility**: Use `getAshbyIdFromApplicantId()` from `@/lib/ashby/utils` for consistent ashby_id lookups in APIs.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ats-integration/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

---
description: **Frontend ID Strategy**: All frontend components use `applicant_id` as the primary identifier for consistency. **Backend ID Mapping**: APIs accept `applicant_id` and internally join to `ashby_candidates` table to get `ashby_id` when needed for external API calls. **Separation of Concerns**: Frontend handles business logic with applicant entities, backend handles integration-specific identifiers. **Reusable Utility**: Use `getAshbyIdFromApplicantId()` from `@/lib/ashby/utils` for consistent ashby_id lookups in APIs.
globs:
alwaysApply: false
---

---
> Source: [mousberg/le-commit](https://github.com/mousberg/le-commit) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-07 -->
