# Subsystem: utils

## admin/app/utils/downloads.ts
- Doc: doResumableDownload: Perform a resumable download with progress tracking @param param0...
- Layer: utility
- Language: ts
- Symbols:
  - `doResumableDownload` (function, line 18)
  - `doResumableDownloadWithRetry` (function, line 226)
  - `delay` (function, line 284)
  - `fetchStream` (function, line 96)
  - `clearStallTimer` (function, line 128)
  - `resetStallTimer` (function, line 135)
  - `cleanup` (function, line 171)
- Depends on: `admin/app/utils/fs.ts`

## admin/app/utils/fs.ts
- Doc: isValidZimFile: Validates that a file has the ZIM magic number (0x44D495A).
- Layer: utility
- Language: ts
- Symbols:
  - `listDirectoryContents` (function, line 10)
  - `listDirectoryContentsRecursive` (function, line 31)
  - `ensureDirectoryExists` (function, line 50)
  - `getFile` (function, line 60)
  - `getFile` (function, line 61)
  - `getFile` (function, line 65)
  - `getFile` (function, line 66)
  - `getFileStatsIfExists` (function, line 85)
  - `isValidZimFile` (function, line 108)
  - `deleteFileIfExists` (function, line 124)
  - `getAllFilesystems` (function, line 134)
  - `traverse` (function, line 141)
  - `matchesDevice` (function, line 160)
  - `determineFileType` (function, line 177)
  - `sanitizeFilename` (function, line 199)
- Imported by: `admin/app/controllers/rag_controller.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/collection_manifest_service.ts`, `admin/app/services/collection_update_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/docs_service.ts`, `admin/app/services/download_service.ts`, `admin/app/services/kiwix_library_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/system_update_service.ts`, `admin/app/services/zim_extraction_service.ts`, `admin/app/services/zim_service.ts`, `admin/app/utils/downloads.ts`

## admin/app/utils/kb_ingest_decision.ts
- Doc: decideScanAction: Decide what scanAndSyncStorage should do for a single embeddable file.
- Layer: utility
- Language: ts
- Symbols:
  - `decideScanAction` (function, line 44)
- Imported by: `admin/app/services/rag_service.ts`, `admin/tests/unit/kb_ingest_decision.spec.ts`

## admin/app/utils/kb_job_health.ts
- Layer: utility
- Language: ts
- Symbols:
  - `computeJobHealth` (function, line 32)
- Imported by: `admin/inertia/lib/kb_job_health_display.ts`, `admin/tests/unit/kb_job_health.spec.ts`

## admin/app/utils/kb_ratio_lookup.ts
- Doc: estimateBatch: Aggregate an embedding-disk-cost estimate across a batch of files (curated tier...
- Layer: utility
- Language: ts
- Symbols:
  - `estimateBatch` (function, line 38)
  - `findChunksPerMb` (function, line 70)
  - `estimateChunkCount` (function, line 88)
- Imported by: `admin/app/models/kb_ratio_registry.ts`, `admin/tests/unit/kb_ratio_lookup.spec.ts`

## admin/app/utils/kb_warning_decision.ts
- Layer: utility
- Language: ts
- Symbols:
  - `decideWarnings` (function, line 41)
- Imported by: `admin/app/services/rag_service.ts`, `admin/tests/unit/kb_warning_decision.spec.ts`

## admin/app/utils/misc.ts
- Layer: utility
- Language: ts
- Symbols:
  - `formatSpeed` (function, line 1)
  - `toTitleCase` (function, line 7)
  - `parseBoolean` (function, line 15)
- Imported by: `admin/inertia/components/chat/ChatModal.tsx`

## admin/app/utils/version.ts
- Doc: isNewerVersion: Compare two semantic version strings to determine if the first is newer than the...
- Layer: utility
- Language: ts
- Symbols:
  - `isNewerVersion` (function, line 7)
  - `parseMajorVersion` (function, line 45)
  - `normalize` (function, line 8)
- Imported by: `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/container_registry_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/system_service.ts`, `admin/inertia/components/UpdateServiceModal.tsx`, `admin/inertia/pages/settings/update.tsx`

## admin/app/utils/zim_filename.ts
- Doc: zimFilenameStem: Strip the trailing `_YYYY-MM(-DD).zim` date suffix from a Kiwix-style ZIM...
- Layer: utility
- Language: ts
- Symbols:
  - `zimFilenameStem` (function, line 7)
  - `findReplacedWikipediaFiles` (function, line 17)
- Imported by: `admin/app/services/zim_service.ts`, `admin/tests/unit/zim_filename.spec.ts`
