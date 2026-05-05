# dot-pi

> Enable extensions, skills, and rules by creating symlinks in `~/.pi/agent/`:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/dot-pi/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Development Guidelines

## Installation

Enable extensions, skills, and rules by creating symlinks in `~/.pi/agent/`:

```bash
# Extensions
ln -s /path/to/dot-pi/extensions/codesearch.ts ~/.pi/agent/extensions/

# Skills
ln -s /path/to/dot-pi/skills/ai-news ~/.pi/agent/skills/

# Rules
ln -s /path/to/dot-pi/rules/typescript.md ~/.pi/agent/rules/
```

Each symlink points directly to the source file or directory. No intermediate symlinks.

## Adding New Components

When adding new extensions, skills, or rules:

1. Add entry to the corresponding table in `README.md`
2. Keep tables alphabetically sorted
3. Include Origin column with link to source if adapted from another project
4. Commit both the component and README update together

---
> Source: [dannote/dot-pi](https://github.com/dannote/dot-pi) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-02 -->
