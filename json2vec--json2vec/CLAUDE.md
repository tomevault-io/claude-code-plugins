# json2vec

> Read `AGENTS.md` first. It defines the public JSON2Vec API style, schema patterns, gotchas, and verification commands.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/json2vec/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# GitHub Copilot Instructions

Read `AGENTS.md` first. It defines the public JSON2Vec API style, schema patterns, gotchas, and verification commands.

Use `import json2vec as j2v` in generated examples. Prefer `Model.from_schema(...)`, built-in tensorfield constructors, `Array(...)`, and top-level package exports. Do not invent a public `Struct(...)` API.

Keep inline docs examples and notebooks runnable and small. When changing package behavior, update tests and docs together.

---
> Source: [json2vec/json2vec](https://github.com/json2vec/json2vec) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-17 -->
