# namespace-diagnostic-wording

> Prefer clear wording for unrecognized extension namespaces

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/namespace-diagnostic-wording/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Namespace diagnostic wording

When a PSL namespaced attribute is used but the namespace is unavailable in config, avoid phrasing like "namespace not composed".

Use clear user-facing wording such as:
- "unrecognized namespace"
- "namespace is not available"

Preferred guidance in messages:
- Name the namespace explicitly.
- Tell the user to add the corresponding extension pack to `extensionPacks` in `prisma-next.config.ts`.

---
> Source: [prisma/prisma-next](https://github.com/prisma/prisma-next) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-20 -->
