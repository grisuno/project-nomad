# API (page 1 of 2)
Pages: [API.md](API.md), [API_p2.md](API_p2.md)

## admin/app/controllers/benchmark_controller.ts
Depends on: `admin/app/jobs/run_benchmark_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/validators/settings.ts`, `admin/commands/benchmark/results.ts`, `admin/commands/benchmark/run.ts`, `admin/commands/benchmark/submit.ts`, `admin/inertia/pages/docs/show.tsx`
- `statusCode` (function) `admin/app/controllers/benchmark_controller.ts:185` -- Pass through the status code from the service if available, otherwise default to 400

## admin/app/jobs/embed_file_job.ts
Depends on: `admin/app/services/docker_service.ts`, `admin/app/services/ollama_service.ts`, `admin/app/services/queue_service.ts`, `admin/app/services/rag_service.ts`, `admin/config/queue.ts`, `admin/constants/zim_extraction.ts`, `admin/inertia/pages/settings/update.tsx`, `admin/types/services.ts`
Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_download_job.ts`, `admin/commands/queue/work.ts`
- `onProgress` (function) `admin/app/jobs/embed_file_job.ts:116` -- Progress callback.
- `articlesDone` (function) `admin/app/jobs/embed_file_job.ts:119`
- `nextOffset` (function) `admin/app/jobs/embed_file_job.ts:144`
- `totalChunks` (function) `admin/app/jobs/embed_file_job.ts:196` -- Final batch or non-batched file - mark as complete
- `filePath` (function) `admin/app/jobs/embed_file_job.ts:394`

## admin/app/jobs/run_download_job.ts
Depends on: `admin/app/jobs/embed_file_job.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/queue_service.ts`, `admin/app/services/zim_service.ts`, `admin/config/queue.ts`, `admin/inertia/pages/settings/update.tsx`
Imported by: `admin/app/services/collection_manifest_service.ts`, `admin/app/services/collection_update_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/zim_service.ts`, `admin/commands/queue/work.ts`
- `progressPercent` (function) `admin/app/jobs/run_download_job.ts:86`

## admin/app/services/benchmark_service.ts
Depends on: `admin/app/services/docker_service.ts`, `admin/app/services/system_service.ts`, `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/pages/settings/update.tsx`
Imported by: `admin/app/controllers/benchmark_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/run_benchmark_job.ts`
- `totalTime` (function) `admin/app/services/benchmark_service.ts:504`

## admin/app/services/container_registry_service.ts
Depends on: `admin/app/utils/version.ts`
Imported by: `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`
- `data` (function) `admin/app/services/container_registry_service.ts:104`
- `data` (function) `admin/app/services/container_registry_service.ts:137`
- `manifest` (function) `admin/app/services/container_registry_service.ts:177`
- `manifest` (function) `admin/app/services/container_registry_service.ts:236`
- `childManifest` (function) `admin/app/services/container_registry_service.ts:256`
- `config` (function) `admin/app/services/container_registry_service.ts:278`

## admin/app/services/countries_service.ts
Depends on: `admin/inertia/pages/settings/update.tsx`
Imported by: `admin/app/services/map_service.ts`
- `codes` (function) `admin/app/services/countries_service.ts:144`
- `typeRank` (function) `admin/app/services/countries_service.ts:215`
- `resolveIso2` (function) `admin/app/services/countries_service.ts:225`
- `bufferGeometry` (function) `admin/app/services/countries_service.ts:242`
- `bufferPolygonRings` (function) `admin/app/services/countries_service.ts:258`
- `bufferRing` (function) `admin/app/services/countries_service.ts:262`
- `n1x` (function) `admin/app/services/countries_service.ts:278`
- `n1y` (function) `admin/app/services/countries_service.ts:279`
- `n2x` (function) `admin/app/services/countries_service.ts:280`
- `n2y` (function) `admin/app/services/countries_service.ts:281`
- `signedArea` (function) `admin/app/services/countries_service.ts:290`
- `resolveIso3` (function) `admin/app/services/countries_service.ts:298`

## admin/app/services/docker_service.ts
Depends on: `admin/app/services/kiwix_library_service.ts`, `admin/app/utils/fs.ts`, `admin/app/utils/version.ts`, `admin/constants/broadcast.ts`, `admin/constants/kiwix.ts`, `admin/constants/service_names.ts`, `admin/inertia/pages/settings/update.tsx`
Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_service_updates_job.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_benchmark_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/zim_service.ts`
- `used` (function) `admin/app/services/docker_service.ts:548`
- `is` (function) `admin/app/services/docker_service.ts:826`
- `marker` (function) `admin/app/services/docker_service.ts:934`
- `gfx` (function) `admin/app/services/docker_service.ts:1043`

