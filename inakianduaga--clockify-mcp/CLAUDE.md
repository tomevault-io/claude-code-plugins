# archiecture-understanding

> rules to parse solution architecture from docs/architecture.md

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/archiecture-understanding/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

---
description: rules to parse solution architecture from docs/architecture.md
globs: 
alwaysApply: false
---
# Architecture Understanding
READ_ARCHITECTURE: |
  File: docs/architecture.md @architecture.md
  Required parsing:
  1. Load and parse complete Mermaid diagram
  2. Extract and understand:
     - Module boundaries and relationships
     - Data flow patterns
     - System interfaces
     - Component dependencies
  3. Validate any changes against architectural constraints
  4. Ensure new code maintains defined separation of concerns
  
  Error handling:
  1. If file not found: STOP and notify user
  2. If diagram parse fails: REQUEST clarification
  3. If architectural violation detected: WARN user

---
> Source: [inakianduaga/clockify-mcp](https://github.com/inakianduaga/clockify-mcp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-22 -->
