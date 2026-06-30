# translate-python

> **Important:** Run `nix develop` in every new terminal session to activate the development environment with all required dependencies and correct Python paths.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/translate-python/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Development Environment

### Getting Started

**Important:** Run `nix develop` in every new terminal session to activate the development environment with all required dependencies and correct Python paths.

## Testing

### How to Run Tests

**For humans:**
- Run tests using pytest: `pytest` or `make test`
- The test configuration is in `pytest.ini`
- Tests are located in the `tests/` directory

**For AI assistants:**
- Use `nix develop -c pytest` to run tests in the Nix development environment
- Use `nix develop -c make test` to run tests via Makefile
- This ensures tests run in the correct environment with all dependencies

### Test Configuration
- Test paths: `tests/`
- Coverage reporting: enabled with `--cov=translate`
- Verbose output: `-vv` flag enabled by default

---
> Source: [terryyin/translate-python](https://github.com/terryyin/translate-python) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-29 -->
