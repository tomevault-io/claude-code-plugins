# tts-audiobook-tool

> When inspecting large source files, prefer targeted searches and bounded line-range reads when the available tools support them. Read the entire file only when its full context is genuinely needed.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tts-audiobook-tool/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent operation

When inspecting large source files, prefer targeted searches and bounded line-range reads when the available tools support them. Read the entire file only when its full context is genuinely needed.

# Testing and validation

Once appropriate validation has passed, stop. Do not expand testing merely to increase confidence when the remaining risk is low relative to the scope of the change.

The full project test suite is relatively expensive. Treat it as broad validation, not the default completion step for every edit.


# Python environment

- Treat `pyproject.toml` as effectively irrelevant to dependency and tooling discovery; its only agent-relevant content is the configuration concerning the `tests` directory.


# Project directories

`testx/`: Durable developer-facing scripts that demonstrate a mostly working subsystem, verify assumptions, or serve as rerunnable reference material belong in `testx/` instead. Run scripts in `testx/` like so:

```bash
./some-venv/bin/python -m testx.llm_util
```

---
> Source: [zeropointnine/tts-audiobook-tool](https://github.com/zeropointnine/tts-audiobook-tool) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-04 -->
