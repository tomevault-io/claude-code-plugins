# go

> Go standards for K8s projects

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/go/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Go
chain:gofmt→vet→golangci-lint→test
doc:≤80ch|pkg-comment req for public
pattern:accept-interface,return-struct|fmt.Errorf("%w",err)|ctx 1st|defer Close()
naming:Export=Pascal|unexport=camel|acronym-consistent(URL/Url)
error:never _=f()|wrap+ctx|sentinel sparingly
concurrency:mutex/chan for shared|goroutine exit strategy|ctx cancel
test:table-driven|t.Parallel() safe|*_test.go
k8s:graceful(SIGTERM/INT)|json-log|probes|no-hardcoded-secrets

## Security Scans (verify phase)
- `govulncheck ./...` — Go vulnerability check
- `gosec ./...` — Go security linter
- `trivy fs .` — filesystem/dependency vulnerability scan
Run all three before claiming implementation is complete.

---
> Source: [ArangoGutierrez/promptsLibrary](https://github.com/ArangoGutierrez/promptsLibrary) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-08 -->
