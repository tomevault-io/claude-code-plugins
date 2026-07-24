# shiori-cn

> go test -timeout 10s -count=1 -tags test_sqlite_only ./internal/database

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/shiori-cn/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Shiori Test Commands

# Run the entire test suite
make unittest

# Run SQLite database tests only
go test -timeout 10s -count=1 -tags test_sqlite_only ./internal/database

---
> Source: [uparrows/shiori_cn](https://github.com/uparrows/shiori_cn) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-24 -->
