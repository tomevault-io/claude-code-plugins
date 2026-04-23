# option-analysis

> 1. Always run `cargo check` after modifications to ensure that the code compiles.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/option-analysis/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# General AI Agent Instructions
1. Always run `cargo check` after modifications to ensure that the code compiles.
2. Only write project files in the main directory context, nowhere else unless instructed.
3. Keep UI modifications visually distinct, clear, and performant according to modern terminal standards using `ratatui`.

# Git & Workflow Constraints
1. **Branch Protection:** NEVER commit code directly to the `master` or `main` branches under any circumstances.
2. **Feature Branching:** Before making file changes, always checkout a new descriptively named branch: e.g., `git checkout -b <feature-name>`.
3. **Pull Requests:** Always plan for pushing feature branches to remote via `git push origin <feature-name>` for Pull Requests, honoring the required branch checks.

---
> Source: [harsh-vardhhan/option-analysis](https://github.com/harsh-vardhhan/option-analysis) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-23 -->
