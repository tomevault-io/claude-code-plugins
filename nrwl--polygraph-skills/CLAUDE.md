# polygraph-skills

> Never add exports to `source/opencode/server.js`. OpenCode loads it as a plugin; any export beyond the plugin entry breaks OpenCode for every user with the plugin installed. Put shared or testable logic in sibling modules under `source/opencode/` and import it into `server.js`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/polygraph-skills/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Guidelines for polygraph-skills

## OpenCode plugin — server.js export rule

Never add exports to `source/opencode/server.js`. OpenCode loads it as a plugin; any export beyond the plugin entry breaks OpenCode for every user with the plugin installed. Put shared or testable logic in sibling modules under `source/opencode/` and import it into `server.js`.

---
> Source: [nrwl/polygraph-skills](https://github.com/nrwl/polygraph-skills) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-11 -->
