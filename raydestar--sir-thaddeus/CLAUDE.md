# sir-thaddeus

> Testing contract — how to build and run tests in this repo.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/sir-thaddeus/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Testing Contract

## Running Tests

- Do NOT invent test commands. Always use the harness scripts.
- Run tests via PowerShell from repo root: `./dev/test.ps1`
- To run a subset: `./dev/test.ps1 -Filter "FullyQualifiedName~MyClass"`
- Full suite (Release + restore): `./dev/test_all.ps1`
- First-time setup: `./dev/bootstrap.ps1`

## After Making Changes

- Re-run `./dev/test.ps1` after every code change until it exits 0.
- If tests fail, read the console output and fix the code.
- TRX reports are in `./artifacts/test-results/` for detailed inspection.

## Test Discipline

- Do NOT add new tests unless explicitly asked.
- Do NOT delete or skip existing tests to make the suite pass.
- If `dotnet` SDK mismatch occurs, check `global.json` and align.
- If `./dev/test.ps1` does not exist, create it per `README_TESTING.md`.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/raydeStar) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
