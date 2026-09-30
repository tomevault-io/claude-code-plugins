# datasette-agent

> To run a development localhost server:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/datasette-agent/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

To run a development localhost server:

    uv run datasette -s plugins.datasette-llm.default_model gpt-6-luna \
      --internal internal.db --create demo.db --root --secret 1 -p 8518 --reload

---
> Source: [datasette/datasette-agent](https://github.com/datasette/datasette-agent) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-30 -->
