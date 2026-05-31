# keen-pbr

> Always build using the root `Makefile`:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/keen-pbr/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Notes

## Build

Always build using the root `Makefile`:

```sh
make
```

This runs `cmake -S . -B cmake-build ...` followed by `cmake --build cmake-build`.

## Generated Files

Never edit generated files by hand. Update the source schema/config and run the
appropriate codegen command instead.

- Backend API types (`src/api/generated/api_types.hpp`): run `make generate`.
- Frontend API client/models (`frontend/src/api/generated/`): run `make frontend-api-generate`.

## Frontend

Frontend is lives in the `frontend/` folder. 
Always use bun/bunx as a package manager.
We are using base-ui instead of radix-ui.

Do not run make to compile C++ code if it wasn't edited (e.g. you edited only frontend code or docs)

---
> Source: [maksimkurb/keen-pbr](https://github.com/maksimkurb/keen-pbr) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-31 -->
