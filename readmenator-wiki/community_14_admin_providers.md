# admin/providers

*Community 14 | 2 files | cohesion 1.00*

## Definition

This community groups 2 file(s) rooted at `admin/providers` with dominant language ts (cohesion 1.00). Central symbols: `MapStaticProvider`. Core file: `admin/providers/map_static_provider.ts` (1 symbols).

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/config/static.ts` | ts | infrastructure | 0 | no |
| `admin/providers/map_static_provider.ts` | ts | infrastructure | 1 | no |

## Key Symbols

- `MapStaticProvider` (class, `admin/providers/map_static_provider.ts:16`) - This is a bit of a hack to serve static files from the /storage/maps directory using AdonisJS static

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 1
- Cross-boundary resolved imports (EXTRACTED): 0

## Connections

- No cross-community bridges recorded. This community is self-contained.

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- Why do 2 file(s) lack file-level docs (e.g. `admin/config/static.ts`)? What purpose do they serve?
- What would break if the most connected file in admin/providers changed?
- Should admin/providers be split, given cohesion 1.00?

## Sources

- `admin/config/static.ts`
- `admin/providers/map_static_provider.ts`
