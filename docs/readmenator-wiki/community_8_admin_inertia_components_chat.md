# admin/inertia/components/chat

*Community 8 | 7 files | cohesion 0.50*

## Definition

This community groups 7 file(s) rooted at `admin/inertia/components/chat` with dominant language ts (cohesion 0.50). Central symbols: `DocsController`, `DocsService`, `KnowledgeBaseModal`, `Show`, `asInfos`, `classifyKbFile`, `groupAndSortKbFiles`, `handleConfirmSync`. Core file: `admin/inertia/components/chat/KnowledgeBaseModal.tsx` (5 symbols).

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/app/controllers/docs_controller.ts` | ts | presentation | 1 | no |
| `admin/app/services/docs_service.ts` | ts | business_logic | 1 | no |
| `admin/inertia/components/chat/KnowledgeBaseModal.tsx` | tsx | presentation | 5 | no |
| `admin/inertia/lib/kb_file_grouping.ts` | ts | utility | 3 | no |
| `admin/inertia/pages/docs/show.tsx` | tsx | presentation | 1 | no |
| `admin/tests/unit/kb_file_grouping.spec.ts` | ts | testing | 1 | no |
| `admin/util/docs.ts` | ts | utility | 1 | no |

## Key Symbols

- `DocsController` (class, `admin/app/controllers/docs_controller.ts:6`)
- `DocsService` (class, `admin/app/services/docs_service.ts:8`)
- `renderStatePill` (function, `admin/inertia/components/chat/KnowledgeBaseModal.tsx:32`)
- `pickRowAction` (function, `admin/inertia/components/chat/KnowledgeBaseModal.tsx:77`)
- `KnowledgeBaseModal` (function, `admin/inertia/components/chat/KnowledgeBaseModal.tsx:96`)
- `handleUpload` (function, `admin/inertia/components/chat/KnowledgeBaseModal.tsx:282`)
- `handleConfirmSync` (function, `admin/inertia/components/chat/KnowledgeBaseModal.tsx:313`)
- `classifyKbFile` (function, `admin/inertia/lib/kb_file_grouping.ts:21`)
- `sourceToDisplayName` (function, `admin/inertia/lib/kb_file_grouping.ts:34`)
- `groupAndSortKbFiles` (function, `admin/inertia/lib/kb_file_grouping.ts:67`) - Group stored-file rows into table rows for the Stored Files panel.  - Admin docs (`/app/docs/*`, REA
- `Show` (function, `admin/inertia/pages/docs/show.tsx:5`)
- `asInfos` (function, `admin/tests/unit/kb_file_grouping.spec.ts:15`) - Wrap source paths into the minimal StoredFileInfo shape that `groupAndSortKbFiles` now expects. Stat
- `streamToString` (function, `admin/util/docs.ts:2`)

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 7
- Cross-boundary resolved imports (EXTRACTED): 6

## Connections

- [EXTRACTED] depends_on community 3 <-> 8 (strength 0.9): Extracted import edge crosses communities: admin/app/controllers/benchmark_controller.ts imports admin/inertia/pages/docs/show.tsx.
- [EXTRACTED] depends_on community 2 <-> 8 (strength 0.9): Extracted import edge crosses communities: admin/app/controllers/chats_controller.ts imports admin/inertia/pages/docs/show.tsx.
- [EXTRACTED] depends_on community 8 <-> 1 (strength 0.9): Extracted import edge crosses communities: admin/app/services/docs_service.ts imports admin/app/utils/fs.ts.
- [EXTRACTED] depends_on community 8 <-> 0 (strength 0.9): Extracted import edge crosses communities: admin/inertia/components/chat/KnowledgeBaseModal.tsx imports admin/inertia/context/NotificationContext.ts.

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- Why do 7 file(s) lack file-level docs (e.g. `admin/app/controllers/docs_controller.ts`)? What purpose do they serve?
- What would break if the most connected file in admin/inertia/components/chat changed?
- Should admin/inertia/components/chat be split, given cohesion 0.50?

## Sources

- `admin/app/controllers/docs_controller.ts`
- `admin/app/services/docs_service.ts`
- `admin/inertia/components/chat/KnowledgeBaseModal.tsx`
- `admin/inertia/lib/kb_file_grouping.ts`
- `admin/inertia/pages/docs/show.tsx`
- `admin/tests/unit/kb_file_grouping.spec.ts`
- `admin/util/docs.ts`
