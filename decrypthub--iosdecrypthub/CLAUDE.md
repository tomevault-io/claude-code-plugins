# iosdecrypthub

> Always respond in Chinese-simplified

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/iosdecrypthub/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md — IOSDecryptHubJB

Always respond in Chinese-simplified

ElleKit 把 `IOSDecryptHubLoader.dylib` 装进 UIKit App 后：读 `enabledBundles.plist` → 允许则 `dlopen` `vendor` 里的 `decrypt_helper.dylib`。

不得加入 hook、inline hook、daemon。

```bash
make deb
```

- ❌ `MSHookFunction` / `%hook`
- ❌ daemon / `dh_server`
- ✅ 版本号：`Makefile` 的 `VERSION`

---
> Source: [decrypthub/IOSDecryptHub](https://github.com/decrypthub/IOSDecryptHub) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-01 -->
