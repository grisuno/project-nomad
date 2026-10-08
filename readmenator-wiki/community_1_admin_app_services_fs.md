# admin/app/services: fs

*Community 1 | 26 files | cohesion 0.56*

## Definition

This community groups 26 file(s) rooted at `admin/app/services` with dominant language ts (cohesion 0.56). Central symbols: `CheckUpdateJob`, `CollectionManifestService`, `CollectionUpdateService`, `CollectionUpdatesController`, `DownloadModelJob`, `DownloadService`, `DownloadsController`, `EasySetupController`. Core file: `admin/app/utils/fs.ts` (15 symbols).

## Files

### `admin/app/services` (7 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/app/services/collection_manifest_service.ts` | ts | business_logic | 1 | no |
| `admin/app/services/collection_update_service.ts` | ts | business_logic | 1 | no |
| `admin/app/services/download_service.ts` | ts | business_logic | 1 | no |
| `admin/app/services/kiwix_library_service.ts` | ts | business_logic | 2 | no |

### `admin/app/controllers` (5 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/app/controllers/collection_updates_controller.ts` | ts | presentation | 1 | no |
| `admin/app/controllers/downloads_controller.ts` | ts | presentation | 1 | no |
| `admin/app/controllers/easy_setup_controller.ts` | ts | presentation | 1 | no |

### `admin/app/jobs` (4 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/app/jobs/check_update_job.ts` | ts | utility | 1 | no |
| `admin/app/jobs/download_model_job.ts` | ts | business_logic | 1 | no |
| `admin/app/jobs/run_download_job.ts` | ts | utility | 2 | no |

### `admin/app/utils` (3 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/app/utils/downloads.ts` | ts | utility | 7 | no |
| `admin/app/utils/fs.ts` | ts | utility | 15 | no |
| `admin/app/utils/zim_filename.ts` | ts | utility | 2 | no |

### `admin/app/validators` (3 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/app/validators/common.ts` | ts | utility | 2 | no |
| `admin/app/validators/curated_collections.ts` | ts | utility | 0 | no |
| `admin/app/validators/download.ts` | ts | utility | 0 | no |

### `admin/tests/unit` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/tests/unit/cloud_metadata_url.spec.ts` | ts | testing | 2 | no |
| `admin/tests/unit/zim_filename.spec.ts` | ts | testing | 0 | no |

### `admin/config` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/config/queue.ts` | ts | infrastructure | 0 | no |

### `admin/constants` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/constants/map_regions.ts` | ts | utility | 1 | no |

*... and 6 more files in this community.*


## Key Symbols

- `CollectionUpdatesController` (class, `admin/app/controllers/collection_updates_controller.ts:9`)
- `DownloadsController` (class, `admin/app/controllers/downloads_controller.ts:7`)
- `EasySetupController` (class, `admin/app/controllers/easy_setup_controller.ts:9`)
- `MapsController` (class, `admin/app/controllers/maps_controller.ts:17`)
- `ZimController` (class, `admin/app/controllers/zim_controller.ts:14`)
- `CheckUpdateJob` (class, `admin/app/jobs/check_update_job.ts:8`)
- `DownloadModelJob` (class, `admin/app/jobs/download_model_job.ts:11`)
- `RunDownloadJob` (class, `admin/app/jobs/run_download_job.ts:11`)
- `progressPercent` (function, `admin/app/jobs/run_download_job.ts:86`)
- `RunExtractPmtilesJob` (class, `admin/app/jobs/run_extract_pmtiles_job.ts:29`)
- `CollectionManifestService` (class, `admin/app/services/collection_manifest_service.ts:39`)
- `CollectionUpdateService` (class, `admin/app/services/collection_update_service.ts:20`)
- `DownloadService` (class, `admin/app/services/download_service.ts:18`)
- `KiwixLibraryService` (class, `admin/app/services/kiwix_library_service.ts:31`)
- `getMeta` (function, `admin/app/services/kiwix_library_service.ts:65`)
- `MapService` (class, `admin/app/services/map_service.ts:73`)
- `files` (function, `admin/app/services/map_service.ts:84`)
- `regions` (function, `admin/app/services/map_service.ts:326`)
- `unit` (function, `admin/app/services/map_service.ts:768`)
- `getHost` (function, `admin/app/services/map_service.ts:839`)
- `specifiedHostOrDefault` (function, `admin/app/services/map_service.ts:851`)
- `findExactGroupMatch` (function, `admin/app/services/map_service.ts:877`)
- `QueueService` (class, `admin/app/services/queue_service.ts:9`) - Process-wide singleton. Each `Queue` opens two ioredis connections (one for commands, one blocking).
- `ZimService` (class, `admin/app/services/zim_service.ts:39`)
- `doResumableDownload` (function, `admin/app/utils/downloads.ts:18`) - Perform a resumable download with progress tracking @param param0 - Download parameters. Leave allow
- `fetchStream` (function, `admin/app/utils/downloads.ts:96`)
- `clearStallTimer` (function, `admin/app/utils/downloads.ts:128`)
- `resetStallTimer` (function, `admin/app/utils/downloads.ts:135`)
- `cleanup` (function, `admin/app/utils/downloads.ts:171`)
- `doResumableDownloadWithRetry` (function, `admin/app/utils/downloads.ts:226`)

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 52
- Cross-boundary resolved imports (EXTRACTED): 40

