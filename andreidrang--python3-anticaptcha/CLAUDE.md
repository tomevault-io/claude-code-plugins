# python3-anticaptcha

> Shared utilities: base classes, enums, HTTP instruments, serialization.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/python3-anticaptcha/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Core Module

## OVERVIEW
Shared utilities: base classes, enums, HTTP instruments, serialization.

## WHERE TO LOOK
| Component | File |
|-----------|------|
| Base classes | base.py - CaptchaParams, CaptchaResponse |
| Enums | enum.py - CaptchaTypeEnm, ProxyTypeEnm, ResponseStatusEnm, SaveFormatsEnm |
| HTTP sync | captcha_instrument.py - SynchronousInstrument |
| HTTP async | captcha_instrument.py - AsyncInstrument |
| Serialization | serializer.py - msgspec.Struct configs |

## CONVENTIONS
- All params classes inherit CaptchaParams
- All response classes inherit CaptchaResponse
- msgspec.Struct for fast serialization
- HTTP instruments handle session lifecycle

## ANTI-PATTERNS
- `verify=False` in sio_captcha_instrument.py:32 - INTENTIONAL, don't "fix"
- Don't add new enums without updating parent package

---
> Source: [AndreiDrang/python3-anticaptcha](https://github.com/AndreiDrang/python3-anticaptcha) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-21 -->