## admin/app/services/kiwix_library_service.ts
Depends on: `admin/app/utils/fs.ts`
Imported by: `admin/app/services/docker_service.ts`, `admin/app/services/zim_service.ts`
- `getMeta` (function) `admin/app/services/kiwix_library_service.ts:65`

## admin/app/services/map_service.ts
Depends on: `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/utils/fs.ts`, `admin/app/validators/common.ts`, `admin/constants/map_regions.ts`, `admin/inertia/pages/settings/update.tsx`
Imported by: `admin/app/controllers/maps_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/run_download_job.ts`
- `files` (function) `admin/app/services/map_service.ts:84`
- `regions` (function) `admin/app/services/map_service.ts:326`
- `unit` (function) `admin/app/services/map_service.ts:768`
- `getHost` (function) `admin/app/services/map_service.ts:839`
- `specifiedHostOrDefault` (function) `admin/app/services/map_service.ts:851`
- `findExactGroupMatch` (function) `admin/app/services/map_service.ts:877`

## admin/app/services/ollama_service.ts
Depends on: `admin/app/jobs/download_model_job.ts`, `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/types/services.ts`
Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/services/chat_service.ts`, `admin/app/services/rag_service.ts`
- `customUrl` (function) `admin/app/services/ollama_service.ts:64` -- Check KVStore for a custom base URL (remote Ollama, LM Studio, llama.cpp, etc.)
- `onAbort` (function) `admin/app/services/ollama_service.ts:187` -- If the abort fires after headers are received but mid-stream, axios's signal handling destroys the stream which...
- `stream` (function) `admin/app/services/ollama_service.ts:367`
- `partialTagSuffix` (function) `admin/app/services/ollama_service.ts:370` -- Returns how many trailing chars of `text` could be the start of `tag`
- `parsePulls` (function) `admin/app/services/ollama_service.ts:860`
- `parseSize` (function) `admin/app/services/ollama_service.ts:879`

## admin/app/services/rag_service.ts
Depends on: `admin/app/services/docker_service.ts`, `admin/app/services/ollama_service.ts`, `admin/app/services/zim_extraction_service.ts`, `admin/app/utils/fs.ts`, `admin/app/utils/kb_ingest_decision.ts`, `admin/app/utils/kb_warning_decision.ts`, `admin/constants/service_names.ts`, `admin/constants/zim_extraction.ts`
Imported by: `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/embed_file_job.ts`
- `progress` (function) `admin/app/services/rag_service.ts:373`

## admin/app/services/system_service.ts
Depends on: `admin/app/services/docker_service.ts`, `admin/app/utils/fs.ts`, `admin/app/utils/version.ts`, `admin/config/inertia.ts`, `admin/constants/service_names.ts`, `admin/types/services.ts`
Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/easy_setup_controller.ts`, `admin/app/controllers/home_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/controllers/system_controller.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/config/inertia.ts`
- `buf` (function) `admin/app/services/system_service.ts:131`
- `actualImage` (function) `admin/app/services/system_service.ts:251`
- `isDiscreteGpuVendor` (function) `admin/app/services/system_service.ts:440`
- `isBogusDgpuVram` (function) `admin/app/services/system_service.ts:442`
- `hasLspciBogusDgpuVram` (function) `admin/app/services/system_service.ts:452` -- Clear the bogus value up front.
- `earlyAccess` (function) `admin/app/services/system_service.ts:630`

## admin/app/utils/downloads.ts
Depends on: `admin/app/utils/fs.ts`
- `doResumableDownload` (function) `admin/app/utils/downloads.ts:18` -- Perform a resumable download with progress tracking @param param0 - Download parameters.
- `fetchStream` (function) `admin/app/utils/downloads.ts:96`
- `clearStallTimer` (function) `admin/app/utils/downloads.ts:128`
- `resetStallTimer` (function) `admin/app/utils/downloads.ts:135`
- `cleanup` (function) `admin/app/utils/downloads.ts:171`
- `doResumableDownloadWithRetry` (function) `admin/app/utils/downloads.ts:226`
- `delay` (function) `admin/app/utils/downloads.ts:284`

