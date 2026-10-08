# Gotchas

## God Nodes (high connectivity)

These files have the most connections. Changes here have high blast radius.

- `admin/inertia/lib/classNames.ts` (score: 40.10, imported by 20 files)
- `admin/app/services/docker_service.ts` (score: 36.50, imported by 11 files)
- `admin/constants/service_names.ts` (score: 36.00, imported by 18 files)
- `admin/inertia/pages/settings/update.tsx` (score: 34.90, imported by 13 files)
- `admin/app/utils/fs.ts` (score: 31.50, imported by 15 files)
- `admin/app/services/system_service.ts` (score: 26.70, imported by 8 files)
- `admin/inertia/context/NotificationContext.ts` (score: 24.10, imported by 12 files)
- `admin/app/jobs/embed_file_job.ts` (score: 22.60, imported by 3 files)
- `admin/app/services/rag_service.ts` (score: 22.30, imported by 3 files)
- `admin/app/jobs/run_download_job.ts` (score: 22.20, imported by 6 files)

## Blast Radius (change impact)

Editing these files can break the listed number of dependents. Run their tests after any change.

- `admin/inertia/context/NotificationContext.ts` -- 12 direct, 50 total dependents
- `admin/types/system.ts` -- 9 direct, 49 total dependents
- `admin/constants/service_names.ts` -- 18 direct, 41 total dependents
- `admin/types/kv_store.ts` -- 1 direct, 41 total dependents
- `admin/types/services.ts` -- 9 direct, 41 total dependents
- `admin/inertia/hooks/useSystemSetting.ts` -- 4 direct, 40 total dependents
- `admin/app/utils/version.ts` -- 6 direct, 39 total dependents
- `admin/inertia/pages/settings/update.tsx` -- 13 direct, 36 total dependents
- `admin/app/utils/fs.ts` -- 15 direct, 35 total dependents
- `admin/constants/broadcast.ts` -- 8 direct, 35 total dependents

## Hotspots (complexity + centrality)

- `admin/inertia/pages/easy-setup/index.tsx` -- complexity: 1.0, centrality: 0.5, combined: 0.7
- `admin/app/services/rag_service.ts` -- complexity: 0.1, centrality: 1.0, combined: 0.6
- `admin/app/services/docker_service.ts` -- complexity: 0.2, centrality: 0.8, combined: 0.6
- `admin/app/services/system_service.ts` -- complexity: 0.3, centrality: 0.5, combined: 0.4
- `admin/inertia/pages/settings/zim/remote-explorer.tsx` -- complexity: 0.5, centrality: 0.4, combined: 0.4
- `admin/app/services/map_service.ts` -- complexity: 0.3, centrality: 0.5, combined: 0.4
- `admin/app/services/ollama_service.ts` -- complexity: 0.3, centrality: 0.5, combined: 0.4
- `install/install_nomad.sh` -- complexity: 0.8, centrality: 0.0, combined: 0.3
- `admin/app/utils/fs.ts` -- complexity: 0.6, centrality: 0.1, combined: 0.3
- `admin/inertia/pages/settings/update.tsx` -- complexity: 0.3, centrality: 0.3, combined: 0.3

## Dependency Cycles

Circular dependencies. Refactor to break the cycle.

- `admin/app/jobs/run_download_job.ts` -> `admin/app/services/zim_service.ts` -> `admin/app/services/collection_manifest_service.ts` -> `admin/app/jobs/run_download_job.ts`
- `admin/app/services/system_service.ts` -> `admin/config/inertia.ts` -> `admin/app/services/system_service.ts`
- `admin/app/services/ollama_service.ts` -> `admin/app/jobs/download_model_job.ts` -> `admin/app/services/ollama_service.ts`
- `admin/app/jobs/run_download_job.ts` -> `admin/app/services/zim_service.ts` -> `admin/app/jobs/run_download_job.ts`
- `admin/app/jobs/run_download_job.ts` -> `admin/app/services/map_service.ts` -> `admin/app/jobs/run_download_job.ts`

## Layer Violations

- `admin/inertia/components/TierSelectionModal.tsx` (presentation) -> `admin/inertia/hooks/useDiskDisplayData.ts` (data_access): presentation must not import data_access
- `admin/inertia/pages/easy-setup/index.tsx` (presentation) -> `admin/inertia/hooks/useDiskDisplayData.ts` (data_access): presentation must not import data_access
- `admin/inertia/pages/settings/system.tsx` (presentation) -> `admin/inertia/hooks/useDiskDisplayData.ts` (data_access): presentation must not import data_access

## Dataflow Issues (INFERRED, review each lead)

- `admin/app/utils/fs.ts:111` `isValidZimFile` [UNCHECKED_ALLOC] `fh`: Result of allocator stored in `fh` is never checked against NULL.
