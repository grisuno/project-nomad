# API (page 2 of 2)
Previous: [API.md](API.md)

## admin/inertia/hooks/useSystemSetting.ts
Depends on: `admin/types/kv_store.ts`
Imported by: `admin/inertia/components/chat/ChatModal.tsx`, `admin/inertia/components/chat/index.tsx`, `admin/inertia/pages/home.tsx`, `admin/inertia/pages/settings/update.tsx`
- `useSystemSetting` (function) `admin/inertia/hooks/useSystemSetting.ts:12`

## admin/inertia/hooks/useTheme.ts
Imported by: `admin/inertia/providers/ThemeProvider.tsx`
- `getInitialTheme` (function) `admin/inertia/hooks/useTheme.ts:7`
- `useTheme` (function) `admin/inertia/hooks/useTheme.ts:16`

## admin/inertia/hooks/useUpdateAvailable.ts
Depends on: `admin/types/system.ts`
Imported by: `admin/inertia/pages/home.tsx`
- `useUpdateAvailable` (function) `admin/inertia/hooks/useUpdateAvailable.ts:6`

## admin/inertia/layouts/AppLayout.tsx
Depends on: `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/lib/classNames.ts`
- `AppLayout` (function) `admin/inertia/layouts/AppLayout.tsx:11`

## admin/inertia/layouts/DocsLayout.tsx
- `DocsLayout` (function) `admin/inertia/layouts/DocsLayout.tsx:6`

## admin/inertia/layouts/MapsLayout.tsx
- `MapsLayout` (function) `admin/inertia/layouts/MapsLayout.tsx:3`

## admin/inertia/layouts/SettingsLayout.tsx
Depends on: `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/lib/navigation.ts`
- `SettingsLayout` (function) `admin/inertia/layouts/SettingsLayout.tsx:20`

## admin/inertia/lib/classNames.ts
Imported by: `admin/inertia/components/Alert.tsx`, `admin/inertia/components/CountryPickerModal.tsx`, `admin/inertia/components/DynamicIcon.tsx`, `admin/inertia/components/HorizontalBarChart.tsx`, `admin/inertia/components/InstallActivityFeed.tsx`, `admin/inertia/components/StorageProjectionBar.tsx`, `admin/inertia/components/StyledModal.tsx`, `admin/inertia/components/StyledSidebar.tsx`, `admin/inertia/components/StyledTable.tsx`, `admin/inertia/components/TierSelectionModal.tsx`, `admin/inertia/components/WikipediaSelector.tsx`, `admin/inertia/components/chat/ChatInterface.tsx`, `admin/inertia/components/chat/ChatMessageBubble.tsx`, `admin/inertia/components/chat/ChatSidebar.tsx`, `admin/inertia/components/chat/index.tsx`, `admin/inertia/components/inputs/Input.tsx`, `admin/inertia/components/systeminfo/CircularGauge.tsx`, `admin/inertia/components/systeminfo/InfoCard.tsx`, `admin/inertia/layouts/AppLayout.tsx`, `admin/inertia/pages/easy-setup/index.tsx`
- `classNames` (function) `admin/inertia/lib/classNames.ts:2`

## admin/inertia/lib/collections.ts
- `resolveTierResources` (function) `admin/inertia/lib/collections.ts:7` -- Resolve all resources for a tier, including inherited resources from includesTier chain.
- `resolveTierResourcesInner` (function) `admin/inertia/lib/collections.ts:11`

## admin/inertia/lib/global_map_banner.ts
Imported by: `admin/inertia/pages/settings/maps.tsx`, `admin/tests/unit/global_map_banner.spec.ts`
- `hasDownloadedGlobalMap` (function) `admin/inertia/lib/global_map_banner.ts:1`

## admin/inertia/lib/kb_file_grouping.ts
Depends on: `admin/util/docs.ts`
Imported by: `admin/inertia/components/chat/KnowledgeBaseModal.tsx`, `admin/tests/unit/kb_file_grouping.spec.ts`
- `classifyKbFile` (function) `admin/inertia/lib/kb_file_grouping.ts:21`
- `sourceToDisplayName` (function) `admin/inertia/lib/kb_file_grouping.ts:34`
- `groupAndSortKbFiles` (function) `admin/inertia/lib/kb_file_grouping.ts:67` -- Group stored-file rows into table rows for the Stored Files panel.  - Admin docs (`/app/docs/*`, README) collapse...