## admin/app/utils/fs.ts
Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/collection_update_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/docs_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/kiwix_library_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/system_update_service.ts`, `admin/app/services/zim_extraction_service.ts`, `admin/app/services/zim_service.ts`, `admin/app/utils/downloads.ts`
- `listDirectoryContents` (function) `admin/app/utils/fs.ts:10`
- `listDirectoryContentsRecursive` (function) `admin/app/utils/fs.ts:31`
- `ensureDirectoryExists` (function) `admin/app/utils/fs.ts:50`
- `getFile` (function) `admin/app/utils/fs.ts:60`
- `getFile` (function) `admin/app/utils/fs.ts:61`
- `getFile` (function) `admin/app/utils/fs.ts:65`
- `getFile` (function) `admin/app/utils/fs.ts:66`
- `getFileStatsIfExists` (function) `admin/app/utils/fs.ts:85`
- `isValidZimFile` (function) `admin/app/utils/fs.ts:108` -- Validates that a file has the ZIM magic number (0x44D495A).
- `deleteFileIfExists` (function) `admin/app/utils/fs.ts:124`
- `getAllFilesystems` (function) `admin/app/utils/fs.ts:134`
- `traverse` (function) `admin/app/utils/fs.ts:141`
- `matchesDevice` (function) `admin/app/utils/fs.ts:160`
- `determineFileType` (function) `admin/app/utils/fs.ts:177`
- `sanitizeFilename` (function) `admin/app/utils/fs.ts:199` -- Sanitize a filename by removing potentially dangerous characters. @param filename The original filename @returns The...

## admin/app/utils/kb_ingest_decision.ts
Imported by: `admin/app/services/rag_service.ts`, `admin/tests/unit/kb_ingest_decision.spec.ts`
- `decideScanAction` (function) `admin/app/utils/kb_ingest_decision.ts:44` -- Decide what scanAndSyncStorage should do for a single embeddable file.

## admin/app/utils/kb_job_health.ts
Imported by: `admin/inertia/lib/kb_job_health_display.ts`, `admin/tests/unit/kb_job_health.spec.ts`
- `computeJobHealth` (function) `admin/app/utils/kb_job_health.ts:32`

## admin/app/utils/kb_ratio_lookup.ts
Imported by: `admin/app/models/kb_ratio_registry.ts`, `admin/tests/unit/kb_ratio_lookup.spec.ts`
- `estimateBatch` (function) `admin/app/utils/kb_ratio_lookup.ts:38` -- Aggregate an embedding-disk-cost estimate across a batch of files (curated tier add, multi-upload, sync preview, etc).
- `findChunksPerMb` (function) `admin/app/utils/kb_ratio_lookup.ts:70` -- Pick the chunks_per_mb estimate for a filename by longest-prefix match.
- `estimateChunkCount` (function) `admin/app/utils/kb_ratio_lookup.ts:88` -- Estimate the number of embedding chunks a ZIM-style file will produce given its size on disk in bytes.

## admin/app/utils/kb_warning_decision.ts
Imported by: `admin/app/services/rag_service.ts`, `admin/tests/unit/kb_warning_decision.spec.ts`
- `decideWarnings` (function) `admin/app/utils/kb_warning_decision.ts:41`

## admin/app/utils/misc.ts
Imported by: `admin/inertia/components/chat/ChatModal.tsx`
- `formatSpeed` (function) `admin/app/utils/misc.ts:1`
- `toTitleCase` (function) `admin/app/utils/misc.ts:7`
- `parseBoolean` (function) `admin/app/utils/misc.ts:15`

## admin/app/utils/version.ts
Imported by: `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/container_registry_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/system_service.ts`, `admin/inertia/components/UpdateServiceModal.tsx`, `admin/inertia/pages/settings/update.tsx`
- `isNewerVersion` (function) `admin/app/utils/version.ts:7` -- Compare two semantic version strings to determine if the first is newer than the second. @param version1 - The...
- `normalize` (function) `admin/app/utils/version.ts:8`
- `parseMajorVersion` (function) `admin/app/utils/version.ts:45` -- Parse the major version number from a tag string.

## admin/app/utils/zim_filename.ts
Imported by: `admin/app/services/zim_service.ts`, `admin/tests/unit/zim_filename.spec.ts`
- `zimFilenameStem` (function) `admin/app/utils/zim_filename.ts:7` -- Strip the trailing `_YYYY-MM(-DD).zim` date suffix from a Kiwix-style ZIM filename so different release dates of the...
- `findReplacedWikipediaFiles` (function) `admin/app/utils/zim_filename.ts:17` -- Of the existing files, return only those that are prior-version replacements of `currentFilename` — same Wikipedia...

## admin/app/validators/common.ts
Imported by: `admin/app/controllers/collection_updates_controller.ts`, `admin/app/controllers/maps_controller.ts`, `admin/app/controllers/ollama_controller.ts`, `admin/app/controllers/zim_controller.ts`, `admin/app/services/map_service.ts`, `admin/app/services/zim_service.ts`, `admin/tests/unit/cloud_metadata_url.spec.ts`
- `assertNotPrivateUrl` (function) `admin/app/validators/common.ts:15` -- Checks whether a URL points to a loopback or link-local address.
- `assertNotCloudMetadataUrl` (function) `admin/app/validators/common.ts:61`

## admin/config/inertia.ts
Depends on: `admin/app/services/system_service.ts`
Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/services/system_service.ts`
- `invalidateAssistantNameCache` (function) `admin/config/inertia.ts:8`
- `value` (function) `admin/config/inertia.ts:30`

