# API

## admin/app/controllers/benchmark_controller.ts

### statusCode
- Defined: `admin/app/controllers/benchmark_controller.ts:185`
- Doc: Pass through the status code from the service if available, otherwise default to 400
- Depends on: `admin/app/jobs/run_benchmark_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/validators/settings.ts`, `admin/commands/benchmark/results.ts`, `admin/commands/benchmark/run.ts`, `admin/commands/benchmark/submit.ts`, `admin/inertia/pages/docs/show.tsx`

## admin/app/jobs/embed_file_job.ts

### onProgress
- Defined: `admin/app/jobs/embed_file_job.ts:116`
- Doc: Progress callback. For multi-batch ZIM ingestions, scale the service-reported 0-100% (which is % through the current bat
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/services/ollama_service.ts`, `admin/app/services/queue_service.ts`, `admin/app/services/rag_service.ts`, `admin/config/queue.ts`, `admin/inertia/pages/settings/update.tsx`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/commands/queue/work.ts`

### articlesDone
- Defined: `admin/app/jobs/embed_file_job.ts:119`
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/services/ollama_service.ts`, `admin/app/services/queue_service.ts`, `admin/app/services/rag_service.ts`, `admin/config/queue.ts`, `admin/inertia/pages/settings/update.tsx`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/commands/queue/work.ts`

### nextOffset
- Defined: `admin/app/jobs/embed_file_job.ts:144`
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/services/ollama_service.ts`, `admin/app/services/queue_service.ts`, `admin/app/services/rag_service.ts`, `admin/config/queue.ts`, `admin/inertia/pages/settings/update.tsx`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/commands/queue/work.ts`

### totalChunks
- Defined: `admin/app/jobs/embed_file_job.ts:196`
- Doc: Final batch or non-batched file - mark as complete
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/services/ollama_service.ts`, `admin/app/services/queue_service.ts`, `admin/app/services/rag_service.ts`, `admin/config/queue.ts`, `admin/inertia/pages/settings/update.tsx`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/commands/queue/work.ts`

### filePath
- Defined: `admin/app/jobs/embed_file_job.ts:394`
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/services/ollama_service.ts`, `admin/app/services/queue_service.ts`, `admin/app/services/rag_service.ts`, `admin/config/queue.ts`, `admin/inertia/pages/settings/update.tsx`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/commands/queue/work.ts`

## admin/app/jobs/run_download_job.ts

### progressPercent
- Defined: `admin/app/jobs/run_download_job.ts:86`
- Depends on: `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/queue_service.ts`, `admin/app/services/zim_service.ts`, `admin/config/queue.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/services/collection_manifest_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/zim_service.ts`, `admin/commands/queue/work.ts`

## admin/app/services/benchmark_service.ts

### totalTime
- Defined: `admin/app/services/benchmark_service.ts:504`
- Depends on: `admin/app/services/system_service.ts`, `admin/constants/broadcast.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/benchmark_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/run_benchmark_job.ts`

## admin/app/services/container_registry_service.ts

### data
- Defined: `admin/app/services/container_registry_service.ts:104`
- Imported by: `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`

### data
- Defined: `admin/app/services/container_registry_service.ts:137`
- Imported by: `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`

### manifest
- Defined: `admin/app/services/container_registry_service.ts:177`
- Imported by: `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`

### manifest
- Defined: `admin/app/services/container_registry_service.ts:236`
- Imported by: `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`

### childManifest
- Defined: `admin/app/services/container_registry_service.ts:256`
- Imported by: `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`

### config
- Defined: `admin/app/services/container_registry_service.ts:278`
- Imported by: `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`

## admin/app/services/countries_service.ts

### typeRank
- Defined: `admin/app/services/countries_service.ts:215`
- Depends on: `admin/inertia/pages/settings/update.tsx`

### resolveIso2
- Defined: `admin/app/services/countries_service.ts:225`
- Depends on: `admin/inertia/pages/settings/update.tsx`

### bufferGeometry
- Defined: `admin/app/services/countries_service.ts:242`
- Depends on: `admin/inertia/pages/settings/update.tsx`

### bufferPolygonRings
- Defined: `admin/app/services/countries_service.ts:258`
- Depends on: `admin/inertia/pages/settings/update.tsx`

### bufferRing
- Defined: `admin/app/services/countries_service.ts:262`
- Depends on: `admin/inertia/pages/settings/update.tsx`

### signedArea
- Defined: `admin/app/services/countries_service.ts:290`
- Depends on: `admin/inertia/pages/settings/update.tsx`

### resolveIso3
- Defined: `admin/app/services/countries_service.ts:298`
- Depends on: `admin/inertia/pages/settings/update.tsx`

### codes
- Defined: `admin/app/services/countries_service.ts:144`
- Depends on: `admin/inertia/pages/settings/update.tsx`

### n1x
- Defined: `admin/app/services/countries_service.ts:278`
- Depends on: `admin/inertia/pages/settings/update.tsx`

### n1y
- Defined: `admin/app/services/countries_service.ts:279`
- Depends on: `admin/inertia/pages/settings/update.tsx`

### n2x
- Defined: `admin/app/services/countries_service.ts:280`
- Depends on: `admin/inertia/pages/settings/update.tsx`

### n2y
- Defined: `admin/app/services/countries_service.ts:281`
- Depends on: `admin/inertia/pages/settings/update.tsx`

## admin/app/services/docker_service.ts

### used
- Defined: `admin/app/services/docker_service.ts:548`
- Depends on: `admin/app/utils/version.ts`, `admin/constants/broadcast.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_benchmark_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/services/system_service.ts`

### is
- Defined: `admin/app/services/docker_service.ts:826`
- Depends on: `admin/app/utils/version.ts`, `admin/constants/broadcast.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_benchmark_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/services/system_service.ts`

### marker
- Defined: `admin/app/services/docker_service.ts:934`
- Depends on: `admin/app/utils/version.ts`, `admin/constants/broadcast.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_benchmark_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/services/system_service.ts`

### gfx
- Defined: `admin/app/services/docker_service.ts:1043`
- Depends on: `admin/app/utils/version.ts`, `admin/constants/broadcast.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_benchmark_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/services/system_service.ts`

## admin/app/services/kiwix_library_service.ts

### getMeta
- Defined: `admin/app/services/kiwix_library_service.ts:65`

## admin/app/services/map_service.ts

### getHost
- Defined: `admin/app/services/map_service.ts:839`
- Depends on: `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/validators/common.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/maps_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/run_download_job.ts`

### specifiedHostOrDefault
- Defined: `admin/app/services/map_service.ts:851`
- Depends on: `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/validators/common.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/maps_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/run_download_job.ts`

### findExactGroupMatch
- Defined: `admin/app/services/map_service.ts:877`
- Depends on: `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/validators/common.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/maps_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/run_download_job.ts`

### files
- Defined: `admin/app/services/map_service.ts:84`
- Depends on: `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/validators/common.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/maps_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/run_download_job.ts`

### regions
- Defined: `admin/app/services/map_service.ts:326`
- Depends on: `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/validators/common.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/maps_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/run_download_job.ts`

### unit
- Defined: `admin/app/services/map_service.ts:768`
- Depends on: `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/validators/common.ts`, `admin/inertia/pages/settings/update.tsx`
- Imported by: `admin/app/controllers/maps_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/run_download_job.ts`

## admin/app/services/ollama_service.ts

### partialTagSuffix
- Defined: `admin/app/services/ollama_service.ts:370`
- Doc: Returns how many trailing chars of `text` could be the start of `tag`
- Depends on: `admin/app/jobs/download_model_job.ts`, `admin/constants/broadcast.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`

### customUrl
- Defined: `admin/app/services/ollama_service.ts:64`
- Doc: Check KVStore for a custom base URL (remote Ollama, LM Studio, llama.cpp, etc.)
- Depends on: `admin/app/jobs/download_model_job.ts`, `admin/constants/broadcast.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`

### onAbort
- Defined: `admin/app/services/ollama_service.ts:187`
- Doc: If the abort fires after headers are received but mid-stream, axios's signal handling destroys the stream which surfaces
- Depends on: `admin/app/jobs/download_model_job.ts`, `admin/constants/broadcast.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`

### stream
- Defined: `admin/app/services/ollama_service.ts:367`
- Depends on: `admin/app/jobs/download_model_job.ts`, `admin/constants/broadcast.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`

### parsePulls
- Defined: `admin/app/services/ollama_service.ts:860`
- Depends on: `admin/app/jobs/download_model_job.ts`, `admin/constants/broadcast.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`

### parseSize
- Defined: `admin/app/services/ollama_service.ts:879`
- Depends on: `admin/app/jobs/download_model_job.ts`, `admin/constants/broadcast.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`

## admin/app/services/rag_service.ts

### progress
- Defined: `admin/app/services/rag_service.ts:373`
- Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/embed_file_job.ts`

## admin/app/services/system_service.ts

### buf
- Defined: `admin/app/services/system_service.ts:131`
- Depends on: `admin/app/services/docker_service.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/easy_setup_controller.ts`, `admin/app/controllers/home_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/config/inertia.ts`

### actualImage
- Defined: `admin/app/services/system_service.ts:251`
- Depends on: `admin/app/services/docker_service.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/easy_setup_controller.ts`, `admin/app/controllers/home_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/config/inertia.ts`

### isDiscreteGpuVendor
- Defined: `admin/app/services/system_service.ts:440`
- Depends on: `admin/app/services/docker_service.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/easy_setup_controller.ts`, `admin/app/controllers/home_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/config/inertia.ts`

### isBogusDgpuVram
- Defined: `admin/app/services/system_service.ts:442`
- Depends on: `admin/app/services/docker_service.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/easy_setup_controller.ts`, `admin/app/controllers/home_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/config/inertia.ts`

### hasLspciBogusDgpuVram
- Defined: `admin/app/services/system_service.ts:452`
- Doc: Clear the bogus value up front. If a probe replaces the entry below we get the real VRAM; if no probe succeeds (Ollama n
- Depends on: `admin/app/services/docker_service.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/easy_setup_controller.ts`, `admin/app/controllers/home_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/config/inertia.ts`

### earlyAccess
- Defined: `admin/app/services/system_service.ts:630`
- Depends on: `admin/app/services/docker_service.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/easy_setup_controller.ts`, `admin/app/controllers/home_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/config/inertia.ts`

## admin/app/utils/downloads.ts

### doResumableDownload
- Defined: `admin/app/utils/downloads.ts:18`
- Doc: Perform a resumable download with progress tracking @param param0 - Download parameters. Leave allowedMimeTypes empty to
- Depends on: `admin/app/utils/fs.ts`

### doResumableDownloadWithRetry
- Defined: `admin/app/utils/downloads.ts:226`
- Depends on: `admin/app/utils/fs.ts`

### delay
- Defined: `admin/app/utils/downloads.ts:284`
- Depends on: `admin/app/utils/fs.ts`

### fetchStream
- Defined: `admin/app/utils/downloads.ts:96`
- Depends on: `admin/app/utils/fs.ts`

### clearStallTimer
- Defined: `admin/app/utils/downloads.ts:128`
- Depends on: `admin/app/utils/fs.ts`

### resetStallTimer
- Defined: `admin/app/utils/downloads.ts:135`
- Depends on: `admin/app/utils/fs.ts`

### cleanup
- Defined: `admin/app/utils/downloads.ts:171`
- Depends on: `admin/app/utils/fs.ts`

## admin/app/utils/fs.ts

### listDirectoryContents
- Defined: `admin/app/utils/fs.ts:10`
- Imported by: `admin/app/services/system_update_service.ts`, `admin/app/utils/downloads.ts`

### listDirectoryContentsRecursive
- Defined: `admin/app/utils/fs.ts:31`
- Imported by: `admin/app/services/system_update_service.ts`, `admin/app/utils/downloads.ts`

### ensureDirectoryExists
- Defined: `admin/app/utils/fs.ts:50`
- Imported by: `admin/app/services/system_update_service.ts`, `admin/app/utils/downloads.ts`

### getFile
- Defined: `admin/app/utils/fs.ts:60`
- Imported by: `admin/app/services/system_update_service.ts`, `admin/app/utils/downloads.ts`

### getFile
- Defined: `admin/app/utils/fs.ts:61`
- Imported by: `admin/app/services/system_update_service.ts`, `admin/app/utils/downloads.ts`

### getFile
- Defined: `admin/app/utils/fs.ts:65`
- Imported by: `admin/app/services/system_update_service.ts`, `admin/app/utils/downloads.ts`

### getFile
- Defined: `admin/app/utils/fs.ts:66`
- Imported by: `admin/app/services/system_update_service.ts`, `admin/app/utils/downloads.ts`

### getFileStatsIfExists
- Defined: `admin/app/utils/fs.ts:85`
- Imported by: `admin/app/services/system_update_service.ts`, `admin/app/utils/downloads.ts`

### isValidZimFile
- Defined: `admin/app/utils/fs.ts:108`
- Doc: Validates that a file has the ZIM magic number (0x44D495A). Must be called before passing a file to @openzim/libzim Arch
- Imported by: `admin/app/services/system_update_service.ts`, `admin/app/utils/downloads.ts`

### deleteFileIfExists
- Defined: `admin/app/utils/fs.ts:124`
- Imported by: `admin/app/services/system_update_service.ts`, `admin/app/utils/downloads.ts`

### getAllFilesystems
- Defined: `admin/app/utils/fs.ts:134`
- Imported by: `admin/app/services/system_update_service.ts`, `admin/app/utils/downloads.ts`

### traverse
- Defined: `admin/app/utils/fs.ts:141`
- Imported by: `admin/app/services/system_update_service.ts`, `admin/app/utils/downloads.ts`

### matchesDevice
- Defined: `admin/app/utils/fs.ts:160`
- Imported by: `admin/app/services/system_update_service.ts`, `admin/app/utils/downloads.ts`

### determineFileType
- Defined: `admin/app/utils/fs.ts:177`
- Imported by: `admin/app/services/system_update_service.ts`, `admin/app/utils/downloads.ts`

### sanitizeFilename
- Defined: `admin/app/utils/fs.ts:199`
- Doc: Sanitize a filename by removing potentially dangerous characters. @param filename The original filename @returns The san
- Imported by: `admin/app/services/system_update_service.ts`, `admin/app/utils/downloads.ts`

## admin/app/utils/kb_ingest_decision.ts

### decideScanAction
- Defined: `admin/app/utils/kb_ingest_decision.ts:44`
- Doc: Decide what scanAndSyncStorage should do for a single embeddable file.  Replaces the earlier `!sourcesInQdrant.has(fileP

## admin/app/utils/kb_job_health.ts

### computeJobHealth
- Defined: `admin/app/utils/kb_job_health.ts:32`

## admin/app/utils/kb_ratio_lookup.ts

### estimateBatch
- Defined: `admin/app/utils/kb_ratio_lookup.ts:38`
- Doc: Aggregate an embedding-disk-cost estimate across a batch of files (curated tier add, multi-upload, sync preview, etc). `

### findChunksPerMb
- Defined: `admin/app/utils/kb_ratio_lookup.ts:70`
- Doc: Pick the chunks_per_mb estimate for a filename by longest-prefix match.  Patterns are filename prefixes (`devdocs_`, `wi

### estimateChunkCount
- Defined: `admin/app/utils/kb_ratio_lookup.ts:88`
- Doc: Estimate the number of embedding chunks a ZIM-style file will produce given its size on disk in bytes. Returns `null` wh

## admin/app/utils/kb_warning_decision.ts

### decideWarnings
- Defined: `admin/app/utils/kb_warning_decision.ts:41`

## admin/app/utils/misc.ts

### formatSpeed
- Defined: `admin/app/utils/misc.ts:1`

### toTitleCase
- Defined: `admin/app/utils/misc.ts:7`

### parseBoolean
- Defined: `admin/app/utils/misc.ts:15`

## admin/app/utils/version.ts

### isNewerVersion
- Defined: `admin/app/utils/version.ts:7`
- Doc: Compare two semantic version strings to determine if the first is newer than the second. @param version1 - The version t
- Imported by: `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/docker_service.ts`, `admin/inertia/components/UpdateServiceModal.tsx`, `admin/inertia/pages/settings/update.tsx`

### parseMajorVersion
- Defined: `admin/app/utils/version.ts:45`
- Doc: Parse the major version number from a tag string. Strips the 'v' prefix if present. @param tag - Version tag (e.g., "v3.
- Imported by: `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/docker_service.ts`, `admin/inertia/components/UpdateServiceModal.tsx`, `admin/inertia/pages/settings/update.tsx`

### normalize
- Defined: `admin/app/utils/version.ts:8`
- Imported by: `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/docker_service.ts`, `admin/inertia/components/UpdateServiceModal.tsx`, `admin/inertia/pages/settings/update.tsx`

## admin/app/utils/zim_filename.ts

### zimFilenameStem
- Defined: `admin/app/utils/zim_filename.ts:7`
- Doc: Strip the trailing `_YYYY-MM(-DD).zim` date suffix from a Kiwix-style ZIM filename so different release dates of the sam

### findReplacedWikipediaFiles
- Defined: `admin/app/utils/zim_filename.ts:17`
- Doc: Of the existing files, return only those that are prior-version replacements of `currentFilename` — same Wikipedia varia

## admin/app/validators/common.ts

### assertNotPrivateUrl
- Defined: `admin/app/validators/common.ts:15`
- Doc: Checks whether a URL points to a loopback or link-local address. Used to prevent SSRF — the server should not fetch from
- Imported by: `admin/app/controllers/collection_updates_controller.ts`, `admin/app/controllers/maps_controller.ts`, `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/zim_controller.ts`, `admin/app/services/map_service.ts`, `admin/app/services/zim_service.ts`

### assertNotCloudMetadataUrl
- Defined: `admin/app/validators/common.ts:61`
- Imported by: `admin/app/controllers/collection_updates_controller.ts`, `admin/app/controllers/maps_controller.ts`, `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/zim_controller.ts`, `admin/app/services/map_service.ts`, `admin/app/services/zim_service.ts`

## admin/config/inertia.ts

### invalidateAssistantNameCache
- Defined: `admin/config/inertia.ts:8`
- Depends on: `admin/app/services/system_service.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`

### value
- Defined: `admin/config/inertia.ts:30`
- Depends on: `admin/app/services/system_service.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`

## admin/constants/map_regions.ts

### buildPmtilesExtractArgs
- Defined: `admin/constants/map_regions.ts:24`
- Imported by: `admin/inertia/components/CountryPickerModal.tsx`

## admin/inertia/app/app.tsx

### environment
- Defined: `admin/inertia/app/app.tsx:38`
- Depends on: `admin/inertia/providers/ThemeProvider.tsx`

## admin/inertia/components/ActiveDownloads.tsx

### formatSpeed
- Defined: `admin/inertia/components/ActiveDownloads.tsx:12`
- Depends on: `admin/inertia/hooks/useDownloads.ts`

### getDownloadStatus
- Defined: `admin/inertia/components/ActiveDownloads.tsx:21`
- Depends on: `admin/inertia/hooks/useDownloads.ts`

### ActiveDownloads
- Defined: `admin/inertia/components/ActiveDownloads.tsx:38`
- Depends on: `admin/inertia/hooks/useDownloads.ts`

### deltaSec
- Defined: `admin/inertia/components/ActiveDownloads.tsx:56`
- Depends on: `admin/inertia/hooks/useDownloads.ts`

### handleDismiss
- Defined: `admin/inertia/components/ActiveDownloads.tsx:81`
- Depends on: `admin/inertia/hooks/useDownloads.ts`

### handleCancel
- Defined: `admin/inertia/components/ActiveDownloads.tsx:86`
- Depends on: `admin/inertia/hooks/useDownloads.ts`

## admin/inertia/components/ActiveEmbedJobs.tsx

### ActiveEmbedJobs
- Defined: `admin/inertia/components/ActiveEmbedJobs.tsx:15`
- Depends on: `admin/inertia/hooks/useEmbedJobs.ts`, `admin/inertia/lib/kb_job_health_display.ts`

## admin/inertia/components/ActiveModelDownloads.tsx

### formatSpeed
- Defined: `admin/inertia/components/ActiveModelDownloads.tsx:13`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useOllamaModelDownloads.ts`

### ActiveModelDownloads
- Defined: `admin/inertia/components/ActiveModelDownloads.tsx:21`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useOllamaModelDownloads.ts`

### deltaSec
- Defined: `admin/inertia/components/ActiveModelDownloads.tsx:39`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useOllamaModelDownloads.ts`

### runCancel
- Defined: `admin/inertia/components/ActiveModelDownloads.tsx:62`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useOllamaModelDownloads.ts`

### confirmCancel
- Defined: `admin/inertia/components/ActiveModelDownloads.tsx:85`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useOllamaModelDownloads.ts`

## admin/inertia/components/Alert.tsx

### Alert
- Defined: `admin/inertia/components/Alert.tsx:17`
- Depends on: `admin/inertia/lib/classNames.ts`

### getDefaultIcon
- Defined: `admin/inertia/components/Alert.tsx:29`
- Depends on: `admin/inertia/lib/classNames.ts`

### getIconColor
- Defined: `admin/inertia/components/Alert.tsx:44`
- Depends on: `admin/inertia/lib/classNames.ts`

### getVariantStyles
- Defined: `admin/inertia/components/Alert.tsx:60`
- Depends on: `admin/inertia/lib/classNames.ts`

### getTitleColor
- Defined: `admin/inertia/components/Alert.tsx:113`
- Depends on: `admin/inertia/lib/classNames.ts`

### getMessageColor
- Defined: `admin/inertia/components/Alert.tsx:132`
- Depends on: `admin/inertia/lib/classNames.ts`

### getCloseButtonStyles
- Defined: `admin/inertia/components/Alert.tsx:149`
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/BouncingDots.tsx

### BouncingDots
- Defined: `admin/inertia/components/BouncingDots.tsx:9`

## admin/inertia/components/BouncingLogo.tsx

### FadingImage
- Defined: `admin/inertia/components/BouncingLogo.tsx:4`
- Doc: Fading Image Component

## admin/inertia/components/BuilderTagSelector.tsx

### BuilderTagSelector
- Defined: `admin/inertia/components/BuilderTagSelector.tsx:18`

### updateTag
- Defined: `admin/inertia/components/BuilderTagSelector.tsx:50`
- Doc: Update parent when selections change

### handleAdjectiveChange
- Defined: `admin/inertia/components/BuilderTagSelector.tsx:55`

### handleNounChange
- Defined: `admin/inertia/components/BuilderTagSelector.tsx:60`

### handleRandomize
- Defined: `admin/inertia/components/BuilderTagSelector.tsx:65`

## admin/inertia/components/CategoryCard.tsx

### getTierTotalSize
- Defined: `admin/inertia/components/CategoryCard.tsx:15`
- Doc: Calculate total size range across all tiers

## admin/inertia/components/CountryPickerModal.tsx

### toggleCountry
- Defined: `admin/inertia/components/CountryPickerModal.tsx:100`
- Depends on: `admin/constants/map_regions.ts`, `admin/inertia/lib/classNames.ts`

### toggleGroup
- Defined: `admin/inertia/components/CountryPickerModal.tsx:109`
- Depends on: `admin/constants/map_regions.ts`, `admin/inertia/lib/classNames.ts`

### clearAll
- Defined: `admin/inertia/components/CountryPickerModal.tsx:122`
- Depends on: `admin/constants/map_regions.ts`, `admin/inertia/lib/classNames.ts`

### startDownload
- Defined: `admin/inertia/components/CountryPickerModal.tsx:164`
- Depends on: `admin/constants/map_regions.ts`, `admin/inertia/lib/classNames.ts`

### PreflightStatus
- Defined: `admin/inertia/components/CountryPickerModal.tsx:392`
- Depends on: `admin/constants/map_regions.ts`, `admin/inertia/lib/classNames.ts`

## admin/inertia/components/DebugInfoModal.tsx

### DebugInfoModal
- Defined: `admin/inertia/components/DebugInfoModal.tsx:11`

### handleCopy
- Defined: `admin/inertia/components/DebugInfoModal.tsx:36`

## admin/inertia/components/DownloadURLModal.tsx

### runPreflightCheck
- Defined: `admin/inertia/components/DownloadURLModal.tsx:23`

## admin/inertia/components/Footer.tsx

### Footer
- Defined: `admin/inertia/components/Footer.tsx:8`

## admin/inertia/components/HorizontalBarChart.tsx

### HorizontalBarChart
- Defined: `admin/inertia/components/HorizontalBarChart.tsx:19`
- Depends on: `admin/inertia/lib/classNames.ts`

### getBarColor
- Defined: `admin/inertia/components/HorizontalBarChart.tsx:26`
- Depends on: `admin/inertia/lib/classNames.ts`

### getGlowColor
- Defined: `admin/inertia/components/HorizontalBarChart.tsx:34`
- Depends on: `admin/inertia/lib/classNames.ts`

### getStatusLabel
- Defined: `admin/inertia/components/HorizontalBarChart.tsx:41`
- Depends on: `admin/inertia/lib/classNames.ts`

### getStatusColor
- Defined: `admin/inertia/components/HorizontalBarChart.tsx:51`
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/InfoTooltip.tsx

### InfoTooltip
- Defined: `admin/inertia/components/InfoTooltip.tsx:9`

## admin/inertia/components/KbGuardrailModal.tsx

### KbGuardrailModal
- Defined: `admin/inertia/components/KbGuardrailModal.tsx:22`

## admin/inertia/components/MarkdocRenderer.tsx

### Paragraph
- Defined: `admin/inertia/components/MarkdocRenderer.tsx:10`
- Doc: Paragraph component
- Depends on: `admin/inertia/components/markdoc/Heading.tsx`, `admin/inertia/components/markdoc/Image.tsx`, `admin/inertia/components/markdoc/List.tsx`, `admin/inertia/components/markdoc/ListItem.tsx`, `admin/inertia/components/markdoc/Table.tsx`

### Link
- Defined: `admin/inertia/components/MarkdocRenderer.tsx:15`
- Doc: Link component
- Depends on: `admin/inertia/components/markdoc/Heading.tsx`, `admin/inertia/components/markdoc/Image.tsx`, `admin/inertia/components/markdoc/List.tsx`, `admin/inertia/components/markdoc/ListItem.tsx`, `admin/inertia/components/markdoc/Table.tsx`

### InlineCode
- Defined: `admin/inertia/components/MarkdocRenderer.tsx:38`
- Doc: Inline code component
- Depends on: `admin/inertia/components/markdoc/Heading.tsx`, `admin/inertia/components/markdoc/Image.tsx`, `admin/inertia/components/markdoc/List.tsx`, `admin/inertia/components/markdoc/ListItem.tsx`, `admin/inertia/components/markdoc/Table.tsx`

### CodeBlock
- Defined: `admin/inertia/components/MarkdocRenderer.tsx:47`
- Doc: Code block component
- Depends on: `admin/inertia/components/markdoc/Heading.tsx`, `admin/inertia/components/markdoc/Image.tsx`, `admin/inertia/components/markdoc/List.tsx`, `admin/inertia/components/markdoc/ListItem.tsx`, `admin/inertia/components/markdoc/Table.tsx`

### HorizontalRule
- Defined: `admin/inertia/components/MarkdocRenderer.tsx:74`
- Doc: Horizontal rule component
- Depends on: `admin/inertia/components/markdoc/Heading.tsx`, `admin/inertia/components/markdoc/Image.tsx`, `admin/inertia/components/markdoc/List.tsx`, `admin/inertia/components/markdoc/ListItem.tsx`, `admin/inertia/components/markdoc/Table.tsx`

### Callout
- Defined: `admin/inertia/components/MarkdocRenderer.tsx:81`
- Doc: Callout component
- Depends on: `admin/inertia/components/markdoc/Heading.tsx`, `admin/inertia/components/markdoc/Image.tsx`, `admin/inertia/components/markdoc/List.tsx`, `admin/inertia/components/markdoc/ListItem.tsx`, `admin/inertia/components/markdoc/Table.tsx`

## admin/inertia/components/ProgressBar.tsx

### ProgressBar
- Defined: `admin/inertia/components/ProgressBar.tsx:1`

## admin/inertia/components/StorageProjectionBar.tsx

### StorageProjectionBar
- Defined: `admin/inertia/components/StorageProjectionBar.tsx:11`
- Depends on: `admin/inertia/lib/classNames.ts`

### currentPercent
- Defined: `admin/inertia/components/StorageProjectionBar.tsx:17`
- Depends on: `admin/inertia/lib/classNames.ts`

### projectedPercent
- Defined: `admin/inertia/components/StorageProjectionBar.tsx:18`
- Depends on: `admin/inertia/lib/classNames.ts`

### projectedTotalPercent
- Defined: `admin/inertia/components/StorageProjectionBar.tsx:19`
- Depends on: `admin/inertia/lib/classNames.ts`

### getProjectedColor
- Defined: `admin/inertia/components/StorageProjectionBar.tsx:24`
- Doc: Determine warning level based on projected total
- Depends on: `admin/inertia/lib/classNames.ts`

### getProjectedGlow
- Defined: `admin/inertia/components/StorageProjectionBar.tsx:31`
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/StyledButton.tsx

### getIconSize
- Defined: `admin/inertia/components/StyledButton.tsx:30`

### getSizeClasses
- Defined: `admin/inertia/components/StyledButton.tsx:41`

### getVariantClasses
- Defined: `admin/inertia/components/StyledButton.tsx:52`

### getLoadingSpinner
- Defined: `admin/inertia/components/StyledButton.tsx:131`

### onClickHandler
- Defined: `admin/inertia/components/StyledButton.tsx:140`

## admin/inertia/components/StyledSectionHeader.tsx

### StyledSectionHeader
- Defined: `admin/inertia/components/StyledSectionHeader.tsx:10`

## admin/inertia/components/StyledSidebar.tsx

### ListItem
- Defined: `admin/inertia/components/StyledSidebar.tsx:34`
- Depends on: `admin/inertia/lib/classNames.ts`

### content
- Defined: `admin/inertia/components/StyledSidebar.tsx:41`
- Depends on: `admin/inertia/lib/classNames.ts`

### Sidebar
- Defined: `admin/inertia/components/StyledSidebar.tsx:62`
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/StyledTable.tsx

### StyledTable
- Defined: `admin/inertia/components/StyledTable.tsx:33`
- Depends on: `admin/inertia/lib/classNames.ts`

### isRowExpanded
- Defined: `admin/inertia/components/StyledTable.tsx:59`
- Depends on: `admin/inertia/lib/classNames.ts`

### toggleRowExpansion
- Defined: `admin/inertia/components/StyledTable.tsx:64`
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/ThemeToggle.tsx

### ThemeToggle
- Defined: `admin/inertia/components/ThemeToggle.tsx:8`
- Depends on: `admin/inertia/providers/ThemeProvider.tsx`

## admin/inertia/components/TierSelectionModal.tsx

### resourceFilename
- Defined: `admin/inertia/components/TierSelectionModal.tsx:21`
- Depends on: `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/inertia/lib/kb_guardrail.ts`

### getAllResourcesForTier
- Defined: `admin/inertia/components/TierSelectionModal.tsx:55`
- Doc: Get all resources for a tier (including inherited resources). Defined as a hook-safe closure (always callable, returns [
- Depends on: `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/inertia/lib/kb_guardrail.ts`

### getTierTotalSize
- Defined: `admin/inertia/components/TierSelectionModal.tsx:116`
- Depends on: `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/inertia/lib/kb_guardrail.ts`

### handleTierClick
- Defined: `admin/inertia/components/TierSelectionModal.tsx:120`
- Depends on: `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/inertia/lib/kb_guardrail.ts`

### finalizeSubmit
- Defined: `admin/inertia/components/TierSelectionModal.tsx:134`
- Doc: Runs the original onSelectTier-then-onClose flow. Pulled out of handleSubmit so the guardrail modal's confirm path can c
- Depends on: `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/inertia/lib/kb_guardrail.ts`

### handleSubmit
- Defined: `admin/inertia/components/TierSelectionModal.tsx:143`
- Depends on: `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/inertia/lib/kb_guardrail.ts`

## admin/inertia/components/UpdateServiceModal.tsx

### UpdateServiceModal
- Defined: `admin/inertia/components/UpdateServiceModal.tsx:17`
- Depends on: `admin/app/utils/version.ts`, `admin/types/services.ts`

### loadVersions
- Defined: `admin/inertia/components/UpdateServiceModal.tsx:30`
- Depends on: `admin/app/utils/version.ts`, `admin/types/services.ts`

### handleToggleAdvanced
- Defined: `admin/inertia/components/UpdateServiceModal.tsx:45`
- Depends on: `admin/app/utils/version.ts`, `admin/types/services.ts`

## admin/inertia/components/chat/ChatAssistantAvatar.tsx

### ChatAssistantAvatar
- Defined: `admin/inertia/components/chat/ChatAssistantAvatar.tsx:3`

## admin/inertia/components/chat/ChatButton.tsx

### ChatButton
- Defined: `admin/inertia/components/chat/ChatButton.tsx:7`

## admin/inertia/components/chat/ChatInterface.tsx

### ChatInterface
- Defined: `admin/inertia/components/chat/ChatInterface.tsx:24`
- Depends on: `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/classNames.ts`

### handleDownloadModel
- Defined: `admin/inertia/components/chat/ChatInterface.tsx:41`
- Depends on: `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/classNames.ts`

### scrollToBottom
- Defined: `admin/inertia/components/chat/ChatInterface.tsx:54`
- Depends on: `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/classNames.ts`

### handleSubmit
- Defined: `admin/inertia/components/chat/ChatInterface.tsx:62`
- Depends on: `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/classNames.ts`

### handleKeyDown
- Defined: `admin/inertia/components/chat/ChatInterface.tsx:73`
- Depends on: `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/classNames.ts`

### handleInput
- Defined: `admin/inertia/components/chat/ChatInterface.tsx:80`
- Depends on: `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/classNames.ts`

## admin/inertia/components/chat/ChatMessageBubble.tsx

### ChatMessageBubble
- Defined: `admin/inertia/components/chat/ChatMessageBubble.tsx:10`
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/chat/ChatModal.tsx

### ChatModal
- Defined: `admin/inertia/components/chat/ChatModal.tsx:11`
- Depends on: `admin/inertia/hooks/useSystemSetting.ts`

## admin/inertia/components/chat/ChatSidebar.tsx

### ChatSidebar
- Defined: `admin/inertia/components/chat/ChatSidebar.tsx:18`
- Depends on: `admin/inertia/lib/classNames.ts`

### handleCloseKnowledgeBase
- Defined: `admin/inertia/components/chat/ChatSidebar.tsx:31`
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/chat/KbPolicyPromptBanner.tsx

### KbPolicyPromptBanner
- Defined: `admin/inertia/components/chat/KbPolicyPromptBanner.tsx:27`
- Doc: (`rag.defaultIngestPolicy` unset). Two buttons let the user decide once, after which the prompt never returns:  - "Index
- Depends on: `admin/inertia/context/NotificationContext.ts`

## admin/inertia/components/chat/KnowledgeBaseModal.tsx

### renderStatePill
- Defined: `admin/inertia/components/chat/KnowledgeBaseModal.tsx:32`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/kb_file_grouping.ts`

### pickRowAction
- Defined: `admin/inertia/components/chat/KnowledgeBaseModal.tsx:77`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/kb_file_grouping.ts`

### KnowledgeBaseModal
- Defined: `admin/inertia/components/chat/KnowledgeBaseModal.tsx:96`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/kb_file_grouping.ts`

### handleUpload
- Defined: `admin/inertia/components/chat/KnowledgeBaseModal.tsx:282`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/kb_file_grouping.ts`

### handleConfirmSync
- Defined: `admin/inertia/components/chat/KnowledgeBaseModal.tsx:313`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/kb_file_grouping.ts`

## admin/inertia/components/chat/index.tsx

### Chat
- Defined: `admin/inertia/components/chat/index.tsx:24`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`, `admin/inertia/lib/classNames.ts`

## admin/inertia/components/inputs/Switch.tsx

### Switch
- Defined: `admin/inertia/components/inputs/Switch.tsx:12`

## admin/inertia/components/layout/BackToHomeHeader.tsx

### BackToHomeHeader
- Defined: `admin/inertia/components/layout/BackToHomeHeader.tsx:10`

## admin/inertia/components/maps/CoordinateOverlay.tsx

### CoordinateOverlay
- Defined: `admin/inertia/components/maps/CoordinateOverlay.tsx:8`

## admin/inertia/components/maps/MapComponent.tsx

### MapComponent
- Defined: `admin/inertia/components/maps/MapComponent.tsx:31`
- Depends on: `admin/inertia/hooks/useMapMarkers.ts`

## admin/inertia/components/maps/MarkerPanel.tsx

### MarkerPanel
- Defined: `admin/inertia/components/maps/MarkerPanel.tsx:14`
- Depends on: `admin/inertia/hooks/useMapMarkers.ts`

## admin/inertia/components/maps/MarkerPin.tsx

### MarkerPin
- Defined: `admin/inertia/components/maps/MarkerPin.tsx:8`

## admin/inertia/components/maps/ScaleUnitToggle.tsx

### ScaleUnitToggle
- Defined: `admin/inertia/components/maps/ScaleUnitToggle.tsx:9`

## admin/inertia/components/markdoc/Heading.tsx

### Heading
- Defined: `admin/inertia/components/markdoc/Heading.tsx:3`
- Imported by: `admin/inertia/components/MarkdocRenderer.tsx`

## admin/inertia/components/markdoc/Image.tsx

### Image
- Defined: `admin/inertia/components/markdoc/Image.tsx:1`
- Imported by: `admin/inertia/components/MarkdocRenderer.tsx`

## admin/inertia/components/markdoc/List.tsx

### List
- Defined: `admin/inertia/components/markdoc/List.tsx:1`
- Imported by: `admin/inertia/components/MarkdocRenderer.tsx`

## admin/inertia/components/markdoc/ListItem.tsx

### ListItem
- Defined: `admin/inertia/components/markdoc/ListItem.tsx:1`
- Imported by: `admin/inertia/components/MarkdocRenderer.tsx`

## admin/inertia/components/markdoc/Table.tsx

### Table
- Defined: `admin/inertia/components/markdoc/Table.tsx:1`
- Imported by: `admin/inertia/components/MarkdocRenderer.tsx`

### TableHead
- Defined: `admin/inertia/components/markdoc/Table.tsx:11`
- Imported by: `admin/inertia/components/MarkdocRenderer.tsx`

### TableBody
- Defined: `admin/inertia/components/markdoc/Table.tsx:15`
- Imported by: `admin/inertia/components/MarkdocRenderer.tsx`

### TableRow
- Defined: `admin/inertia/components/markdoc/Table.tsx:19`
- Imported by: `admin/inertia/components/MarkdocRenderer.tsx`

### TableHeader
- Defined: `admin/inertia/components/markdoc/Table.tsx:23`
- Imported by: `admin/inertia/components/MarkdocRenderer.tsx`

### TableCell
- Defined: `admin/inertia/components/markdoc/Table.tsx:31`
- Imported by: `admin/inertia/components/MarkdocRenderer.tsx`

## admin/inertia/components/systeminfo/CircularGauge.tsx

### CircularGauge
- Defined: `admin/inertia/components/systeminfo/CircularGauge.tsx:14`
- Depends on: `admin/inertia/lib/classNames.ts`

### getColor
- Defined: `admin/inertia/components/systeminfo/CircularGauge.tsx:63`
- Depends on: `admin/inertia/lib/classNames.ts`

### angle
- Defined: `admin/inertia/components/systeminfo/CircularGauge.tsx:118`
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/systeminfo/InfoCard.tsx

### InfoCard
- Defined: `admin/inertia/components/systeminfo/InfoCard.tsx:13`
- Depends on: `admin/inertia/lib/classNames.ts`

### getVariantStyles
- Defined: `admin/inertia/components/systeminfo/InfoCard.tsx:14`
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/systeminfo/StatusCard.tsx

### StatusCard
- Defined: `admin/inertia/components/systeminfo/StatusCard.tsx:6`

## admin/inertia/context/ModalContext.ts

### useModals
- Defined: `admin/inertia/context/ModalContext.ts:13`
- Imported by: `admin/inertia/components/ActiveModelDownloads.tsx`, `admin/inertia/components/chat/KnowledgeBaseModal.tsx`, `admin/inertia/components/chat/index.tsx`, `admin/inertia/pages/settings/apps.tsx`, `admin/inertia/pages/settings/maps.tsx`, `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/system.tsx`, `admin/inertia/pages/settings/zim/index.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`, `admin/inertia/providers/ModalProvider.tsx`

## admin/inertia/context/NotificationContext.ts

### useNotifications
- Defined: `admin/inertia/context/NotificationContext.ts:20`
- Imported by: `admin/inertia/components/chat/ChatInterface.tsx`, `admin/inertia/components/chat/KbPolicyPromptBanner.tsx`, `admin/inertia/components/chat/KnowledgeBaseModal.tsx`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/lib/util.ts`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/settings/maps.tsx`, `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/system.tsx`, `admin/inertia/pages/settings/update.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`, `admin/inertia/providers/NotificationProvider.tsx`

## admin/inertia/hooks/useDebounce.ts

### useDebounce
- Defined: `admin/inertia/hooks/useDebounce.ts:3`
- Imported by: `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`

### debounce
- Defined: `admin/inertia/hooks/useDebounce.ts:6`
- Imported by: `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`

## admin/inertia/hooks/useDiskDisplayData.ts

### getAllDiskDisplayItems
- Defined: `admin/inertia/hooks/useDiskDisplayData.ts:16`
- Doc: import { Systeminformation } from 'systeminformation' import { formatBytes } from '~/lib/util' type DiskDisplayItem = { 
- Imported by: `admin/inertia/components/TierSelectionModal.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/settings/system.tsx`

### getPrimaryDiskInfo
- Defined: `admin/inertia/hooks/useDiskDisplayData.ts:88`
- Doc: value: fs.use || 0, total: formatBytes(fs.size), used: formatBytes(fs.used), subtext: `${formatBytes(fs.used)} / ${forma
- Imported by: `admin/inertia/components/TierSelectionModal.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/settings/system.tsx`

## admin/inertia/hooks/useDownloads.ts

### useDownloads
- Defined: `admin/inertia/hooks/useDownloads.ts:10`
- Imported by: `admin/inertia/components/ActiveDownloads.tsx`, `admin/inertia/pages/settings/maps.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`

### invalidate
- Defined: `admin/inertia/hooks/useDownloads.ts:29`
- Imported by: `admin/inertia/components/ActiveDownloads.tsx`, `admin/inertia/pages/settings/maps.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`

## admin/inertia/hooks/useEmbedJobs.ts

### useEmbedJobs
- Defined: `admin/inertia/hooks/useEmbedJobs.ts:5`
- Imported by: `admin/inertia/components/ActiveEmbedJobs.tsx`

### invalidate
- Defined: `admin/inertia/hooks/useEmbedJobs.ts:29`
- Imported by: `admin/inertia/components/ActiveEmbedJobs.tsx`

## admin/inertia/hooks/useErrorNotification.ts

### useErrorNotification
- Defined: `admin/inertia/hooks/useErrorNotification.ts:4`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/pages/settings/apps.tsx`

### showError
- Defined: `admin/inertia/hooks/useErrorNotification.ts:7`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/pages/settings/apps.tsx`

## admin/inertia/hooks/useInternetStatus.ts

### useInternetStatus
- Defined: `admin/inertia/hooks/useInternetStatus.ts:6`
- Imported by: `admin/inertia/pages/easy-setup/complete.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/settings/apps.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`

## admin/inertia/hooks/useMapMarkers.ts

### useMapMarkers
- Defined: `admin/inertia/hooks/useMapMarkers.ts:25`
- Imported by: `admin/inertia/components/maps/MapComponent.tsx`, `admin/inertia/components/maps/MapComponent.tsx`, `admin/inertia/components/maps/MarkerPanel.tsx`

## admin/inertia/hooks/useMapRegionFiles.ts

### useMapRegionFiles
- Defined: `admin/inertia/hooks/useMapRegionFiles.ts:5`

## admin/inertia/hooks/useOllamaModelDownloads.ts

### useOllamaModelDownloads
- Defined: `admin/inertia/hooks/useOllamaModelDownloads.ts:25`
- Imported by: `admin/inertia/components/ActiveModelDownloads.tsx`

## admin/inertia/hooks/useServiceInstallationActivity.ts

### useServiceInstallationActivity
- Defined: `admin/inertia/hooks/useServiceInstallationActivity.ts:6`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/components/InstallActivityFeed.tsx`
- Imported by: `admin/inertia/pages/easy-setup/complete.tsx`, `admin/inertia/pages/settings/apps.tsx`

## admin/inertia/hooks/useServiceInstalledStatus.tsx

### useServiceInstalledStatus
- Defined: `admin/inertia/hooks/useServiceInstalledStatus.tsx:5`
- Depends on: `admin/types/services.ts`
- Imported by: `admin/inertia/layouts/AppLayout.tsx`, `admin/inertia/layouts/SettingsLayout.tsx`, `admin/inertia/pages/settings/benchmark.tsx`, `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/zim/index.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`

## admin/inertia/hooks/useSystemInfo.ts

### useSystemInfo
- Defined: `admin/inertia/hooks/useSystemInfo.ts:10`
- Imported by: `admin/inertia/components/TierSelectionModal.tsx`, `admin/inertia/components/TierSelectionModal.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/system.tsx`, `admin/inertia/pages/settings/system.tsx`

## admin/inertia/hooks/useSystemSetting.ts

### useSystemSetting
- Defined: `admin/inertia/hooks/useSystemSetting.ts:12`
- Imported by: `admin/inertia/components/chat/ChatModal.tsx`, `admin/inertia/components/chat/ChatModal.tsx`, `admin/inertia/components/chat/index.tsx`, `admin/inertia/components/chat/index.tsx`, `admin/inertia/components/chat/index.tsx`, `admin/inertia/pages/home.tsx`, `admin/inertia/pages/home.tsx`, `admin/inertia/pages/settings/update.tsx`, `admin/inertia/pages/settings/update.tsx`

## admin/inertia/hooks/useTheme.ts

### getInitialTheme
- Defined: `admin/inertia/hooks/useTheme.ts:7`
- Imported by: `admin/inertia/providers/ThemeProvider.tsx`, `admin/inertia/providers/ThemeProvider.tsx`

### useTheme
- Defined: `admin/inertia/hooks/useTheme.ts:16`
- Imported by: `admin/inertia/providers/ThemeProvider.tsx`, `admin/inertia/providers/ThemeProvider.tsx`

## admin/inertia/hooks/useUpdateAvailable.ts

### useUpdateAvailable
- Defined: `admin/inertia/hooks/useUpdateAvailable.ts:6`
- Imported by: `admin/inertia/pages/home.tsx`, `admin/inertia/pages/home.tsx`

## admin/inertia/layouts/AppLayout.tsx

### AppLayout
- Defined: `admin/inertia/layouts/AppLayout.tsx:11`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/lib/classNames.ts`

## admin/inertia/layouts/DocsLayout.tsx

### DocsLayout
- Defined: `admin/inertia/layouts/DocsLayout.tsx:6`

## admin/inertia/layouts/MapsLayout.tsx

### MapsLayout
- Defined: `admin/inertia/layouts/MapsLayout.tsx:3`

## admin/inertia/layouts/SettingsLayout.tsx

### SettingsLayout
- Defined: `admin/inertia/layouts/SettingsLayout.tsx:20`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/lib/navigation.ts`

## admin/inertia/lib/classNames.ts

### classNames
- Defined: `admin/inertia/lib/classNames.ts:2`
- Imported by: `admin/inertia/components/Alert.tsx`, `admin/inertia/components/Alert.tsx`, `admin/inertia/components/Alert.tsx`, `admin/inertia/components/Alert.tsx`, `admin/inertia/components/Alert.tsx`, `admin/inertia/components/Alert.tsx`, `admin/inertia/components/Alert.tsx`, `admin/inertia/components/CountryPickerModal.tsx`, `admin/inertia/components/CountryPickerModal.tsx`, `admin/inertia/components/CountryPickerModal.tsx`, `admin/inertia/components/DynamicIcon.tsx`, `admin/inertia/components/HorizontalBarChart.tsx`, `admin/inertia/components/HorizontalBarChart.tsx`, `admin/inertia/components/HorizontalBarChart.tsx`, `admin/inertia/components/InstallActivityFeed.tsx`, `admin/inertia/components/InstallActivityFeed.tsx`, `admin/inertia/components/StorageProjectionBar.tsx`, `admin/inertia/components/StorageProjectionBar.tsx`, `admin/inertia/components/StorageProjectionBar.tsx`, `admin/inertia/components/StyledModal.tsx`, `admin/inertia/components/StyledModal.tsx`, `admin/inertia/components/StyledSidebar.tsx`, `admin/inertia/components/StyledTable.tsx`, `admin/inertia/components/StyledTable.tsx`, `admin/inertia/components/StyledTable.tsx`, `admin/inertia/components/StyledTable.tsx`, `admin/inertia/components/StyledTable.tsx`, `admin/inertia/components/StyledTable.tsx`, `admin/inertia/components/TierSelectionModal.tsx`, `admin/inertia/components/TierSelectionModal.tsx`, `admin/inertia/components/WikipediaSelector.tsx`, `admin/inertia/components/WikipediaSelector.tsx`, `admin/inertia/components/WikipediaSelector.tsx`, `admin/inertia/components/chat/ChatInterface.tsx`, `admin/inertia/components/chat/ChatInterface.tsx`, `admin/inertia/components/chat/ChatMessageBubble.tsx`, `admin/inertia/components/chat/ChatMessageBubble.tsx`, `admin/inertia/components/chat/ChatSidebar.tsx`, `admin/inertia/components/chat/ChatSidebar.tsx`, `admin/inertia/components/chat/ChatSidebar.tsx`, `admin/inertia/components/chat/index.tsx`, `admin/inertia/components/chat/index.tsx`, `admin/inertia/components/inputs/Input.tsx`, `admin/inertia/components/inputs/Input.tsx`, `admin/inertia/components/inputs/Input.tsx`, `admin/inertia/components/systeminfo/CircularGauge.tsx`, `admin/inertia/components/systeminfo/CircularGauge.tsx`, `admin/inertia/components/systeminfo/CircularGauge.tsx`, `admin/inertia/components/systeminfo/InfoCard.tsx`, `admin/inertia/components/systeminfo/InfoCard.tsx`, `admin/inertia/layouts/AppLayout.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/easy-setup/index.tsx`

## admin/inertia/lib/collections.ts

### resolveTierResources
- Defined: `admin/inertia/lib/collections.ts:7`
- Doc: Resolve all resources for a tier, including inherited resources from includesTier chain. Shared between frontend compone

### resolveTierResourcesInner
- Defined: `admin/inertia/lib/collections.ts:11`

## admin/inertia/lib/global_map_banner.ts

### hasDownloadedGlobalMap
- Defined: `admin/inertia/lib/global_map_banner.ts:1`
- Imported by: `admin/inertia/pages/settings/maps.tsx`

## admin/inertia/lib/kb_file_grouping.ts

### classifyKbFile
- Defined: `admin/inertia/lib/kb_file_grouping.ts:21`
- Depends on: `admin/util/docs.ts`
- Imported by: `admin/inertia/components/chat/KnowledgeBaseModal.tsx`

### sourceToDisplayName
- Defined: `admin/inertia/lib/kb_file_grouping.ts:34`
- Depends on: `admin/util/docs.ts`
- Imported by: `admin/inertia/components/chat/KnowledgeBaseModal.tsx`

### groupAndSortKbFiles
- Defined: `admin/inertia/lib/kb_file_grouping.ts:67`
- Doc: Group stored-file rows into table rows for the Stored Files panel.  - Admin docs (`/app/docs/*`, README) collapse into a
- Depends on: `admin/util/docs.ts`
- Imported by: `admin/inertia/components/chat/KnowledgeBaseModal.tsx`

## admin/inertia/lib/kb_guardrail.ts

### evaluateGuardrail
- Defined: `admin/inertia/lib/kb_guardrail.ts:47`
- Doc: Decide whether a bulk indexing action should be gated behind the guardrail modal. Caller passes the precomputed embeddin
- Imported by: `admin/inertia/components/TierSelectionModal.tsx`

## admin/inertia/lib/kb_job_health_display.ts

### formatTimeAgo
- Defined: `admin/inertia/lib/kb_job_health_display.ts:45`
- Doc: Format a relative timestamp as "Xs ago", "Xm ago", "Xh ago" with sensible thresholds for the KB Processing Queue's "Last
- Imported by: `admin/inertia/components/ActiveEmbedJobs.tsx`

### computeJobHealthNow
- Defined: `admin/inertia/lib/kb_job_health_display.ts:59`
- Doc: Convenience wrapper that resolves a job's health status without the caller having to remember to pass `now`. Mostly for 
- Imported by: `admin/inertia/components/ActiveEmbedJobs.tsx`

## admin/inertia/lib/navigation.ts

### getServiceLink
- Defined: `admin/inertia/lib/navigation.ts:3`
- Imported by: `admin/inertia/layouts/SettingsLayout.tsx`, `admin/inertia/pages/home.tsx`, `admin/inertia/pages/settings/apps.tsx`

## admin/inertia/lib/util.ts

### setGlobalNotificationCallback
- Defined: `admin/inertia/lib/util.ts:6`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### capitalizeFirstLetter
- Defined: `admin/inertia/lib/util.ts:10`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### formatBytes
- Defined: `admin/inertia/lib/util.ts:15`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### generateRandomString
- Defined: `admin/inertia/lib/util.ts:24`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### generateUUID
- Defined: `admin/inertia/lib/util.ts:33`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### that
- Defined: `admin/inertia/lib/util.ts:69`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### to
- Defined: `admin/inertia/lib/util.ts:69`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### to
- Defined: `admin/inertia/lib/util.ts:70`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### that
- Defined: `admin/inertia/lib/util.ts:71`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### and
- Defined: `admin/inertia/lib/util.ts:71`
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### catchInternal
- Defined: `admin/inertia/lib/util.ts:73`
- Doc: A higher-order function that wraps an asynchronous function to catch and log internal errors. @param fn The asynchronous
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

### extractFileName
- Defined: `admin/inertia/lib/util.ts:57`
- Doc: Extracts the file name from a given path while handling both forward and backward slashes. @param path The full file pat
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`

## admin/inertia/pages/about.tsx

### About
- Defined: `admin/inertia/pages/about.tsx:3`

## admin/inertia/pages/chat.tsx

### Chat
- Defined: `admin/inertia/pages/chat.tsx:4`

## admin/inertia/pages/docs/show.tsx

### Show
- Defined: `admin/inertia/pages/docs/show.tsx:5`
- Imported by: `admin/app/controllers/benchmark_controller.ts`, `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/docs_controller.ts`

## admin/inertia/pages/easy-setup/complete.tsx

### EasySetupWizardComplete
- Defined: `admin/inertia/pages/easy-setup/complete.tsx:11`
- Depends on: `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`
- Imported by: `admin/app/controllers/easy_setup_controller.ts`

## admin/inertia/pages/easy-setup/index.tsx

### buildCoreCapabilities
- Defined: `admin/inertia/pages/easy-setup/index.tsx:35`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### EasySetupWizard
- Defined: `admin/inertia/pages/easy-setup/index.tsx:115`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### toggleMapCollection
- Defined: `admin/inertia/pages/easy-setup/index.tsx:215`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### toggleAiModel
- Defined: `admin/inertia/pages/easy-setup/index.tsx:221`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### handleCategoryClick
- Defined: `admin/inertia/pages/easy-setup/index.tsx:228`
- Doc: Category/tier handlers
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### handleTierSelect
- Defined: `admin/inertia/pages/easy-setup/index.tsx:234`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### closeTierModal
- Defined: `admin/inertia/pages/easy-setup/index.tsx:247`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### getSelectedTierResources
- Defined: `admin/inertia/pages/easy-setup/index.tsx:253`
- Doc: Get all resources from selected tiers for storage projection
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### unit
- Defined: `admin/inertia/pages/easy-setup/index.tsx:293`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### canProceedToNextStep
- Defined: `admin/inertia/pages/easy-setup/index.tsx:334`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### handleNext
- Defined: `admin/inertia/pages/easy-setup/index.tsx:340`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### handleBack
- Defined: `admin/inertia/pages/easy-setup/index.tsx:347`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### handleFinish
- Defined: `admin/inertia/pages/easy-setup/index.tsx:354`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### msg
- Defined: `admin/inertia/pages/easy-setup/index.tsx:385`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### markAsVisited
- Defined: `admin/inertia/pages/easy-setup/index.tsx:460`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### renderStepIndicator
- Defined: `admin/inertia/pages/easy-setup/index.tsx:472`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### isCapabilitySelected
- Defined: `admin/inertia/pages/easy-setup/index.tsx:562`
- Doc: Check if a capability is selected (all its services are in selectedServices)
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### isCapabilityInstalled
- Defined: `admin/inertia/pages/easy-setup/index.tsx:567`
- Doc: Check if a capability is already installed (all its services are installed)
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### capabilityExists
- Defined: `admin/inertia/pages/easy-setup/index.tsx:574`
- Doc: Check if a capability exists in the system (has at least one matching service)
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### toggleCapability
- Defined: `admin/inertia/pages/easy-setup/index.tsx:581`
- Doc: Toggle all services for a capability (only if not already installed)
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### renderCapabilityCard
- Defined: `admin/inertia/pages/easy-setup/index.tsx:621`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### renderStep1
- Defined: `admin/inertia/pages/easy-setup/index.tsx:723`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### renderStep2
- Defined: `admin/inertia/pages/easy-setup/index.tsx:843`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### renderStep3
- Defined: `admin/inertia/pages/easy-setup/index.tsx:889`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### renderStep4
- Defined: `admin/inertia/pages/easy-setup/index.tsx:991`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

### renderStep5
- Defined: `admin/inertia/pages/easy-setup/index.tsx:1134`
- Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`

## admin/inertia/pages/errors/not_found.tsx

### NotFound
- Defined: `admin/inertia/pages/errors/not_found.tsx:1`

## admin/inertia/pages/errors/server_error.tsx

### ServerError
- Defined: `admin/inertia/pages/errors/server_error.tsx:1`

## admin/inertia/pages/home.tsx

### Home
- Defined: `admin/inertia/pages/home.tsx:87`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/hooks/useSystemSetting.ts`, `admin/inertia/hooks/useUpdateAvailable.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/home_controller.ts`

### tileContent
- Defined: `admin/inertia/pages/home.tsx:160`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/hooks/useSystemSetting.ts`, `admin/inertia/hooks/useUpdateAvailable.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/home_controller.ts`

## admin/inertia/pages/maps.tsx

### Maps
- Defined: `admin/inertia/pages/maps.tsx:12`

## admin/inertia/pages/settings/apps.tsx

### extractTag
- Defined: `admin/inertia/pages/settings/apps.tsx:20`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### SettingsPage
- Defined: `admin/inertia/pages/settings/apps.tsx:27`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleCheckUpdates
- Defined: `admin/inertia/pages/settings/apps.tsx:60`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### installService
- Defined: `admin/inertia/pages/settings/apps.tsx:103`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleAffectAction
- Defined: `admin/inertia/pages/settings/apps.tsx:126`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleForceReinstall
- Defined: `admin/inertia/pages/settings/apps.tsx:149`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleUpdateService
- Defined: `admin/inertia/pages/settings/apps.tsx:172`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleInstallService
- Defined: `admin/inertia/pages/settings/apps.tsx:78`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### AppActions
- Defined: `admin/inertia/pages/settings/apps.tsx:202`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### ForceReinstallButton
- Defined: `admin/inertia/pages/settings/apps.tsx:203`
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

## admin/inertia/pages/settings/benchmark.tsx

### BenchmarkPage
- Defined: `admin/inertia/pages/settings/benchmark.tsx:30`
- Depends on: `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### handleFullBenchmarkClick
- Defined: `admin/inertia/pages/settings/benchmark.tsx:198`
- Doc: Handle Full Benchmark click with pre-flight check
- Depends on: `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### advanceStage
- Defined: `admin/inertia/pages/settings/benchmark.tsx:277`
- Depends on: `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### formatBytes
- Defined: `admin/inertia/pages/settings/benchmark.tsx:321`
- Depends on: `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### getScoreColor
- Defined: `admin/inertia/pages/settings/benchmark.tsx:326`
- Depends on: `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### getProgressPercent
- Defined: `admin/inertia/pages/settings/benchmark.tsx:332`
- Depends on: `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### getAIScore
- Defined: `admin/inertia/pages/settings/benchmark.tsx:353`
- Doc: Calculate AI score from tokens per second (normalized to 0-100) Reference: 30 tok/s = 50 score, 60 tok/s = 100 score
- Depends on: `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### score
- Defined: `admin/inertia/pages/settings/benchmark.tsx:355`
- Depends on: `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

## admin/inertia/pages/settings/legal.tsx

### LegalPage
- Defined: `admin/inertia/pages/settings/legal.tsx:4`
- Imported by: `admin/app/controllers/settings_controller.ts`

## admin/inertia/pages/settings/maps.tsx

### MapsManager
- Defined: `admin/inertia/pages/settings/maps.tsx:26`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`

### downloadBaseAssets
- Defined: `admin/inertia/pages/settings/maps.tsx:83`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`

### downloadCollection
- Defined: `admin/inertia/pages/settings/maps.tsx:110`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`

### downloadCustomFile
- Defined: `admin/inertia/pages/settings/maps.tsx:123`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`

### deleteFile
- Defined: `admin/inertia/pages/settings/maps.tsx:136`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`

### confirmDeleteFile
- Defined: `admin/inertia/pages/settings/maps.tsx:159`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`

### confirmDownload
- Defined: `admin/inertia/pages/settings/maps.tsx:179`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`

### confirmGlobalMapDownload
- Defined: `admin/inertia/pages/settings/maps.tsx:213`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`

### openCountryPickerModal
- Defined: `admin/inertia/pages/settings/maps.tsx:236`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`

### openDownloadModal
- Defined: `admin/inertia/pages/settings/maps.tsx:254`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`

## admin/inertia/pages/settings/models.tsx

### ModelsPage
- Defined: `admin/inertia/pages/settings/models.tsx:25`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/hooks/useSystemInfo.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleSaveRemoteOllama
- Defined: `admin/inertia/pages/settings/models.tsx:108`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/hooks/useSystemInfo.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleClearRemoteOllama
- Defined: `admin/inertia/pages/settings/models.tsx:125`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/hooks/useSystemInfo.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleForceRefresh
- Defined: `admin/inertia/pages/settings/models.tsx:175`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/hooks/useSystemInfo.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleInstallModel
- Defined: `admin/inertia/pages/settings/models.tsx:183`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/hooks/useSystemInfo.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleDeleteModel
- Defined: `admin/inertia/pages/settings/models.tsx:201`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/hooks/useSystemInfo.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### confirmDeleteModel
- Defined: `admin/inertia/pages/settings/models.tsx:221`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/hooks/useSystemInfo.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleDismissGpuBanner
- Defined: `admin/inertia/pages/settings/models.tsx:48`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/hooks/useSystemInfo.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

### handleForceReinstallOllama
- Defined: `admin/inertia/pages/settings/models.tsx:55`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/hooks/useSystemInfo.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

## admin/inertia/pages/settings/support.tsx

### SupportPage
- Defined: `admin/inertia/pages/settings/support.tsx:5`
- Imported by: `admin/app/controllers/settings_controller.ts`

## admin/inertia/pages/settings/system.tsx

### SettingsPage
- Defined: `admin/inertia/pages/settings/system.tsx:19`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`

### handleDismissGpuBanner
- Defined: `admin/inertia/pages/settings/system.tsx:37`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`

### handleForceReinstallOllama
- Defined: `admin/inertia/pages/settings/system.tsx:44`
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`

## admin/inertia/pages/settings/update.tsx

### ContentUpdatesSection
- Defined: `admin/inertia/pages/settings/update.tsx:43`
- Depends on: `admin/app/utils/version.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/providers/qdrant_restart_policy_provider.ts`, `admin/providers/qdrant_restart_policy_provider.ts`

### SystemUpdatePage
- Defined: `admin/inertia/pages/settings/update.tsx:260`
- Depends on: `admin/app/utils/version.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/providers/qdrant_restart_policy_provider.ts`, `admin/providers/qdrant_restart_policy_provider.ts`

### handleCheck
- Defined: `admin/inertia/pages/settings/update.tsx:52`
- Depends on: `admin/app/utils/version.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/providers/qdrant_restart_policy_provider.ts`, `admin/providers/qdrant_restart_policy_provider.ts`

### handleApply
- Defined: `admin/inertia/pages/settings/update.tsx:70`
- Depends on: `admin/app/utils/version.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/providers/qdrant_restart_policy_provider.ts`, `admin/providers/qdrant_restart_policy_provider.ts`

### handleApplyAll
- Defined: `admin/inertia/pages/settings/update.tsx:99`
- Depends on: `admin/app/utils/version.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/providers/qdrant_restart_policy_provider.ts`, `admin/providers/qdrant_restart_policy_provider.ts`

### handleStartUpdate
- Defined: `admin/inertia/pages/settings/update.tsx:338`
- Depends on: `admin/app/utils/version.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/providers/qdrant_restart_policy_provider.ts`, `admin/providers/qdrant_restart_policy_provider.ts`

### handleViewLogs
- Defined: `admin/inertia/pages/settings/update.tsx:353`
- Depends on: `admin/app/utils/version.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/providers/qdrant_restart_policy_provider.ts`, `admin/providers/qdrant_restart_policy_provider.ts`

### getProgressBarColor
- Defined: `admin/inertia/pages/settings/update.tsx:394`
- Depends on: `admin/app/utils/version.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/providers/qdrant_restart_policy_provider.ts`, `admin/providers/qdrant_restart_policy_provider.ts`

### getStatusIcon
- Defined: `admin/inertia/pages/settings/update.tsx:400`
- Depends on: `admin/app/utils/version.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/providers/qdrant_restart_policy_provider.ts`, `admin/providers/qdrant_restart_policy_provider.ts`

## admin/inertia/pages/settings/zim/index.tsx

### ZimPage
- Defined: `admin/inertia/pages/settings/zim/index.tsx:20`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### getFiles
- Defined: `admin/inertia/pages/settings/zim/index.tsx:31`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### toggleSort
- Defined: `admin/inertia/pages/settings/zim/index.tsx:55`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### renderSortHeader
- Defined: `admin/inertia/pages/settings/zim/index.tsx:64`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### confirmDeleteFile
- Defined: `admin/inertia/pages/settings/zim/index.tsx:79`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### aName
- Defined: `admin/inertia/pages/settings/zim/index.tsx:46`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### bName
- Defined: `admin/inertia/pages/settings/zim/index.tsx:47`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

## admin/inertia/pages/settings/zim/remote-explorer.tsx

### ZimRemoteExplorer
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:54`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### confirmDownload
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:238`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### confirmCustomDownload
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:263`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### downloadFile
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:288`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### downloadCustomFile
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:302`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### handleSourceChange
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:210`
- Doc: When selecting a custom library, navigate to its root
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### navigateToDirectory
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:227`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### navigateToBreadcrumb
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:232`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### handleCategoryClick
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:323`
- Doc: Category/tier handlers
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### handleTierSelect
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:329`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### closeTierModal
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:350`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### handleWikipediaSelect
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:356`
- Doc: Wikipedia selection handlers
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

### handleWikipediaSubmit
- Defined: `admin/inertia/pages/settings/zim/remote-explorer.tsx:361`
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`

## admin/inertia/providers/ModalProvider.tsx

### openModal
- Defined: `admin/inertia/providers/ModalProvider.tsx:12`
- Depends on: `admin/inertia/context/ModalContext.ts`

### closeModal
- Defined: `admin/inertia/providers/ModalProvider.tsx:20`
- Depends on: `admin/inertia/context/ModalContext.ts`

### closeAllModals
- Defined: `admin/inertia/providers/ModalProvider.tsx:31`
- Depends on: `admin/inertia/context/ModalContext.ts`

### _getCurrentModals
- Defined: `admin/inertia/providers/ModalProvider.tsx:36`
- Depends on: `admin/inertia/context/ModalContext.ts`

## admin/inertia/providers/NotificationProvider.tsx

### NotificationsProvider
- Defined: `admin/inertia/providers/NotificationProvider.tsx:6`
- Depends on: `admin/inertia/context/NotificationContext.ts`

### addNotification
- Defined: `admin/inertia/providers/NotificationProvider.tsx:9`
- Depends on: `admin/inertia/context/NotificationContext.ts`

### removeNotification
- Defined: `admin/inertia/providers/NotificationProvider.tsx:29`
- Depends on: `admin/inertia/context/NotificationContext.ts`

### removeAllNotifications
- Defined: `admin/inertia/providers/NotificationProvider.tsx:33`
- Depends on: `admin/inertia/context/NotificationContext.ts`

### Icon
- Defined: `admin/inertia/providers/NotificationProvider.tsx:37`
- Depends on: `admin/inertia/context/NotificationContext.ts`

## admin/inertia/providers/ThemeProvider.tsx

### ThemeProvider
- Defined: `admin/inertia/providers/ThemeProvider.tsx:16`
- Depends on: `admin/inertia/hooks/useTheme.ts`
- Imported by: `admin/inertia/app/app.tsx`, `admin/inertia/components/ThemeToggle.tsx`

### useThemeContext
- Defined: `admin/inertia/providers/ThemeProvider.tsx:25`
- Depends on: `admin/inertia/hooks/useTheme.ts`
- Imported by: `admin/inertia/app/app.tsx`, `admin/inertia/components/ThemeToggle.tsx`

## admin/providers/gpu_passthrough_remediation_provider.ts

### KVStore
- Defined: `admin/providers/gpu_passthrough_remediation_provider.ts:31`

### Docker
- Defined: `admin/providers/gpu_passthrough_remediation_provider.ts:34`

## admin/providers/kiwix_migration_provider.ts

### Service
- Defined: `admin/providers/kiwix_migration_provider.ts:22`

## admin/providers/qdrant_restart_policy_provider.ts

### Service
- Defined: `admin/providers/qdrant_restart_policy_provider.ts:22`
- Depends on: `admin/inertia/pages/settings/update.tsx`

### Docker
- Defined: `admin/providers/qdrant_restart_policy_provider.ts:24`
- Depends on: `admin/inertia/pages/settings/update.tsx`

## admin/providers/version_check_provider.ts

### KVStore
- Defined: `admin/providers/version_check_provider.ts:30`

### cachedLatest
- Defined: `admin/providers/version_check_provider.ts:42`

### earlyAccess
- Defined: `admin/providers/version_check_provider.ts:43`

## admin/tests/bootstrap.ts

### to
- Defined: `admin/tests/bootstrap.ts:18`

## admin/tests/unit/cloud_metadata_url.spec.ts

### expectBlocked
- Defined: `admin/tests/unit/cloud_metadata_url.spec.ts:6`

### expectAllowed
- Defined: `admin/tests/unit/cloud_metadata_url.spec.ts:10`

## admin/tests/unit/kb_file_grouping.spec.ts

### asInfos
- Defined: `admin/tests/unit/kb_file_grouping.spec.ts:15`
- Doc: Wrap source paths into the minimal StoredFileInfo shape that `groupAndSortKbFiles` now expects. State + chunk count are 

## admin/util/docs.ts

### streamToString
- Defined: `admin/util/docs.ts:2`
- Imported by: `admin/inertia/lib/kb_file_grouping.ts`, `admin/inertia/lib/kb_file_grouping.ts`

## admin/util/files.ts

### chmodRecursive
- Defined: `admin/util/files.ts:4`

### chownRecursive
- Defined: `admin/util/files.ts:30`

## admin/util/zim.ts

### isRawListRemoteZimFilesResponse
- Defined: `admin/util/zim.ts:3`

### isRawRemoteZimFileEntry
- Defined: `admin/util/zim.ts:21`

## install/install_nomad.sh

### header
- Defined: `install/install_nomad.sh:47`

### header_red
- Defined: `install/install_nomad.sh:52`

### check_has_sudo
- Defined: `install/install_nomad.sh:57`

### check_is_bash
- Defined: `install/install_nomad.sh:69`

### check_is_debian_based
- Defined: `install/install_nomad.sh:79`

### check_is_x86_64
- Defined: `install/install_nomad.sh:89`

### ensure_dependencies_installed
- Defined: `install/install_nomad.sh:104`

### check_is_debug_mode
- Defined: `install/install_nomad.sh:140`

### generateRandomPass
- Defined: `install/install_nomad.sh:149`

### ensure_docker_installed
- Defined: `install/install_nomad.sh:159`

### check_docker_compose
- Defined: `install/install_nomad.sh:220`

### setup_nvidia_container_toolkit
- Defined: `install/install_nomad.sh:230`

### get_install_confirmation
- Defined: `install/install_nomad.sh:355`

### accept_terms
- Defined: `install/install_nomad.sh:370`

### create_nomad_directory
- Defined: `install/install_nomad.sh:391`

### download_management_compose_file
- Defined: `install/install_nomad.sh:410`

### download_helper_scripts
- Defined: `install/install_nomad.sh:445`

### start_management_containers
- Defined: `install/install_nomad.sh:472`

### get_local_ip
- Defined: `install/install_nomad.sh:481`

### verify_gpu_setup
- Defined: `install/install_nomad.sh:488`

### success_message
- Defined: `install/install_nomad.sh:598`

## install/migrate-disk-collector.sh

### check_is_bash
- Defined: `install/migrate-disk-collector.sh:46`

### check_has_sudo
- Defined: `install/migrate-disk-collector.sh:55`

### check_confirmation
- Defined: `install/migrate-disk-collector.sh:65`

### check_docker_running
- Defined: `install/migrate-disk-collector.sh:81`

### check_compose_file
- Defined: `install/migrate-disk-collector.sh:93`

### stop_old_host_process
- Defined: `install/migrate-disk-collector.sh:103`
- Doc: Step 1: Stop old host process

### backup_compose_file
- Defined: `install/migrate-disk-collector.sh:122`
- Doc: Step 2: Backup compose.yml

### remove_old_bind_mount
- Defined: `install/migrate-disk-collector.sh:134`
- Doc: Step 3: Remove old bind-mount from admin volumes

### add_disk_collector_service
- Defined: `install/migrate-disk-collector.sh:153`
- Doc: Step 4: Add disk-collector service block

### restart_stack
- Defined: `install/migrate-disk-collector.sh:186`
- Doc: Step 5 — Pull new image and restart the full stack This will re-create the admin container and drop the old /tmp bind, a

### verify_disk_collector_running
- Defined: `install/migrate-disk-collector.sh:203`
- Doc: Step 6: Verify

## install/run_updater_fixes.sh

### check_is_bash
- Defined: `install/run_updater_fixes.sh:55`

### check_confirmation
- Defined: `install/run_updater_fixes.sh:64`

### check_has_sudo
- Defined: `install/run_updater_fixes.sh:75`

### check_docker_running
- Defined: `install/run_updater_fixes.sh:85`

### check_compose_file
- Defined: `install/run_updater_fixes.sh:97`

### check_sidecar_dir
- Defined: `install/run_updater_fixes.sh:106`

### backup_compose_file
- Defined: `install/run_updater_fixes.sh:119`

### fix_sidecar_volume_mount
- Defined: `install/run_updater_fixes.sh:130`

### download_updated_sidecar_files
- Defined: `install/run_updater_fixes.sh:153`

### rebuild_sidecar
- Defined: `install/run_updater_fixes.sh:170`

### restart_sidecar
- Defined: `install/run_updater_fixes.sh:179`

### verify_sidecar_running
- Defined: `install/run_updater_fixes.sh:197`

## install/sidecar-disk-collector/collect-disk-info.sh

### log
- Defined: `install/sidecar-disk-collector/collect-disk-info.sh:9`

## install/sidecar-updater/update-watcher.sh

### log
- Defined: `install/sidecar-updater/update-watcher.sh:12`

### write_status
- Defined: `install/sidecar-updater/update-watcher.sh:16`

### perform_update
- Defined: `install/sidecar-updater/update-watcher.sh:31`

### cleanup
- Defined: `install/sidecar-updater/update-watcher.sh:111`

## install/uninstall_nomad.sh

### check_has_sudo
- Defined: `install/uninstall_nomad.sh:27`

### check_current_directory
- Defined: `install/uninstall_nomad.sh:39`

### ensure_management_compose_file_exists
- Defined: `install/uninstall_nomad.sh:46`

### get_uninstall_confirmation
- Defined: `install/uninstall_nomad.sh:53`

### ensure_docker_installed
- Defined: `install/uninstall_nomad.sh:71`

### check_docker_compose
- Defined: `install/uninstall_nomad.sh:78`

### storage_cleanup
- Defined: `install/uninstall_nomad.sh:88`

### uninstall_nomad
- Defined: `install/uninstall_nomad.sh:105`

## install/update_nomad.sh

### check_has_sudo
- Defined: `install/update_nomad.sh:31`

### check_is_bash
- Defined: `install/update_nomad.sh:43`

### check_is_debian_based
- Defined: `install/update_nomad.sh:53`

### get_update_confirmation
- Defined: `install/update_nomad.sh:63`

### ensure_docker_installed_and_running
- Defined: `install/update_nomad.sh:81`

### check_docker_compose
- Defined: `install/update_nomad.sh:97`

### ensure_docker_compose_file_exists
- Defined: `install/update_nomad.sh:107`

### force_recreate
- Defined: `install/update_nomad.sh:114`

### get_local_ip
- Defined: `install/update_nomad.sh:128`

### success_message
- Defined: `install/update_nomad.sh:136`
