# directory-structure

> directory structure to follow

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/directory-structure/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

---
description: the top-level directory structure for the project
globs: 
alwaysApply: false
---     
# Directory Structure
```mermaid
flowchart TD
    Root[Project Root]
    Root --> Docs[docs/]
    Root --> Tasks[tasks/]
    Root --> Cursor[.cursor/rules/]
    Root --> CLINE[.clinerules]
    Root --> SourceCode[src/]
    Root --> Test[test/]
    Root --> Utils[utils/]
    Root --> Config[config/]
    Root --> Data[data/]
    Root --> Other[Other Directories]
```

---
> Source: [Bhartendu-Kumar/rules_template](https://github.com/Bhartendu-Kumar/rules_template) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
