# admin/app/models

*Community 11 | 3 files | cohesion 1.00*

## Definition

This community groups 3 file(s) rooted at `admin/app/models` with dominant language ts (cohesion 1.00). Central symbols: `KbRatioRegistry`, `estimateBatch`, `estimateChunkCount`, `findChunksPerMb`. Core file: `admin/app/utils/kb_ratio_lookup.ts` (3 symbols).

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/app/models/kb_ratio_registry.ts` | ts | business_logic | 1 | no |
| `admin/app/utils/kb_ratio_lookup.ts` | ts | utility | 3 | no |
| `admin/tests/unit/kb_ratio_lookup.spec.ts` | ts | testing | 0 | no |

## Key Symbols

- `KbRatioRegistry` (class, `admin/app/models/kb_ratio_registry.ts:21`) - Self-calibrating registry of `{filename-prefix → chunks_per_mb}` ratios used for disk-footprint and
- `estimateBatch` (function, `admin/app/utils/kb_ratio_lookup.ts:38`) - Aggregate an embedding-disk-cost estimate across a batch of files (curated tier add, multi-upload, s
- `findChunksPerMb` (function, `admin/app/utils/kb_ratio_lookup.ts:70`) - Pick the chunks_per_mb estimate for a filename by longest-prefix match.  Patterns are filename prefi
- `estimateChunkCount` (function, `admin/app/utils/kb_ratio_lookup.ts:88`) - Estimate the number of embedding chunks a ZIM-style file will produce given its size on disk in byte

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 2
- Cross-boundary resolved imports (EXTRACTED): 0

## Connections

- No cross-community bridges recorded. This community is self-contained.

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- Why do 3 file(s) lack file-level docs (e.g. `admin/app/models/kb_ratio_registry.ts`)? What purpose do they serve?
- What would break if the most connected file in admin/app/models changed?
- Should admin/app/models be split, given cohesion 1.00?

## Sources

- `admin/app/models/kb_ratio_registry.ts`
- `admin/app/utils/kb_ratio_lookup.ts`
- `admin/tests/unit/kb_ratio_lookup.spec.ts`