## admin/inertia/lib/kb_guardrail.ts
Imported by: `admin/inertia/components/TierSelectionModal.tsx`, `admin/tests/unit/kb_guardrail.spec.ts`
- `evaluateGuardrail` (function) `admin/inertia/lib/kb_guardrail.ts:47` -- Decide whether a bulk indexing action should be gated behind the guardrail modal.

## admin/inertia/lib/kb_job_health_display.ts
Depends on: `admin/app/utils/kb_job_health.ts`
Imported by: `admin/inertia/components/ActiveEmbedJobs.tsx`
- `formatTimeAgo` (function) `admin/inertia/lib/kb_job_health_display.ts:45` -- Format a relative timestamp as "Xs ago", "Xm ago", "Xh ago" with sensible thresholds for the KB Processing Queue's...
- `computeJobHealthNow` (function) `admin/inertia/lib/kb_job_health_display.ts:59` -- Convenience wrapper that resolves a job's health status without the caller having to remember to pass `now`.

## admin/inertia/lib/navigation.ts
Imported by: `admin/inertia/layouts/SettingsLayout.tsx`, `admin/inertia/pages/home.tsx`, `admin/inertia/pages/settings/apps.tsx`
- `getServiceLink` (function) `admin/inertia/lib/navigation.ts:3`

## admin/inertia/lib/util.ts
Depends on: `admin/inertia/context/NotificationContext.ts`
Imported by: `admin/inertia/lib/api.ts`
- `setGlobalNotificationCallback` (function) `admin/inertia/lib/util.ts:6`
- `capitalizeFirstLetter` (function) `admin/inertia/lib/util.ts:10`
- `formatBytes` (function) `admin/inertia/lib/util.ts:15`
- `generateRandomString` (function) `admin/inertia/lib/util.ts:24`
- `generateUUID` (function) `admin/inertia/lib/util.ts:33`
- `extractFileName` (function) `admin/inertia/lib/util.ts:57` -- Extracts the file name from a given path while handling both forward and backward slashes. @param path The full file...
- `that` (function) `admin/inertia/lib/util.ts:69`
- `to` (function) `admin/inertia/lib/util.ts:69`
- `to` (function) `admin/inertia/lib/util.ts:70`
- `that` (function) `admin/inertia/lib/util.ts:71`
- `and` (function) `admin/inertia/lib/util.ts:71`
- `catchInternal` (function) `admin/inertia/lib/util.ts:73` -- A higher-order function that wraps an asynchronous function to catch and log internal errors. @param fn The...

## admin/inertia/pages/about.tsx
- `About` (function) `admin/inertia/pages/about.tsx:3`

## admin/inertia/pages/chat.tsx
- `Chat` (function) `admin/inertia/pages/chat.tsx:4`

## admin/inertia/pages/docs/show.tsx
Imported by: `admin/app/controllers/benchmark_controller.ts`, `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/docs_controller.ts`
- `Show` (function) `admin/inertia/pages/docs/show.tsx:5`

## admin/inertia/pages/easy-setup/complete.tsx
Depends on: `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`
Imported by: `admin/app/controllers/easy_setup_controller.ts`
- `EasySetupWizardComplete` (function) `admin/inertia/pages/easy-setup/complete.tsx:11`

