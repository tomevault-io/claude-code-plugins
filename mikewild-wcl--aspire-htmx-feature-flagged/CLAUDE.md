# aspire-htmx-feature-flagged

> This is a .NET Aspire project. Target framework: net10.0. Package versions are centrally managed in Directory.Packages.props.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/aspire-htmx-feature-flagged/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# GitHub Copilot Instructions

## Project Context

This is a .NET Aspire project. Target framework: net10.0. Package versions are centrally managed in Directory.Packages.props.

## Code Standards

- Use nullable reference types and implicit usings (both enabled)
- Follow SonarAnalyzer rules (code analysis warnings are treated as errors)
- Use file-scoped namespaces
- Don't specify package versions in .csproj files (use central package management)

## Documentation Practices

- When promising documentation changes, apply them in the workspace before reporting completion; do not claim a file was updated unless the edit was actually applied and verified.
- When stating that a change will be made, apply the change immediately and verify it before reporting completion; do not defer or merely describe it.

## .NET Aspire Patterns

- AppHost.cs orchestrates all services using DistributedApplication builder
- ServiceDefaults project provides shared configuration for all services
- Services should call `builder.AddServiceDefaults()` and `app.MapDefaultEndpoints()`

---
> Source: [mikewild-wcl/aspire-htmx-feature-flagged](https://github.com/mikewild-wcl/aspire-htmx-feature-flagged) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-07 -->
