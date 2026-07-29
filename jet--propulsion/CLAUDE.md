# propulsion

> Propulsion is a suite of .NET/F# NuGet packages for reactive event-processing pipelines.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/propulsion/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Copilot Instructions

Propulsion is a suite of .NET/F# NuGet packages for reactive event-processing pipelines.

## Build & test

```bash
dotnet build Propulsion.sln --configuration Release
dotnet test  Propulsion.sln --no-restore --verbosity minimal
```

## Key conventions

- All library code is **F#**; follow existing style in each file.
- Keep public API changes minimal and backward-compatible where possible.
- Do not introduce new NuGet dependencies without a strong reason.
- Each package lives in its own subdirectory under `src/`.

---
> Source: [jet/propulsion](https://github.com/jet/propulsion) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-24 -->
