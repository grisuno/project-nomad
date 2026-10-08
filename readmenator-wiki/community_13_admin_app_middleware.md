# admin/app/middleware

*Community 13 | 2 files | cohesion 1.00*

## Definition

This community groups 2 file(s) rooted at `admin/app/middleware` with dominant language ts (cohesion 1.00). Central symbols: `ContainerBindingsMiddleware`, `to`. Core file: `admin/app/middleware/container_bindings_middleware.ts` (3 symbols).

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/app/middleware/container_bindings_middleware.ts` | ts | infrastructure | 3 | no |
| `admin/config/logger.ts` | ts | infrastructure | 0 | no |

## Key Symbols

- `to` (class, `admin/app/middleware/container_bindings_middleware.ts:9`)
- `to` (class, `admin/app/middleware/container_bindings_middleware.ts:10`)
- `ContainerBindingsMiddleware` (class, `admin/app/middleware/container_bindings_middleware.ts:12`) - The container bindings middleware binds classes to their request specific value using the container

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 1
- Cross-boundary resolved imports (EXTRACTED): 0

## Connections

- No cross-community bridges recorded. This community is self-contained.

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- Why do 2 file(s) lack file-level docs (e.g. `admin/app/middleware/container_bindings_middleware.ts`)? What purpose do they serve?
- What would break if the most connected file in admin/app/middleware changed?
- Should admin/app/middleware be split, given cohesion 1.00?

## Sources

- `admin/app/middleware/container_bindings_middleware.ts`
- `admin/config/logger.ts`
