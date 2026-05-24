# arcanum

> This repository is the canonical Arcanum framework and registry for reusable agent capabilities.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/arcanum/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Arcanum Copilot Instructions

This repository is the canonical Arcanum framework and registry for reusable agent capabilities.

For Arcanum requests, prefer the `arcanum-orchestrate` skill. It routes through the canonical registries instead of copying sigil internals into the command wrapper.

Core references:

- `registry/SIGILS.md` for sigil lookup.
- `registry/SPELLS.md` for spell lookup.
- `framework/` for authoring, validation, observability, and lifecycle rules.
- `arcana/`, `transmutations/`, and `formulae/` for canonical sigil files.

Keep installed runtime adapters thin. Canonical behavior lives in the sigil and spell files.

---
> Source: [cyberAlchemyAI/Arcanum](https://github.com/cyberAlchemyAI/Arcanum) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-23 -->
