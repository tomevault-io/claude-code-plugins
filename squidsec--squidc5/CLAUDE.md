# squidc5

> Read and obey root **AGENTS.md**.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/squidc5/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# GitHub Copilot instructions for SquidC5

Read and obey root **AGENTS.md**.

- Security-first C2 for authorized testing only
- Do not weaken MCP tool allow-lists or Admin AI `sanitize_untrusted` boundaries
- Do not commit tokens, API keys, or `data/` contents
- Prefer deterministic templates over autonomous agent loops
- Operator CLI is `sc5` - keep help/README/AGENTS in sync when adding commands
- Docker compose uses host networking for listener ports; document privileged-port sysctl for &lt;1024

---
> Source: [SquidSec/SquidC5](https://github.com/SquidSec/SquidC5) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-26 -->
