# telegram-ai-agent

> Follow `AGENTS.md`. This is a public generic Telegram bot runtime, not a

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/telegram-ai-agent/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Claude Instructions

Follow `AGENTS.md`. This is a public generic Telegram bot runtime, not a
personal assistant repository.

Before editing, inspect the relevant files and keep changes scoped. Do not copy
private prompts, private project knowledge, local runtime configs, secrets, or
machine-specific deployment files into this repository.

Use the public project knowledge skill when you need architecture or release
context:

- `.codex/skills/project-knowledge/SKILL.md`

Use `.codex/skills/bot-setup/SKILL.md` for installation, systemd autostart,
language, commands, and operator troubleshooting. Use
`.codex/skills/topic-setup/SKILL.md` for Telegram forum topic wiring.

Run the standard checks before final handoff:

```bash
uv run ruff check .
uv run ruff format --check .
uv run mypy src/ mcp-servers/bot/server.py
uv run pytest
```

---
> Source: [pavel-molyanov/telegram-ai-agent](https://github.com/pavel-molyanov/telegram-ai-agent) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-29 -->
