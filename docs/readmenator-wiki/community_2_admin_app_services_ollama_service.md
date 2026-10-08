# admin/app/services: ollama_service

*Community 2 | 23 files | cohesion 0.45*

## Definition

This community groups 23 file(s) rooted at `admin/app/services` with dominant language ts (cohesion 0.45). Central symbols: `ChatService`, `ChatsController`, `EmbedFileJob`, `Home`, `HomeController`, `OllamaController`, `OllamaService`, `RagController`. Core file: `admin/app/services/ollama_service.ts` (7 symbols).

## Files

### `admin/app/services` (5 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/app/services/chat_service.ts` | ts | business_logic | 1 | no |
| `admin/app/services/ollama_service.ts` | ts | business_logic | 7 | no |
| `admin/app/services/rag_service.ts` | ts | business_logic | 3 | no |

### `admin/app/controllers` (4 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/app/controllers/chats_controller.ts` | ts | presentation | 1 | no |
| `admin/app/controllers/home_controller.ts` | ts | presentation | 1 | no |
| `admin/app/controllers/ollama_controller.ts` | ts | presentation | 1 | no |

### `admin/app/utils` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/app/utils/kb_ingest_decision.ts` | ts | utility | 1 | no |
| `admin/app/utils/kb_warning_decision.ts` | ts | utility | 1 | no |

### `admin/constants` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/constants/service_names.ts` | ts | business_logic | 0 | no |
| `admin/constants/zim_extraction.ts` | ts | utility | 0 | no |

### `admin/tests/unit` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/tests/unit/kb_ingest_decision.spec.ts` | ts | testing | 0 | no |
| `admin/tests/unit/kb_warning_decision.spec.ts` | ts | testing | 0 | no |

### `admin/app/jobs` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/app/jobs/embed_file_job.ts` | ts | utility | 6 | no |

### `admin/config` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/config/inertia.ts` | ts | infrastructure | 2 | no |

### `admin/inertia/components` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/components/UpdateServiceModal.tsx` | tsx | presentation | 3 | no |

### `admin/inertia/hooks` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/hooks/useUpdateAvailable.ts` | ts | utility | 1 | no |

### `admin/inertia/layouts` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/layouts/SettingsLayout.tsx` | tsx | presentation | 1 | no |

### `admin/inertia/lib` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/lib/navigation.ts` | ts | utility | 1 | no |

### `admin/inertia/pages` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/pages/home.tsx` | tsx | presentation | 2 | no |

### `admin/types` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/types/services.ts` | ts | business_logic | 0 | no |

*... and 3 more files in this community.*


## Key Symbols

