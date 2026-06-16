# promptito

> Each prompt is a Markdown file with YAML frontmatter.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/promptito/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# SKILL.md Format

Each prompt is a Markdown file with YAML frontmatter.

## Required Fields

```yaml
---
name: Prompt Name
description: One sentence description
version: 1.0.0
---
```

## Optional Fields

```yaml
---
category: engineering    # engineering, writing, design, data, other
tags: [code, review]    # Searchable tags
sfia:
  level: 3              # 1-5 (competency)
framework:
  type: risen           # risen, costar, or custom
qualityMetrics:
  accuracy: 0.9         # 0-1 score
guardrails:
  do: [allowed uses]
  dont: [disallowed uses]
ethics:
  humanAgency: "Human must approve"
author: Your Name
---
```

## Content

```markdown
---
name: Code Reviewer
---

# Role
You are a senior code reviewer...

# Instructions
- Check for bugs
- Verify tests pass
```

[Example](./public/prompts/code-reviewer/SKILL.md)

---
> Source: [jacotoledo/Promptito](https://github.com/jacotoledo/Promptito) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-16 -->
