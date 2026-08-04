# queue

> Guidelines for AI agents working in this repository.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/queue/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

Guidelines for AI agents working in this repository.

## Commands

All commands are executed via `make`.

```bash
make <target> [VARIABLE=value ...]
```

### Variables

| Variable | Description |
|---|---|
| `NO_TTY=1` | **Always pass this** — there is no interactive terminal |
| `ARGS="..."` | Extra arguments passed to the underlying tool |
| `PHP_VERSION=8.3` | Override PHP version (default: 8.4) |

### Targets

| Target | Description |
|---|---|
| `make test` | Run PHPUnit tests (alias for `make phpunit`) |
| `make phpunit` | Run PHPUnit tests |
| `make coverage` | Generate HTML coverage report to `runtime/coverage/` |
| `make infection` | Run mutation testing with Infection (alias: `make mutation`) |
| `make psalm` | Run Psalm static analysis |
| `make php-cs-fixer` | Fix code style with PHP-CS-Fixer (alias: `make cs-fix`) |
| `make composer` | Run Composer |

---
> Source: [yiisoft/queue](https://github.com/yiisoft/queue) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-22 -->
