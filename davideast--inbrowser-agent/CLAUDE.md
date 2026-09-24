# inbrowser-agent

> Browser-native workspace runtime for the inbrowser stack.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/inbrowser-agent/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# `@inbrowser/workspace`

Browser-native workspace runtime for the inbrowser stack.

## Boundaries

- Owns infrastructure: file system adapters, preview compilation, shell execution, git, package import maps, and optional agent tool adapters.
- Does not own UI, prompting strategy, model selection, product copy, or app-builder policy.
- Does not promise a real Vite/dev server in V1. Preview compiles and mounts browser-compatible app code.

## Code health

- Keep `fs` independent. Preview, shell, git, packages, and tools may depend on `fs`; `fs` must not depend on them.
- Avoid package-level singletons in public APIs. Hosts create explicit workspace instances.
- Expected failures should return typed result objects where practical.
- Heavy/runtime-specific imports should stay in subpath modules.

---
> Source: [davideast/inbrowser-agent](https://github.com/davideast/inbrowser-agent) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-23 -->
