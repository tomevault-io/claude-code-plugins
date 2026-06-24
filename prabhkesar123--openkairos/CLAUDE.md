# openkairos

> Read .kairos/memory/MEMORY.md for full project context before responding.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/openkairos/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# openkairos — persistent memory for this project
# The openkairos daemon maintains .kairos/memory/MEMORY.md
# This file is automatically updated as the daemon observes your codebase

# Always read project memory at start of conversation:
Read .kairos/memory/MEMORY.md for full project context before responding.

# Memory structure:
# .kairos/memory/MEMORY.md — index of all topics
# .kairos/memory/*.md — detailed topic files (architecture, bugs, decisions)
# .kairos/logs/ — raw daily observations

# If .kairos/memory/MEMORY.md doesn't exist yet:
# Run: kairos init && kairos watch

---
> Source: [prabhkesar123/openkairos](https://github.com/prabhkesar123/openkairos) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-24 -->
