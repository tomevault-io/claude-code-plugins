# date-sniffer

> Guidelines for creating new agent rules - categorize rules appropriately, use required frontmatter fields, keep rules concise and generic, avoid project-specific details.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/date-sniffer/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Rule Creation

## Category Organization

- Each directory in the rules folder represents a category
- When creating a new rule, attempt to fit it into an existing category
- Only create a new category if the rule cannot fit into any existing category

## Required Frontmatter

All rule files must include these fields in order:

```
---
alwaysApply: true | false
description: concise description
author: Himel Das
---
```

## Content Guidelines

- Be concise and generic
- Remain project and programming language independent
- Avoid code snippets, examples, or project-specific information
- Do not include confidential or personal information
- Explain what to do, not how to do it
- Follow professional best practices for AI agent rules

## File Format

- Always save rules in `.mdc` files
- Use lowercase words separated by dashes for filenames

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/sayeedjoy) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
