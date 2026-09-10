# tagpr

> `docs/site` is a Hugo module, not a Go source module.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tagpr/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Contributor instructions

## Hugo site dependencies

`docs/site` is a Hugo module, not a Go source module.

- Never run `go mod tidy` in `docs/site`. It removes Hugo theme dependencies,
  such as Hextra, because they are not Go packages.
- Use `make docs-deps` or run `hugo mod tidy` from `docs/site` instead.
- Running `go mod tidy` at the repository root is safe; it does not traverse
  into the nested `docs/site` module.

---
> Source: [Songmu/tagpr](https://github.com/Songmu/tagpr) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-09 -->
