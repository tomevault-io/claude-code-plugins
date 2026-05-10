# agentic

> This repository contains subagents and commands designed to enhance opencode's capabilities through modular, specialized components.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/agentic/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agentic Repository Overview

This repository contains subagents and commands designed to enhance opencode's capabilities through modular, specialized components.

## Directory Structure

### `/agent`
Contains subagents that function as specialized task performers for opencode. Each subagent executes a series of tool calls and returns structured information that the main agent can process and utilize.

### `/command`
Houses commands available to the main agent. These commands leverage subagents to perform complex operations while minimizing context consumption through contextual compression, allowing the main agent to work more efficiently.

---
> Source: [Cluster444/agentic](https://github.com/Cluster444/agentic) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-04 -->
