# Subsystem: settings

## admin/inertia/pages/settings/apps.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `extractTag` (function, line 20)
  - `SettingsPage` (function, line 27)
  - `handleCheckUpdates` (function, line 60)
  - `installService` (function, line 103)
  - `handleAffectAction` (function, line 126)
  - `handleForceReinstall` (function, line 149)
  - `handleUpdateService` (function, line 172)
  - `handleInstallService` (function, line 78)
  - `AppActions` (function, line 202)
  - `ForceReinstallButton` (function, line 203)
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

## admin/inertia/pages/settings/benchmark.tsx
- Doc: handleFullBenchmarkClick: Handle Full Benchmark click with pre-flight check
- Layer: presentation
- Language: tsx
- Symbols:
  - `BenchmarkPage` (function, line 30)
  - `handleFullBenchmarkClick` (function, line 198)
  - `advanceStage` (function, line 277)
  - `formatBytes` (function, line 321)
  - `getScoreColor` (function, line 326)
  - `getProgressPercent` (function, line 332)
  - `getAIScore` (function, line 353)
  - `score` (function, line 355)
- Depends on: `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/benchmark.ts`

## admin/inertia/pages/settings/legal.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `LegalPage` (function, line 4)
- Imported by: `admin/app/controllers/settings_controller.ts`

## admin/inertia/pages/settings/maps.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `MapsManager` (function, line 26)
  - `downloadBaseAssets` (function, line 83)
  - `downloadCollection` (function, line 110)
  - `downloadCustomFile` (function, line 123)
  - `deleteFile` (function, line 136)
  - `confirmDeleteFile` (function, line 159)
  - `confirmDownload` (function, line 179)
  - `confirmGlobalMapDownload` (function, line 213)
  - `openCountryPickerModal` (function, line 236)
  - `openDownloadModal` (function, line 254)
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`, `admin/types/files.ts`

## admin/inertia/pages/settings/models.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `ModelsPage` (function, line 25)
  - `handleSaveRemoteOllama` (function, line 108)
  - `handleClearRemoteOllama` (function, line 125)
  - `handleForceRefresh` (function, line 175)
  - `handleInstallModel` (function, line 183)
  - `handleDeleteModel` (function, line 201)
  - `confirmDeleteModel` (function, line 221)
  - `handleDismissGpuBanner` (function, line 48)
  - `handleForceReinstallOllama` (function, line 55)
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/types/ollama.ts`
- Imported by: `admin/app/controllers/settings_controller.ts`

## admin/inertia/pages/settings/support.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `SupportPage` (function, line 5)
- Imported by: `admin/app/controllers/settings_controller.ts`

## admin/inertia/pages/settings/system.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `SettingsPage` (function, line 19)
  - `handleDismissGpuBanner` (function, line 37)
  - `handleForceReinstallOllama` (function, line 44)
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/types/system.ts`

## admin/inertia/pages/settings/update.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `ContentUpdatesSection` (function, line 43)
  - `SystemUpdatePage` (function, line 260)
  - `handleCheck` (function, line 52)
  - `handleApply` (function, line 70)
  - `handleApplyAll` (function, line 99)
  - `handleStartUpdate` (function, line 338)
  - `handleViewLogs` (function, line 353)
  - `getProgressBarColor` (function, line 394)
  - `getStatusIcon` (function, line 400)
- Depends on: `admin/app/utils/version.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`, `admin/types/system.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/providers/qdrant_restart_policy_provider.ts`
