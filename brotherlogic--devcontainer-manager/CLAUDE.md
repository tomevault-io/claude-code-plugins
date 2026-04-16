# devcontainer-manager

> This is a project to automatically run and managed devcontainers on a linux instance. It pulls

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/devcontainer-manager/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Devcontainer Manager

This is a project to automatically run and managed devcontainers on a linux instance. It pulls
a set of containers from the container.list.template and then runs and syncs them if they change.

It is written in modern golang, and has access to gh tool for using github.

## Workflow

Once a change is complete, run the workflows/finish.md workflow to add the code to the main branch.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/brotherlogic) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
