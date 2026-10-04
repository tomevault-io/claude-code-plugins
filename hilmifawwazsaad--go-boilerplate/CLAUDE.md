# go-boilerplate

> Read the relevant skill file before writing any code.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/go-boilerplate/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

Read the relevant skill file before writing any code.
Check `go.mod` for available modules — never import what isn't listed.

**Stack:** Go 1.26 · net/http (stdlib) · golangci-lint · gofmt · goimports · Lefthook — no ORM or auth library by default.

**Always read first:** `.agents/software-principles/SKILL.md` — naming, function design, and engineering principles.

| Domain                                                                    | Skill file                 |
| ------------------------------------------------------------------------- | -------------------------- |
| Backend — handler, usecase, repository, domain, middleware, routes | `.agents/backend/SKILL.md` |

Convention missing from skill file → ask before inventing.

---
> Source: [hilmifawwazsaad/Go-Boilerplate](https://github.com/hilmifawwazsaad/Go-Boilerplate) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-04 -->
