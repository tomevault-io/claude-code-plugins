# vexml

> After making code changes:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/vexml/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

After making code changes:

- `vex fix` typecheck, format, and lint the project.
- `vex test` test the project.
- `vex test --update` update the test snapshots.

MusicXML tools:

- `vex validate -i <path>` validate a MusicXML file.
- `vex render -i <path>` render a MusicXML file to a PNG. Delete screenshots when you are done, unless you're showing the user something.

---
> Source: [stringsync/vexml](https://github.com/stringsync/vexml) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-20 -->
