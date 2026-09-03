# alphafold2-webgpu

> - Never change reference tensors or tolerances merely to make a failing test pass.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/alphafold2-webgpu/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AFWebGPU engineering invariants

- Never change reference tensors or tolerances merely to make a failing test pass.
- Never fall back to the CPU for AlphaFold neural-network operations in production paths.
- Every GPU kernel must have a deterministic differential test against an independent reference implementation.
- Do not materialize tensors with `O(L^3)` storage.
- Route all GPU allocations through the shared allocator so peak memory remains measurable.
- Target Chrome on macOS Apple Silicon first while keeping standards-compliant WebGPU/WGSL.
- Establish numerical correctness before optimizing performance.
- Keep shape, dtype, and byte-size validation at public boundaries.

---
> Source: [martin-steinegger/alphafold2-webgpu](https://github.com/martin-steinegger/alphafold2-webgpu) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-03 -->
