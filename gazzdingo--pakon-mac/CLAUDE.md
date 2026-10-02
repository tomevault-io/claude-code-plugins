# no-commit-images

> Never commit or push scan images, captures, or personal photo data

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/no-commit-images/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# No images in git

Never commit, stage, force-add, or push scan captures, decoded PNGs/TIFFs, or personal photograph data.

- `captures/` is gitignored on purpose — do not `git add -f` anything under it.
- Do not commit large image binaries elsewhere either (decoded strips, frame exports, sample scans).
- Tools and docs that *produce* or document decoding are fine; the image files themselves are not.
- If asked to "commit the strip / scan / PNG", commit only the code path — refuse the image and say why.

---
> Source: [gazzdingo/pakon-mac](https://github.com/gazzdingo/pakon-mac) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-01 -->
