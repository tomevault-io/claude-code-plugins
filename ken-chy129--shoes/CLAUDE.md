# shoes

> - Develop directly on `master` unless the user explicitly requests another branch. Do not create feature branches by default.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/shoes/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository Workflow

- Develop directly on `master` unless the user explicitly requests another branch. Do not create feature branches by default.
- Keep `master` as the complete, deployable history: validate changes, commit them on `master`, and push to `origin/master`.
- Production deployment must use the server's `master` branch after it has been fast-forwarded to `origin/master`; do not deploy a feature-branch-only commit.
- Before changing or deploying code, verify that the local, remote, and server `master` revisions are aligned or deliberately reconcile them first.

---
> Source: [Ken-Chy129/shoes](https://github.com/Ken-Chy129/shoes) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-22 -->
