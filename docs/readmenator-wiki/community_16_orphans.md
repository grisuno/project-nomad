# orphans

*Community 16 | 116 files | cohesion 0.00*

## Definition

This community groups 116 file(s) rooted at `admin/database/migrations` with dominant language ts (cohesion 0.00). Central symbols: `About`, `BackToHomeHeader`, `BenchmarkResult`, `BenchmarkSetting`, `BouncingDots`, `BuilderTagSelector`, `Chat`, `ChatAssistantAvatar`. Core file: `install/install_nomad.sh` (21 symbols). Documented purpose: import env from '#start/env' import app from '@adonisjs/core/services/app' import { defineConfig, stores } from '@adonisjs/session'  const sessionConfig = defin.

## Files

### `admin/database/migrations` (27 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/database/migrations/1751086751801_create_services_table.ts` | ts | data_access | 1 | no |

### `admin/inertia/components` (13 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/components/BouncingDots.tsx` | tsx | presentation | 1 | no |

### `admin/app/models` (11 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/app/models/benchmark_result.ts` | ts | business_logic | 1 | no |

### `install` (9 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `install/collect_disk_info.sh` | sh | utility | 0 | no |

### `admin/config` (8 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/config/app.ts` | ts | infrastructure | 0 | no |

### `admin/app/validators` (6 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/app/validators/benchmark.ts` | ts | utility | 0 | no |

### `admin/types` (5 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/types/collections.ts` | ts | utility | 0 | no |

### `admin` (3 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/adonisrc.ts` | ts | utility | 0 | no |

### `admin/app/middleware` (3 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/app/middleware/compression_middleware.ts` | ts | infrastructure | 1 | no |

### `admin/inertia/components/maps` (3 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/components/maps/CoordinateOverlay.tsx` | tsx | presentation | 1 | no |

### `admin/providers` (3 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/providers/gpu_passthrough_remediation_provider.ts` | ts | infrastructure | 3 | no |

### `admin/start` (3 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/start/env.ts` | ts | infrastructure | 0 | no |

### `admin/app/exceptions` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/app/exceptions/handler.ts` | ts | presentation | 1 | no |

### `admin/constants` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/constants/kv_store.ts` | ts | data_access | 0 | no |

### `admin/inertia/components/chat` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/components/chat/ChatAssistantAvatar.tsx` | tsx | presentation | 1 | no |

### `admin/inertia/layouts` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/layouts/DocsLayout.tsx` | tsx | presentation | 1 | no |

### `admin/inertia/pages` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/pages/about.tsx` | tsx | presentation | 1 | no |

### `admin/inertia/pages/errors` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/pages/errors/not_found.tsx` | tsx | presentation | 1 | no |

### `admin/util` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/util/files.ts` | ts | utility | 2 | no |

### `admin/inertia/components/file-uploader` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/components/file-uploader/index.tsx` | tsx | presentation | 0 | no |

*... and 96 more files in this community.*


## Key Symbols

- `HttpExceptionHandler` (class, `admin/app/exceptions/handler.ts:5`)
- `InternalServerErrorException` (class, `admin/app/exceptions/internal_server_error_exception.ts:3`)
- `CompressionMiddleware` (class, `admin/app/middleware/compression_middleware.ts:22`)
- `ForceJsonResponseMiddleware` (class, `admin/app/middleware/force_json_response_middleware.ts:9`) - Updating the "Accept" header to always accept "application/json" response from the server. This will
- `MapsStaticMiddleware` (class, `admin/app/middleware/maps_static_middleware.ts:10`) - See #providers/map_static_provider.ts for explanation of why this middleware exists.
- `BenchmarkResult` (class, `admin/app/models/benchmark_result.ts:5`)
- `BenchmarkSetting` (class, `admin/app/models/benchmark_setting.ts:5`)
- `ChatMessage` (class, `admin/app/models/chat_message.ts:6`)
- `ChatSession` (class, `admin/app/models/chat_session.ts:6`)
- `CollectionManifest` (class, `admin/app/models/collection_manifest.ts:5`)
- `CustomLibrarySource` (class, `admin/app/models/custom_library_source.ts:4`)
- `InstalledResource` (class, `admin/app/models/installed_resource.ts:4`)
- `KbIngestState` (class, `admin/app/models/kb_ingest_state.ts:15`) - Tracks the per-file decision and outcome of AI knowledge-base ingestion.  The row exists for any emb
- `KVStore` (class, `admin/app/models/kv_store.ts:10`) - Generic key-value store model for storing various settings that don't necessitate their own dedicate
- `MapMarker` (class, `admin/app/models/map_marker.ts:4`)
- `WikipediaSelection` (class, `admin/app/models/wikipedia_selection.ts:4`)
- `extends` (class, `admin/database/migrations/1751086751801_create_services_table.ts:3`)
- `extends` (class, `admin/database/migrations/1763499145832_update_services_table.ts:3`)
- `extends` (class, `admin/database/migrations/1764912210741_create_curated_collections_table.ts:3`)
- `extends` (class, `admin/database/migrations/1764912270123_create_curated_collection_resources_table.ts:3`)
- `extends` (class, `admin/database/migrations/1768170944482_update_services_add_installation_statuses_table.ts:3`)
- `extends` (class, `admin/database/migrations/1768453747522_update_services_add_icon.ts:3`)
- `extends` (class, `admin/database/migrations/1769097600001_create_benchmark_results_table.ts:3`)
- `extends` (class, `admin/database/migrations/1769097600002_create_benchmark_settings_table.ts:3`)
- `extends` (class, `admin/database/migrations/1769300000001_add_powered_by_and_display_order_to_services.ts:3`)
- `extends` (class, `admin/database/migrations/1769300000002_update_services_friendly_names.ts:3`)
- `extends` (class, `admin/database/migrations/1769324448000_add_builder_tag_to_benchmark_results.ts:3`)
- `extends` (class, `admin/database/migrations/1769400000001_create_installed_tiers_table.ts:3`)
- `extends` (class, `admin/database/migrations/1769400000002_create_kv_store_table.ts:3`)
- `extends` (class, `admin/database/migrations/1769500000001_create_wikipedia_selection_table.ts:3`)

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 0
- Cross-boundary resolved imports (EXTRACTED): 0

## Connections

- No cross-community bridges recorded. This community is self-contained.

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- Why do 107 file(s) lack file-level docs (e.g. `admin/adonisrc.ts`)? What purpose do they serve?
- What would break if the most connected file in orphans changed?
- Should orphans be split, given cohesion 0.00?

## Sources

- `admin/adonisrc.ts`
- `admin/app/exceptions/handler.ts`
- `admin/app/exceptions/internal_server_error_exception.ts`
- `admin/app/middleware/compression_middleware.ts`
- `admin/app/middleware/force_json_response_middleware.ts`
- `admin/app/middleware/maps_static_middleware.ts`
- `admin/app/models/benchmark_result.ts`
- `admin/app/models/benchmark_setting.ts`
- `admin/app/models/chat_message.ts`
- `admin/app/models/chat_session.ts`
- `admin/app/models/collection_manifest.ts`
- `admin/app/models/custom_library_source.ts`
- `admin/app/models/installed_resource.ts`
- `admin/app/models/kb_ingest_state.ts`
- `admin/app/models/kv_store.ts`
- `admin/app/models/map_marker.ts`
- `admin/app/models/wikipedia_selection.ts`
- `admin/app/validators/benchmark.ts`
- `admin/app/validators/chat.ts`
- `admin/app/validators/ollama.ts`
- *... and 96 more*
