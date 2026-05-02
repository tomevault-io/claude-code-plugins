# claude-bash-approve

> Go project in `hooks/bash-approve/`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/claude-bash-approve/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# claude-bash-approve

Go project in `hooks/bash-approve/`.

## Commands

```bash
cd hooks/bash-approve
go test ./...                # run tests
golangci-lint run ./...      # lint
```

## Adding commands

1. Add pattern to `allCommandPatterns` or `allWrapperPatterns` in `rules.go`
2. Add test cases in `main_test.go`
3. Update `categories.yaml` if introducing a new group

## Testing

1. Avoid tautological tests that purely test the existance of code/config files already present in the codebase.

---
> Source: [mariusvniekerk/claude-bash-approve](https://github.com/mariusvniekerk/claude-bash-approve) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-29 -->
