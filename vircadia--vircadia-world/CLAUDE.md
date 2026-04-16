# vircadia-world

> const generalRules = `Use for of instead of foreach.`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/vircadia-world/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

// General
const generalRules = `Use for of instead of foreach.`
const useBun = `Use bun instead of node.`
// const preferTemplatePropsViaMainScene = `Prefer template props via MainScene.vue instead of local refs and using default prop values in components, instead require props from MainScene.vue in the template.`

// Babylon.js
const babylonRules = `For Babylon.js: use ImportMeshAsync, SceneLoader is deprecated:
ImportMeshAsync(
    source: SceneSource,
    scene: Scene,
    options?: ImportMeshOptions,
): Promise<ISceneLoaderAsyncResult>
`;

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/vircadia) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
