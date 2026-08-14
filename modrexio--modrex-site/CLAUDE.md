# modrex-site

> Read `CLAUDE.md` — it is the canonical source of architecture, conventions, and domain knowledge for this project.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/modrex-site/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agents

Read `CLAUDE.md` — it is the canonical source of architecture, conventions, and domain knowledge for this project.

## Skills

Reusable agent skills live in `.agents/skills/`. Load the relevant skill before executing it.

| Skill  | File                                                             | Description                                                |
| ------ | ---------------------------------------------------------------- | ---------------------------------------------------------- |
| commit | [.agents/skills/commit/SKILL.md](.agents/skills/commit/SKILL.md) | Propose a conventional commit message for the current diff |

---
> Source: [modrexio/modrex-site](https://github.com/modrexio/modrex-site) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-12 -->
