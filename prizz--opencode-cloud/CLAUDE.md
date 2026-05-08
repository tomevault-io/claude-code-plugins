# post-push-mirror

> Post-push: also push to mirror remote when configured

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/post-push-mirror/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Post-Push Mirror Remote

- After any successful `git push`, also run `git push mirror`.
- Only do this if a remote named `mirror` exists (check `git remote -v`).
- If `mirror` is not configured, ignore this rule.

---
> Source: [pRizz/opencode-cloud](https://github.com/pRizz/opencode-cloud) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-03 -->
