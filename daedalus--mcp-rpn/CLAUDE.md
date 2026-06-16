# mcp-rpn

> MCP server exposing an RPN (Reverse Polish Notation) calculator.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mcp-rpn/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# MCP RPN

MCP server exposing an RPN (Reverse Polish Notation) calculator.

## When to use this skill

Use this skill when you need to:
- Perform calculator operations
- Evaluate mathematical expressions in RPN format

## Tools

- `evaluate` - Evaluate RPN expression
- `clear` - Clear the stack

**Operators:** +, -, *, /, **, %
**Commands:** clear, dup, swap

## Install

```bash
pip install mcp-rpn
```

---
> Source: [daedalus/mcp-rpn](https://github.com/daedalus/mcp-rpn) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-16 -->
