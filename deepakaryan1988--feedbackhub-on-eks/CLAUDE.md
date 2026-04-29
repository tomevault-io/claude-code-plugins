# feedbackhub-on-eks

> CI/CD guardrails and expectations

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/feedbackhub-on-eks/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


### CI/CD Expectations

- **Non‑interactive**: Use `--yes`, `-input=false`, and similar flags. Fail fast.
- **Caching**: Cache deps (npm, Docker layers, Terraform plugins) safely.
- **Checks**: fmt/lint/test/build/security scan stages. Artifacts uploaded for troubleshooting.
- **Immutability**: Build once, tag with git SHA, promote same image across envs.
- **Secrets**: Pass via CI secrets store; never echo. Mask sensitive output.
- **Terraform**: `fmt` + `validate` + `plan` in PRs; applies via protected branches.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/deepakaryan1988) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-10 -->
