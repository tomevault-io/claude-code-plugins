# chemical-structures

> The system uses RDKit for chemical structure management as defined in [db/schema.sql](mdc:db/schema.sql).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/chemical-structures/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Chemical Structure Handling

The system uses RDKit for chemical structure management as defined in [db/schema.sql](mdc:db/schema.sql).

## Chemical Structure Representations
Compounds are stored with multiple representations:
- `canonical_smiles`: RDKit canonical SMILES notation
- `original_molfile`: Original structure as drawn
- `inchi`: IUPAC International Chemical Identifier
- `inchikey`: Fixed-length InChI hash for indexing

## RDKit Integration
The `rdk` schema provides chemical structure searching capabilities:
1. RDKit extension is automatically enabled
2. `rdk.mols` table stores molecules in native RDKit format
3. GIST index on molecules enables substructure searching
4. Automatic synchronization via triggers:
   - New compounds automatically create RDKit molecules
   - Maintains consistency between `moltrack.compounds` and `rdk.mols`

## Structure Operations
The RDKit integration enables:
- Substructure searching
- Chemical similarity calculations
- Structure standardization
- Molecular property calculations

---
> Source: [datagrok-ai/mol-track](https://github.com/datagrok-ai/mol-track) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-27 -->
