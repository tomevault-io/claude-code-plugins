# 20-codegen-boundaries

> Keep manual code separate from generated SDK code

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/20-codegen-boundaries/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Guideline:

- Avoid modifying auto-generated files in `src/agentex/` except where explicitly intended. Place custom logic, extensions, and higher-level abstractions in `src/agentex/lib/`.
- When adding features, prefer adding new modules under `src/agentex/lib/**` rather than changing generated files directly.
- If a change to generated code is required, document the reason and ensure the generator configuration or upstream schema is updated to make the change reproducible.

---
> Source: [scaleapi/scale-agentex-python](https://github.com/scaleapi/scale-agentex-python) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-06 -->
