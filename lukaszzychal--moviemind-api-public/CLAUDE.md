# 030-breaking-changes

> If a change may affect DB schema/data, API contracts, identifiers/slugs, validation rules, or existing behavior:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/030-breaking-changes/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Breaking changes: stop and analyze

If a change may affect DB schema/data, API contracts, identifiers/slugs, validation rules, or existing behavior:
STOP and provide:
1) what breaks (exactly)
2) affected endpoints/data
3) safe plan: backward compatibility, migration steps, rollout, rollback
4) tests covering existing data/clients
Only then implement.

---
> Source: [lukaszzychal/moviemind-api-public](https://github.com/lukaszzychal/moviemind-api-public) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-13 -->
