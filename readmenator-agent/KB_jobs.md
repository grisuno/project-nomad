# Subsystem: jobs

## admin/app/jobs/check_service_updates_job.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `CheckServiceUpdatesJob` (class, line 11)
- Depends on: `admin/app/models/service.ts`, `admin/app/services/container_registry_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/queue_service.ts`, `admin/config/queue.ts`, `admin/constants/broadcast.ts`
- Imported by: `admin/app/controllers/system_controller.ts`, `admin/commands/queue/work.ts`

## admin/app/jobs/check_update_job.ts
- Layer: utility
- Language: ts
- Symbols:
  - `CheckUpdateJob` (class, line 8)
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/services/queue_service.ts`, `admin/app/services/system_service.ts`, `admin/config/queue.ts`
- Imported by: `admin/commands/queue/work.ts`

## admin/app/jobs/download_model_job.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `DownloadModelJob` (class, line 11)
- Depends on: `admin/app/services/ollama_service.ts`, `admin/app/services/queue_service.ts`, `admin/config/queue.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/services/download_service.ts`, `admin/app/services/ollama_service.ts`, `admin/commands/queue/work.ts`

## admin/app/jobs/embed_file_job.ts
- Layer: utility
- Language: ts
- Symbols:
  - `onProgress` (function, line 116)
  - `articlesDone` (function, line 119)
  - `nextOffset` (function, line 144)
  - `totalChunks` (function, line 196)
  - `filePath` (function, line 394)
  - `EmbedFileJob` (class, line 23)
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/services/ollama_service.ts`, `admin/app/services/queue_service.ts`, `admin/app/services/rag_service.ts`, `admin/config/queue.ts`, `admin/constants/zim_extraction.ts`, `admin/inertia/pages/settings/update.tsx`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_download_job.ts`, `admin/commands/queue/work.ts`

## admin/app/jobs/run_benchmark_job.ts
- Layer: utility
- Language: ts
- Symbols:
  - `RunBenchmarkJob` (class, line 8)
- Depends on: `admin/app/services/benchmark_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/queue_service.ts`, `admin/config/queue.ts`
- Imported by: `admin/app/controllers/benchmark_controller.ts`, `admin/commands/queue/work.ts`

## admin/app/jobs/run_download_job.ts
- Layer: utility
- Language: ts
- Symbols:
  - `progressPercent` (function, line 86)
  - `RunDownloadJob` (class, line 11)
- Depends on: `admin/app/jobs/embed_file_job.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/queue_service.ts`, `admin/app/services/zim_service.ts`, `admin/config/queue.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/services/collection_manifest_service.ts`, `admin/app/services/collection_update_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/zim_service.ts`, `admin/commands/queue/work.ts`

## admin/app/jobs/run_extract_pmtiles_job.ts
- Layer: utility
- Language: ts
- Symbols:
  - `RunExtractPmtilesJob` (class, line 29)
- Depends on: `admin/app/services/queue_service.ts`, `admin/app/utils/fs.ts`, `admin/app/utils/version.ts`, `admin/config/queue.ts`, `admin/constants/map_regions.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/services/download_service.ts`, `admin/app/services/map_service.ts`, `admin/commands/queue/work.ts`
