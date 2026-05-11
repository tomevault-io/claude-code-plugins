# cyberfabric-core

> <!-- @cpt:root-agents -->

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/cyberfabric-core/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

<!-- @cpt:root-agents -->
```toml
cypilot_path = ".cypilot"
```
<!-- /@cpt:root-agents -->

These instructions are for AI assistants working in this project.

If the instruction sounds unclear, vague or requires more context. Ask for clarification.

Always open `@/guidelines/README.md` first (entry point for project-wide guidelines).

Open additional docs only when relevant:

- If the task adds/changes dependencies (Cargo.toml), introduces a new crate, involves working with 3rd-party crates (such as those for serialization/deserialization), open `@/guidelines/DEPENDENCIES.md`.

- If the task touches ModKit/module architecture (modules layout, `@/lib/modkit*`, plugins, REST wiring, ClientHub, OpenAPI, lifecycle/stateful tasks, SSE, standardized HTTP errors), open `@/docs/modkit_unified_system/README.md`.

---
> Source: [cyberfabric/cyberfabric-core](https://github.com/cyberfabric/cyberfabric-core) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-06 -->