## admin/constants/map_regions.ts
Imported by: `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/map_service.ts`, `admin/inertia/components/CountryPickerModal.tsx`
- `buildPmtilesExtractArgs` (function) `admin/constants/map_regions.ts:24`

## admin/inertia/app/app.tsx
Depends on: `admin/inertia/providers/ThemeProvider.tsx`, `admin/types/system.ts`
- `environment` (function) `admin/inertia/app/app.tsx:38`

## admin/inertia/components/ActiveDownloads.tsx
Depends on: `admin/inertia/hooks/useDownloads.ts`
- `formatSpeed` (function) `admin/inertia/components/ActiveDownloads.tsx:12`
- `getDownloadStatus` (function) `admin/inertia/components/ActiveDownloads.tsx:21`
- `ActiveDownloads` (function) `admin/inertia/components/ActiveDownloads.tsx:38`
- `deltaSec` (function) `admin/inertia/components/ActiveDownloads.tsx:56`
- `handleDismiss` (function) `admin/inertia/components/ActiveDownloads.tsx:81`
- `handleCancel` (function) `admin/inertia/components/ActiveDownloads.tsx:86`

## admin/inertia/components/ActiveEmbedJobs.tsx
Depends on: `admin/inertia/hooks/useEmbedJobs.ts`, `admin/inertia/lib/kb_job_health_display.ts`
- `ActiveEmbedJobs` (function) `admin/inertia/components/ActiveEmbedJobs.tsx:15`

