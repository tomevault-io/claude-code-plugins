# no-manual-css-parsing

> Do not hand-roll CSS parsing; use real parsers or engine pipelines — manual CSS is not scalable.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/no-manual-css-parsing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# CSS: no manual parsing

Do **not** implement CSS by hand (ad-hoc brace splitting, regex rules, string hacks for selectors, etc.). That approach does **not** scale and will diverge from real CSS behavior.

Prefer:

- Established **Rust CSS tooling** (e.g. Servo’s **`cssparser`** and a proper selector/cascade story), or  
- An **embeddable HTML/CSS pipeline** where styles come from a real style system (e.g. [DioxusLabs/blitz](https://github.com/DioxusLabs/blitz) documents **Stylo** for CSS in **`blitz-dom`** — useful as **architecture reference**, not a mandatory dependency).

Choose what fits the **target** (e.g. WASM-in-tab vs native); the rule is **no bespoke CSS grammar**, not “must use Blitz.”

---
> Source: [pdufour/browserbrowserbrowser](https://github.com/pdufour/browserbrowserbrowser) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-04 -->
