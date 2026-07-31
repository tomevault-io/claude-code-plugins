# prism-app

> Never add Cursor as git commit author or co-author

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/prism-app/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Git commits — no Cursor attribution

Do **not** add Cursor to commits in any form:

- No `Co-authored-by: Cursor <cursoragent@cursor.com>` (or variants)
- No `--trailer "Co-authored-by: ..."` for Cursor
- Author must remain the human user only

When creating commits via `git commit`:

- Use a plain `-m` message or HEREDOC **without** co-author trailers
- If a tool or template adds Cursor automatically, amend or rewrite the message before push

Repo ships `.githooks/prepare-commit-msg` to strip Cursor trailers locally. Enable once per clone:

```bash
./scripts/install-githooks.sh
```

---
> Source: [WFP-VAM/prism-app](https://github.com/WFP-VAM/prism-app) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-27 -->
