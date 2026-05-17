# crabpot

> - Keep this repo fixture-driven. Add plugins to `crabpot.config.json`; do not

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/crabpot/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# crabpot agent notes

- Keep this repo fixture-driven. Add plugins to `crabpot.config.json`; do not
  hardcode fixture lists in scripts.
- External plugin code lives under `plugins/` as git submodules. Do not vendor or
  rewrite external plugin source here.
- Default checks must stay cheap and credential-free. Live tests require explicit
  opt-in and secrets.
- Prefer seam labels over product categories: `dynamic-tool`, `llm-observer`,
  `gateway-service`, `provider-capability`, and similar.
- Treat `openclaw` package dependencies as host-linked inputs owned by the
  inspector/workspace plan, not as upstream plugin install findings.
- When plugin-inspector behavior or package versions change, update both the
  source ref and generated report/test expectations. After npm publish, update
  the package pin and run both source-mode and package-mode smoke checks.
- When adding a fixture, explain the unique seam it covers in `why`.

---
> Source: [openclaw/crabpot](https://github.com/openclaw/crabpot) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-17 -->
