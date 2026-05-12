# kagi-skills

> Multi-module monorepo. Each skill lives in its own directory with its own `go.mod`:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/kagi-skills/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

Multi-module monorepo. Each skill lives in its own directory with its own `go.mod`:

```
kagi-search/      # Search API — Teclis + content extraction
kagi-fastgpt/     # FastGPT API — AI-synthesized answers
kagi-summarizer/  # Universal Summarizer API
kagi-enrich/      # Enrichment API — Teclis (web) + TinyGem (news)
```

A `Makefile` at the repo root provides common tasks:

| Target       | Description                                     |
| ------------ | ----------------------------------------------- |
| `make build` | Build all four binaries into their `.bin/` dirs |
| `make lint`  | Run golangci-lint on all modules                |
| `make test`  | Run `go test ./...` on all modules              |
| `make fmt`   | Run `gofumpt -w -l .`                           |
| `make clean` | Remove built binaries                           |

---
> Source: [joelazar/kagi-skills](https://github.com/joelazar/kagi-skills) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-09 -->