## admin/inertia/components/ActiveModelDownloads.tsx
Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useOllamaModelDownloads.ts`
- `formatSpeed` (function) `admin/inertia/components/ActiveModelDownloads.tsx:13`
- `ActiveModelDownloads` (function) `admin/inertia/components/ActiveModelDownloads.tsx:21`
- `deltaSec` (function) `admin/inertia/components/ActiveModelDownloads.tsx:39`
- `runCancel` (function) `admin/inertia/components/ActiveModelDownloads.tsx:62`
- `confirmCancel` (function) `admin/inertia/components/ActiveModelDownloads.tsx:85`

## admin/inertia/components/Alert.tsx
Depends on: `admin/inertia/lib/classNames.ts`
- `Alert` (function) `admin/inertia/components/Alert.tsx:17`
- `getDefaultIcon` (function) `admin/inertia/components/Alert.tsx:29`
- `getIconColor` (function) `admin/inertia/components/Alert.tsx:44`
- `getVariantStyles` (function) `admin/inertia/components/Alert.tsx:60`
- `getTitleColor` (function) `admin/inertia/components/Alert.tsx:113`
- `getMessageColor` (function) `admin/inertia/components/Alert.tsx:132`
- `getCloseButtonStyles` (function) `admin/inertia/components/Alert.tsx:149`

## admin/inertia/components/BouncingDots.tsx
- `BouncingDots` (function) `admin/inertia/components/BouncingDots.tsx:9`

## admin/inertia/components/BouncingLogo.tsx
- `FadingImage` (function) `admin/inertia/components/BouncingLogo.tsx:4` -- Fading Image Component

## admin/inertia/components/BuilderTagSelector.tsx
- `BuilderTagSelector` (function) `admin/inertia/components/BuilderTagSelector.tsx:18`
- `updateTag` (function) `admin/inertia/components/BuilderTagSelector.tsx:50` -- Update parent when selections change
- `handleAdjectiveChange` (function) `admin/inertia/components/BuilderTagSelector.tsx:55`
- `handleNounChange` (function) `admin/inertia/components/BuilderTagSelector.tsx:60`
- `handleRandomize` (function) `admin/inertia/components/BuilderTagSelector.tsx:65`

## admin/inertia/components/CategoryCard.tsx
- `getTierTotalSize` (function) `admin/inertia/components/CategoryCard.tsx:15` -- Calculate total size range across all tiers

## admin/inertia/components/CountryPickerModal.tsx
Depends on: `admin/constants/map_regions.ts`, `admin/inertia/lib/classNames.ts`
- `toggleCountry` (function) `admin/inertia/components/CountryPickerModal.tsx:100`
- `toggleGroup` (function) `admin/inertia/components/CountryPickerModal.tsx:109`
- `clearAll` (function) `admin/inertia/components/CountryPickerModal.tsx:122`
- `startDownload` (function) `admin/inertia/components/CountryPickerModal.tsx:164`
- `PreflightStatus` (function) `admin/inertia/components/CountryPickerModal.tsx:392`

## admin/inertia/components/DebugInfoModal.tsx
- `DebugInfoModal` (function) `admin/inertia/components/DebugInfoModal.tsx:11`
- `handleCopy` (function) `admin/inertia/components/DebugInfoModal.tsx:36`

## admin/inertia/components/DownloadURLModal.tsx
- `runPreflightCheck` (function) `admin/inertia/components/DownloadURLModal.tsx:23`

## admin/inertia/components/Footer.tsx
Depends on: `admin/types/system.ts`
- `Footer` (function) `admin/inertia/components/Footer.tsx:8`

## admin/inertia/components/HorizontalBarChart.tsx
Depends on: `admin/inertia/lib/classNames.ts`
- `HorizontalBarChart` (function) `admin/inertia/components/HorizontalBarChart.tsx:19`
- `getBarColor` (function) `admin/inertia/components/HorizontalBarChart.tsx:26`
- `getGlowColor` (function) `admin/inertia/components/HorizontalBarChart.tsx:34`
- `getStatusLabel` (function) `admin/inertia/components/HorizontalBarChart.tsx:41`
- `getStatusColor` (function) `admin/inertia/components/HorizontalBarChart.tsx:51`

## admin/inertia/components/InfoTooltip.tsx
- `InfoTooltip` (function) `admin/inertia/components/InfoTooltip.tsx:9`

## admin/inertia/components/KbGuardrailModal.tsx
- `KbGuardrailModal` (function) `admin/inertia/components/KbGuardrailModal.tsx:22`

## admin/inertia/components/MarkdocRenderer.tsx
Depends on: `admin/inertia/components/markdoc/Heading.tsx`, `admin/inertia/components/markdoc/Image.tsx`, `admin/inertia/components/markdoc/List.tsx`, `admin/inertia/components/markdoc/ListItem.tsx`, `admin/inertia/components/markdoc/Table.tsx`
- `Paragraph` (function) `admin/inertia/components/MarkdocRenderer.tsx:10` -- Paragraph component
- `Link` (function) `admin/inertia/components/MarkdocRenderer.tsx:15` -- Link component
- `InlineCode` (function) `admin/inertia/components/MarkdocRenderer.tsx:38` -- Inline code component
- `CodeBlock` (function) `admin/inertia/components/MarkdocRenderer.tsx:47` -- Code block component
- `HorizontalRule` (function) `admin/inertia/components/MarkdocRenderer.tsx:74` -- Horizontal rule component
- `Callout` (function) `admin/inertia/components/MarkdocRenderer.tsx:81` -- Callout component

## admin/inertia/components/ProgressBar.tsx
- `ProgressBar` (function) `admin/inertia/components/ProgressBar.tsx:1`

## admin/inertia/components/StorageProjectionBar.tsx
Depends on: `admin/inertia/lib/classNames.ts`
- `StorageProjectionBar` (function) `admin/inertia/components/StorageProjectionBar.tsx:11`
- `currentPercent` (function) `admin/inertia/components/StorageProjectionBar.tsx:17`
- `projectedPercent` (function) `admin/inertia/components/StorageProjectionBar.tsx:18`
- `projectedTotalPercent` (function) `admin/inertia/components/StorageProjectionBar.tsx:19`
- `getProjectedColor` (function) `admin/inertia/components/StorageProjectionBar.tsx:24` -- Determine warning level based on projected total
- `getProjectedGlow` (function) `admin/inertia/components/StorageProjectionBar.tsx:31`

## admin/inertia/components/StyledButton.tsx
- `getIconSize` (function) `admin/inertia/components/StyledButton.tsx:30`
- `getSizeClasses` (function) `admin/inertia/components/StyledButton.tsx:41`
- `getVariantClasses` (function) `admin/inertia/components/StyledButton.tsx:52`
- `getLoadingSpinner` (function) `admin/inertia/components/StyledButton.tsx:131`
- `onClickHandler` (function) `admin/inertia/components/StyledButton.tsx:140`

## admin/inertia/components/StyledSectionHeader.tsx
- `StyledSectionHeader` (function) `admin/inertia/components/StyledSectionHeader.tsx:10`

## admin/inertia/components/StyledSidebar.tsx
Depends on: `admin/inertia/lib/classNames.ts`, `admin/types/system.ts`
- `ListItem` (function) `admin/inertia/components/StyledSidebar.tsx:34`
- `content` (function) `admin/inertia/components/StyledSidebar.tsx:41`
- `Sidebar` (function) `admin/inertia/components/StyledSidebar.tsx:62`

## admin/inertia/components/StyledTable.tsx
Depends on: `admin/inertia/lib/classNames.ts`
- `StyledTable` (function) `admin/inertia/components/StyledTable.tsx:33`
- `isRowExpanded` (function) `admin/inertia/components/StyledTable.tsx:59`
- `toggleRowExpansion` (function) `admin/inertia/components/StyledTable.tsx:64`

## admin/inertia/components/ThemeToggle.tsx
Depends on: `admin/inertia/providers/ThemeProvider.tsx`
- `ThemeToggle` (function) `admin/inertia/components/ThemeToggle.tsx:8`

## admin/inertia/components/TierSelectionModal.tsx
Depends on: `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/inertia/lib/kb_guardrail.ts`
- `resourceFilename` (function) `admin/inertia/components/TierSelectionModal.tsx:21`
- `getAllResourcesForTier` (function) `admin/inertia/components/TierSelectionModal.tsx:55` -- Get all resources for a tier (including inherited resources).
- `getTierTotalSize` (function) `admin/inertia/components/TierSelectionModal.tsx:116`
- `handleTierClick` (function) `admin/inertia/components/TierSelectionModal.tsx:120`
- `finalizeSubmit` (function) `admin/inertia/components/TierSelectionModal.tsx:134` -- Runs the original onSelectTier-then-onClose flow.
- `handleSubmit` (function) `admin/inertia/components/TierSelectionModal.tsx:143`

## admin/inertia/components/UpdateServiceModal.tsx
Depends on: `admin/app/utils/version.ts`, `admin/types/services.ts`
- `UpdateServiceModal` (function) `admin/inertia/components/UpdateServiceModal.tsx:17`
- `loadVersions` (function) `admin/inertia/components/UpdateServiceModal.tsx:30`
- `handleToggleAdvanced` (function) `admin/inertia/components/UpdateServiceModal.tsx:45`

## admin/inertia/components/chat/ChatAssistantAvatar.tsx
- `ChatAssistantAvatar` (function) `admin/inertia/components/chat/ChatAssistantAvatar.tsx:3`

## admin/inertia/components/chat/ChatButton.tsx
- `ChatButton` (function) `admin/inertia/components/chat/ChatButton.tsx:7`

## admin/inertia/components/chat/ChatInterface.tsx
Depends on: `admin/constants/ollama.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/chat.ts`
- `ChatInterface` (function) `admin/inertia/components/chat/ChatInterface.tsx:24`
- `handleDownloadModel` (function) `admin/inertia/components/chat/ChatInterface.tsx:41`
- `scrollToBottom` (function) `admin/inertia/components/chat/ChatInterface.tsx:54`
- `handleSubmit` (function) `admin/inertia/components/chat/ChatInterface.tsx:62`
- `handleKeyDown` (function) `admin/inertia/components/chat/ChatInterface.tsx:73`
- `handleInput` (function) `admin/inertia/components/chat/ChatInterface.tsx:80`

## admin/inertia/components/chat/ChatMessageBubble.tsx
Depends on: `admin/inertia/lib/classNames.ts`, `admin/types/chat.ts`
- `ChatMessageBubble` (function) `admin/inertia/components/chat/ChatMessageBubble.tsx:10`

## admin/inertia/components/chat/ChatModal.tsx
Depends on: `admin/app/utils/misc.ts`, `admin/inertia/hooks/useSystemSetting.ts`
- `ChatModal` (function) `admin/inertia/components/chat/ChatModal.tsx:11`

## admin/inertia/components/chat/ChatSidebar.tsx
Depends on: `admin/inertia/lib/classNames.ts`, `admin/types/chat.ts`
- `ChatSidebar` (function) `admin/inertia/components/chat/ChatSidebar.tsx:18`
- `handleCloseKnowledgeBase` (function) `admin/inertia/components/chat/ChatSidebar.tsx:31`

## admin/inertia/components/chat/KbPolicyPromptBanner.tsx
Depends on: `admin/inertia/context/NotificationContext.ts`
- `KbPolicyPromptBanner` (function) `admin/inertia/components/chat/KbPolicyPromptBanner.tsx:27` -- (`rag.defaultIngestPolicy` unset).

## admin/inertia/components/chat/KnowledgeBaseModal.tsx
Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/kb_file_grouping.ts`
- `renderStatePill` (function) `admin/inertia/components/chat/KnowledgeBaseModal.tsx:32`
- `pickRowAction` (function) `admin/inertia/components/chat/KnowledgeBaseModal.tsx:77`
- `KnowledgeBaseModal` (function) `admin/inertia/components/chat/KnowledgeBaseModal.tsx:96`
- `handleUpload` (function) `admin/inertia/components/chat/KnowledgeBaseModal.tsx:282`
- `handleConfirmSync` (function) `admin/inertia/components/chat/KnowledgeBaseModal.tsx:313`

