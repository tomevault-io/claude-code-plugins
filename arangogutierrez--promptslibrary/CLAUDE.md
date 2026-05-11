# python

> Python standards

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/python/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Python
style:PEP8|black|isort|type-hints-required
pattern:dataclass>dict-as-struct|pathlib>os.path|f-string>format()
error:never bare-except|always-log-traceback|raise-from-original
test:pytest|fixtures>setup/teardown|parametrize for variants
security:no-eval/exec|validate-inputs|secrets-from-env

---
> Source: [ArangoGutierrez/promptsLibrary](https://github.com/ArangoGutierrez/promptsLibrary) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-08 -->
