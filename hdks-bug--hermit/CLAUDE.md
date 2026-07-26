# hermit

> The `agent` command manages C2 agents.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/hermit/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent

The `agent` command manages C2 agents.  
Basically, this command is used after the C2 agent connected to listeners.  

For usage, run `help agent`, `help agent <subcommand>`.

## `agent list`, `agents`

List agents connected to our listeners.

## `agent info <ID>`

Prints the agent detailed information.

## `agent note <ID>`

Takes a note for the agent.  
This is useful when we want to write down arbitrary information.  
It spawns `nano` editor by default. If error occured, tries `vim`.

## `agent delete <ID>`

Deletes an agent.

---
> Source: [hdks-bug/hermit](https://github.com/hdks-bug/hermit) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-26 -->
