# admin/inertia/components: useEmbedJobs

*Community 10 | 5 files | cohesion 1.00*

## Definition

This community groups 5 file(s) rooted at `admin/inertia/components` with dominant language ts (cohesion 1.00). Central symbols: `ActiveEmbedJobs`, `computeJobHealth`, `computeJobHealthNow`, `formatTimeAgo`, `invalidate`, `useEmbedJobs`. Core file: `admin/inertia/hooks/useEmbedJobs.ts` (2 symbols).

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/app/utils/kb_job_health.ts` | ts | utility | 1 | no |
| `admin/inertia/components/ActiveEmbedJobs.tsx` | tsx | presentation | 1 | no |
| `admin/inertia/hooks/useEmbedJobs.ts` | ts | presentation | 2 | no |
| `admin/inertia/lib/kb_job_health_display.ts` | ts | utility | 2 | no |
| `admin/tests/unit/kb_job_health.spec.ts` | ts | testing | 0 | no |

## Key Symbols

- `computeJobHealth` (function, `admin/app/utils/kb_job_health.ts:32`)
- `ActiveEmbedJobs` (function, `admin/inertia/components/ActiveEmbedJobs.tsx:15`)
- `useEmbedJobs` (function, `admin/inertia/hooks/useEmbedJobs.ts:5`)
- `invalidate` (function, `admin/inertia/hooks/useEmbedJobs.ts:29`)
- `formatTimeAgo` (function, `admin/inertia/lib/kb_job_health_display.ts:45`) - Format a relative timestamp as "Xs ago", "Xm ago", "Xh ago" with sensible thresholds for the KB Proc
- `computeJobHealthNow` (function, `admin/inertia/lib/kb_job_health_display.ts:59`) - Convenience wrapper that resolves a job's health status without the caller having to remember to pas

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 4
- Cross-boundary resolved imports (EXTRACTED): 0

## Connections

- No cross-community bridges recorded. This community is self-contained.

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- Why do 5 file(s) lack file-level docs (e.g. `admin/app/utils/kb_job_health.ts`)? What purpose do they serve?
- What would break if the most connected file in admin/inertia/components: useEmbedJobs changed?
- Should admin/inertia/components: useEmbedJobs be split, given cohesion 1.00?

## Sources

- `admin/app/utils/kb_job_health.ts`
- `admin/inertia/components/ActiveEmbedJobs.tsx`
- `admin/inertia/hooks/useEmbedJobs.ts`
- `admin/inertia/lib/kb_job_health_display.ts`
- `admin/tests/unit/kb_job_health.spec.ts`