## admin/inertia/pages/easy-setup/index.tsx
Depends on: `admin/commands/benchmark/submit.ts`, `admin/constants/service_names.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/services.ts`
- `buildCoreCapabilities` (function) `admin/inertia/pages/easy-setup/index.tsx:35`
- `EasySetupWizard` (function) `admin/inertia/pages/easy-setup/index.tsx:115`
- `toggleMapCollection` (function) `admin/inertia/pages/easy-setup/index.tsx:215`
- `toggleAiModel` (function) `admin/inertia/pages/easy-setup/index.tsx:221`
- `handleCategoryClick` (function) `admin/inertia/pages/easy-setup/index.tsx:228` -- Category/tier handlers
- `handleTierSelect` (function) `admin/inertia/pages/easy-setup/index.tsx:234`
- `closeTierModal` (function) `admin/inertia/pages/easy-setup/index.tsx:247`
- `getSelectedTierResources` (function) `admin/inertia/pages/easy-setup/index.tsx:253` -- Get all resources from selected tiers for storage projection
- `unit` (function) `admin/inertia/pages/easy-setup/index.tsx:293`
- `canProceedToNextStep` (function) `admin/inertia/pages/easy-setup/index.tsx:334`
- `handleNext` (function) `admin/inertia/pages/easy-setup/index.tsx:340`
- `handleBack` (function) `admin/inertia/pages/easy-setup/index.tsx:347`
- `handleFinish` (function) `admin/inertia/pages/easy-setup/index.tsx:354`
- `msg` (function) `admin/inertia/pages/easy-setup/index.tsx:385`
- `markAsVisited` (function) `admin/inertia/pages/easy-setup/index.tsx:460`
- `renderStepIndicator` (function) `admin/inertia/pages/easy-setup/index.tsx:472`
- `isCapabilitySelected` (function) `admin/inertia/pages/easy-setup/index.tsx:562` -- Check if a capability is selected (all its services are in selectedServices)
- `isCapabilityInstalled` (function) `admin/inertia/pages/easy-setup/index.tsx:567` -- Check if a capability is already installed (all its services are installed)
- `capabilityExists` (function) `admin/inertia/pages/easy-setup/index.tsx:574` -- Check if a capability exists in the system (has at least one matching service)
- `toggleCapability` (function) `admin/inertia/pages/easy-setup/index.tsx:581` -- Toggle all services for a capability (only if not already installed)
- `renderCapabilityCard` (function) `admin/inertia/pages/easy-setup/index.tsx:621`
- `renderStep1` (function) `admin/inertia/pages/easy-setup/index.tsx:723`
- `renderStep2` (function) `admin/inertia/pages/easy-setup/index.tsx:843`
- `renderStep3` (function) `admin/inertia/pages/easy-setup/index.tsx:889`
- `renderStep4` (function) `admin/inertia/pages/easy-setup/index.tsx:991`
- `renderStep5` (function) `admin/inertia/pages/easy-setup/index.tsx:1134`

## admin/inertia/pages/errors/not_found.tsx
- `NotFound` (function) `admin/inertia/pages/errors/not_found.tsx:1`

## admin/inertia/pages/errors/server_error.tsx
- `ServerError` (function) `admin/inertia/pages/errors/server_error.tsx:1`

