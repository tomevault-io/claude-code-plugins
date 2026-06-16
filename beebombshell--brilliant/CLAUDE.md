# brilliant

> Project guidelines for AI assistants.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/brilliant/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

Project guidelines for AI assistants.


<!-- tambo-docs-v1.0 -->
## Tambo AI Framework

This project uses **Tambo AI** for building AI assistants with generative UI and MCP support.

**Documentation**: https://docs.tambo.co/llms.txt

### CLI Commands (Non-Interactive)

The Tambo CLI auto-detects non-interactive environments. Use these commands:

```bash
# Initialize (requires API key from https://console.tambo.co)
npx tambo init --api-key=sk_...

# Add components
npx tambo add <component> --yes

# List available components
npx tambo list --yes

# Create new app
npx tambo create-app <name> --template=standard

# Get help
npx tambo --help
npx tambo <command> --help
```

**Exit codes**: 0=success, 1=error, 2=requires flags (check stderr for exact command)

---
> Source: [BeeBombshell/brilliant](https://github.com/BeeBombshell/brilliant) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-16 -->
