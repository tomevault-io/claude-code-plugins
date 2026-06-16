# mcp-parigp

> MCP server exposing PARI/GP number theory library via cypari2.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mcp-parigp/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# MCP PARI/GP

MCP server exposing PARI/GP number theory library via cypari2.

## When to use this skill

Use this skill when you need to:
- Factor integers
- Test primality
- Compute elliptic curves
- Work with polynomials
- Number field computations

## Tools

**Number Theory:**
- `factor`, `isprime`, `gcd`, `phi`, `sigma`
- `jacobi`, `znorder`, `primes`, `nextprime`

**Polynomials:**
- `polroots`, `polcyclo`, `deriv`, `subst`

**Number Fields:**
- `nfinit`, `bnfinit`, `idealadd`, `idealmul`

**Elliptic Curves:**
- `ellinit`, `ellap`, `elltors`, `ellheight`

**Matrices:**
- `matid`, `matdet`, `matinv`, `matrank`

**Elementary Functions:**
- `sin`, `cos`, `tan`, `exp`, `log`, `sqrt`, `pi()`

## Install

```bash
pip install mcp-parigp
```

---
> Source: [daedalus/mcp-parigp](https://github.com/daedalus/mcp-parigp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-16 -->
