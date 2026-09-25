# harness-engineering

> - Use the imported guide as the owning Python contract; do not infer a second

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/harness-engineering/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

@AGENTS.md

# Claude Code

- Use the imported guide as the owning Python contract; do not infer a second
  style from nearby raw-source files.
- Prefer replacing defensive branches with one closed parser and a stronger
  domain object. Preserve useful error locations at the JSON boundary.
- Keep changes focused across models, decoders, tests, and executable adapters,
  then run the complete proof loop from the imported guide.
- Treat `uv` lockfiles as generated artifacts. Refresh them through `uv`; never
  edit them by hand.

---
> Source: [lopopolo/harness-engineering](https://github.com/lopopolo/harness-engineering) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-25 -->
