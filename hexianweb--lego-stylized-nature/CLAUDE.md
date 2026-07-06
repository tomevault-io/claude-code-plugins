# compute-shaders

> GPU compute shaders in Three.js WebGPU using TSL. Covers instanced array buffers, parallel simulation, particle systems, atomic operations, and workgroup barriers. Use when writing compute passes, particle systems, or GPU-side simulations.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/compute-shaders/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Three.js WebGPU Compute Shaders (TSL)

Compute shaders in TSL use `Fn()` wrapped with `.compute(count)` and dispatched via `renderer.computeAsync()`. Data lives in `instancedArray()` buffers accessed by `instanceIndex`.

Key patterns:
- `instancedArray(count, 'vec3')` for storage buffers
- `Fn(() => { ... }).compute(count)` to define a compute kernel
- `renderer.computeAsync(kernel)` to dispatch
- Workgroup barriers via `workgroupBarrier()` for shared memory sync

@skills/webgpu-threejs-tsl/docs/compute-shaders.md
@skills/webgpu-threejs-tsl/examples/particle-system.js
@skills/webgpu-threejs-tsl/templates/compute-shader.js

---
> Source: [hexianWeb/lego-stylized-nature](https://github.com/hexianWeb/lego-stylized-nature) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-06 -->
