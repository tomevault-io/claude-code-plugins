# comfyture

> When asked to add a new ComfyUI extension, update the following three files **in alphabetical order** by the extension slug / GitHub owner:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/comfyture/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agents

## Adding a new extension

When asked to add a new ComfyUI extension, update the following three files **in alphabetical order** by the extension slug / GitHub owner:

### 1. `extensions.sh`

Add an `install_extension` call:

```sh
install_extension <slug> https://github.com/<owner>/<repo>.git
```

- `<slug>` is lowercase, hyphen-separated (e.g. `comfyui-seedvr2-videoupscaler`).
- Keep entries sorted alphabetically by slug.

### 2. `requirements.in`

Add a block in the `CUSTOM NODES` section, sorted alphabetically by slug:

```plain
# <slug>
# https://github.com/<owner>/<repo>
-r "https://raw.githubusercontent.com/<owner>/<repo>/refs/heads/main/requirements.txt"
```

- If the repository has no `requirements.txt`, leave the `-r` line commented out (`#-r ""`).
- If the extension needs extra packages not in its `requirements.txt`, add them on the lines immediately after the `-r` line (see `comfyui-ipadapter-plus` for an example).
- After editing `requirements.in`, regenerate the lock file: `task lock`.

### 3. `README.md`

Add a row to the `## Pre-installed extensions` table, sorted alphabetically by GitHub owner:

```markdown
| [<owner>/<repo>](https://github.com/<owner>/<repo>) | <one-line description>. |
```

Align the columns to match the surrounding rows (use spaces to pad to the same column widths).

---

### Checklist

- [ ] `extensions.sh` — `install_extension` line added in alphabetical order
- [ ] `requirements.in` — dependency block added in alphabetical order
- [ ] `pylock.toml` regenerated via `task lock`
- [ ] `README.md` — table row added in alphabetical order

---
> Source: [bigbrozer/comfyture](https://github.com/bigbrozer/comfyture) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-21 -->