## admin/inertia/components/chat/index.tsx
Depends on: `admin/constants/ollama.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/chat.ts`
- `Chat` (function) `admin/inertia/components/chat/index.tsx:24`

## admin/inertia/components/inputs/Switch.tsx
- `Switch` (function) `admin/inertia/components/inputs/Switch.tsx:12`

## admin/inertia/components/layout/BackToHomeHeader.tsx
- `BackToHomeHeader` (function) `admin/inertia/components/layout/BackToHomeHeader.tsx:10`

## admin/inertia/components/maps/CoordinateOverlay.tsx
- `CoordinateOverlay` (function) `admin/inertia/components/maps/CoordinateOverlay.tsx:8`

## admin/inertia/components/maps/MapComponent.tsx
Depends on: `admin/inertia/hooks/useMapMarkers.ts`
- `MapComponent` (function) `admin/inertia/components/maps/MapComponent.tsx:31`

## admin/inertia/components/maps/MarkerPanel.tsx
Depends on: `admin/inertia/hooks/useMapMarkers.ts`
- `MarkerPanel` (function) `admin/inertia/components/maps/MarkerPanel.tsx:14`

## admin/inertia/components/maps/MarkerPin.tsx
- `MarkerPin` (function) `admin/inertia/components/maps/MarkerPin.tsx:8`

