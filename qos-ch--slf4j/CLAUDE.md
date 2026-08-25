# slf4j

> **Never commit or push changes.**

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/slf4j/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Agent Rules

**Never commit or push changes.**

### Strict Rules:

- Do not run `git commit`, `git push`, `git add`, or any git command
  that modifies the repository history.

- You may edit files multiple times in one session.

- You may run tests, build commands, invoke linters to validate
  changes or check your work as needed.

- If you believe a commit or any other git action is needed, ask me
  first.

- The code is widely used. Thus, any changes must preserve backward
  compatibility, especially changes in interfaces or super classes.

Follow these rules at all times.

---
> Source: [qos-ch/slf4j](https://github.com/qos-ch/slf4j) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-23 -->
