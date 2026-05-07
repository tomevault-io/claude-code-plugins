# git-commit

> Git commit 规则，执行 git commit 时自动应用

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/git-commit/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Git Commit 规则

## 禁止 Co-authored-by

执行 `git commit` 时，**禁止**在 commit message 中添加 `Co-authored-by` 行。

提交格式示例：

```bash
git commit -m "$(cat <<'EOF'
feat: 功能描述

EOF
)"
```

❌ 禁止：
```
feat: 功能描述

Co-authored-by: Cursor <cursoragent@cursor.com>
```

✅ 正确：
```
feat: 功能描述
```

---
> Source: [asasugar/SuperSpec](https://github.com/asasugar/SuperSpec) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-03 -->
