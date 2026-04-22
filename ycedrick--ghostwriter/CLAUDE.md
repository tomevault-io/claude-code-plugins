# ghostwriter

> This extension provides tools for reducing token usage by parsing source files into an Abstract Syntax Tree (AST) and removing unrelated function and class bodies before submitting them to the context window.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ghostwriter/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# GhostWriter Extension Context

This extension provides tools for reducing token usage by parsing source files into an Abstract Syntax Tree (AST) and removing unrelated function and class bodies before submitting them to the context window.

## Core Commands
- `ghostwriter prune <file>`: Reads the file, replaces unrelated function/class bodies with comments, and outputs to stdout or copies to clipboard.

## Line Auto-Detection
If `prune` is run without `--line`, it will automatically parse the clipboard for terminal error traces to identify the target line number in the specified file.

---
> Source: [ycedrick/ghostwriter](https://github.com/ycedrick/ghostwriter) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-22 -->
