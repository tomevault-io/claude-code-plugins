# afrodite-backend

> Creating database migrations is not needed. When modifying database schema

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/afrodite-backend/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

Creating database migrations is not needed. When modifying database schema
use `make reset-database` command to update `schema.rs` file.

If you run `grep` command for some reason, make sure to exclude
`target` and `.git` directories.

Don't modify `api_client` crate or code which depends on it unless explicitly
requested.

Format code with `make fmt` command.

Use built-in workspace tools if possible.

---
> Source: [afroditeapp/afrodite-backend](https://github.com/afroditeapp/afrodite-backend) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-16 -->
