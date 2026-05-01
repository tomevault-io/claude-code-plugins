# prefer-postgres-apis

> Prefer PostgreSQL utility functions over C standard library equivalents in extension C code

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/prefer-postgres-apis/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Prefer PostgreSQL utility functions

When writing C code for PostgreSQL extensions, prefer PostgreSQL's own utility
functions over C standard library equivalents.

## String functions (`common/string.h`)

- `pg_str_endswith(str, suffix)` instead of manual `strlen` + `strcmp` suffix checks
- `strtoint(str, &endptr, base)` instead of `sscanf(str, "%d", ...)` or `atoi`

## Memory and string allocation (`utils/palloc.h`, `utils/builtins.h`, `lib/stringinfo.h`)

- `palloc` / `pfree` instead of `malloc` / `free`
- `pstrdup` / `pnstrdup` instead of `strdup` / `strndup`
- `psprintf` instead of `snprintf` into a manually-sized buffer
- `StringInfo` (`appendStringInfo`, etc.) instead of repeated `strcat` or manual buffer management

## Output and formatting

- `elog` / `ereport` instead of `fprintf(stderr, ...)`
- `OutputFunctionCall` for datum-to-string conversions instead of hand-rolled formatting

---
> Source: [Snowflake-Labs/pg_lake](https://github.com/Snowflake-Labs/pg_lake) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-20 -->
