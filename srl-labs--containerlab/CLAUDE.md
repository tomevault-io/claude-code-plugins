# containerlab

> Require explicit user authorization for Git mutations

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/containerlab/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Git mutation policy

- Never automatically commit, amend, push, force-push, or create/update a pull request.
- Leave ordinary fixes as working-tree changes unless the user explicitly requests the specific Git or GitHub action.
- A request to implement or fix code alone does not authorize a commit or push.

---
> Source: [srl-labs/containerlab](https://github.com/srl-labs/containerlab) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-23 -->
