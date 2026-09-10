# osint-cli-tool-skeleton

> See [AGENTS.md](AGENTS.md) for how to build a tool from this skeleton.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/osint-cli-tool-skeleton/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

See [AGENTS.md](AGENTS.md) for how to build a tool from this skeleton.

TL;DR: add capabilities by creating **one plugin file** in
`osint_cli_tool_skeleton/plugins/` — subclass `Plugin`, implement
`async def run(self, target)`. Never edit the engine, CLI, server or reports.
Scaffold with `python -m osint_cli_tool_skeleton --new-plugin <name>`.

---
> Source: [soxoj/osint-cli-tool-skeleton](https://github.com/soxoj/osint-cli-tool-skeleton) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-09 -->
