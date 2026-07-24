# shiori

> go test -timeout 10s -count=1 -tags test_sqlite_only ./internal/database

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/shiori/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Shiori Test Commands

# Run the entire test suite
make unittest

# Run SQLite database tests only
go test -timeout 10s -count=1 -tags test_sqlite_only ./internal/database

---
> Source: [go-shiori/shiori](https://github.com/go-shiori/shiori) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-24 -->
