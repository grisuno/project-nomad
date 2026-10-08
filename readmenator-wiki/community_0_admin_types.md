# admin/types

*Community 0 | 30 files | cohesion 0.62*

## Definition

This community groups 30 file(s) rooted at `admin/types` with dominant language ts (cohesion 0.62). Central symbols: `API`, `ActiveDownloads`, `ActiveModelDownloads`, `AppLayout`, `BenchmarkPage`, `Icon`, `KbPolicyPromptBanner`, `Maps`. Core file: `admin/inertia/pages/settings/zim/remote-explorer.tsx` (13 symbols). Documented purpose: General file transfer/download utility types.

## Files

### `admin/types` (6 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/types/benchmark.ts` | ts | utility | 0 | no |
| `admin/types/downloads.ts` | ts | utility | 0 | no |

### `admin/inertia/hooks` (5 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/hooks/useDebounce.ts` | ts | presentation | 2 | no |
| `admin/inertia/hooks/useDownloads.ts` | ts | presentation | 2 | no |

### `admin/inertia/components` (3 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/components/ActiveDownloads.tsx` | tsx | presentation | 6 | no |
| `admin/inertia/components/ActiveModelDownloads.tsx` | tsx | presentation | 5 | no |

### `admin/inertia/lib` (3 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/lib/api.ts` | ts | presentation | 1 | no |
| `admin/inertia/lib/global_map_banner.ts` | ts | utility | 1 | no |

### `admin/inertia/pages/settings` (3 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/pages/settings/benchmark.tsx` | tsx | presentation | 8 | no |
| `admin/inertia/pages/settings/maps.tsx` | tsx | presentation | 10 | no |

### `admin/inertia/context` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/context/ModalContext.ts` | ts | presentation | 1 | no |
| `admin/inertia/context/NotificationContext.ts` | ts | presentation | 1 | no |

### `admin/inertia/pages/settings/zim` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/pages/settings/zim/index.tsx` | tsx | presentation | 7 | no |
| `admin/inertia/pages/settings/zim/remote-explorer.tsx` | tsx | presentation | 13 | no |

### `admin/inertia/providers` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/providers/ModalProvider.tsx` | tsx | presentation | 4 | no |
| `admin/inertia/providers/NotificationProvider.tsx` | tsx | presentation | 5 | no |

### `admin/inertia/components/chat` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/components/chat/KbPolicyPromptBanner.tsx` | tsx | presentation | 1 | no |

### `admin/inertia/layouts` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/layouts/AppLayout.tsx` | tsx | presentation | 1 | no |

### `admin/inertia/pages` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/pages/maps.tsx` | tsx | presentation | 1 | no |

### `admin/tests/unit` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/tests/unit/global_map_banner.spec.ts` | ts | testing | 0 | no |

*... and 10 more files in this community.*


## Key Symbols

