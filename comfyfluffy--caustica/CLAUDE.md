# caustica

> - Keep planning documents and `todos.md` local-only. Do not add `docs/*PLAN*.md` or `todos.md` to Git.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/caustica/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository guidance

- Keep planning documents and `todos.md` local-only. Do not add `docs/*PLAN*.md` or `todos.md` to Git.
- Comments and Javadocs must describe the current implementation and its active invariants only.
- Do not preserve implementation history, migration notes, completed phases, or superseded behavior in source comments. Git history owns that context.
- Do not reference internal plan steps, phase labels, milestone IDs, or numbered design-document sections from source comments.
- Prefer direct explanations of why the current code is required, especially API contracts, synchronization rules, units, and non-obvious constraints.
- Until release, modify only the English locale (`en_us.json`); leave every other locale unchanged.

---
> Source: [ComfyFluffy/Caustica](https://github.com/ComfyFluffy/Caustica) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-11 -->
