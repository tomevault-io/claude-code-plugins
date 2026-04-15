# fabric-atelier

> **Activation Mode**: Glob Pattern

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/fabric-atelier/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Rust Best Practices

**Activation Mode**: Glob Pattern
**Pattern**: `src/**/*.rs`

## Naming Conventions

- Types: `PascalCase`
- Functions: `snake_case`
- Constants: `SCREAMING_SNAKE_CASE`
- Modules: `snake_case`

## Async Code

- Use `tokio` for async runtime
- Prefer `async fn` over `impl Future`
- Use `tokio::spawn` for concurrent tasks
- Use `#[tokio::test]` for async tests

## Testing

- Unit tests in `#[cfg(test)] mod tests`
- Integration tests in `tests/` directory
- Use descriptive test names
- Test both success and error cases

## Logging

- Use `tracing` for structured logging
- Use `#[instrument]` for function tracing
- Log levels: ERROR (unrecoverable), WARN (recoverable), INFO (milestones), DEBUG (detailed), TRACE (verbose)
- Never log sensitive data

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/copyleftdev) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-13 -->
