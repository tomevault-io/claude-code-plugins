# tagpr

> - This is a Go project. Use `go build` to build and `go test ./...` to run tests.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tagpr/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Copilot Instructions for tagpr

## Language & Build

- This is a Go project. Use `go build` to build and `go test ./...` to run tests.

## Code Quality Checks

Before committing, always run the following in order:

1. `goimports -w .` — format code and organize imports
2. `go vet ./...` — check for common errors
3. `staticcheck ./...` — run static analysis

All three must pass with no errors before pushing.

## Testing

- Run `go test ./...` to execute all tests.
- Ensure all existing tests pass after making changes.

---
> Source: [Songmu/tagpr](https://github.com/Songmu/tagpr) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-29 -->
