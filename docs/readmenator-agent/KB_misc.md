# Subsystem: misc

## admin/commands/queue/work.ts
- Layer: infrastructure
- Language: ts
- Symbols:
  - `QueueWork` (class, line 13)
- Depends on: `admin/ace.js`, `admin/app/jobs/check_service_updates_job.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_benchmark_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/commands/benchmark/run.ts`

## admin/database/seeders/service_seeder.ts
- Layer: data_access
- Language: ts
- Symbols:
  - `ServiceSeeder` (class, line 8)
- Depends on: `admin/commands/benchmark/run.ts`, `admin/constants/kiwix.ts`, `admin/constants/service_names.ts`

## admin/inertia/app/app.tsx
- Doc: <reference path="../../adonisrc.ts" /> <reference path="../../config/inertia.ts" />
- Layer: presentation
- Language: tsx
- Symbols:
  - `environment` (function, line 38)
- Depends on: `admin/inertia/providers/ThemeProvider.tsx`, `admin/types/system.ts`

## admin/inertia/components/file-uploader/index.tsx
- Layer: presentation
- Language: tsx

## admin/inertia/components/layout/BackToHomeHeader.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `BackToHomeHeader` (function, line 10)

## admin/inertia/pages/docs/show.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `Show` (function, line 5)
- Imported by: `admin/app/controllers/benchmark_controller.ts`, `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/docs_controller.ts`

## admin/tests/bootstrap.ts
- Layer: infrastructure
- Language: ts
- Symbols:
  - `to` (function, line 18)

## install/sidecar-disk-collector/collect-disk-info.sh
- Doc: Project N.O.M.A.D. - Disk Info Collector Sidecar  Reads host block device and filesystem info...
- Layer: utility
- Language: sh
- Symbols:
  - `log` (function, line 9)

## install/sidecar-updater/update-watcher.sh
- Doc: Project N.O.M.A.D.
- Layer: utility
- Language: sh
- Symbols:
  - `log` (function, line 12)
  - `write_status` (function, line 16)
  - `perform_update` (function, line 31)
  - `cleanup` (function, line 111)
