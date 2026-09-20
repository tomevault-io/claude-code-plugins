# vllm-jev-decison

> - Install and test in an isolated environment: `pip install -e '.[test,bridge]'`; run `pytest -q` and `python -m build`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/vllm-jev-decison/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository rules

- Install and test in an isolated environment: `pip install -e '.[test,bridge]'`; run `pytest -q` and `python -m build`.
- Keep the vLLM endpoint plugin separate from the optional HTTP bridge. Never call bridge tests proof of vLLM plugin deployment.
- Count classification transport tokens, generated tokens, input tokens and engine requests separately.
- Conditional candidate probabilities are not calibrated correctness probabilities. Schema validity is not semantic correctness.
- Do not restart existing model services during ordinary development. Preserve existing experiments and model revisions.
- English README is primary; keep a Chinese edition. No credentials, model weights or caches in Git.

- Classification only: reject nonfinite schemas and unsupported modes before model calls. Never add generative fallback.

---
> Source: [siliconkernel/vllm-jev-decison](https://github.com/siliconkernel/vllm-jev-decison) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-20 -->
