# imp-lab

> - Educational Lean 4 playground for language modeling and debugger experimentation.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/imp-lab/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS

## Scope and priorities
- Educational Lean 4 playground for language modeling and debugger experimentation.
- Optimize for clarity and maintainability, not performance.
- Avoid compatibility shims during refactors; prefer direct clean structure.

## Main surfaces
- Language runtime and semantics: `ImpLab/Lang/*.lean`
- Debugger subsystem: `ImpLab/Debugger/*`
- Executables: `app/`
- Tests: `Test/`
- VS Code client: `client/`

## Build/test commands
- `lake build`
- `lake exe dap-tests`
- `lake exe toydap`
- `lake exe dap-export --help`
- `cd client && npm run compile`

## Global conventions
- `imp%[...]` is the only DSL elaborator and must produce `ProgramInfo`.
- `imp%[...]` accepts top-level `global` declarations and functions, and must include `main()` (zero params).
- `get`/`set` must only access declared globals; undeclared access is a runtime error.
- Keep `mainProgram` as default fixture entrypoint in `examples/Main.lean`.
- Prefer `initialize` over `builtin_initialize` in project code.

## Subsystem-local instructions
- Debugger-specific rules and review checklist live in:
  - `ImpLab/Debugger/AGENTS.md`
- Debugger active work tracking lives in:
  - `docs/debugger-roadmap.md`

---
> Source: [ejgallego/imp-lab](https://github.com/ejgallego/imp-lab) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-03 -->