## admin/inertia/components/maps/ScaleUnitToggle.tsx
- `ScaleUnitToggle` (function) `admin/inertia/components/maps/ScaleUnitToggle.tsx:9`

## admin/inertia/components/markdoc/Heading.tsx
Imported by: `admin/inertia/components/MarkdocRenderer.tsx`
- `Heading` (function) `admin/inertia/components/markdoc/Heading.tsx:3`

## admin/inertia/components/markdoc/Image.tsx
Imported by: `admin/inertia/components/MarkdocRenderer.tsx`
- `Image` (function) `admin/inertia/components/markdoc/Image.tsx:1`

## admin/inertia/components/markdoc/List.tsx
Imported by: `admin/inertia/components/MarkdocRenderer.tsx`
- `List` (function) `admin/inertia/components/markdoc/List.tsx:1`

## admin/inertia/components/markdoc/ListItem.tsx
Imported by: `admin/inertia/components/MarkdocRenderer.tsx`
- `ListItem` (function) `admin/inertia/components/markdoc/ListItem.tsx:1`

## admin/inertia/components/markdoc/Table.tsx
Imported by: `admin/inertia/components/MarkdocRenderer.tsx`
- `Table` (function) `admin/inertia/components/markdoc/Table.tsx:1`
- `TableHead` (function) `admin/inertia/components/markdoc/Table.tsx:11`
- `TableBody` (function) `admin/inertia/components/markdoc/Table.tsx:15`
- `TableRow` (function) `admin/inertia/components/markdoc/Table.tsx:19`
- `TableHeader` (function) `admin/inertia/components/markdoc/Table.tsx:23`
- `TableCell` (function) `admin/inertia/components/markdoc/Table.tsx:31`

## admin/inertia/components/systeminfo/CircularGauge.tsx
Depends on: `admin/inertia/lib/classNames.ts`
- `CircularGauge` (function) `admin/inertia/components/systeminfo/CircularGauge.tsx:14`
- `getColor` (function) `admin/inertia/components/systeminfo/CircularGauge.tsx:63`
- `angle` (function) `admin/inertia/components/systeminfo/CircularGauge.tsx:118`

## admin/inertia/components/systeminfo/InfoCard.tsx
Depends on: `admin/inertia/lib/classNames.ts`
- `InfoCard` (function) `admin/inertia/components/systeminfo/InfoCard.tsx:13`
- `getVariantStyles` (function) `admin/inertia/components/systeminfo/InfoCard.tsx:14`

## admin/inertia/components/systeminfo/StatusCard.tsx
- `StatusCard` (function) `admin/inertia/components/systeminfo/StatusCard.tsx:6`

## admin/inertia/context/ModalContext.ts
Imported by: `admin/inertia/components/ActiveModelDownloads.tsx`, `admin/inertia/components/chat/KnowledgeBaseModal.tsx`, `admin/inertia/components/chat/index.tsx`, `admin/inertia/pages/settings/apps.tsx`, `admin/inertia/pages/settings/maps.tsx`, `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/system.tsx`, `admin/inertia/pages/settings/zim/index.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`, `admin/inertia/providers/ModalProvider.tsx`
- `useModals` (function) `admin/inertia/context/ModalContext.ts:13`

