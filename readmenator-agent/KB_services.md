# Subsystem: services

## admin/app/services/benchmark_service.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `totalTime` (function, line 504)
  - `BenchmarkService` (class, line 67)
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/services/system_service.ts`, `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/benchmark_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/run_benchmark_job.ts`

## admin/app/services/chat_service.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `ChatService` (class, line 11)
- Depends on: `admin/app/services/ollama_service.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/ollama_controller.ts`

## admin/app/services/collection_manifest_service.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `CollectionManifestService` (class, line 39)
- Depends on: `admin/app/jobs/run_download_job.ts`, `admin/app/services/queue_service.ts`, `admin/app/utils/fs.ts`, `admin/app/validators/curated_collections.ts`
- Imported by: `admin/app/controllers/easy_setup_controller.ts`, `admin/app/services/map_service.ts`, `admin/app/services/zim_service.ts`

## admin/app/services/collection_update_service.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `CollectionUpdateService` (class, line 20)
- Depends on: `admin/app/jobs/run_download_job.ts`, `admin/app/utils/fs.ts`
- Imported by: `admin/app/controllers/collection_updates_controller.ts`

## admin/app/services/container_registry_service.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `data` (function, line 104)
  - `data` (function, line 137)
  - `manifest` (function, line 177)
  - `manifest` (function, line 236)
  - `childManifest` (function, line 256)
  - `config` (function, line 278)
  - `ContainerRegistryService` (class, line 28)
- Depends on: `admin/app/utils/version.ts`
- Imported by: `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`

## admin/app/services/countries_service.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `typeRank` (function, line 215)
  - `resolveIso2` (function, line 225)
  - `bufferGeometry` (function, line 242)
  - `bufferPolygonRings` (function, line 258)
  - `bufferRing` (function, line 262)
  - `signedArea` (function, line 290)
  - `resolveIso3` (function, line 298)
  - `codes` (function, line 144)
  - `n1x` (function, line 278)
  - `n1y` (function, line 279)
  - `n2x` (function, line 280)
  - `n2y` (function, line 281)
  - `CountriesService` (class, line 74)
- Depends on: `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/services/map_service.ts`

## admin/app/services/docker_service.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `used` (function, line 548)
  - `is` (function, line 826)
  - `marker` (function, line 934)
  - `gfx` (function, line 1043)
  - `DockerService` (class, line 19)
- Depends on: `admin/app/services/kiwix_library_service.ts`, `admin/app/utils/fs.ts`, `admin/app/utils/version.ts`, `admin/constants/broadcast.ts`, `admin/constants/kiwix.ts`, `admin/constants/service_names.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_benchmark_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/zim_service.ts`

## admin/app/services/docs_service.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `DocsService` (class, line 8)
- Depends on: `admin/app/utils/fs.ts`, `admin/util/docs.ts`
- Imported by: `admin/app/controllers/docs_controller.ts`

## admin/app/services/download_service.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `DownloadService` (class, line 18)
- Depends on: `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/queue_service.ts`, `admin/app/utils/fs.ts`, `admin/app/validators/download.ts`, `admin/constants/broadcast.ts`
- Imported by: `admin/app/controllers/downloads_controller.ts`

## admin/app/services/kiwix_library_service.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `getMeta` (function, line 65)
  - `KiwixLibraryService` (class, line 31)
- Depends on: `admin/app/utils/fs.ts`
- Imported by: `admin/app/services/docker_service.ts`, `admin/app/services/zim_service.ts`

## admin/app/services/map_service.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `getHost` (function, line 839)
  - `specifiedHostOrDefault` (function, line 851)
  - `findExactGroupMatch` (function, line 877)
  - `files` (function, line 84)
  - `regions` (function, line 326)
  - `unit` (function, line 768)
  - `MapService` (class, line 73)
- Depends on: `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/utils/fs.ts`, `admin/app/validators/common.ts`, `admin/constants/map_regions.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/maps_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/run_download_job.ts`

## admin/app/services/ollama_service.ts
- Doc: partialTagSuffix: Returns how many trailing chars of `text` could be the start of `tag`
- Layer: business_logic
- Language: ts
- Symbols:
  - `partialTagSuffix` (function, line 370)
  - `customUrl` (function, line 64)
  - `onAbort` (function, line 187)
  - `stream` (function, line 367)
  - `parsePulls` (function, line 860)
  - `parseSize` (function, line 879)
  - `OllamaService` (class, line 51)
- Depends on: `admin/app/jobs/download_model_job.ts`, `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/services/chat_service.ts`, `admin/app/services/rag_service.ts`

## admin/app/services/queue_service.ts
- Doc: QueueService: Process-wide singleton.
- Layer: business_logic
- Language: ts
- Symbols:
  - `QueueService` (class, line 9)
- Imported by: `admin/app/jobs/check_service_updates_job.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_benchmark_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/download_service.ts`

## admin/app/services/rag_service.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `progress` (function, line 373)
  - `RagService` (class, line 41)
  - `if` (class, line 208)
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/services/ollama_service.ts`, `admin/app/services/zim_extraction_service.ts`, `admin/app/utils/fs.ts`, `admin/app/utils/kb_ingest_decision.ts`, `admin/app/utils/kb_warning_decision.ts`, `admin/constants/service_names.ts`, `admin/constants/zim_extraction.ts`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/embed_file_job.ts`

## admin/app/services/system_service.ts
- Doc: hasLspciBogusDgpuVram: Clear the bogus value up front.
- Layer: business_logic
- Language: ts
- Symbols:
  - `buf` (function, line 131)
  - `actualImage` (function, line 251)
  - `isDiscreteGpuVendor` (function, line 440)
  - `isBogusDgpuVram` (function, line 442)
  - `hasLspciBogusDgpuVram` (function, line 452)
  - `earlyAccess` (function, line 630)
  - `SystemService` (class, line 26)
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/utils/fs.ts`, `admin/app/utils/version.ts`, `admin/config/inertia.ts`, `admin/constants/service_names.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/easy_setup_controller.ts`, `admin/app/controllers/home_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/config/inertia.ts`

## admin/app/services/system_update_service.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `SystemUpdateService` (class, line 14)
- Depends on: `admin/app/utils/fs.ts`
- Imported by: `admin/app/controllers/system_controller.ts`

## admin/app/services/zim_extraction_service.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `ZIMExtractionService` (class, line 10)
- Depends on: `admin/app/utils/fs.ts`, `admin/constants/zim_extraction.ts`
- Imported by: `admin/app/services/rag_service.ts`

## admin/app/services/zim_service.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `ZimService` (class, line 39)
- Depends on: `admin/app/jobs/run_download_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/kiwix_library_service.ts`, `admin/app/utils/fs.ts`, `admin/app/utils/zim_filename.ts`, `admin/app/validators/common.ts`, `admin/app/validators/curated_collections.ts`, `admin/constants/service_names.ts`
- Imported by: `admin/app/controllers/easy_setup_controller.ts`, `admin/app/controllers/zim_controller.ts`, `admin/app/jobs/run_download_job.ts`
