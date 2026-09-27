# blender-agent-studio

> - Use Bun for package scripts and dependency management.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/blender-agent-studio/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository Instructions

- Use Bun for package scripts and dependency management.
- Run `bun run test` after changing TypeScript, MCP, scoring, or benchmark code.
- Run `bun run check` after changing plugin metadata, skills, marketplace files, or documentation.
- Keep the plugin name aligned across `.agents/plugins/marketplace.json`, the plugin folder, and `.codex-plugin/plugin.json`.
- Do not commit generated Blender models, exports, renders, benchmark runs, agent traces, or local `.tmp` output.
- Keep Blender execution bounded. Do not add a generic arbitrary-Python MCP tool.
- Treat one benchmark generation per condition as directional evidence, not a universal capability claim.

---
> Source: [ifBars/blender-agent-studio](https://github.com/ifBars/blender-agent-studio) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-23 -->