- `formatSpeed` (function, `admin/inertia/components/ActiveDownloads.tsx:12`)
- `getDownloadStatus` (function, `admin/inertia/components/ActiveDownloads.tsx:21`)
- `ActiveDownloads` (function, `admin/inertia/components/ActiveDownloads.tsx:38`)
- `deltaSec` (function, `admin/inertia/components/ActiveDownloads.tsx:56`)
- `handleDismiss` (function, `admin/inertia/components/ActiveDownloads.tsx:81`)
- `handleCancel` (function, `admin/inertia/components/ActiveDownloads.tsx:86`)
- `formatSpeed` (function, `admin/inertia/components/ActiveModelDownloads.tsx:13`)
- `ActiveModelDownloads` (function, `admin/inertia/components/ActiveModelDownloads.tsx:21`)
- `deltaSec` (function, `admin/inertia/components/ActiveModelDownloads.tsx:39`)
- `runCancel` (function, `admin/inertia/components/ActiveModelDownloads.tsx:62`)
- `confirmCancel` (function, `admin/inertia/components/ActiveModelDownloads.tsx:85`)
- `KbPolicyPromptBanner` (function, `admin/inertia/components/chat/KbPolicyPromptBanner.tsx:27`) - (`rag.defaultIngestPolicy` unset). Two buttons let the user decide once, after which the prompt neve
- `useModals` (function, `admin/inertia/context/ModalContext.ts:13`)
- `useNotifications` (function, `admin/inertia/context/NotificationContext.ts:20`)
- `useDebounce` (function, `admin/inertia/hooks/useDebounce.ts:3`)
- `debounce` (function, `admin/inertia/hooks/useDebounce.ts:6`)
- `useDownloads` (function, `admin/inertia/hooks/useDownloads.ts:10`)
- `invalidate` (function, `admin/inertia/hooks/useDownloads.ts:29`)
- `useMapRegionFiles` (function, `admin/inertia/hooks/useMapRegionFiles.ts:5`)
- `useOllamaModelDownloads` (function, `admin/inertia/hooks/useOllamaModelDownloads.ts:25`)
- `useServiceInstalledStatus` (function, `admin/inertia/hooks/useServiceInstalledStatus.tsx:5`)
- `AppLayout` (function, `admin/inertia/layouts/AppLayout.tsx:11`)
- `API` (class, `admin/inertia/lib/api.ts:15`)
- `hasDownloadedGlobalMap` (function, `admin/inertia/lib/global_map_banner.ts:1`)
- `setGlobalNotificationCallback` (function, `admin/inertia/lib/util.ts:6`)
- `capitalizeFirstLetter` (function, `admin/inertia/lib/util.ts:10`)
- `formatBytes` (function, `admin/inertia/lib/util.ts:15`)
- `generateRandomString` (function, `admin/inertia/lib/util.ts:24`)
- `generateUUID` (function, `admin/inertia/lib/util.ts:33`)
- `extractFileName` (function, `admin/inertia/lib/util.ts:57`) - Extracts the file name from a given path while handling both forward and backward slashes. @param pa

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 40
- Cross-boundary resolved imports (EXTRACTED): 28

## Connections

- [EXTRACTED] depends_on community 6 <-> 0 (strength 0.9): Extracted import edge crosses communities: admin/app/controllers/settings_controller.ts imports admin/inertia/pages/settings/models.tsx.
- [EXTRACTED] depends_on community 0 <-> 4 (strength 0.9): Extracted import edge crosses communities: admin/inertia/components/WikipediaSelector.tsx imports admin/inertia/lib/classNames.ts.
- [EXTRACTED] depends_on community 8 <-> 0 (strength 0.9): Extracted import edge crosses communities: admin/inertia/components/chat/KnowledgeBaseModal.tsx imports admin/inertia/context/NotificationContext.ts.

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- Why do 29 file(s) lack file-level docs (e.g. `admin/inertia/components/ActiveDownloads.tsx`)? What purpose do they serve?
- What would break if the most connected file in admin/types changed?
- Should admin/types be split, given cohesion 0.62?

## Sources

- `admin/inertia/components/ActiveDownloads.tsx`
- `admin/inertia/components/ActiveModelDownloads.tsx`
- `admin/inertia/components/WikipediaSelector.tsx`
- `admin/inertia/components/chat/KbPolicyPromptBanner.tsx`
- `admin/inertia/context/ModalContext.ts`
- `admin/inertia/context/NotificationContext.ts`
- `admin/inertia/hooks/useDebounce.ts`
- `admin/inertia/hooks/useDownloads.ts`
- `admin/inertia/hooks/useMapRegionFiles.ts`
- `admin/inertia/hooks/useOllamaModelDownloads.ts`
- `admin/inertia/hooks/useServiceInstalledStatus.tsx`
- `admin/inertia/layouts/AppLayout.tsx`
- `admin/inertia/lib/api.ts`
- `admin/inertia/lib/global_map_banner.ts`
- `admin/inertia/lib/util.ts`
- `admin/inertia/pages/maps.tsx`
- `admin/inertia/pages/settings/benchmark.tsx`
- `admin/inertia/pages/settings/maps.tsx`
- `admin/inertia/pages/settings/models.tsx`
- `admin/inertia/pages/settings/zim/index.tsx`
- *... and 10 more*
