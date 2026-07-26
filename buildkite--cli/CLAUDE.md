# cli

> This project is the Buildkite CLI (`bk`)

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/cli/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

This project is the Buildkite CLI (`bk`)

## Commands
- Bootstrap: `mise install`
- Hooks: `mise run hooks`
- Format: `mise run format`
- Test: `mise run test`
- Lint: `mise run lint`
- Generate: `mise run generate` (required after GraphQL changes)
- Run: `go run main.go`

## Environment
- `BUILDKITE_GRAPHQL_TOKEN` required for development

## Project Structure
- Main binary: `main.go`
- GraphQL schema: `schema.graphql`
- CLI commands: `pkg/cmd/`

## Notes
- `mise.toml` pins the local Go/tool versions
- CI: https://buildkite.com/buildkite/buildkite-cli
- Always format after changing code

---
> Source: [buildkite/cli](https://github.com/buildkite/cli) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-26 -->
