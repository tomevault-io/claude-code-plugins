# d365bap-tools

> Create and maintain table views here. One file per type:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/d365bap-tools/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Table format views

Create and maintain table views here. One file per type:

`<TypeName>.Table.Format.ps1xml`

Do not edit `../../d365bap.tools.Table.Format.ps1xml`. After changing a file here, run from the repo root:

```powershell
pwsh -NoProfile -File ./build/Merge-FormatPs1Xml.ps1
```

---
> Source: [d365collaborative/d365bap.tools](https://github.com/d365collaborative/d365bap.tools) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-24 -->
