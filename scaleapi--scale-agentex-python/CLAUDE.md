# 40-temporal-and-agents

> Temporal workflows, activities, and agent development guidance

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/40-temporal-and-agents/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Temporal integration:

- Workflow definitions live in `lib/core/temporal/`
- Include activity definitions for different providers and worker implementations
- Keep workflow logic deterministic and side-effect free; move I/O into activities

Agent framework:

- Agents are manifest-driven and support multiple agent types (sync and Temporal-based)
- Use the examples under `examples/10_async/` and `examples/10_temporal/` for patterns
- For debugging agents, use the CLI flags `--debug-worker` and `--debug-port`

---
> Source: [scaleapi/scale-agentex-python](https://github.com/scaleapi/scale-agentex-python) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-06 -->
