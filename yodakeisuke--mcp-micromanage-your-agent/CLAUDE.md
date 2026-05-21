# solution-exploration-guide

> When examining how to implement an issue

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/solution-exploration-guide/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Purpose
- nformation gathering and Brainstorming potential approaches

## Forbidden: 
- Concrete planning, implementation details, or any code writing

##output-format
- file: ticket_[issue name].md
- chapters:
    - Summary of the issue that will be resolved with the ticket
    - Overview of the architecture, domain model and data model to be changed or added this time
    - Work plan based on PR and commitment units(This is only for creating chapters, do not write content)

## Method
- Understand the issue from the given information and existing code
- research and interviews with users to ensure that we have all the information we need to complete the task
- Analyze potential impacts to the existing codebase

---
> Source: [yodakeisuke/mcp-micromanage-your-agent](https://github.com/yodakeisuke/mcp-micromanage-your-agent) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
