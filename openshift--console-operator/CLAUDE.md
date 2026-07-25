# console-operator

> This file configures Claude Code for the OpenShift Console Operator project.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/console-operator/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Claude Code Configuration

This file configures Claude Code for the OpenShift Console Operator project.

## AI Context

See [AGENTS.md](./AGENTS.md) for the central AI documentation hub, which includes:

- [ARCHITECTURE.md](./ARCHITECTURE.md) - System architecture, components, repository structure
- [CONVENTIONS.md](./CONVENTIONS.md) - Go coding standards, patterns, import organization
- [TESTING.md](./TESTING.md) - Testing patterns, commands, debugging

## Quick Commands

```bash
# Build
make

# Test
make test-unit
make check

# Format
gofmt -w ./pkg ./cmd
```

---
> Source: [openshift/console-operator](https://github.com/openshift/console-operator) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-23 -->