## admin/inertia/pages/home.tsx
Depends on: `admin/constants/service_names.ts`, `admin/inertia/hooks/useSystemSetting.ts`, `admin/inertia/hooks/useUpdateAvailable.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
Imported by: `admin/app/controllers/home_controller.ts`
- `Home` (function) `admin/inertia/pages/home.tsx:87`
- `tileContent` (function) `admin/inertia/pages/home.tsx:160`

## admin/inertia/pages/maps.tsx
Depends on: `admin/types/files.ts`
- `Maps` (function) `admin/inertia/pages/maps.tsx:12`

## admin/inertia/pages/settings/apps.tsx
Depends on: `admin/constants/broadcast.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useErrorNotification.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstallationActivity.ts`, `admin/inertia/lib/navigation.ts`, `admin/types/services.ts`
Imported by: `admin/app/controllers/settings_controller.ts`
- `extractTag` (function) `admin/inertia/pages/settings/apps.tsx:20`
- `SettingsPage` (function) `admin/inertia/pages/settings/apps.tsx:27`
- `handleCheckUpdates` (function) `admin/inertia/pages/settings/apps.tsx:60`
- `handleInstallService` (function) `admin/inertia/pages/settings/apps.tsx:78`
- `installService` (function) `admin/inertia/pages/settings/apps.tsx:103`
- `handleAffectAction` (function) `admin/inertia/pages/settings/apps.tsx:126`
- `handleForceReinstall` (function) `admin/inertia/pages/settings/apps.tsx:149`
- `handleUpdateService` (function) `admin/inertia/pages/settings/apps.tsx:172`
- `AppActions` (function) `admin/inertia/pages/settings/apps.tsx:202`
- `ForceReinstallButton` (function) `admin/inertia/pages/settings/apps.tsx:203`

## admin/inertia/pages/settings/benchmark.tsx
Depends on: `admin/constants/broadcast.ts`, `admin/constants/service_names.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/benchmark.ts`
- `BenchmarkPage` (function) `admin/inertia/pages/settings/benchmark.tsx:30`
- `handleFullBenchmarkClick` (function) `admin/inertia/pages/settings/benchmark.tsx:198` -- Handle Full Benchmark click with pre-flight check
- `advanceStage` (function) `admin/inertia/pages/settings/benchmark.tsx:277`
- `formatBytes` (function) `admin/inertia/pages/settings/benchmark.tsx:321`
- `getScoreColor` (function) `admin/inertia/pages/settings/benchmark.tsx:326`
- `getProgressPercent` (function) `admin/inertia/pages/settings/benchmark.tsx:332`
- `getAIScore` (function) `admin/inertia/pages/settings/benchmark.tsx:353` -- Calculate AI score from tokens per second (normalized to 0-100) Reference: 30 tok/s = 50 score, 60 tok/s = 100 score
- `score` (function) `admin/inertia/pages/settings/benchmark.tsx:355`

## admin/inertia/pages/settings/legal.tsx
Imported by: `admin/app/controllers/settings_controller.ts`
- `LegalPage` (function) `admin/inertia/pages/settings/legal.tsx:4`

## admin/inertia/pages/settings/maps.tsx
Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/lib/global_map_banner.ts`, `admin/types/files.ts`
- `MapsManager` (function) `admin/inertia/pages/settings/maps.tsx:26`
- `downloadBaseAssets` (function) `admin/inertia/pages/settings/maps.tsx:83`
- `downloadCollection` (function) `admin/inertia/pages/settings/maps.tsx:110`
- `downloadCustomFile` (function) `admin/inertia/pages/settings/maps.tsx:123`
- `deleteFile` (function) `admin/inertia/pages/settings/maps.tsx:136`
- `confirmDeleteFile` (function) `admin/inertia/pages/settings/maps.tsx:159`
- `confirmDownload` (function) `admin/inertia/pages/settings/maps.tsx:179`
- `confirmGlobalMapDownload` (function) `admin/inertia/pages/settings/maps.tsx:213`
- `openCountryPickerModal` (function) `admin/inertia/pages/settings/maps.tsx:236`
- `openDownloadModal` (function) `admin/inertia/pages/settings/maps.tsx:254`

## admin/inertia/pages/settings/models.tsx
Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/types/ollama.ts`
Imported by: `admin/app/controllers/settings_controller.ts`
- `ModelsPage` (function) `admin/inertia/pages/settings/models.tsx:25`
- `handleDismissGpuBanner` (function) `admin/inertia/pages/settings/models.tsx:48`
- `handleForceReinstallOllama` (function) `admin/inertia/pages/settings/models.tsx:55`
- `handleSaveRemoteOllama` (function) `admin/inertia/pages/settings/models.tsx:108`
- `handleClearRemoteOllama` (function) `admin/inertia/pages/settings/models.tsx:125`
- `handleForceRefresh` (function) `admin/inertia/pages/settings/models.tsx:175`
- `handleInstallModel` (function) `admin/inertia/pages/settings/models.tsx:183`
- `handleDeleteModel` (function) `admin/inertia/pages/settings/models.tsx:201`
- `confirmDeleteModel` (function) `admin/inertia/pages/settings/models.tsx:221`

## admin/inertia/pages/settings/support.tsx
Imported by: `admin/app/controllers/settings_controller.ts`
- `SupportPage` (function) `admin/inertia/pages/settings/support.tsx:5`

## admin/inertia/pages/settings/system.tsx
Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/types/system.ts`
- `SettingsPage` (function) `admin/inertia/pages/settings/system.tsx:19`
- `handleDismissGpuBanner` (function) `admin/inertia/pages/settings/system.tsx:37`
- `handleForceReinstallOllama` (function) `admin/inertia/pages/settings/system.tsx:44`

