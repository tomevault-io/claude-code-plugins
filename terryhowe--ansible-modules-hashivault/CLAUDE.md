# ansible-modules-hashivault

> This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ansible-modules-hashivault/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

See AGENTS.md for comprehensive project documentation including:
- Project overview and code structure
- Build, test, and development setup commands
- Code style conventions (PEP8, 120 char lines)
- Module patterns and security considerations
- Testing guidelines and CI/CD workflow

## Quick Reference

```bash
# Run all tests
tox

# Lint only
tox -e pep8

# Functional tests (requires Vault)
tox -e py39

# Development install
./link.sh
```

---
> Source: [TerryHowe/ansible-modules-hashivault](https://github.com/TerryHowe/ansible-modules-hashivault) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-23 -->
