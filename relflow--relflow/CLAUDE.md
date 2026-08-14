# relflow

> Read `AGENTS.md` first. It defines the public RelFlow API style, schema patterns, gotchas, and verification commands.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/relflow/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# GitHub Copilot Instructions

Read `AGENTS.md` first. It defines the public RelFlow API style, schema patterns, gotchas, and verification commands.

Use `import relflow as rf` in generated examples. Prefer `Model.from_tree(...)`, built-in tensorfield constructors, `Branch(...)`, and top-level package exports. Do not invent a public `Struct(...)` API.

Keep inline docs examples and Quarto pages runnable and small. When changing package behavior, update tests and docs together.

---
> Source: [relflow/relflow](https://github.com/relflow/relflow) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-13 -->