## admin/inertia/pages/settings/update.tsx
Depends on: `admin/app/utils/version.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`, `admin/types/system.ts`
Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/controllers/settings_controller.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/services/countries_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/map_service.ts`, `admin/database/migrations/1771000000002_pin_latest_service_images.ts`, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`, `admin/providers/qdrant_restart_policy_provider.ts`
- `ContentUpdatesSection` (function) `admin/inertia/pages/settings/update.tsx:43`
- `handleCheck` (function) `admin/inertia/pages/settings/update.tsx:52`
- `handleApply` (function) `admin/inertia/pages/settings/update.tsx:70`
- `handleApplyAll` (function) `admin/inertia/pages/settings/update.tsx:99`
- `SystemUpdatePage` (function) `admin/inertia/pages/settings/update.tsx:260`
- `handleStartUpdate` (function) `admin/inertia/pages/settings/update.tsx:338`
- `handleViewLogs` (function) `admin/inertia/pages/settings/update.tsx:353`
- `getProgressBarColor` (function) `admin/inertia/pages/settings/update.tsx:394`
- `getStatusIcon` (function) `admin/inertia/pages/settings/update.tsx:400`

## admin/inertia/pages/settings/zim/index.tsx
Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`
- `ZimPage` (function) `admin/inertia/pages/settings/zim/index.tsx:20`
- `getFiles` (function) `admin/inertia/pages/settings/zim/index.tsx:31`
- `aName` (function) `admin/inertia/pages/settings/zim/index.tsx:46`
- `bName` (function) `admin/inertia/pages/settings/zim/index.tsx:47`
- `toggleSort` (function) `admin/inertia/pages/settings/zim/index.tsx:55`
- `renderSortHeader` (function) `admin/inertia/pages/settings/zim/index.tsx:64`
- `confirmDeleteFile` (function) `admin/inertia/pages/settings/zim/index.tsx:79`

## admin/inertia/pages/settings/zim/remote-explorer.tsx
Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/hooks/useDebounce.ts`, `admin/inertia/hooks/useDownloads.ts`, `admin/inertia/hooks/useInternetStatus.ts`, `admin/inertia/hooks/useServiceInstalledStatus.tsx`, `admin/types/zim.ts`
- `ZimRemoteExplorer` (function) `admin/inertia/pages/settings/zim/remote-explorer.tsx:54`
- `handleSourceChange` (function) `admin/inertia/pages/settings/zim/remote-explorer.tsx:210` -- When selecting a custom library, navigate to its root
- `navigateToDirectory` (function) `admin/inertia/pages/settings/zim/remote-explorer.tsx:227`
- `navigateToBreadcrumb` (function) `admin/inertia/pages/settings/zim/remote-explorer.tsx:232`
- `confirmDownload` (function) `admin/inertia/pages/settings/zim/remote-explorer.tsx:238`
- `confirmCustomDownload` (function) `admin/inertia/pages/settings/zim/remote-explorer.tsx:263`
- `downloadFile` (function) `admin/inertia/pages/settings/zim/remote-explorer.tsx:288`
- `downloadCustomFile` (function) `admin/inertia/pages/settings/zim/remote-explorer.tsx:302`
- `handleCategoryClick` (function) `admin/inertia/pages/settings/zim/remote-explorer.tsx:323` -- Category/tier handlers
- `handleTierSelect` (function) `admin/inertia/pages/settings/zim/remote-explorer.tsx:329`
- `closeTierModal` (function) `admin/inertia/pages/settings/zim/remote-explorer.tsx:350`
- `handleWikipediaSelect` (function) `admin/inertia/pages/settings/zim/remote-explorer.tsx:356` -- Wikipedia selection handlers
- `handleWikipediaSubmit` (function) `admin/inertia/pages/settings/zim/remote-explorer.tsx:361`

## admin/inertia/providers/ModalProvider.tsx
Depends on: `admin/inertia/context/ModalContext.ts`
- `openModal` (function) `admin/inertia/providers/ModalProvider.tsx:12`
- `closeModal` (function) `admin/inertia/providers/ModalProvider.tsx:20`
- `closeAllModals` (function) `admin/inertia/providers/ModalProvider.tsx:31`

