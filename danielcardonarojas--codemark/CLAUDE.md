# codemark

> - Always run the linter and formatter before creating any PRs.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/codemark/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Development Workflow

- Always run the linter and formatter before creating any PRs.

---

# Debugging with the TUI logging system

The TUI writes structured logs to `$TMPDIR/codemark-tui.log` using `tracing`. Control verbosity via `RUST_LOG`:

```bash
RUST_LOG=codemark=debug cargo run -p codemark-tui   # all subsystems at debug
RUST_LOG=codemark::git=trace                         # only git at trace
RUST_LOG=codemark::db=debug,codemark::http=debug     # multiple subsystems
```

Available subsystem targets:

| Target | Covers |
|--------|--------|
| `codemark::git` | `rev-parse`, `ls-tree`, `status`, context/metadata detection |
| `codemark::db` | DB open, migrations, bookmark/collection/resolution CRUD |
| `codemark::http` | HTTP client, remote tour listing, pack download/upload, sync |
| `codemark::shell` | External editor spawning (program, args, errors) |
| `codemark::auth` | Server authorization decisions: repo read/write access checks, public-repo visibility, allow/deny outcomes |

When adding new functionality, instrument it with `tracing::debug!` (or `info!`/`warn!`/`error!` as appropriate) using the matching subsystem target. If adding a new subsystem, define a new `codemark::` target and add a row to the table above.

---
> Source: [DanielCardonaRojas/codemark](https://github.com/DanielCardonaRojas/codemark) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-13 -->
