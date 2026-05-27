# 301-typescript-test-location

> WHEN creating typescript test files PLACE them adjacent to the file being tested

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/301-typescript-test-location/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


<?xml version="1.0" encoding="UTF-8"?>
<cursor-rule>
  <version>1.0.0</version>
  
  <context>
    When creating unit tests for TypeScript files
  </context>
  
  <requirements>
    <requirement>Create test files in the same directory as the source file</requirement>
    <requirement>Name test files with the pattern: {sourceFileName}.test.{ts,tsx}</requirement>
    <requirement>DO NOT create tests in a separate test directory</requirement>
  </requirements>
  
  <examples>
    <valid>
      <file-structure>
        src/
          components/
            Button.tsx
            Button.test.tsx
          utils/
            format.ts
            format.test.ts
      </file-structure>
    </valid>
    
    <invalid>
      <file-structure>
        src/
          components/
            Button.tsx
          utils/
            format.ts
        tests/
          components/
            Button.test.tsx
          utils/
            format.test.ts
      </file-structure>
    </invalid>
  </examples>
</cursor-rule> 

---
> Source: [bmadcode/cursor-xml-rules-trial](https://github.com/bmadcode/cursor-xml-rules-trial) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-27 -->