## admin/inertia/providers/NotificationProvider.tsx
Depends on: `admin/inertia/context/NotificationContext.ts`
- `NotificationsProvider` (function) `admin/inertia/providers/NotificationProvider.tsx:6`
- `addNotification` (function) `admin/inertia/providers/NotificationProvider.tsx:9`
- `removeNotification` (function) `admin/inertia/providers/NotificationProvider.tsx:29`
- `removeAllNotifications` (function) `admin/inertia/providers/NotificationProvider.tsx:33`
- `Icon` (function) `admin/inertia/providers/NotificationProvider.tsx:37`

## admin/inertia/providers/ThemeProvider.tsx
Depends on: `admin/inertia/hooks/useTheme.ts`
Imported by: `admin/inertia/app/app.tsx`, `admin/inertia/components/ThemeToggle.tsx`
- `ThemeProvider` (function) `admin/inertia/providers/ThemeProvider.tsx:16`
- `useThemeContext` (function) `admin/inertia/providers/ThemeProvider.tsx:25`

## admin/providers/gpu_passthrough_remediation_provider.ts
- `KVStore` (function) `admin/providers/gpu_passthrough_remediation_provider.ts:31`
- `Docker` (function) `admin/providers/gpu_passthrough_remediation_provider.ts:34`

## admin/providers/kiwix_migration_provider.ts
- `Service` (function) `admin/providers/kiwix_migration_provider.ts:22`

## admin/providers/qdrant_restart_policy_provider.ts
Depends on: `admin/inertia/pages/settings/update.tsx`
- `Service` (function) `admin/providers/qdrant_restart_policy_provider.ts:22`
- `Docker` (function) `admin/providers/qdrant_restart_policy_provider.ts:24`

## admin/providers/version_check_provider.ts
- `KVStore` (function) `admin/providers/version_check_provider.ts:30`
- `cachedLatest` (function) `admin/providers/version_check_provider.ts:42`
- `earlyAccess` (function) `admin/providers/version_check_provider.ts:43`

## admin/tests/bootstrap.ts
- `to` (function) `admin/tests/bootstrap.ts:18`

## admin/util/docs.ts
Imported by: `admin/app/services/docs_service.ts`, `admin/inertia/lib/kb_file_grouping.ts`
- `streamToString` (function) `admin/util/docs.ts:2`

## admin/util/files.ts
- `chmodRecursive` (function) `admin/util/files.ts:4`
- `chownRecursive` (function) `admin/util/files.ts:30`

## admin/util/zim.ts
- `isRawListRemoteZimFilesResponse` (function) `admin/util/zim.ts:3`
- `isRawRemoteZimFileEntry` (function) `admin/util/zim.ts:21`

## install/install_nomad.sh
- `header` (function) `install/install_nomad.sh:47`
- `header_red` (function) `install/install_nomad.sh:52`
- `check_has_sudo` (function) `install/install_nomad.sh:57`
- `check_is_bash` (function) `install/install_nomad.sh:69`
- `check_is_debian_based` (function) `install/install_nomad.sh:79`
- `check_is_x86_64` (function) `install/install_nomad.sh:89`
- `ensure_dependencies_installed` (function) `install/install_nomad.sh:104`
- `check_is_debug_mode` (function) `install/install_nomad.sh:140`
- `generateRandomPass` (function) `install/install_nomad.sh:149`
- `ensure_docker_installed` (function) `install/install_nomad.sh:159`
- `check_docker_compose` (function) `install/install_nomad.sh:220`
- `setup_nvidia_container_toolkit` (function) `install/install_nomad.sh:230`
- `get_install_confirmation` (function) `install/install_nomad.sh:355`
- `accept_terms` (function) `install/install_nomad.sh:370`
- `create_nomad_directory` (function) `install/install_nomad.sh:391`
- `download_management_compose_file` (function) `install/install_nomad.sh:410`
- `download_helper_scripts` (function) `install/install_nomad.sh:445`
- `start_management_containers` (function) `install/install_nomad.sh:472`
- `get_local_ip` (function) `install/install_nomad.sh:481`
- `verify_gpu_setup` (function) `install/install_nomad.sh:488`
- `success_message` (function) `install/install_nomad.sh:598`

