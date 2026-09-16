# Gotchas

## God Nodes (high connectivity)

These files have the most connections. Changes here have high blast radius.

- `admin/inertia/lib/classNames.ts` (score: 40.10)
- `admin/app/services/docker_service.ts` (score: 36.50)
- `admin/constants/service_names.ts` (score: 36.00)
- `admin/inertia/pages/settings/update.tsx` (score: 34.90)
- `admin/app/utils/fs.ts` (score: 31.50)
- `admin/app/services/system_service.ts` (score: 26.70)
- `admin/inertia/context/NotificationContext.ts` (score: 24.10)
- `admin/app/jobs/embed_file_job.ts` (score: 22.60)
- `admin/app/services/rag_service.ts` (score: 22.30)
- `admin/app/jobs/run_download_job.ts` (score: 22.20)

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

- `admin/app/jobs/run_download_job.ts` -> `admin/app/services/zim_service.ts` -> `admin/app/services/collection_manifest_service.ts`
- `admin/app/services/system_service.ts` -> `admin/config/inertia.ts`
- `admin/app/services/ollama_service.ts` -> `admin/app/jobs/download_model_job.ts`
- `admin/app/jobs/run_download_job.ts` -> `admin/app/services/zim_service.ts`
- `admin/app/jobs/run_download_job.ts` -> `admin/app/services/map_service.ts`

## Layer Violations

- `admin/inertia/components/TierSelectionModal.tsx` (presentation) -> `admin/inertia/hooks/useDiskDisplayData.ts` (data_access): presentation must not import data_access
- `admin/inertia/hooks/useSystemSetting.ts` (presentation) -> `admin/types/kv_store.ts` (data_access): presentation must not import data_access
- `admin/inertia/pages/easy-setup/index.tsx` (presentation) -> `admin/inertia/hooks/useDiskDisplayData.ts` (data_access): presentation must not import data_access
- `admin/inertia/pages/settings/system.tsx` (presentation) -> `admin/inertia/hooks/useDiskDisplayData.ts` (data_access): presentation must not import data_access
