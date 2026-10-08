# admin/inertia/components/maps

*Community 12 | 3 files | cohesion 1.00*

## Definition

This community groups 3 file(s) rooted at `admin/inertia/components/maps` with dominant language tsx (cohesion 1.00). Central symbols: `MapComponent`, `MarkerPanel`, `useMapMarkers`. Core file: `admin/inertia/components/maps/MapComponent.tsx` (1 symbols).

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/components/maps/MapComponent.tsx` | tsx | presentation | 1 | no |
| `admin/inertia/components/maps/MarkerPanel.tsx` | tsx | presentation | 1 | no |
| `admin/inertia/hooks/useMapMarkers.ts` | ts | presentation | 1 | no |

## Key Symbols

- `MapComponent` (function, `admin/inertia/components/maps/MapComponent.tsx:31`)
- `MarkerPanel` (function, `admin/inertia/components/maps/MarkerPanel.tsx:14`)
- `useMapMarkers` (function, `admin/inertia/hooks/useMapMarkers.ts:25`)

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 3
- Cross-boundary resolved imports (EXTRACTED): 0

## Connections

- No cross-community bridges recorded. This community is self-contained.

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- Why do 3 file(s) lack file-level docs (e.g. `admin/inertia/components/maps/MapComponent.tsx`)? What purpose do they serve?
- What would break if the most connected file in admin/inertia/components/maps changed?
- Should admin/inertia/components/maps be split, given cohesion 1.00?

## Sources

- `admin/inertia/components/maps/MapComponent.tsx`
- `admin/inertia/components/maps/MarkerPanel.tsx`
- `admin/inertia/hooks/useMapMarkers.ts`