## admin/inertia/context/NotificationContext.ts
Imported by: `admin/inertia/components/chat/ChatInterface.tsx`, `admin/inertia/components/chat/KbPolicyPromptBanner.tsx`, `admin/inertia/components/chat/KnowledgeBaseModal.tsx`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/lib/util.ts`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/settings/maps.tsx`, `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/system.tsx`, `admin/inertia/pages/settings/update.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`, `admin/inertia/providers/NotificationProvider.tsx`
- `useNotifications` (function) `admin/inertia/context/NotificationContext.ts:20`

## admin/inertia/hooks/useDebounce.ts
Imported by: `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`
- `useDebounce` (function) `admin/inertia/hooks/useDebounce.ts:3`
- `debounce` (function) `admin/inertia/hooks/useDebounce.ts:6`

## admin/inertia/hooks/useDiskDisplayData.ts
Depends on: `admin/types/system.ts`
Imported by: `admin/inertia/components/TierSelectionModal.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/settings/system.tsx`
- `getAllDiskDisplayItems` (function) `admin/inertia/hooks/useDiskDisplayData.ts:16` -- import { Systeminformation } from 'systeminformation' import { formatBytes } from '~/lib/util' type DiskDisplayItem...
- `getPrimaryDiskInfo` (function) `admin/inertia/hooks/useDiskDisplayData.ts:88` -- value: fs.use || 0, total: formatBytes(fs.size), used: formatBytes(fs.used), subtext: `${formatBytes(fs.used)} /...

## admin/inertia/hooks/useDownloads.ts
Imported by: `admin/inertia/components/ActiveDownloads.tsx`, `admin/inertia/pages/settings/maps.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`
- `useDownloads` (function) `admin/inertia/hooks/useDownloads.ts:10`
- `invalidate` (function) `admin/inertia/hooks/useDownloads.ts:29`

## admin/inertia/hooks/useEmbedJobs.ts
Imported by: `admin/inertia/components/ActiveEmbedJobs.tsx`
- `useEmbedJobs` (function) `admin/inertia/hooks/useEmbedJobs.ts:5`
- `invalidate` (function) `admin/inertia/hooks/useEmbedJobs.ts:29`

## admin/inertia/hooks/useErrorNotification.ts
Depends on: `admin/inertia/context/NotificationContext.ts`
Imported by: `admin/inertia/pages/settings/apps.tsx`
- `useErrorNotification` (function) `admin/inertia/hooks/useErrorNotification.ts:4`
- `showError` (function) `admin/inertia/hooks/useErrorNotification.ts:7`

## admin/inertia/hooks/useInternetStatus.ts
Imported by: `admin/inertia/pages/easy-setup/complete.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/settings/apps.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`
- `useInternetStatus` (function) `admin/inertia/hooks/useInternetStatus.ts:6`

## admin/inertia/hooks/useMapMarkers.ts
Imported by: `admin/inertia/components/maps/MapComponent.tsx`, `admin/inertia/components/maps/MarkerPanel.tsx`
- `useMapMarkers` (function) `admin/inertia/hooks/useMapMarkers.ts:25`

## admin/inertia/hooks/useMapRegionFiles.ts
Depends on: `admin/types/files.ts`
- `useMapRegionFiles` (function) `admin/inertia/hooks/useMapRegionFiles.ts:5`

## admin/inertia/hooks/useOllamaModelDownloads.ts
Imported by: `admin/inertia/components/ActiveModelDownloads.tsx`
- `useOllamaModelDownloads` (function) `admin/inertia/hooks/useOllamaModelDownloads.ts:25`

## admin/inertia/hooks/useServiceInstallationActivity.ts
Depends on: `admin/constants/broadcast.ts`, `admin/inertia/components/InstallActivityFeed.tsx`
Imported by: `admin/inertia/pages/easy-setup/complete.tsx`, `admin/inertia/pages/settings/apps.tsx`
- `useServiceInstallationActivity` (function) `admin/inertia/hooks/useServiceInstallationActivity.ts:6`

## admin/inertia/hooks/useServiceInstalledStatus.tsx
Depends on: `admin/types/services.ts`
Imported by: `admin/inertia/layouts/AppLayout.tsx`, `admin/inertia/layouts/SettingsLayout.tsx`, `admin/inertia/pages/settings/benchmark.tsx`, `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/zim/index.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`
- `useServiceInstalledStatus` (function) `admin/inertia/hooks/useServiceInstalledStatus.tsx:5`

## admin/inertia/hooks/useSystemInfo.ts
Depends on: `admin/types/system.ts`
Imported by: `admin/inertia/components/TierSelectionModal.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/system.tsx`
- `useSystemInfo` (function) `admin/inertia/hooks/useSystemInfo.ts:10`


Next: [API_p2.md](API_p2.md)
