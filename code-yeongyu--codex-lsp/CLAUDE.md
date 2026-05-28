# codex-lsp

> Conventions for humans and agents working on this repository.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/codex-lsp/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository Conventions

Conventions for humans and agents working on this repository.

## Style

- TypeScript strict mode. No `any`, `@ts-ignore`, `@ts-expect-error`, or enums.
- ESM modules with `.js` suffix in import paths.
- Tabs for indentation. Double quotes for strings.
- Runtime is Node only.
- Tests use vitest and should exercise Codex hook/MCP behavior before implementation changes.

## Commands

- `npm install` installs dependencies.
- `npm test` runs the test suite once.
- `npm run typecheck` runs strict TypeScript checking.
- `npm run check` runs typecheck, Biome, and build.

## LSP Constraints

- LSP server processes are owned by `LspManager`.
- Tool execution acquires clients through `withLspClient(...)` unless it only reports static status.
- `lsp.rename` mutates files by applying workspace edits; keep it sequential at the MCP caller level.
- Do not add pi-coding-agent or omo source dependencies. This package is standalone.

---
> Source: [code-yeongyu/codex-lsp](https://github.com/code-yeongyu/codex-lsp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-28 -->