## Connections

- [EXTRACTED] depends_on community 1 <-> 2 (strength 0.9): Extracted import edge crosses communities: admin/app/controllers/easy_setup_controller.ts imports admin/app/services/system_service.ts.
- [EXTRACTED] depends_on community 1 <-> 6 (strength 0.9): Extracted import edge crosses communities: admin/app/controllers/easy_setup_controller.ts imports admin/inertia/pages/easy-setup/complete.tsx.
- [EXTRACTED] depends_on community 3 <-> 1 (strength 0.9): Extracted import edge crosses communities: admin/app/jobs/check_service_updates_job.ts imports admin/app/services/queue_service.ts.
- [EXTRACTED] depends_on community 1 <-> 7 (strength 0.9): Extracted import edge crosses communities: admin/app/jobs/download_model_job.ts imports admin/inertia/pages/settings/update.tsx.
- [EXTRACTED] depends_on community 8 <-> 1 (strength 0.9): Extracted import edge crosses communities: admin/app/services/docs_service.ts imports admin/app/utils/fs.ts.
- [EXTRACTED] depends_on community 4 <-> 1 (strength 0.9): Extracted import edge crosses communities: admin/inertia/components/CountryPickerModal.tsx imports admin/constants/map_regions.ts.

## Risks

- [cycle] `admin/app/jobs/run_download_job.ts` -> `admin/app/services/zim_service.ts` -> `admin/app/services/collection_manifest_service.ts` -> `admin/app/jobs/run_download_job.ts`
- [cycle] `admin/app/services/ollama_service.ts` -> `admin/app/jobs/download_model_job.ts` -> `admin/app/services/ollama_service.ts`
- [cycle] `admin/app/jobs/run_download_job.ts` -> `admin/app/services/zim_service.ts` -> `admin/app/jobs/run_download_job.ts`
- [cycle] `admin/app/jobs/run_download_job.ts` -> `admin/app/services/map_service.ts` -> `admin/app/jobs/run_download_job.ts`
- [dataflow UNCHECKED_ALLOC] `admin/app/utils/fs.ts:111` `isValidZimFile` `fh`: Result of allocator stored in `fh` is never checked against NULL.

## Open Questions

- Why do 26 file(s) lack file-level docs (e.g. `admin/app/controllers/collection_updates_controller.ts`)? What purpose do they serve?
- Can the cycle `admin/app/jobs/run_download_job.ts` -> `admin/app/services/zim_service.ts` -> `admin/app/services/collection_manifest_service.ts` be broken with an interface?
- What would break if the most connected file in admin/app/services: fs changed?
- Should admin/app/services: fs be split, given cohesion 0.56?

## Sources

- `admin/app/controllers/collection_updates_controller.ts`
- `admin/app/controllers/downloads_controller.ts`
- `admin/app/controllers/easy_setup_controller.ts`
- `admin/app/controllers/maps_controller.ts`
- `admin/app/controllers/zim_controller.ts`
- `admin/app/jobs/check_update_job.ts`
- `admin/app/jobs/download_model_job.ts`
- `admin/app/jobs/run_download_job.ts`
- `admin/app/jobs/run_extract_pmtiles_job.ts`
- `admin/app/services/collection_manifest_service.ts`
- `admin/app/services/collection_update_service.ts`
- `admin/app/services/download_service.ts`
- `admin/app/services/kiwix_library_service.ts`
- `admin/app/services/map_service.ts`
- `admin/app/services/queue_service.ts`
- `admin/app/services/zim_service.ts`
- `admin/app/utils/downloads.ts`
- `admin/app/utils/fs.ts`
- `admin/app/utils/zim_filename.ts`
- `admin/app/validators/common.ts`
- *... and 6 more*
