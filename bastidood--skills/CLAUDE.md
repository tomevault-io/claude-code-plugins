# skills

> Use Bun for package installation, dependency management, and package scripts.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/skills/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository Conventions

## Package Management

Use Bun for package installation, dependency management, and package scripts.

## Plugin Manifests

- The [Agent Plugins specification](https://agent-plugins.org/specification.md) is authoritative for plugin manifests.
  - The `.claude-plugin/plugin.json` is a compatibility manifest for Claude, which notably doesn't support the standard.
  - Do not create `.codex-plugin/plugin.json` or `.cursor-plugin/plugin.json`; the namespaced Agent Plugins extension is authoritative.
  - Do not create `.cursor-plugin/plugin.json` unless the plugin requires Cursor-specific components that Agent Plugins does not support.

---
> Source: [BastiDood/skills](https://github.com/BastiDood/skills) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-29 -->