- `ChatsController` (class, `admin/app/controllers/chats_controller.ts:11`)
- `HomeController` (class, `admin/app/controllers/home_controller.ts:6`)
- `OllamaController` (class, `admin/app/controllers/ollama_controller.ts:18`)
- `RagController` (class, `admin/app/controllers/rag_controller.ts:14`)
- `EmbedFileJob` (class, `admin/app/jobs/embed_file_job.ts:23`)
- `onProgress` (function, `admin/app/jobs/embed_file_job.ts:116`) - Progress callback. For multi-batch ZIM ingestions, scale the service-reported 0-100% (which is % thr
- `articlesDone` (function, `admin/app/jobs/embed_file_job.ts:119`)
- `nextOffset` (function, `admin/app/jobs/embed_file_job.ts:144`)
- `totalChunks` (function, `admin/app/jobs/embed_file_job.ts:196`) - Final batch or non-batched file - mark as complete
- `filePath` (function, `admin/app/jobs/embed_file_job.ts:394`)
- `ChatService` (class, `admin/app/services/chat_service.ts:11`)
- `OllamaService` (class, `admin/app/services/ollama_service.ts:51`)
- `customUrl` (function, `admin/app/services/ollama_service.ts:64`) - Check KVStore for a custom base URL (remote Ollama, LM Studio, llama.cpp, etc.)
- `onAbort` (function, `admin/app/services/ollama_service.ts:187`) - If the abort fires after headers are received but mid-stream, axios's signal handling destroys the s
- `stream` (function, `admin/app/services/ollama_service.ts:367`)
- `partialTagSuffix` (function, `admin/app/services/ollama_service.ts:370`) - Returns how many trailing chars of `text` could be the start of `tag`
- `parsePulls` (function, `admin/app/services/ollama_service.ts:860`)
- `parseSize` (function, `admin/app/services/ollama_service.ts:879`)
- `RagService` (class, `admin/app/services/rag_service.ts:41`)
- `if` (class, `admin/app/services/rag_service.ts:208`)
- `progress` (function, `admin/app/services/rag_service.ts:373`)
- `SystemService` (class, `admin/app/services/system_service.ts:26`)
- `buf` (function, `admin/app/services/system_service.ts:131`)
- `actualImage` (function, `admin/app/services/system_service.ts:251`)
- `isDiscreteGpuVendor` (function, `admin/app/services/system_service.ts:440`)
- `isBogusDgpuVram` (function, `admin/app/services/system_service.ts:442`)
- `hasLspciBogusDgpuVram` (function, `admin/app/services/system_service.ts:452`) - Clear the bogus value up front. If a probe replaces the entry below we get the real VRAM; if no prob
- `earlyAccess` (function, `admin/app/services/system_service.ts:630`)
- `ZIMExtractionService` (class, `admin/app/services/zim_extraction_service.ts:10`)
- `decideScanAction` (function, `admin/app/utils/kb_ingest_decision.ts:44`) - Decide what scanAndSyncStorage should do for a single embeddable file.  Replaces the earlier `!sourc

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 41
- Cross-boundary resolved imports (EXTRACTED): 50

## Connections

- [EXTRACTED] depends_on community 2 <-> 8 (strength 0.9): Extracted import edge crosses communities: admin/app/controllers/chats_controller.ts imports admin/inertia/pages/docs/show.tsx.
- [EXTRACTED] depends_on community 2 <-> 7 (strength 0.9): Extracted import edge crosses communities: admin/app/controllers/chats_controller.ts imports admin/inertia/pages/settings/update.tsx.
- [EXTRACTED] depends_on community 1 <-> 2 (strength 0.9): Extracted import edge crosses communities: admin/app/controllers/easy_setup_controller.ts imports admin/app/services/system_service.ts.
- [EXTRACTED] depends_on community 2 <-> 3 (strength 0.9): Extracted import edge crosses communities: admin/app/controllers/ollama_controller.ts imports admin/app/services/docker_service.ts.
- [EXTRACTED] depends_on community 6 <-> 2 (strength 0.9): Extracted import edge crosses communities: admin/app/controllers/settings_controller.ts imports admin/app/services/ollama_service.ts.

## Risks

- [cycle] `admin/app/services/system_service.ts` -> `admin/config/inertia.ts` -> `admin/app/services/system_service.ts`
- [cycle] `admin/app/services/ollama_service.ts` -> `admin/app/jobs/download_model_job.ts` -> `admin/app/services/ollama_service.ts`

## Open Questions

- Why do 23 file(s) lack file-level docs (e.g. `admin/app/controllers/chats_controller.ts`)? What purpose do they serve?
- Can the cycle `admin/app/services/system_service.ts` -> `admin/config/inertia.ts` be broken with an interface?
- What would break if the most connected file in admin/app/services: ollama_service changed?
- Should admin/app/services: ollama_service be split, given cohesion 0.45?

## Sources

- `admin/app/controllers/chats_controller.ts`
- `admin/app/controllers/home_controller.ts`
- `admin/app/controllers/ollama_controller.ts`
- `admin/app/controllers/rag_controller.ts`
- `admin/app/jobs/embed_file_job.ts`
- `admin/app/services/chat_service.ts`
- `admin/app/services/ollama_service.ts`
- `admin/app/services/rag_service.ts`
- `admin/app/services/system_service.ts`
- `admin/app/services/zim_extraction_service.ts`
- `admin/app/utils/kb_ingest_decision.ts`
- `admin/app/utils/kb_warning_decision.ts`
- `admin/config/inertia.ts`
- `admin/constants/service_names.ts`
- `admin/constants/zim_extraction.ts`
- `admin/inertia/components/UpdateServiceModal.tsx`
- `admin/inertia/hooks/useUpdateAvailable.ts`
- `admin/inertia/layouts/SettingsLayout.tsx`
- `admin/inertia/lib/navigation.ts`
- `admin/inertia/pages/home.tsx`
- *... and 3 more*
