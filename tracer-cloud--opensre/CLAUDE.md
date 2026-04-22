# opensre

> - Build `make install`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/opensre/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Tracer Development Reference

## Build and Run commands

- Build `make install`
- Run `opensre`

## Lint & Format

- Lint all: `make lint`
- Fix linting: `ruff check app/ tests/ --fix`
- Type check: `make typecheck`

## Testing

- Test: `make test-cov`
- Test real alerts: `make test-rca`

## Code Style

- Use strict typing, follow DRY principle
- One clear purpose per file (separation of concerns)

### Before Push

1. Clean working tree
2. `make test-cov`
3. `make lint`
4. `make typecheck`

---
> Source: [Tracer-Cloud/opensre](https://github.com/Tracer-Cloud/opensre) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-20 -->
