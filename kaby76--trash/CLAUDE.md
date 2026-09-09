# trash

> The Trash toolchain is a single dotnet tool called `trash`. Subcommands are dispatched via `dotnet trash <subcommand>`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/trash/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Trash project notes for Codex

## CLI invocation

The Trash toolchain is a single dotnet tool called `trash`. Subcommands are dispatched via `dotnet trash <subcommand>`.

- Parse grammars: `dotnet trash parse <file.g4> ...`  (NOT a separate `trparse` binary)
- Generate interp files: `dotnet trash interp [options]`
- Full pipeline example:
  ```
  dotnet trash parse grammar.g4 | dotnet trash interp --atn -o outdir
  ```

There is no standalone `trparse` executable.

## Git commits

Please follow https://www.conventionalcommits.org/en/v1.0.0-beta.1/ for commits, i.e.:
```
<type>[optional scope]: <description>

[optional body]

[optional footer]
```

`<type>` is one of `fix`, `feat`, `BREAKING CHNAGE`.
`scope` is within parentheses and should be named after directory under `./src/`, e.g., `(trparse)`.

---
> Source: [kaby76/Trash](https://github.com/kaby76/Trash) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-08 -->
