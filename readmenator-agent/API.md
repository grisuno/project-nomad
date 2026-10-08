# API

## admin/app/controllers/benchmark_controller.ts

### statusCode (function)
- Defined: `admin/app/controllers/benchmark_controller.ts:185`
- Doc: Pass through the status code from the service if available, otherwise default to 400
- Depends on: `admin/app/jobs/run_benchmark_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/validators/settings.ts`, `admin/commands/benchmark/results.ts`, `admin/commands/benchmark/run.ts`, `admin/commands/benchmark/submit.ts`, `admin/inertia/pages/docs/show.tsx`

## admin/app/jobs/embed_file_job.ts

### onProgress (function)
- Defined: `admin/app/jobs/embed_file_job.ts:116`
- Doc: Progress callback. For multi-batch ZIM ingestions, scale the service-reported 0-100% (which is % through the current bat
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/services/ollama_service.ts`, `admin/app/services/queue_service.ts`, `admin/app/services/rag_service.ts`, `admin/config/queue.ts`, `admin/constants/zim_extraction.ts`, `admin/inertia/pages/settings/update.tsx`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_download_job.ts`, `admin/commands/queue/work.ts`

### articlesDone (function)
- Defined: `admin/app/jobs/embed_file_job.ts:119`
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/services/ollama_service.ts`, `admin/app/services/queue_service.ts`, `admin/app/services/rag_service.ts`, `admin/config/queue.ts`, `admin/constants/zim_extraction.ts`, `admin/inertia/pages/settings/update.tsx`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_download_job.ts`, `admin/commands/queue/work.ts`

### nextOffset (function)
- Defined: `admin/app/jobs/embed_file_job.ts:144`
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/services/ollama_service.ts`, `admin/app/services/queue_service.ts`, `admin/app/services/rag_service.ts`, `admin/config/queue.ts`, `admin/constants/zim_extraction.ts`, `admin/inertia/pages/settings/update.tsx`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_download_job.ts`, `admin/commands/queue/work.ts`

### totalChunks (function)
- Defined: `admin/app/jobs/embed_file_job.ts:196`
- Doc: Final batch or non-batched file - mark as complete
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/services/ollama_service.ts`, `admin/app/services/queue_service.ts`, `admin/app/services/rag_service.ts`, `admin/config/queue.ts`, `admin/constants/zim_extraction.ts`, `admin/inertia/pages/settings/update.tsx`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_download_job.ts`, `admin/commands/queue/work.ts`

### filePath (function)
- Defined: `admin/app/jobs/embed_file_job.ts:394`
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/services/ollama_service.ts`, `admin/app/services/queue_service.ts`, `admin/app/services/rag_service.ts`, `admin/config/queue.ts`, `admin/constants/zim_extraction.ts`, `admin/inertia/pages/settings/update.tsx`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_download_job.ts`, `admin/commands/queue/work.ts`

## admin/app/jobs/run_download_job.ts

### progressPercent (function)
- Defined: `admin/app/jobs/run_download_job.ts:86`
- Depends on: `admin/app/jobs/embed_file_job.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/queue_service.ts`, `admin/app/services/zim_service.ts`, `admin/config/queue.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/services/collection_manifest_service.ts`, `admin/app/services/collection_update_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/zim_service.ts`, `admin/commands/queue/work.ts`

## admin/app/services/benchmark_service.ts

### totalTime (function)
- Defined: `admin/app/services/benchmark_service.ts:504`
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/services/system_service.ts`, `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/benchmark_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/run_benchmark_job.ts`

## admin/app/services/container_registry_service.ts

### data (function)
- Defined: `admin/app/services/container_registry_service.ts:104`
- Depends on: `admin/app/utils/version.ts`
- Imported by: `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`

### data (function)
- Defined: `admin/app/services/container_registry_service.ts:137`
- Depends on: `admin/app/utils/version.ts`
- Imported by: `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`

### manifest (function)
- Defined: `admin/app/services/container_registry_service.ts:177`
- Depends on: `admin/app/utils/version.ts`
- Imported by: `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`

### manifest (function)
- Defined: `admin/app/services/container_registry_service.ts:236`
- Depends on: `admin/app/utils/version.ts`
- Imported by: `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`

### childManifest (function)
- Defined: `admin/app/services/container_registry_service.ts:256`
- Depends on: `admin/app/utils/version.ts`
- Imported by: `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`

### config (function)
- Defined: `admin/app/services/container_registry_service.ts:278`
- Depends on: `admin/app/utils/version.ts`
- Imported by: `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`

## admin/app/services/countries_service.ts

### typeRank (function)
- Defined: `admin/app/services/countries_service.ts:215`
- Depends on: `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/services/map_service.ts`

### resolveIso2 (function)
- Defined: `admin/app/services/countries_service.ts:225`
- Depends on: `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/services/map_service.ts`

### bufferGeometry (function)
- Defined: `admin/app/services/countries_service.ts:242`
- Depends on: `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/services/map_service.ts`

### bufferPolygonRings (function)
- Defined: `admin/app/services/countries_service.ts:258`
- Depends on: `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/services/map_service.ts`

### bufferRing (function)
- Defined: `admin/app/services/countries_service.ts:262`
- Depends on: `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/services/map_service.ts`

### signedArea (function)
- Defined: `admin/app/services/countries_service.ts:290`
- Depends on: `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/services/map_service.ts`

### resolveIso3 (function)
- Defined: `admin/app/services/countries_service.ts:298`
- Depends on: `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/services/map_service.ts`

### codes (function)
- Defined: `admin/app/services/countries_service.ts:144`
- Depends on: `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/services/map_service.ts`

### n1x (function)
- Defined: `admin/app/services/countries_service.ts:278`
- Depends on: `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/services/map_service.ts`

### n1y (function)
- Defined: `admin/app/services/countries_service.ts:279`
- Depends on: `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/services/map_service.ts`

### n2x (function)
- Defined: `admin/app/services/countries_service.ts:280`
- Depends on: `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/services/map_service.ts`

### n2y (function)
- Defined: `admin/app/services/countries_service.ts:281`
- Depends on: `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/services/map_service.ts`

## admin/app/services/docker_service.ts

### used (function)
- Defined: `admin/app/services/docker_service.ts:548`
- Depends on: `admin/app/services/kiwix_library_service.ts`, `admin/app/utils/fs.ts`, `admin/app/utils/version.ts`, `admin/constants/broadcast.ts`, `admin/constants/kiwix.ts`, `admin/constants/service_names.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_benchmark_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/zim_service.ts`

### is (function)
- Defined: `admin/app/services/docker_service.ts:826`
- Depends on: `admin/app/services/kiwix_library_service.ts`, `admin/app/utils/fs.ts`, `admin/app/utils/version.ts`, `admin/constants/broadcast.ts`, `admin/constants/kiwix.ts`, `admin/constants/service_names.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_benchmark_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/zim_service.ts`

### marker (function)
- Defined: `admin/app/services/docker_service.ts:934`
- Depends on: `admin/app/services/kiwix_library_service.ts`, `admin/app/utils/fs.ts`, `admin/app/utils/version.ts`, `admin/constants/broadcast.ts`, `admin/constants/kiwix.ts`, `admin/constants/service_names.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_benchmark_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/zim_service.ts`

### gfx (function)
- Defined: `admin/app/services/docker_service.ts:1043`
- Depends on: `admin/app/services/kiwix_library_service.ts`, `admin/app/utils/fs.ts`, `admin/app/utils/version.ts`, `admin/constants/broadcast.ts`, `admin/constants/kiwix.ts`, `admin/constants/service_names.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_benchmark_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/zim_service.ts`

## admin/app/services/kiwix_library_service.ts

### getMeta (function)
- Defined: `admin/app/services/kiwix_library_service.ts:65`
- Depends on: `admin/app/utils/fs.ts`
- Imported by: `admin/app/services/docker_service.ts`, `admin/app/services/zim_service.ts`

## admin/app/services/map_service.ts

### getHost (function)
- Defined: `admin/app/services/map_service.ts:839`
- Depends on: `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/utils/fs.ts`, `admin/app/validators/common.ts`, `admin/constants/map_regions.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/maps_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/run_download_job.ts`

### specifiedHostOrDefault (function)
- Defined: `admin/app/services/map_service.ts:851`
- Depends on: `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/utils/fs.ts`, `admin/app/validators/common.ts`, `admin/constants/map_regions.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/maps_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/run_download_job.ts`

### findExactGroupMatch (function)
- Defined: `admin/app/services/map_service.ts:877`
- Depends on: `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/utils/fs.ts`, `admin/app/validators/common.ts`, `admin/constants/map_regions.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/maps_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/run_download_job.ts`

### files (function)
- Defined: `admin/app/services/map_service.ts:84`
- Depends on: `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/utils/fs.ts`, `admin/app/validators/common.ts`, `admin/constants/map_regions.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/maps_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/run_download_job.ts`

### regions (function)
- Defined: `admin/app/services/map_service.ts:326`
- Depends on: `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/utils/fs.ts`, `admin/app/validators/common.ts`, `admin/constants/map_regions.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/maps_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/run_download_job.ts`

### unit (function)
- Defined: `admin/app/services/map_service.ts:768`
- Depends on: `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/utils/fs.ts`, `admin/app/validators/common.ts`, `admin/constants/map_regions.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/maps_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/run_download_job.ts`

## admin/app/services/ollama_service.ts

### partialTagSuffix (function)
- Defined: `admin/app/services/ollama_service.ts:370`
- Doc: Returns how many trailing chars of `text` could be the start of `tag`
- Depends on: `admin/app/jobs/download_model_job.ts`, `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/services/chat_service.ts`, `admin/app/services/rag_service.ts`

### customUrl (function)
- Defined: `admin/app/services/ollama_service.ts:64`
- Doc: Check KVStore for a custom base URL (remote Ollama, LM Studio, llama.cpp, etc.)
- Depends on: `admin/app/jobs/download_model_job.ts`, `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/services/chat_service.ts`, `admin/app/services/rag_service.ts`

### onAbort (function)
- Defined: `admin/app/services/ollama_service.ts:187`
- Doc: If the abort fires after headers are received but mid-stream, axios's signal handling destroys the stream which surfaces
- Depends on: `admin/app/jobs/download_model_job.ts`, `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/services/chat_service.ts`, `admin/app/services/rag_service.ts`

### stream (function)
- Defined: `admin/app/services/ollama_service.ts:367`
- Depends on: `admin/app/jobs/download_model_job.ts`, `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/services/chat_service.ts`, `admin/app/services/rag_service.ts`

### parsePulls (function)
- Defined: `admin/app/services/ollama_service.ts:860`
- Depends on: `admin/app/jobs/download_model_job.ts`, `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/services/chat_service.ts`, `admin/app/services/rag_service.ts`

### parseSize (function)
- Defined: `admin/app/services/ollama_service.ts:879`
- Depends on: `admin/app/jobs/download_model_job.ts`, `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/services/chat_service.ts`, `admin/app/services/rag_service.ts`

## admin/app/services/rag_service.ts

### progress (function)
- Defined: `admin/app/services/rag_service.ts:373`
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/services/ollama_service.ts`, `admin/app/services/zim_extraction_service.ts`, `admin/app/utils/fs.ts`, `admin/app/utils/kb_ingest_decision.ts`, `admin/app/utils/kb_warning_decision.ts`, `admin/constants/service_names.ts`, `admin/constants/zim_extraction.ts`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/embed_file_job.ts`

## admin/app/services/system_service.ts

### buf (function)
- Defined: `admin/app/services/system_service.ts:131`
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/utils/fs.ts`, `admin/app/utils/version.ts`, `admin/config/inertia.ts`, `admin/constants/service_names.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/easy_setup_controller.ts`, `admin/app/controllers/home_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/config/inertia.ts`

### actualImage (function)
- Defined: `admin/app/services/system_service.ts:251`
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/utils/fs.ts`, `admin/app/utils/version.ts`, `admin/config/inertia.ts`, `admin/constants/service_names.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/easy_setup_controller.ts`, `admin/app/controllers/home_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/config/inertia.ts`

### isDiscreteGpuVendor (function)
- Defined: `admin/app/services/system_service.ts:440`
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/utils/fs.ts`, `admin/app/utils/version.ts`, `admin/config/inertia.ts`, `admin/constants/service_names.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/easy_setup_controller.ts`, `admin/app/controllers/home_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/config/inertia.ts`

### isBogusDgpuVram (function)
- Defined: `admin/app/services/system_service.ts:442`
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/utils/fs.ts`, `admin/app/utils/version.ts`, `admin/config/inertia.ts`, `admin/constants/service_names.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/easy_setup_controller.ts`, `admin/app/controllers/home_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/config/inertia.ts`

### hasLspciBogusDgpuVram (function)
- Defined: `admin/app/services/system_service.ts:452`
- Doc: Clear the bogus value up front. If a probe replaces the entry below we get the real VRAM; if no probe succeeds (Ollama n
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/utils/fs.ts`, `admin/app/utils/version.ts`, `admin/config/inertia.ts`, `admin/constants/service_names.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/easy_setup_controller.ts`, `admin/app/controllers/home_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/config/inertia.ts`

### earlyAccess (function)
- Defined: `admin/app/services/system_service.ts:630`
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/utils/fs.ts`, `admin/app/utils/version.ts`, `admin/config/inertia.ts`, `admin/constants/service_names.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/easy_setup_controller.ts`, `admin/app/controllers/home_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/config/inertia.ts`

## admin/app/utils/downloads.ts

### doResumableDownload (function)
- Defined: `admin/app/utils/downloads.ts:18`
- Doc: Perform a resumable download with progress tracking @param param0 - Download parameters. Leave allowedMimeTypes empty to
- Depends on: `admin/app/utils/fs.ts`

### doResumableDownloadWithRetry (function)
- Defined: `admin/app/utils/downloads.ts:226`
- Depends on: `admin/app/utils/fs.ts`

### delay (function)
- Defined: `admin/app/utils/downloads.ts:284`
- Depends on: `admin/app/utils/fs.ts`

### fetchStream (function)
- Defined: `admin/app/utils/downloads.ts:96`
- Depends on: `admin/app/utils/fs.ts`

### clearStallTimer (function)
- Defined: `admin/app/utils/downloads.ts:128`
- Depends on: `admin/app/utils/fs.ts`

### resetStallTimer (function)
- Defined: `admin/app/utils/downloads.ts:135`
- Depends on: `admin/app/utils/fs.ts`

### cleanup (function)
- Defined: `admin/app/utils/downloads.ts:171`
- Depends on: `admin/app/utils/fs.ts`

## admin/app/utils/fs.ts

### listDirectoryContents (function)
- Defined: `admin/app/utils/fs.ts:10`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/collection_update_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/docs_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/kiwix_library_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/system_update_service.ts`, `admin/app/services/zim_extraction_service.ts`, `admin/app/services/zim_service.ts`, `admin/app/utils/downloads.ts`, `admin/app/utils/downloads.ts`

### listDirectoryContentsRecursive (function)
- Defined: `admin/app/utils/fs.ts:31`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/collection_update_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/docs_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/kiwix_library_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/system_update_service.ts`, `admin/app/services/zim_extraction_service.ts`, `admin/app/services/zim_service.ts`, `admin/app/utils/downloads.ts`, `admin/app/utils/downloads.ts`

### ensureDirectoryExists (function)
- Defined: `admin/app/utils/fs.ts:50`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/collection_update_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/docs_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/kiwix_library_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/system_update_service.ts`, `admin/app/services/zim_extraction_service.ts`, `admin/app/services/zim_service.ts`, `admin/app/utils/downloads.ts`, `admin/app/utils/downloads.ts`

### getFile (function)
- Defined: `admin/app/utils/fs.ts:60`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/collection_update_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/docs_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/kiwix_library_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/system_update_service.ts`, `admin/app/services/zim_extraction_service.ts`, `admin/app/services/zim_service.ts`, `admin/app/utils/downloads.ts`, `admin/app/utils/downloads.ts`

### getFile (function)
- Defined: `admin/app/utils/fs.ts:61`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/collection_update_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/docs_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/kiwix_library_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/system_update_service.ts`, `admin/app/services/zim_extraction_service.ts`, `admin/app/services/zim_service.ts`, `admin/app/utils/downloads.ts`, `admin/app/utils/downloads.ts`

### getFile (function)
- Defined: `admin/app/utils/fs.ts:65`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/collection_update_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/docs_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/kiwix_library_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/system_update_service.ts`, `admin/app/services/zim_extraction_service.ts`, `admin/app/services/zim_service.ts`, `admin/app/utils/downloads.ts`, `admin/app/utils/downloads.ts`

### getFile (function)
- Defined: `admin/app/utils/fs.ts:66`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/collection_update_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/docs_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/kiwix_library_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/system_update_service.ts`, `admin/app/services/zim_extraction_service.ts`, `admin/app/services/zim_service.ts`, `admin/app/utils/downloads.ts`, `admin/app/utils/downloads.ts`

### getFileStatsIfExists (function)
- Defined: `admin/app/utils/fs.ts:85`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/collection_update_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/docs_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/kiwix_library_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/system_update_service.ts`, `admin/app/services/zim_extraction_service.ts`, `admin/app/services/zim_service.ts`, `admin/app/utils/downloads.ts`, `admin/app/utils/downloads.ts`

### isValidZimFile (function)
- Defined: `admin/app/utils/fs.ts:108`
- Doc: Validates that a file has the ZIM magic number (0x44D495A). Must be called before passing a file to @openzim/libzim Arch
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/collection_update_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/docs_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/kiwix_library_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/system_update_service.ts`, `admin/app/services/zim_extraction_service.ts`, `admin/app/services/zim_service.ts`, `admin/app/utils/downloads.ts`, `admin/app/utils/downloads.ts`

### deleteFileIfExists (function)
- Defined: `admin/app/utils/fs.ts:124`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/collection_update_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/docs_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/kiwix_library_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/system_update_service.ts`, `admin/app/services/zim_extraction_service.ts`, `admin/app/services/zim_service.ts`, `admin/app/utils/downloads.ts`, `admin/app/utils/downloads.ts`

### getAllFilesystems (function)
- Defined: `admin/app/utils/fs.ts:134`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/collection_update_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/docs_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/kiwix_library_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/system_update_service.ts`, `admin/app/services/zim_extraction_service.ts`, `admin/app/services/zim_service.ts`, `admin/app/utils/downloads.ts`, `admin/app/utils/downloads.ts`

### traverse (function)
- Defined: `admin/app/utils/fs.ts:141`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/collection_update_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/docs_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/kiwix_library_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/system_update_service.ts`, `admin/app/services/zim_extraction_service.ts`, `admin/app/services/zim_service.ts`, `admin/app/utils/downloads.ts`, `admin/app/utils/downloads.ts`

### matchesDevice (function)
- Defined: `admin/app/utils/fs.ts:160`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/collection_update_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/docs_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/kiwix_library_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/system_update_service.ts`, `admin/app/services/zim_extraction_service.ts`, `admin/app/services/zim_service.ts`, `admin/app/utils/downloads.ts`, `admin/app/utils/downloads.ts`

### determineFileType (function)
- Defined: `admin/app/utils/fs.ts:177`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/collection_update_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/docs_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/kiwix_library_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/system_update_service.ts`, `admin/app/services/zim_extraction_service.ts`, `admin/app/services/zim_service.ts`, `admin/app/utils/downloads.ts`, `admin/app/utils/downloads.ts`

### sanitizeFilename (function)
- Defined: `admin/app/utils/fs.ts:199`
- Doc: Sanitize a filename by removing potentially dangerous characters. @param filename The original filename @returns The san
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/collection_update_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/docs_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/kiwix_library_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/system_update_service.ts`, `admin/app/services/zim_extraction_service.ts`, `admin/app/services/zim_service.ts`, `admin/app/utils/downloads.ts`, `admin/app/utils/downloads.ts`

## admin/app/utils/kb_ingest_decision.ts

### decideScanAction (function)
- Defined: `admin/app/utils/kb_ingest_decision.ts:44`
- Doc: Decide what scanAndSyncStorage should do for a single embeddable file.  Replaces the earlier `!sourcesInQdrant.has(fileP
- Imported by: `admin/app/services/rag_service.ts`, `admin/tests/unit/kb_ingest_decision.spec.ts`

## admin/app/utils/kb_job_health.ts

### computeJobHealth (function)
- Defined: `admin/app/utils/kb_job_health.ts:32`
- Imported by: `admin/inertia/lib/kb_job_health_display.ts`, `admin/tests/unit/kb_job_health.spec.ts`

## admin/app/utils/kb_ratio_lookup.ts

### estimateBatch (function)
- Defined: `admin/app/utils/kb_ratio_lookup.ts:38`
- Doc: Aggregate an embedding-disk-cost estimate across a batch of files (curated tier add, multi-upload, sync preview, etc). `
- Imported by: `admin/app/models/kb_ratio_registry.ts`, `admin/tests/unit/kb_ratio_lookup.spec.ts`

### findChunksPerMb (function)
- Defined: `admin/app/utils/kb_ratio_lookup.ts:70`
- Doc: Pick the chunks_per_mb estimate for a filename by longest-prefix match.  Patterns are filename prefixes (`devdocs_`, `wi
- Imported by: `admin/app/models/kb_ratio_registry.ts`, `admin/tests/unit/kb_ratio_lookup.spec.ts`

### estimateChunkCount (function)
- Defined: `admin/app/utils/kb_ratio_lookup.ts:88`
- Doc: Estimate the number of embedding chunks a ZIM-style file will produce given its size on disk in bytes. Returns `null` wh
- Imported by: `admin/app/models/kb_ratio_registry.ts`, `admin/tests/unit/kb_ratio_lookup.spec.ts`

## admin/app/utils/kb_warning_decision.ts

### decideWarnings (function)
- Defined: `admin/app/utils/kb_warning_decision.ts:41`
- Imported by: `admin/app/services/rag_service.ts`, `admin/tests/unit/kb_warning_decision.spec.ts`

## admin/app/utils/misc.ts

### formatSpeed (function)
- Defined: `admin/app/utils/misc.ts:1`
- Imported by: `admin/inertia/components/chat/ChatModal.tsx`

### toTitleCase (function)
- Defined: `admin/app/utils/misc.ts:7`
- Imported by: `admin/inertia/components/chat/ChatModal.tsx`

### parseBoolean (function)
- Defined: `admin/app/utils/misc.ts:15`
- Imported by: `admin/inertia/components/chat/ChatModal.tsx`

## admin/app/utils/version.ts

### isNewerVersion (function)
- Defined: `admin/app/utils/version.ts:7`
- Doc: Compare two semantic version strings to determine if the first is newer than the second. @param version1 - The version t
- Imported by: `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/container_registry_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/system_service.ts`, `admin/inertia/components/UpdateServiceModal.tsx`, `admin/inertia/pages/settings/update.tsx`

### parseMajorVersion (function)
- Defined: `admin/app/utils/version.ts:45`
- Doc: Parse the major version number from a tag string. Strips the 'v' prefix if present. @param tag - Version tag (e.g., "v3.
- Imported by: `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/container_registry_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/system_service.ts`, `admin/inertia/components/UpdateServiceModal.tsx`, `admin/inertia/pages/settings/update.tsx`

### normalize (function)
- Defined: `admin/app/utils/version.ts:8`
- Imported by: `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/container_registry_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/system_service.ts`, `admin/inertia/components/UpdateServiceModal.tsx`, `admin/inertia/pages/settings/update.tsx`

## admin/app/utils/zim_filename.ts

### zimFilenameStem (function)
- Defined: `admin/app/utils/zim_filename.ts:7`
- Doc: Strip the trailing `_YYYY-MM(-DD).zim` date suffix from a Kiwix-style ZIM filename so different release dates of the sam
- Imported by: `admin/app/services/zim_service.ts`, `admin/tests/unit/zim_filename.spec.ts`

### findReplacedWikipediaFiles (function)
- Defined: `admin/app/utils/zim_filename.ts:17`
- Doc: Of the existing files, return only those that are prior-version replacements of `currentFilename` — same Wikipedia varia
- Imported by: `admin/app/services/zim_service.ts`, `admin/tests/unit/zim_filename.spec.ts`

## admin/app/validators/common.ts

### assertNotPrivateUrl (function)
- Defined: `admin/app/validators/common.ts:15`
- Doc: Checks whether a URL points to a loopback or link-local address. Used to prevent SSRF — the server should not fetch from
- Imported by: `admin/app/controllers/collection_updates_controller.ts`, `admin/app/controllers/maps_controller.ts`, `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/zim_controller.ts`, `admin/app/services/map_service.ts`, `admin/app/services/zim_service.ts`, `admin/tests/unit/cloud_metadata_url.spec.ts`

### assertNotCloudMetadataUrl (function)
- Defined: `admin/app/validators/common.ts:61`
- Imported by: `admin/app/controllers/collection_updates_controller.ts`, `admin/app/controllers/maps_controller.ts`, `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/zim_controller.ts`, `admin/app/services/map_service.ts`, `admin/app/services/zim_service.ts`, `admin/tests/unit/cloud_metadata_url.spec.ts`

## admin/config/inertia.ts

### invalidateAssistantNameCache (function)
- Defined: `admin/config/inertia.ts:8`
- Depends on: `admin/app/services/system_service.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/services/system_service.ts`

### value (function)
- Defined: `admin/config/inertia.ts:30`
- Depends on: `admin/app/services/system_service.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/services/system_service.ts`

## admin/constants/map_regions.ts

### buildPmtilesExtractArgs (function)
- Defined: `admin/constants/map_regions.ts:24`
- Imported by: `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/map_service.ts`, `admin/inertia/components/CountryPickerModal.tsx`

## admin/inertia/app/app.tsx

### environment (function)
- Defined: `admin/inertia/app/app.tsx:38`
- Depends on: `admin/inertia/providers/ThemeProvider.tsx`, `admin/types/system.ts`

## admin/inertia/components/ActiveDownloads.tsx

### formatSpeed (function)
- Defined: `admin/inertia/components/ActiveDownloads.tsx:12`
- Depends on: `admin/inertia/hooks/useDownloads.ts`

### getDownloadStatus (function)
- Defined: `admin/inertia/components/ActiveDownloads.tsx:21`
- Depends on: `admin/inertia/hooks/useDownloads.ts`

### ActiveDownloads (function)
- Defined: `admin/inertia/components/ActiveDownloads.tsx:38`
- Depends on: `admin/inertia/hooks/useDownloads.ts`

### deltaSec (function)
- Defined: `admin/inertia/components/ActiveDownloads.tsx:56`
- Depends on: `admin/inertia/hooks/useDownloads.ts`

### handleDismiss (function)
- Defined: `admin/inertia/components/ActiveDownloads.tsx:81`
- Depends on: `admin/inertia/hooks/useDownloads.ts`

### handleCancel (function)
- Defined: `admin/inertia/components/ActiveDownloads.tsx:86`
- Depends on: `admin/inertia/hooks/useDownloads.ts`

## admin/inertia/components/ActiveEmbedJobs.tsx

### ActiveEmbedJobs (function)
- Defined: `admin/inertia/components/ActiveEmbedJobs.tsx:15`
- Depends on: `admin/inertia/hooks/useEmbedJobs.ts`, `admin/inertia/lib/kb_job_health_display.ts`

## admin/inertia/components/ActiveModelDownloads.tsx

### formatSpeed (function)
- Defined: `admin/inertia/components/ActiveModelDownloads.tsx:13`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useOllamaModelDownloads.ts`

### ActiveModelDownloads (function)
- Defined: `admin/inertia/components/ActiveModelDownloads.tsx:21`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useOllamaModelDownloads.ts`

### deltaSec (function)
- Defined: `admin/inertia/components/ActiveModelDownloads.tsx:39`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useOllamaModelDownloads.ts`

### runCancel (function)
- Defined: `admin/inertia/components/ActiveModelDownloads.tsx:62`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useOllamaModelDownloads.ts`

### confirmCancel (function)
- Defined: `admin/inertia/components/ActiveModelDownloads.tsx:85`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useOllamaModelDownloads.ts`

## admin/inertia/components/Alert.tsx

### Alert (function)
- Defined: `admin/inertia/components/Alert.tsx:17`
- Depends on: `admin/inertia/lib/classNames.ts`

### getDefaultIcon (function)
- Defined: `admin/inertia/components/Alert.tsx:29`
- Depends on: `admin/inertia/lib/classNames.ts`

### getIconColor (function)
- Defined: `admin/inertia/components/Alert.tsx:44`
- Depends on: `admin/inertia/lib/classNames.ts`

### getVariantStyles (function)
- Defined: `admin/inertia/components/Alert.tsx:60`
- Depends on: `admin/inertia/lib/classNames.ts`

### getTitleColor (function)
- Defined: `admin/inertia/components/Alert.tsx:113`
- Depends on: `admin/inertia/lib/classNames.ts`

### getMessageColor (function)
- Defined: `admin/inertia/components/Alert.tsx:132`
- Depends on: `admin/inertia/lib/classNames.ts`

### getCloseButtonStyles (function)
- Defined: `admin/inertia/components/Alert.tsx:149`
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/BouncingDots.tsx

### BouncingDots (function)
- Defined: `admin/inertia/components/BouncingDots.tsx:9`

## admin/inertia/components/BouncingLogo.tsx

### FadingImage (function)
- Defined: `admin/inertia/components/BouncingLogo.tsx:4`
- Doc: Fading Image Component

## admin/inertia/components/BuilderTagSelector.tsx

### BuilderTagSelector (function)
- Defined: `admin/inertia/components/BuilderTagSelector.tsx:18`

### updateTag (function)
- Defined: `admin/inertia/components/BuilderTagSelector.tsx:50`
- Doc: Update parent when selections change

### handleAdjectiveChange (function)
- Defined: `admin/inertia/components/BuilderTagSelector.tsx:55`

### handleNounChange (function)
- Defined: `admin/inertia/components/BuilderTagSelector.tsx:60`

### handleRandomize (function)
- Defined: `admin/inertia/components/BuilderTagSelector.tsx:65`

## admin/inertia/components/CategoryCard.tsx

### getTierTotalSize (function)
- Defined: `admin/inertia/components/CategoryCard.tsx:15`
- Doc: Calculate total size range across all tiers

## admin/inertia/components/CountryPickerModal.tsx

### toggleCountry (function)
- Defined: `admin/inertia/components/CountryPickerModal.tsx:100`
- Depends on: `admin/constants/map_regions.ts`, `admin/inertia/lib/classNames.ts`

### toggleGroup (function)
- Defined: `admin/inertia/components/CountryPickerModal.tsx:109`
- Depends on: `admin/constants/map_regions.ts`, `admin/inertia/lib/classNames.ts`

### clearAll (function)
- Defined: `admin/inertia/components/CountryPickerModal.tsx:122`
- Depends on: `admin/constants/map_regions.ts`, `admin/inertia/lib/classNames.ts`

### startDownload (function)
- Defined: `admin/inertia/components/CountryPickerModal.tsx:164`
- Depends on: `admin/constants/map_regions.ts`, `admin/inertia/lib/classNames.ts`

### PreflightStatus (function)
- Defined: `admin/inertia/components/CountryPickerModal.tsx:392`
- Depends on: `admin/constants/map_regions.ts`, `admin/inertia/lib/classNames.ts`

## admin/inertia/components/DebugInfoModal.tsx

### DebugInfoModal (function)
- Defined: `admin/inertia/components/DebugInfoModal.tsx:11`

### handleCopy (function)
- Defined: `admin/inertia/components/DebugInfoModal.tsx:36`

## admin/inertia/components/DownloadURLModal.tsx

### runPreflightCheck (function)
- Defined: `admin/inertia/components/DownloadURLModal.tsx:23`

## admin/inertia/components/Footer.tsx

### Footer (function)
- Defined: `admin/inertia/components/Footer.tsx:8`
- Depends on: `admin/types/system.ts`

## admin/inertia/components/HorizontalBarChart.tsx

### HorizontalBarChart (function)
- Defined: `admin/inertia/components/HorizontalBarChart.tsx:19`
- Depends on: `admin/inertia/lib/classNames.ts`

### getBarColor (function)
- Defined: `admin/inertia/components/HorizontalBarChart.tsx:26`
- Depends on: `admin/inertia/lib/classNames.ts`

### getGlowColor (function)
- Defined: `admin/inertia/components/HorizontalBarChart.tsx:34`
- Depends on: `admin/inertia/lib/classNames.ts`

### getStatusLabel (function)
- Defined: `admin/inertia/components/HorizontalBarChart.tsx:41`
- Depends on: `admin/inertia/lib/classNames.ts`

### getStatusColor (function)
- Defined: `admin/inertia/components/HorizontalBarChart.tsx:51`
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/InfoTooltip.tsx

### InfoTooltip (function)
- Defined: `admin/inertia/components/InfoTooltip.tsx:9`

## admin/inertia/components/KbGuardrailModal.tsx

### KbGuardrailModal (function)
- Defined: `admin/inertia/components/KbGuardrailModal.tsx:22`

## admin/inertia/components/MarkdocRenderer.tsx

### Paragraph (function)
- Defined: `admin/inertia/components/MarkdocRenderer.tsx:10`
- Doc: Paragraph component
- Depends on: `admin/inertia/components/markdoc/Heading.tsx`, `admin/inertia/components/markdoc/Image.tsx`, `admin/inertia/components/markdoc/List.tsx`, `admin/inertia/components/markdoc/ListItem.tsx`, `admin/inertia/components/markdoc/Table.tsx`

### Link (function)
- Defined: `admin/inertia/components/MarkdocRenderer.tsx:15`
- Doc: Link component
- Depends on: `admin/inertia/components/markdoc/Heading.tsx`, `admin/inertia/components/markdoc/Image.tsx`, `admin/inertia/components/markdoc/List.tsx`, `admin/inertia/components/markdoc/ListItem.tsx`, `admin/inertia/components/markdoc/Table.tsx`

### InlineCode (function)
- Defined: `admin/inertia/components/MarkdocRenderer.tsx:38`
- Doc: Inline code component
- Depends on: `admin/inertia/components/markdoc/Heading.tsx`, `admin/inertia/components/markdoc/Image.tsx`, `admin/inertia/components/markdoc/List.tsx`, `admin/inertia/components/markdoc/ListItem.tsx`, `admin/inertia/components/markdoc/Table.tsx`

### CodeBlock (function)
- Defined: `admin/inertia/components/MarkdocRenderer.tsx:47`
- Doc: Code block component
- Depends on: `admin/inertia/components/markdoc/Heading.tsx`, `admin/inertia/components/markdoc/Image.tsx`, `admin/inertia/components/markdoc/List.tsx`, `admin/inertia/components/markdoc/ListItem.tsx`, `admin/inertia/components/markdoc/Table.tsx`

### HorizontalRule (function)
- Defined: `admin/inertia/components/MarkdocRenderer.tsx:74`
- Doc: Horizontal rule component
- Depends on: `admin/inertia/components/markdoc/Heading.tsx`, `admin/inertia/components/markdoc/Image.tsx`, `admin/inertia/components/markdoc/List.tsx`, `admin/inertia/components/markdoc/ListItem.tsx`, `admin/inertia/components/markdoc/Table.tsx`

### Callout (function)
- Defined: `admin/inertia/components/MarkdocRenderer.tsx:81`
- Doc: Callout component
- Depends on: `admin/inertia/components/markdoc/Heading.tsx`, `admin/inertia/components/markdoc/Image.tsx`, `admin/inertia/components/markdoc/List.tsx`, `admin/inertia/components/markdoc/ListItem.tsx`, `admin/inertia/components/markdoc/Table.tsx`

## admin/inertia/components/ProgressBar.tsx

### ProgressBar (function)
- Defined: `admin/inertia/components/ProgressBar.tsx:1`

## admin/inertia/components/StorageProjectionBar.tsx

### StorageProjectionBar (function)
- Defined: `admin/inertia/components/StorageProjectionBar.tsx:11`
- Depends on: `admin/inertia/lib/classNames.ts`

### currentPercent (function)
- Defined: `admin/inertia/components/StorageProjectionBar.tsx:17`
- Depends on: `admin/inertia/lib/classNames.ts`

### projectedPercent (function)
- Defined: `admin/inertia/components/StorageProjectionBar.tsx:18`
- Depends on: `admin/inertia/lib/classNames.ts`

### projectedTotalPercent (function)
- Defined: `admin/inertia/components/StorageProjectionBar.tsx:19`
- Depends on: `admin/inertia/lib/classNames.ts`

### getProjectedColor (function)
- Defined: `admin/inertia/components/StorageProjectionBar.tsx:24`
- Doc: Determine warning level based on projected total
- Depends on: `admin/inertia/lib/classNames.ts`

### getProjectedGlow (function)
- Defined: `admin/inertia/components/StorageProjectionBar.tsx:31`
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/StyledButton.tsx

### getIconSize (function)
- Defined: `admin/inertia/components/StyledButton.tsx:30`

### getSizeClasses (function)
- Defined: `admin/inertia/components/StyledButton.tsx:41`

### getVariantClasses (function)
- Defined: `admin/inertia/components/StyledButton.tsx:52`

### getLoadingSpinner (function)
- Defined: `admin/inertia/components/StyledButton.tsx:131`

### onClickHandler (function)
- Defined: `admin/inertia/components/StyledButton.tsx:140`

## admin/inertia/components/StyledSectionHeader.tsx

### StyledSectionHeader (function)
- Defined: `admin/inertia/components/StyledSectionHeader.tsx:10`

## admin/inertia/components/StyledSidebar.tsx

### ListItem (function)
- Defined: `admin/inertia/components/StyledSidebar.tsx:34`
- Depends on: `admin/inertia/lib/classNames.ts`, `admin/types/system.ts`

### content (function)
- Defined: `admin/inertia/components/StyledSidebar.tsx:41`
- Depends on: `admin/inertia/lib/classNames.ts`, `admin/types/system.ts`

### Sidebar (function)
- Defined: `admin/inertia/components/StyledSidebar.tsx:62`
- Depends on: `admin/inertia/lib/classNames.ts`, `admin/types/system.ts`

## admin/inertia/components/StyledTable.tsx

### StyledTable (function)
- Defined: `admin/inertia/components/StyledTable.tsx:33`
- Depends on: `admin/inertia/lib/classNames.ts`

### isRowExpanded (function)
- Defined: `admin/inertia/components/StyledTable.tsx:59`
- Depends on: `admin/inertia/lib/classNames.ts`

### toggleRowExpansion (function)
- Defined: `admin/inertia/components/StyledTable.tsx:64`
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/ThemeToggle.tsx

### ThemeToggle (function)
- Defined: `admin/inertia/components/ThemeToggle.tsx:8`
- Depends on: `admin/inertia/providers/ThemeProvider.tsx`

## admin/inertia/components/TierSelectionModal.tsx

### resourceFilename (function)
- Defined: `admin/inertia/components/TierSelectionModal.tsx:21`
- Depends on: `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/inertia/lib/kb_guardrail.ts`

### getAllResourcesForTier (function)
- Defined: `admin/inertia/components/TierSelectionModal.tsx:55`
- Doc: Get all resources for a tier (including inherited resources). Defined as a hook-safe closure (always callable, returns [
- Depends on: `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/inertia/lib/kb_guardrail.ts`

### getTierTotalSize (function)
- Defined: `admin/inertia/components/TierSelectionModal.tsx:116`
- Depends on: `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/inertia/lib/kb_guardrail.ts`

### handleTierClick (function)
- Defined: `admin/inertia/components/TierSelectionModal.tsx:120`
- Depends on: `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/inertia/lib/kb_guardrail.ts`

### finalizeSubmit (function)
- Defined: `admin/inertia/components/TierSelectionModal.tsx:134`
- Doc: Runs the original onSelectTier-then-onClose flow. Pulled out of handleSubmit so the guardrail modal's confirm path can c
- Depends on: `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/inertia/lib/kb_guardrail.ts`

### handleSubmit (function)
- Defined: `admin/inertia/components/TierSelectionModal.tsx:143`
- Depends on: `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/inertia/lib/kb_guardrail.ts`

## admin/inertia/components/UpdateServiceModal.tsx

### UpdateServiceModal (function)
- Defined: `admin/inertia/components/UpdateServiceModal.tsx:17`
- Depends on: `admin/app/utils/version.ts`, `admin/types/services.ts`

### loadVersions (function)
- Defined: `admin/inertia/components/UpdateServiceModal.tsx:30`
- Depends on: `admin/app/utils/version.ts`, `admin/types/services.ts`

### handleToggleAdvanced (function)
- Defined: `admin/inertia/components/UpdateServiceModal.tsx:45`
- Depends on: `admin/app/utils/version.ts`, `admin/types/services.ts`

## admin/inertia/components/chat/ChatAssistantAvatar.tsx

### ChatAssistantAvatar (function)
- Defined: `admin/inertia/components/chat/ChatAssistantAvatar.tsx:3`

## admin/inertia/components/chat/ChatButton.tsx

### ChatButton (function)
- Defined: `admin/inertia/components/chat/ChatButton.tsx:7`

## admin/inertia/components/chat/ChatInterface.tsx

### ChatInterface (function)
- Defined: `admin/inertia/components/chat/ChatInterface.tsx:24`
- Depends on: `admin/constants/ollama.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/chat.ts`

### handleDownloadModel (function)
- Defined: `admin/inertia/components/chat/ChatInterface.tsx:41`
- Depends on: `admin/constants/ollama.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/chat.ts`

### scrollToBottom (function)
- Defined: `admin/inertia/components/chat/ChatInterface.tsx:54`
- Depends on: `admin/constants/ollama.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/chat.ts`

### handleSubmit (function)
- Defined: `admin/inertia/components/chat/ChatInterface.tsx:62`
- Depends on: `admin/constants/ollama.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/chat.ts`

### handleKeyDown (function)
- Defined: `admin/inertia/components/chat/ChatInterface.tsx:73`
- Depends on: `admin/constants/ollama.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/chat.ts`

### handleInput (function)
- Defined: `admin/inertia/components/chat/ChatInterface.tsx:80`
- Depends on: `admin/constants/ollama.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/chat.ts`

## admin/inertia/components/chat/ChatMessageBubble.tsx

### ChatMessageBubble (function)
- Defined: `admin/inertia/components/chat/ChatMessageBubble.tsx:10`
- Depends on: `admin/inertia/lib/classNames.ts`, `admin/types/chat.ts`

## admin/inertia/components/chat/ChatModal.tsx

### ChatModal (function)
- Defined: `admin/inertia/components/chat/ChatModal.tsx:11`
- Depends on: `admin/app/utils/misc.ts`, `admin/inertia/hooks/useSystemSetting.ts`

## admin/inertia/components/chat/ChatSidebar.tsx

### ChatSidebar (function)
- Defined: `admin/inertia/components/chat/ChatSidebar.tsx:18`
- Depends on: `admin/inertia/lib/classNames.ts`, `admin/types/chat.ts`

### handleCloseKnowledgeBase (function)
- Defined: `admin/inertia/components/chat/ChatSidebar.tsx:31`
- Depends on: `admin/inertia/lib/classNames.ts`, `admin/types/chat.ts`

## admin/inertia/components/chat/KbPolicyPromptBanner.tsx

### KbPolicyPromptBanner (function)
- Defined: `admin/inertia/components/chat/KbPolicyPromptBanner.tsx:27`
- Doc: (`rag.defaultIngestPolicy` unset). Two buttons let the user decide once, after which the prompt never returns:  - "Index
- Depends on: `admin/inertia/context/NotificationContext.ts`

## admin/inertia/components/chat/KnowledgeBaseModal.tsx

### renderStatePill (function)
- Defined: `admin/inertia/components/chat/KnowledgeBaseModal.tsx:32`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/kb_file_grouping.ts`

### pickRowAction (function)
- Defined: `admin/inertia/components/chat/KnowledgeBaseModal.tsx:77`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/kb_file_grouping.ts`

### KnowledgeBaseModal (function)
- Defined: `admin/inertia/components/chat/KnowledgeBaseModal.tsx:96`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/kb_file_grouping.ts`

### handleUpload (function)
- Defined: `admin/inertia/components/chat/KnowledgeBaseModal.tsx:282`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/kb_file_grouping.ts`

### handleConfirmSync (function)
- Defined: `admin/inertia/components/chat/KnowledgeBaseModal.tsx:313`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/kb_file_grouping.ts`

## admin/inertia/components/chat/index.tsx

### Chat (function)
- Defined: `admin/inertia/components/chat/index.tsx:24`
- Depends on: `admin/constants/ollama.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/chat.ts`

## admin/inertia/components/inputs/Switch.tsx

### Switch (function)
- Defined: `admin/inertia/components/inputs/Switch.tsx:12`

## admin/inertia/components/layout/BackToHomeHeader.tsx

### BackToHomeHeader (function)
- Defined: `admin/inertia/components/layout/BackToHomeHeader.tsx:10`

## admin/inertia/components/maps/CoordinateOverlay.tsx

### CoordinateOverlay (function)
- Defined: `admin/inertia/components/maps/CoordinateOverlay.tsx:8`

## admin/inertia/components/maps/MapComponent.tsx

### MapComponent (function)
- Defined: `admin/inertia/components/maps/MapComponent.tsx:31`
- Depends on: `admin/inertia/hooks/useMapMarkers.ts`

## admin/inertia/components/maps/MarkerPanel.tsx

### MarkerPanel (function)
- Defined: `admin/inertia/components/maps/MarkerPanel.tsx:14`
- Depends on: `admin/inertia/hooks/useMapMarkers.ts`

## admin/inertia/components/maps/MarkerPin.tsx

### MarkerPin (function)
- Defined: `admin/inertia/components/maps/MarkerPin.tsx:8`

## admin/inertia/components/maps/ScaleUnitToggle.tsx

### ScaleUnitToggle (function)
- Defined: `admin/inertia/components/maps/ScaleUnitToggle.tsx:9`

## admin/inertia/components/markdoc/Heading.tsx

### Heading (function)
- Defined: `admin/inertia/components/markdoc/Heading.tsx:3`
- Imported by: `admin/inertia/components/MarkdocRenderer.tsx`

## admin/inertia/components/markdoc/Image.tsx

### Image (function)
- Defined: `admin/inertia/components/markdoc/Image.tsx:1`
- Imported by: `admin/inertia/components/MarkdocRenderer.tsx`

## admin/inertia/components/markdoc/List.tsx

### List (function)
- Defined: `admin/inertia/components/markdoc/List.tsx:1`
- Imported by: `admin/inertia/components/MarkdocRenderer.tsx`

## admin/inertia/components/markdoc/ListItem.tsx

### ListItem (function)
- Defined: `admin/inertia/components/markdoc/ListItem.tsx:1`
- Imported by: `admin/inertia/components/MarkdocRenderer.tsx`

## admin/inertia/components/markdoc/Table.tsx

### Table (function)
- Defined: `admin/inertia/components/markdoc/Table.tsx:1`
- Imported by: `admin/inertia/components/MarkdocRenderer.tsx`

### TableHead (function)
- Defined: `admin/inertia/components/markdoc/Table.tsx:11`
- Imported by: `admin/inertia/components/MarkdocRenderer.tsx`

### TableBody (function)
- Defined: `admin/inertia/components/markdoc/Table.tsx:15`
- Imported by: `admin/inertia/components/MarkdocRenderer.tsx`

### TableRow (function)
- Defined: `admin/inertia/components/markdoc/Table.tsx:19`
- Imported by: `admin/inertia/components/MarkdocRenderer.tsx`

### TableHeader (function)
- Defined: `admin/inertia/components/markdoc/Table.tsx:23`
- Imported by: `admin/inertia/components/MarkdocRenderer.tsx`

### TableCell (function)
- Defined: `admin/inertia/components/markdoc/Table.tsx:31`
- Imported by: `admin/inertia/components/MarkdocRenderer.tsx`

## admin/inertia/components/systeminfo/CircularGauge.tsx

### CircularGauge (function)
- Defined: `admin/inertia/components/systeminfo/CircularGauge.tsx:14`
- Depends on: `admin/inertia/lib/classNames.ts`

### getColor (function)
- Defined: `admin/inertia/components/systeminfo/CircularGauge.tsx:63`
- Depends on: `admin/inertia/lib/classNames.ts`

### angle (function)
- Defined: `admin/inertia/components/systeminfo/CircularGauge.tsx:118`
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/systeminfo/InfoCard.tsx

### InfoCard (function)
- Defined: `admin/inertia/components/systeminfo/InfoCard.tsx:13`
- Depends on: `admin/inertia/lib/classNames.ts`

### getVariantStyles (function)
- Defined: `admin/inertia/components/systeminfo/InfoCard.tsx:14`
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/systeminfo/StatusCard.tsx

### StatusCard (function)
- Defined: `admin/inertia/components/systeminfo/StatusCard.tsx:6`

## admin/inertia/context/ModalContext.ts

### useModals (function)
- Defined: `admin/inertia/context/ModalContext.ts:13`
- Imported by: `admin/inertia/components/ActiveModelDownloads.tsx`, `admin/inertia/components/chat/KnowledgeBaseModal.tsx`, `admin/inertia/components/chat/index.tsx`, `admin/inertia/pages/settings/apps.tsx`, `admin/inertia/pages/settings/maps.tsx`, `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/system.tsx`, `admin/inertia/pages/settings/zim/index.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`, `admin/inertia/providers/ModalProvider.tsx`

## admin/inertia/context/NotificationContext.ts

### useNotifications (function)
- Defined: `admin/inertia/context/NotificationContext.ts:20`
- Imported by: `admin/inertia/components/chat/ChatInterface.tsx`, `admin/inertia/components/chat/KbPolicyPromptBanner.tsx`, `admin/inertia/components/chat/KnowledgeBaseModal.tsx`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/lib/util.ts`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/settings/maps.tsx`, `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/system.tsx`, `admin/inertia/pages/settings/update.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`, `admin/inertia/providers/NotificationProvider.tsx`

## admin/inertia/hooks/useDebounce.ts

### useDebounce (function)
- Defined: `admin/inertia/hooks/useDebounce.ts:3`
- Imported by: `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`

### debounce (function)
- Defined: `admin/inertia/hooks/useDebounce.ts:6`
- Imported by: `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`

## admin/inertia/hooks/useDiskDisplayData.ts

### getAllDiskDisplayItems (function)
- Defined: `admin/inertia/hooks/useDiskDisplayData.ts:16`
- Doc: import { Systeminformation } from 'systeminformation' import { formatBytes } from '~/lib/util' type DiskDisplayItem = { 
- Depends on: `admin/types/system.ts`
- Imported by: `admin/inertia/components/TierSelectionModal.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/settings/system.tsx`

### getPrimaryDiskInfo (function)
- Defined: `admin/inertia/hooks/useDiskDisplayData.ts:88`
- Doc: value: fs.use || 0, total: formatBytes(fs.size), used: formatBytes(fs.used), subtext: `${formatBytes(fs.used)} / ${forma
- Depends on: `admin/types/system.ts`
- Imported by: `admin/inertia/components/TierSelectionModal.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/settings/system.tsx`

## admin/inertia/hooks/useDownloads.ts

### useDownloads (function)
- Defined: `admin/inertia/hooks/useDownloads.ts:10`
- Imported by: `admin/inertia/components/ActiveDownloads.tsx`, `admin/inertia/pages/settings/maps.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`

### invalidate (function)
- Defined: `admin/inertia/hooks/useDownloads.ts:29`
- Imported by: `admin/inertia/components/ActiveDownloads.tsx`, `admin/inertia/pages/settings/maps.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`

## admin/inertia/hooks/useEmbedJobs.ts

### useEmbedJobs (function)
- Defined: `admin/inertia/hooks/useEmbedJobs.ts:5`
- Imported by: `admin/inertia/components/ActiveEmbedJobs.tsx`

### invalidate (function)
- Defined: `admin/inertia/hooks/useEmbedJobs.ts:29`
- Imported by: `admin/inertia/components/ActiveEmbedJobs.tsx`

## admin/inertia/hooks/useErrorNotification.ts

### useErrorNotification (function)
- Defined: `admin/inertia/hooks/useErrorNotification.ts:4`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/pages/settings/apps.tsx`

### showError (function)
- Defined: `admin/inertia/hooks/useErrorNotification.ts:7`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/pages/settings/apps.tsx`

## admin/inertia/hooks/useInternetStatus.ts

### useInternetStatus (function)
- Defined: `admin/inertia/hooks/useInternetStatus.ts:6`
- Imported by: `admin/inertia/pages/easy-setup/complete.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/settings/apps.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`

## admin/inertia/hooks/useMapMarkers.ts

### useMapMarkers (function)
- Defined: `admin/inertia/hooks/useMapMarkers.ts:25`
- Imported by: `admin/inertia/components/maps/MapComponent.tsx`, `admin/inertia/components/maps/MapComponent.tsx`, `admin/inertia/components/maps/MarkerPanel.tsx`

## admin/inertia/hooks/useMapRegionFiles.ts

### useMapRegionFiles (function)
- Defined: `admin/inertia/hooks/useMapRegionFiles.ts:5`
- Depends on: `admin/types/files.ts`

## admin/inertia/hooks/useOllamaModelDownloads.ts

### useOllamaModelDownloads (function)
- Defined: `admin/inertia/hooks/useOllamaModelDownloads.ts:25`
- Imported by: `admin/inertia/components/ActiveModelDownloads.tsx`

## admin/inertia/hooks/useServiceInstallationActivity.ts

### useServiceInstallationActivity (function)
- Defined: `admin/inertia/hooks/useServiceInstallationActivity.ts:6`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/components/InstallActivityFeed.tsx`
- Imported by: `admin/inertia/pages/easy-setup/complete.tsx`, `admin/inertia/pages/settings/apps.tsx`

## admin/inertia/hooks/useServiceInstalledStatus.tsx

### useServiceInstalledStatus (function)
- Defined: `admin/inertia/hooks/useServiceInstalledStatus.tsx:5`
- Depends on: `admin/types/services.ts`
- Imported by: `admin/inertia/layouts/AppLayout.tsx`, `admin/inertia/layouts/SettingsLayout.tsx`, `admin/inertia/pages/settings/benchmark.tsx`, `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/zim/index.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`

## admin/inertia/hooks/useSystemInfo.ts

### useSystemInfo (function)
- Defined: `admin/inertia/hooks/useSystemInfo.ts:10`
- Depends on: `admin/types/system.ts`
- Imported by: `admin/inertia/components/TierSelectionModal.tsx`, `admin/inertia/components/TierSelectionModal.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/system.tsx`, `admin/inertia/pages/settings/system.tsx`

## admin/inertia/hooks/useSystemSetting.ts

### useSystemSetting (function)
- Defined: `admin/inertia/hooks/useSystemSetting.ts:12`
- Depends on: `admin/types/kv_store.ts`
- Imported by: `admin/inertia/components/chat/ChatModal.tsx`, `admin/inertia/components/chat/ChatModal.tsx`, `admin/inertia/components/chat/index.tsx`, `admin/inertia/components/chat/index.tsx`, `admin/inertia/components/chat/index.tsx`, `admin/inertia/pages/home.tsx`, `admin/inertia/pages/home.tsx`, `admin/inertia/pages/settings/update.tsx`, `admin/inertia/pages/settings/update.tsx`

## admin/inertia/hooks/useTheme.ts

### getInitialTheme (function)
- Defined: `admin/inertia/hooks/useTheme.ts:7`
- Imported by: `admin/inertia/providers/ThemeProvider.tsx`, `admin/inertia/providers/ThemeProvider.tsx`

### useTheme (function)
- Defined: `admin/inertia/hooks/useTheme.ts:16`
- Imported by: `admin/inertia/providers/ThemeProvider.tsx`, `admin/inertia/providers/ThemeProvider.tsx`

## admin/inertia/hooks/useUpdateAvailable.ts

### useUpdateAvailable (function)
- Defined: `admin/inertia/hooks/useUpdateAvailable.ts:6`
- Depends on: `admin/types/system.ts`
- Imported by: `admin/inertia/pages/home.tsx`, `admin/inertia/pages/home.tsx`

## admin/inertia/layouts/AppLayout.tsx

### AppLayout (function)
- Defined: `admin/inertia/layouts/AppLayout.tsx:11`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/lib/classNames.ts`

## admin/inertia/layouts/DocsLayout.tsx

### DocsLayout (function)
- Defined: `admin/inertia/layouts/DocsLayout.tsx:6`

## admin/inertia/layouts/MapsLayout.tsx

### MapsLayout (function)
- Defined: `admin/inertia/layouts/MapsLayout.tsx:3`

## admin/inertia/layouts/SettingsLayout.tsx

### SettingsLayout (function)
- Defined: `admin/inertia/layouts/SettingsLayout.tsx:20`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/lib/navigation.ts`

## admin/inertia/lib/classNames.ts

### classNames (function)
- Defined: `admin/inertia/lib/classNames.ts:2`
- Imported by: `admin/inertia/components/Alert.tsx`, `admin/inertia/components/Alert.tsx`, `admin/inertia/components/Alert.tsx`, `admin/inertia/components/Alert.tsx`, `admin/inertia/components/Alert.tsx`, `admin/inertia/components/Alert.tsx`, `admin/inertia/components/Alert.tsx`, `admin/inertia/components/CountryPickerModal.tsx`, `admin/inertia/components/CountryPickerModal.tsx`, `admin/inertia/components/CountryPickerModal.tsx`, `admin/inertia/components/DynamicIcon.tsx`, `admin/inertia/components/HorizontalBarChart.tsx`, `admin/inertia/components/HorizontalBarChart.tsx`, `admin/inertia/components/HorizontalBarChart.tsx`, `admin/inertia/components/InstallActivityFeed.tsx`, `admin/inertia/components/InstallActivityFeed.tsx`, `admin/inertia/components/StorageProjectionBar.tsx`, `admin/inertia/components/StorageProjectionBar.tsx`, `admin/inertia/components/StorageProjectionBar.tsx`, `admin/inertia/components/StyledModal.tsx`, `admin/inertia/components/StyledModal.tsx`, `admin/inertia/components/StyledSidebar.tsx`, `admin/inertia/components/StyledTable.tsx`, `admin/inertia/components/StyledTable.tsx`, `admin/inertia/components/StyledTable.tsx`, `admin/inertia/components/StyledTable.tsx`, `admin/inertia/components/StyledTable.tsx`, `admin/inertia/components/StyledTable.tsx`, `admin/inertia/components/TierSelectionModal.tsx`, `admin/inertia/components/TierSelectionModal.tsx`, `admin/inertia/components/WikipediaSelector.tsx`, `admin/inertia/components/WikipediaSelector.tsx`, `admin/inertia/components/WikipediaSelector.tsx`, `admin/inertia/components/chat/ChatInterface.tsx`, `admin/inertia/components/chat/ChatInterface.tsx`, `admin/inertia/components/chat/ChatMessageBubble.tsx`, `admin/inertia/components/chat/ChatMessageBubble.tsx`, `admin/inertia/components/chat/ChatSidebar.tsx`, `admin/inertia/components/chat/ChatSidebar.tsx`, `admin/inertia/components/chat/ChatSidebar.tsx`, `admin/inertia/components/chat/index.tsx`, `admin/inertia/components/chat/index.tsx`, `admin/inertia/components/inputs/Input.tsx`, `admin/inertia/components/inputs/Input.tsx`, `admin/inertia/components/inputs/Input.tsx`, `admin/inertia/components/systeminfo/CircularGauge.tsx`, `admin/inertia/components/systeminfo/CircularGauge.tsx`, `admin/inertia/components/systeminfo/CircularGauge.tsx`, `admin/inertia/components/systeminfo/InfoCard.tsx`, `admin/inertia/components/systeminfo/InfoCard.tsx`, `admin/inertia/layouts/AppLayout.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`

## admin/inertia/lib/collections.ts

### resolveTierResources (function)
- Defined: `admin/inertia/lib/collections.ts:7`
- Doc: Resolve all resources for a tier, including inherited resources from includesTier chain. Shared between frontend compone

### resolveTierResourcesInner (function)
- Defined: `admin/inertia/lib/collections.ts:11`

## admin/inertia/lib/global_map_banner.ts

### hasDownloadedGlobalMap (function)
- Defined: `admin/inertia/lib/global_map_banner.ts:1`
- Imported by: `admin/inertia/pages/settings/maps.tsx`, `admin/tests/unit/global_map_banner.spec.ts`

## admin/inertia/lib/kb_file_grouping.ts

### classifyKbFile (function)
- Defined: `admin/inertia/lib/kb_file_grouping.ts:21`
- Depends on: `admin/util/docs.ts`
- Imported by: `admin/inertia/components/chat/KnowledgeBaseModal.tsx`, `admin/tests/unit/kb_file_grouping.spec.ts`

### sourceToDisplayName (function)
- Defined: `admin/inertia/lib/kb_file_grouping.ts:34`
- Depends on: `admin/util/docs.ts`
- Imported by: `admin/inertia/components/chat/KnowledgeBaseModal.tsx`, `admin/tests/unit/kb_file_grouping.spec.ts`

### groupAndSortKbFiles (function)
- Defined: `admin/inertia/lib/kb_file_grouping.ts:67`
- Doc: Group stored-file rows into table rows for the Stored Files panel.  - Admin docs (`/app/docs/*`, README) collapse into a
- Depends on: `admin/util/docs.ts`
- Imported by: `admin/inertia/components/chat/KnowledgeBaseModal.tsx`, `admin/tests/unit/kb_file_grouping.spec.ts`

## admin/inertia/lib/kb_guardrail.ts

### evaluateGuardrail (function)
- Defined: `admin/inertia/lib/kb_guardrail.ts:47`
- Doc: Decide whether a bulk indexing action should be gated behind the guardrail modal. Caller passes the precomputed embeddin
- Imported by: `admin/inertia/components/TierSelectionModal.tsx`, `admin/tests/unit/kb_guardrail.spec.ts`

## admin/inertia/lib/kb_job_health_display.ts

### formatTimeAgo (function)
- Defined: `admin/inertia/lib/kb_job_health_display.ts:45`
- Doc: Format a relative timestamp as "Xs ago", "Xm ago", "Xh ago" with sensible thresholds for the KB Processing Queue's "Last
- Depends on: `admin/app/utils/kb_job_health.ts`
- Imported by: `admin/inertia/components/ActiveEmbedJobs.tsx`

### computeJobHealthNow (function)
- Defined: `admin/inertia/lib/kb_job_health_display.ts:59`
- Doc: Convenience wrapper that resolves a job's health status without the caller having to remember to pass `now`. Mostly for 
- Depends on: `admin/app/utils/kb_job_health.ts`
- Imported by: `admin/inertia/components/ActiveEmbedJobs.tsx`

## admin/inertia/lib/navigation.ts

### getServiceLink (function)
- Defined: `admin/inertia/lib/navigation.ts:3`
- Imported by: `admin/inertia/layouts/SettingsLayout.tsx`, `admin/inertia/pages/home.tsx`, `admin/inertia/pages/settings/apps.tsx`

## admin/inertia/lib/util.ts

### setGlobalNotificationCallback (function)
- Defined: `admin/inertia/lib/util.ts:6`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### capitalizeFirstLetter (function)
- Defined: `admin/inertia/lib/util.ts:10`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### formatBytes (function)
- Defined: `admin/inertia/lib/util.ts:15`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### generateRandomString (function)
- Defined: `admin/inertia/lib/util.ts:24`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### generateUUID (function)
- Defined: `admin/inertia/lib/util.ts:33`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### that (function)
- Defined: `admin/inertia/lib/util.ts:69`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### to (function)
- Defined: `admin/inertia/lib/util.ts:69`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### to (function)
- Defined: `admin/inertia/lib/util.ts:70`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### that (function)
- Defined: `admin/inertia/lib/util.ts:71`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### and (function)
- Defined: `admin/inertia/lib/util.ts:71`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### catchInternal (function)
- Defined: `admin/inertia/lib/util.ts:73`
- Doc: A higher-order function that wraps an asynchronous function to catch and log internal errors. @param fn The asynchronous
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### extractFileName (function)
- Defined: `admin/inertia/lib/util.ts:57`
- Doc: Extracts the file name from a given path while handling both forward and backward slashes. @param path The full file pat
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

## admin/inertia/pages/about.tsx

### About (function)
- Defined: `admin/inertia/pages/about.tsx:3`

## admin/inertia/pages/chat.tsx

### Chat (function)
- Defined: `admin/inertia/pages/chat.tsx:4`

## admin/inertia/pages/docs/show.tsx

### Show (function)
- Defined: `admin/inertia/pages/docs/show.tsx:5`
- Imported by: `admin/app/controllers/benchmark_controller.ts`, `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/docs_controller.ts`

## admin/inertia/pages/easy-setup/complete.tsx

### EasySetupWizardComplete (function)
- Defined: `admin/inertia/pages/easy-setup/complete.tsx:11`
- Depends on: `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`
- Imported by: `admin/app/controllers/easy_setup_controller.ts`

## admin/inertia/pages/easy-setup/index.tsx

### buildCoreCapabilities (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:35`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### EasySetupWizard (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:115`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### toggleMapCollection (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:215`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### toggleAiModel (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:221`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### handleCategoryClick (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:228`
- Doc: Category/tier handlers
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### handleTierSelect (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:234`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### closeTierModal (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:247`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### getSelectedTierResources (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:253`
- Doc: Get all resources from selected tiers for storage projection
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### unit (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:293`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### canProceedToNextStep (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:334`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### handleNext (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:340`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### handleBack (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:347`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### handleFinish (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:354`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### msg (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:385`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### markAsVisited (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:460`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### renderStepIndicator (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:472`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### isCapabilitySelected (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:562`
- Doc: Check if a capability is selected (all its services are in selectedServices)
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### isCapabilityInstalled (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:567`
- Doc: Check if a capability is already installed (all its services are installed)
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### capabilityExists (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:574`
- Doc: Check if a capability exists in the system (has at least one matching service)
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### toggleCapability (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:581`
- Doc: Toggle all services for a capability (only if not already installed)
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### renderCapabilityCard (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:621`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### renderStep1 (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:723`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### renderStep2 (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:843`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### renderStep3 (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:889`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### renderStep4 (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:991`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### renderStep5 (function)
- Defined: `admin/inertia/pages/easy-setup/index.tsx:1134`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

## admin/inertia/pages/errors/not_found.tsx

### NotFound (function)
- Defined: `admin/inertia/pages/errors/not_found.tsx:1`

## admin/inertia/pages/errors/server_error.tsx

### ServerError (function)
- Defined: `admin/inertia/pages/errors/server_error.tsx:1`

## admin/inertia/pages/home.tsx

### Home (function)
- Defined: `admin/inertia/pages/home.tsx:87`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/hooks/useSystemSetting.ts`, `admin/inertia/hooks/useUpdateAvailable.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/home_controller.ts`

### tileContent (function)
- Defined: `admin/inertia/pages/home.tsx:160`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/hooks/useSystemSetting.ts`, `admin/inertia/hooks/useUpdateAvailable.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/home_controller.ts`

## admin/inertia/pages/maps.tsx

### Maps (function)
- Defined: `admin/inertia/pages/maps.tsx:12`
- Depends on: `admin/types/files.ts`

## admin/inertia/pages/settings/apps.tsx

### extractTag (function)
- Defined: `admin/inertia/pages/settings/apps.tsx:20`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### SettingsPage (function)
- Defined: `admin/inertia/pages/settings/apps.tsx:27`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleCheckUpdates (function)
- Defined: `admin/inertia/pages/settings/apps.tsx:60`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### installService (function)
- Defined: `admin/inertia/pages/settings/apps.tsx:103`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleAffectAction (function)
- Defined: `admin/inertia/pages/settings/apps.tsx:126`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleForceReinstall (function)
- Defined: `admin/inertia/pages/settings/apps.tsx:149`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleUpdateService (function)
- Defined: `admin/inertia/pages/settings/apps.tsx:172`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleInstallService (function)
- Defined: `admin/inertia/pages/settings/apps.tsx:78`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### AppActions (function)
- Defined: `admin/inertia/pages/settings/apps.tsx:202`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### ForceReinstallButton (function)
- Defined: `admin/inertia/pages/settings/apps.tsx:203`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

## admin/inertia/pages/settings/benchmark.tsx

### BenchmarkPage (function)
- Defined: `admin/inertia/pages/settings/benchmark.tsx:30`
- Depends on: `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/benchmark.ts`

### handleFullBenchmarkClick (function)
- Defined: `admin/inertia/pages/settings/benchmark.tsx:198`
- Doc: Handle Full Benchmark click with pre-flight check
- Depends on: `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/benchmark.ts`

### advanceStage (function)
- Defined: `admin/inertia/pages/settings/benchmark.tsx:277`
- Depends on: `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/benchmark.ts`

### formatBytes (function)
- Defined: `admin/inertia/pages/settings/benchmark.tsx:321`
- Depends on: `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/benchmark.ts`

### getScoreColor (function)
- Defined: `admin/inertia/pages/settings/benchmark.tsx:326`
- Depends on: `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/benchmark.ts`

### getProgressPercent (function)
- Defined: `admin/inertia/pages/settings/benchmark.tsx:332`
- Depends on: `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/benchmark.ts`

### getAIScore (function)
- Defined: `admin/inertia/pages/settings/benchmark.tsx:353`
- Doc: Calculate AI score from tokens per second (normalized to 0-100) Reference: 30 tok/s = 50 score, 60 tok/s = 100 score
- Depends on: `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/benchmark.ts`

### score (function)
- Defined: `admin/inertia/pages/settings/benchmark.tsx:355`
- Depends on: `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/benchmark.ts`

## admin/inertia/pages/settings/legal.tsx

### LegalPage (function)
- Defined: `admin/inertia/pages/settings/legal.tsx:4`
- Imported by: `admin/app/controllers/settings_controller.ts`

## admin/inertia/pages/settings/maps.tsx

### MapsManager (function)
- Defined: `admin/inertia/pages/settings/maps.tsx:26`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`, `admin/types/files.ts`

### downloadBaseAssets (function)
- Defined: `admin/inertia/pages/settings/maps.tsx:83`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`, `admin/types/files.ts`

### downloadCollection (function)
- Defined: `admin/inertia/pages/settings/maps.tsx:110`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`, `admin/types/files.ts`

### downloadCustomFile (function)
- Defined: `admin/inertia/pages/settings/maps.tsx:123`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`, `admin/types/files.ts`

### deleteFile (function)
- Defined: `admin/inertia/pages/settings/maps.tsx:136`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`, `admin/types/files.ts`

### confirmDeleteFile (function)
- Defined: `admin/inertia/pages/settings/maps.tsx:159`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`, `admin/types/files.ts`

### confirmDownload (function)
- Defined: `admin/inertia/pages/settings/maps.tsx:179`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`, `admin/types/files.ts`

### confirmGlobalMapDownload (function)
- Defined: `admin/inertia/pages/settings/maps.tsx:213`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`, `admin/types/files.ts`

### openCountryPickerModal (function)
- Defined: `admin/inertia/pages/settings/maps.tsx:236`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`, `admin/types/files.ts`

### openDownloadModal (function)
- Defined: `admin/inertia/pages/settings/maps.tsx:254`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`, `admin/types/files.ts`

## admin/inertia/pages/settings/models.tsx

### ModelsPage (function)
- Defined: `admin/inertia/pages/settings/models.tsx:25`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/types/ollama.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleSaveRemoteOllama (function)
- Defined: `admin/inertia/pages/settings/models.tsx:108`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/types/ollama.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleClearRemoteOllama (function)
- Defined: `admin/inertia/pages/settings/models.tsx:125`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/types/ollama.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleForceRefresh (function)
- Defined: `admin/inertia/pages/settings/models.tsx:175`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/types/ollama.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleInstallModel (function)
- Defined: `admin/inertia/pages/settings/models.tsx:183`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/types/ollama.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleDeleteModel (function)
- Defined: `admin/inertia/pages/settings/models.tsx:201`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/types/ollama.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### confirmDeleteModel (function)
- Defined: `admin/inertia/pages/settings/models.tsx:221`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/types/ollama.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleDismissGpuBanner (function)
- Defined: `admin/inertia/pages/settings/models.tsx:48`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/types/ollama.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleForceReinstallOllama (function)
- Defined: `admin/inertia/pages/settings/models.tsx:55`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/types/ollama.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

## admin/inertia/pages/settings/support.tsx

### SupportPage (function)
- Defined: `admin/inertia/pages/settings/support.tsx:5`
- Imported by: `admin/app/controllers/settings_controller.ts`

## admin/inertia/pages/settings/system.tsx

### SettingsPage (function)
- Defined: `admin/inertia/pages/settings/system.tsx:19`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/types/system.ts`

### handleDismissGpuBanner (function)
- Defined: `admin/inertia/pages/settings/system.tsx:37`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/types/system.ts`

### handleForceReinstallOllama (function)
- Defined: `admin/inertia/pages/settings/system.tsx:44`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/types/system.ts`

## admin/inertia/pages/settings/update.tsx

### ContentUpdatesSection (function)
- Defined: `admin/inertia/pages/settings/update.tsx:43`
- Depends on: `admin/app/utils/version.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`, `admin/types/system.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/providers/qdrant_restart_policy_provider.ts`, `admin/providers/qdrant_restart_policy_provider.ts`

### SystemUpdatePage (function)
- Defined: `admin/inertia/pages/settings/update.tsx:260`
- Depends on: `admin/app/utils/version.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`, `admin/types/system.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/providers/qdrant_restart_policy_provider.ts`, `admin/providers/qdrant_restart_policy_provider.ts`

### handleCheck (function)
- Defined: `admin/inertia/pages/settings/update.tsx:52`
- Depends on: `admin/app/utils/version.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`, `admin/types/system.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/providers/qdrant_restart_policy_provider.ts`, `admin/providers/qdrant_restart_policy_provider.ts`

### handleApply (function)
- Defined: `admin/inertia/pages/settings/update.tsx:70`
- Depends on: `admin/app/utils/version.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`, `admin/types/system.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/providers/qdrant_restart_policy_provider.ts`, `admin/providers/qdrant_restart_policy_provider.ts`

### handleApplyAll (function)
- Defined: `admin/inertia/pages/settings/update.tsx:99`
- Depends on: `admin/app/utils/version.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`, `admin/types/system.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/providers/qdrant_restart_policy_provider.ts`, `admin/providers/qdrant_restart_policy_provider.ts`

### handleStartUpdate (function)
- Defined: `admin/inertia/pages/settings/update.tsx:338`
- Depends on: `admin/app/utils/version.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`, `admin/types/system.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/providers/qdrant_restart_policy_provider.ts`, `admin/providers/qdrant_restart_policy_provider.ts`

### handleViewLogs (function)
- Defined: `admin/inertia/pages/settings/update.tsx:353`
- Depends on: `admin/app/utils/version.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`, `admin/types/system.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/providers/qdrant_restart_policy_provider.ts`, `admin/providers/qdrant_restart_policy_provider.ts`

### getProgressBarColor (function)
- Defined: `admin/inertia/pages/settings/update.tsx:394`
- Depends on: `admin/app/utils/version.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`, `admin/types/system.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/providers/qdrant_restart_policy_provider.ts`, `admin/providers/qdrant_restart_policy_provider.ts`

### getStatusIcon (function)
- Defined: `admin/inertia/pages/settings/update.tsx:400`
- Depends on: `admin/app/utils/version.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`, `admin/types/system.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/providers/qdrant_restart_policy_provider.ts`, `admin/providers/qdrant_restart_policy_provider.ts`

## admin/inertia/pages/settings/zim/index.tsx

### ZimPage (function)
- Defined: `admin/inertia/pages/settings/zim/index.tsx:20`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`

### getFiles (function)
- Defined: `admin/inertia/pages/settings/zim/index.tsx:31`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`

### toggleSort (function)
- Defined: `admin/inertia/pages/settings/zim/index.tsx:55`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`

### renderSortHeader (function)
- Defined: `admin/inertia/pages/settings/zim/index.tsx:64`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`

### confirmDeleteFile (function)
- Defined: `admin/inertia/pages/settings/zim/index.tsx:79`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`

### aName (function)
- Defined: `admin/inertia/pages/settings/zim/index.tsx:46`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`

### bName (function)
- Defined: `admin/inertia/pages/settings/zim/index.tsx:47`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`

## admin/inertia/pages/settings/zim/remote-explorer.tsx

### ZimRemoteExplorer (function)
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:54`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`

### confirmDownload (function)
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:238`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`

### confirmCustomDownload (function)
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:263`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`

### downloadFile (function)
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:288`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`

### downloadCustomFile (function)
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:302`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`

### handleSourceChange (function)
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:210`
- Doc: When selecting a custom library, navigate to its root
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`

### navigateToDirectory (function)
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:227`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`

### navigateToBreadcrumb (function)
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:232`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`

### handleCategoryClick (function)
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:323`
- Doc: Category/tier handlers
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`

### handleTierSelect (function)
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:329`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`

### closeTierModal (function)
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:350`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`

### handleWikipediaSelect (function)
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:356`
- Doc: Wikipedia selection handlers
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`

### handleWikipediaSubmit (function)
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:361`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`

## admin/inertia/providers/ModalProvider.tsx

### openModal (function)
- Defined: `admin/inertia/providers/ModalProvider.tsx:12`
- Depends on: `admin/inertia/context/ModalContext.ts`

### closeModal (function)
- Defined: `admin/inertia/providers/ModalProvider.tsx:20`
- Depends on: `admin/inertia/context/ModalContext.ts`

### closeAllModals (function)
- Defined: `admin/inertia/providers/ModalProvider.tsx:31`
- Depends on: `admin/inertia/context/ModalContext.ts`

### _getCurrentModals (function)
- Defined: `admin/inertia/providers/ModalProvider.tsx:36`
- Depends on: `admin/inertia/context/ModalContext.ts`

## admin/inertia/providers/NotificationProvider.tsx

### NotificationsProvider (function)
- Defined: `admin/inertia/providers/NotificationProvider.tsx:6`
- Depends on: `admin/inertia/context/NotificationContext.ts`

### addNotification (function)
- Defined: `admin/inertia/providers/NotificationProvider.tsx:9`
- Depends on: `admin/inertia/context/NotificationContext.ts`

### removeNotification (function)
- Defined: `admin/inertia/providers/NotificationProvider.tsx:29`
- Depends on: `admin/inertia/context/NotificationContext.ts`

### removeAllNotifications (function)
- Defined: `admin/inertia/providers/NotificationProvider.tsx:33`
- Depends on: `admin/inertia/context/NotificationContext.ts`

### Icon (function)
- Defined: `admin/inertia/providers/NotificationProvider.tsx:37`
- Depends on: `admin/inertia/context/NotificationContext.ts`

## admin/inertia/providers/ThemeProvider.tsx

### ThemeProvider (function)
- Defined: `admin/inertia/providers/ThemeProvider.tsx:16`
- Depends on: `admin/inertia/hooks/useTheme.ts`
- Imported by: `admin/inertia/app/app.tsx`, `admin/inertia/components/ThemeToggle.tsx`

### useThemeContext (function)
- Defined: `admin/inertia/providers/ThemeProvider.tsx:25`
- Depends on: `admin/inertia/hooks/useTheme.ts`
- Imported by: `admin/inertia/app/app.tsx`, `admin/inertia/components/ThemeToggle.tsx`

## admin/providers/gpu_passthrough_remediation_provider.ts

### KVStore (function)
- Defined: `admin/providers/gpu_passthrough_remediation_provider.ts:31`

### Docker (function)
- Defined: `admin/providers/gpu_passthrough_remediation_provider.ts:34`

## admin/providers/kiwix_migration_provider.ts

### Service (function)
- Defined: `admin/providers/kiwix_migration_provider.ts:22`

## admin/providers/qdrant_restart_policy_provider.ts

### Service (function)
- Defined: `admin/providers/qdrant_restart_policy_provider.ts:22`
- Depends on: `admin/inertia/pages/settings/update.tsx`

### Docker (function)
- Defined: `admin/providers/qdrant_restart_policy_provider.ts:24`
- Depends on: `admin/inertia/pages/settings/update.tsx`

## admin/providers/version_check_provider.ts

### KVStore (function)
- Defined: `admin/providers/version_check_provider.ts:30`

### cachedLatest (function)
- Defined: `admin/providers/version_check_provider.ts:42`

### earlyAccess (function)
- Defined: `admin/providers/version_check_provider.ts:43`

## admin/tests/bootstrap.ts

### to (function)
- Defined: `admin/tests/bootstrap.ts:18`

## admin/tests/unit/cloud_metadata_url.spec.ts

### expectBlocked (function)
- Defined: `admin/tests/unit/cloud_metadata_url.spec.ts:6`
- Depends on: `admin/app/validators/common.ts`

### expectAllowed (function)
- Defined: `admin/tests/unit/cloud_metadata_url.spec.ts:10`
- Depends on: `admin/app/validators/common.ts`

## admin/tests/unit/kb_file_grouping.spec.ts

### asInfos (function)
- Defined: `admin/tests/unit/kb_file_grouping.spec.ts:15`
- Doc: Wrap source paths into the minimal StoredFileInfo shape that `groupAndSortKbFiles` now expects. State + chunk count are 
- Depends on: `admin/inertia/lib/kb_file_grouping.ts`

## admin/util/docs.ts

### streamToString (function)
- Defined: `admin/util/docs.ts:2`
- Imported by: `admin/app/services/docs_service.ts`, `admin/inertia/lib/kb_file_grouping.ts`, `admin/inertia/lib/kb_file_grouping.ts`

## admin/util/files.ts

### chmodRecursive (function)
- Defined: `admin/util/files.ts:4`

### chownRecursive (function)
- Defined: `admin/util/files.ts:30`

## admin/util/zim.ts

### isRawListRemoteZimFilesResponse (function)
- Defined: `admin/util/zim.ts:3`

### isRawRemoteZimFileEntry (function)
- Defined: `admin/util/zim.ts:21`

## install/install_nomad.sh

### header (function)
- Defined: `install/install_nomad.sh:47`

### header_red (function)
- Defined: `install/install_nomad.sh:52`

### check_has_sudo (function)
- Defined: `install/install_nomad.sh:57`

### check_is_bash (function)
- Defined: `install/install_nomad.sh:69`

### check_is_debian_based (function)
- Defined: `install/install_nomad.sh:79`

### check_is_x86_64 (function)
- Defined: `install/install_nomad.sh:89`

### ensure_dependencies_installed (function)
- Defined: `install/install_nomad.sh:104`

### check_is_debug_mode (function)
- Defined: `install/install_nomad.sh:140`

### generateRandomPass (function)
- Defined: `install/install_nomad.sh:149`

### ensure_docker_installed (function)
- Defined: `install/install_nomad.sh:159`

### check_docker_compose (function)
- Defined: `install/install_nomad.sh:220`

### setup_nvidia_container_toolkit (function)
- Defined: `install/install_nomad.sh:230`

### get_install_confirmation (function)
- Defined: `install/install_nomad.sh:355`

### accept_terms (function)
- Defined: `install/install_nomad.sh:370`

### create_nomad_directory (function)
- Defined: `install/install_nomad.sh:391`

### download_management_compose_file (function)
- Defined: `install/install_nomad.sh:410`

### download_helper_scripts (function)
- Defined: `install/install_nomad.sh:445`

### start_management_containers (function)
- Defined: `install/install_nomad.sh:472`

### get_local_ip (function)
- Defined: `install/install_nomad.sh:481`

### verify_gpu_setup (function)
- Defined: `install/install_nomad.sh:488`

### success_message (function)
- Defined: `install/install_nomad.sh:598`

## install/migrate-disk-collector.sh

### check_is_bash (function)
- Defined: `install/migrate-disk-collector.sh:46`

### check_has_sudo (function)
- Defined: `install/migrate-disk-collector.sh:55`

### check_confirmation (function)
- Defined: `install/migrate-disk-collector.sh:65`

### check_docker_running (function)
- Defined: `install/migrate-disk-collector.sh:81`

### check_compose_file (function)
- Defined: `install/migrate-disk-collector.sh:93`

### stop_old_host_process (function)
- Defined: `install/migrate-disk-collector.sh:103`
- Doc: Step 1: Stop old host process

### backup_compose_file (function)
- Defined: `install/migrate-disk-collector.sh:122`
- Doc: Step 2: Backup compose.yml

### remove_old_bind_mount (function)
- Defined: `install/migrate-disk-collector.sh:134`
- Doc: Step 3: Remove old bind-mount from admin volumes

### add_disk_collector_service (function)
- Defined: `install/migrate-disk-collector.sh:153`
- Doc: Step 4: Add disk-collector service block

### restart_stack (function)
- Defined: `install/migrate-disk-collector.sh:186`
- Doc: Step 5 — Pull new image and restart the full stack This will re-create the admin container and drop the old /tmp bind, a

### verify_disk_collector_running (function)
- Defined: `install/migrate-disk-collector.sh:203`
- Doc: Step 6: Verify

## install/run_updater_fixes.sh

### check_is_bash (function)
- Defined: `install/run_updater_fixes.sh:55`

### check_confirmation (function)
- Defined: `install/run_updater_fixes.sh:64`

### check_has_sudo (function)
- Defined: `install/run_updater_fixes.sh:75`

### check_docker_running (function)
- Defined: `install/run_updater_fixes.sh:85`

### check_compose_file (function)
- Defined: `install/run_updater_fixes.sh:97`

### check_sidecar_dir (function)
- Defined: `install/run_updater_fixes.sh:106`

### backup_compose_file (function)
- Defined: `install/run_updater_fixes.sh:119`

### fix_sidecar_volume_mount (function)
- Defined: `install/run_updater_fixes.sh:130`

### download_updated_sidecar_files (function)
- Defined: `install/run_updater_fixes.sh:153`

### rebuild_sidecar (function)
- Defined: `install/run_updater_fixes.sh:170`

### restart_sidecar (function)
- Defined: `install/run_updater_fixes.sh:179`

### verify_sidecar_running (function)
- Defined: `install/run_updater_fixes.sh:197`

## install/sidecar-disk-collector/collect-disk-info.sh

### log (function)
- Defined: `install/sidecar-disk-collector/collect-disk-info.sh:9`

## install/sidecar-updater/update-watcher.sh

### log (function)
- Defined: `install/sidecar-updater/update-watcher.sh:12`

### write_status (function)
- Defined: `install/sidecar-updater/update-watcher.sh:16`

### perform_update (function)
- Defined: `install/sidecar-updater/update-watcher.sh:31`

### cleanup (function)
- Defined: `install/sidecar-updater/update-watcher.sh:111`

## install/uninstall_nomad.sh

### check_has_sudo (function)
- Defined: `install/uninstall_nomad.sh:27`

### check_current_directory (function)
- Defined: `install/uninstall_nomad.sh:39`

### ensure_management_compose_file_exists (function)
- Defined: `install/uninstall_nomad.sh:46`

### get_uninstall_confirmation (function)
- Defined: `install/uninstall_nomad.sh:53`

### ensure_docker_installed (function)
- Defined: `install/uninstall_nomad.sh:71`

### check_docker_compose (function)
- Defined: `install/uninstall_nomad.sh:78`

### storage_cleanup (function)
- Defined: `install/uninstall_nomad.sh:88`

### uninstall_nomad (function)
- Defined: `install/uninstall_nomad.sh:105`

## install/update_nomad.sh

### check_has_sudo (function)
- Defined: `install/update_nomad.sh:31`

### check_is_bash (function)
- Defined: `install/update_nomad.sh:43`

### check_is_debian_based (function)
- Defined: `install/update_nomad.sh:53`

### get_update_confirmation (function)
- Defined: `install/update_nomad.sh:63`

### ensure_docker_installed_and_running (function)
- Defined: `install/update_nomad.sh:81`

### check_docker_compose (function)
- Defined: `install/update_nomad.sh:97`

### ensure_docker_compose_file_exists (function)
- Defined: `install/update_nomad.sh:107`

### force_recreate (function)
- Defined: `install/update_nomad.sh:114`

### get_local_ip (function)
- Defined: `install/update_nomad.sh:128`

### success_message (function)
- Defined: `install/update_nomad.sh:136`
