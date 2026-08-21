# kmp-contest-starter-kit

> This project ships vendor-neutral **Agent Skills**. Before implementing a task,

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/kmp-contest-starter-kit/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Copilot instructions

This project ships vendor-neutral **Agent Skills**. Before implementing a task,
check whether a skill already covers it.

- Full index — a 5-phase developer journey (guides) plus one-job task skills:
  [`skills/README.md`](../skills/README.md).
- Read the matching `skills/<name>/SKILL.md` and follow it. Steps are exact
  (real commands, file paths, console URLs) and are written to be followed
  manually or by an agent.
- Broader project conventions and the same skills index live in
  [`AGENTS.md`](../AGENTS.md).

**Firebase data in shared code** (Firestore, sync, cloud storage, server-side
balances): there is no Firebase client SDK for the `wasmJs` target, so this
decision trades away the web build. **Stop and ask the developer which they
want** before writing code or recommending an approach — see
[`skills/setup-firebase/SKILL.md`](../skills/setup-firebase/SKILL.md).

---
> Source: [KotlinFoundation/kmp-contest-starter-kit](https://github.com/KotlinFoundation/kmp-contest-starter-kit) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-20 -->