## install/migrate-disk-collector.sh
- `check_is_bash` (function) `install/migrate-disk-collector.sh:46`
- `check_has_sudo` (function) `install/migrate-disk-collector.sh:55`
- `check_confirmation` (function) `install/migrate-disk-collector.sh:65`
- `check_docker_running` (function) `install/migrate-disk-collector.sh:81`
- `check_compose_file` (function) `install/migrate-disk-collector.sh:93`
- `stop_old_host_process` (function) `install/migrate-disk-collector.sh:103` -- Step 1: Stop old host process
- `backup_compose_file` (function) `install/migrate-disk-collector.sh:122` -- Step 2: Backup compose.yml
- `remove_old_bind_mount` (function) `install/migrate-disk-collector.sh:134` -- Step 3: Remove old bind-mount from admin volumes
- `add_disk_collector_service` (function) `install/migrate-disk-collector.sh:153` -- Step 4: Add disk-collector service block
- `restart_stack` (function) `install/migrate-disk-collector.sh:186` -- Step 5 — Pull new image and restart the full stack This will re-create the admin container and drop the old /tmp...
- `verify_disk_collector_running` (function) `install/migrate-disk-collector.sh:203` -- Step 6: Verify

## install/run_updater_fixes.sh
- `check_is_bash` (function) `install/run_updater_fixes.sh:55`
- `check_confirmation` (function) `install/run_updater_fixes.sh:64`
- `check_has_sudo` (function) `install/run_updater_fixes.sh:75`
- `check_docker_running` (function) `install/run_updater_fixes.sh:85`
- `check_compose_file` (function) `install/run_updater_fixes.sh:97`
- `check_sidecar_dir` (function) `install/run_updater_fixes.sh:106`
- `backup_compose_file` (function) `install/run_updater_fixes.sh:119`
- `fix_sidecar_volume_mount` (function) `install/run_updater_fixes.sh:130`
- `download_updated_sidecar_files` (function) `install/run_updater_fixes.sh:153`
- `rebuild_sidecar` (function) `install/run_updater_fixes.sh:170`
- `restart_sidecar` (function) `install/run_updater_fixes.sh:179`
- `verify_sidecar_running` (function) `install/run_updater_fixes.sh:197`

## install/sidecar-disk-collector/collect-disk-info.sh
- `log` (function) `install/sidecar-disk-collector/collect-disk-info.sh:9`

## install/sidecar-updater/update-watcher.sh
- `log` (function) `install/sidecar-updater/update-watcher.sh:12`
- `write_status` (function) `install/sidecar-updater/update-watcher.sh:16`
- `perform_update` (function) `install/sidecar-updater/update-watcher.sh:31`
- `cleanup` (function) `install/sidecar-updater/update-watcher.sh:111`

## install/uninstall_nomad.sh
- `check_has_sudo` (function) `install/uninstall_nomad.sh:27`
- `check_current_directory` (function) `install/uninstall_nomad.sh:39`
- `ensure_management_compose_file_exists` (function) `install/uninstall_nomad.sh:46`
- `get_uninstall_confirmation` (function) `install/uninstall_nomad.sh:53`
- `ensure_docker_installed` (function) `install/uninstall_nomad.sh:71`
- `check_docker_compose` (function) `install/uninstall_nomad.sh:78`
- `storage_cleanup` (function) `install/uninstall_nomad.sh:88`
- `uninstall_nomad` (function) `install/uninstall_nomad.sh:105`

## install/update_nomad.sh
- `check_has_sudo` (function) `install/update_nomad.sh:31`
- `check_is_bash` (function) `install/update_nomad.sh:43`
- `check_is_debian_based` (function) `install/update_nomad.sh:53`
- `get_update_confirmation` (function) `install/update_nomad.sh:63`
- `ensure_docker_installed_and_running` (function) `install/update_nomad.sh:81`
- `check_docker_compose` (function) `install/update_nomad.sh:97`
- `ensure_docker_compose_file_exists` (function) `install/update_nomad.sh:107`
- `force_recreate` (function) `install/update_nomad.sh:114`
- `get_local_ip` (function) `install/update_nomad.sh:128`
- `success_message` (function) `install/update_nomad.sh:136`

