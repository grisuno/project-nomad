# Polyglot Codebase Knowledge Graph

> Generated offline by **readmenator**. Supports C, C++, Python, Go, Rust, JS/TS, Java, C#, Shell, PHP, Dart, GDScript, Nim, ASM.
> No LLMs. No tokens. Pure static analysis. See more [here](https://github.com/grisuno/ReadMenator)

**Total Files Parsed:** 295 | **Total Symbols Extracted:** 567 | **Total Imports:** 668

## Structural Knowledge Map
> **Note:** The visual graph below has been intelligently pruned to the top 300 most relevant nodes to prevent rendering crashes. Full details of all 295 files are documented below.

```mermaid
graph TD
    classDef mod fill:#1e1e1e,stroke:#ff6666,stroke-width:2px,color:#fff;
    classDef cls fill:#2d2d2d,stroke:#4ec9b0,stroke-width:2px,color:#fff;
    classDef fn fill:#333,stroke:#dcdcaa,stroke-width:1px,color:#dcdcaa;
    classDef ext fill:#111,stroke:#666,stroke-dasharray:5 5,color:#aaa;
    admin_app_services_rag_service_ts["rag_service.ts (ts)"]
    class admin_app_services_rag_service_ts mod;
    admin_app_services_rag_service_ts_progress["progress"]
    class admin_app_services_rag_service_ts_progress fn;
    admin_app_services_rag_service_ts --> admin_app_services_rag_service_ts_progress
    admin_app_services_rag_service_ts_RagService["RagService"]
    class admin_app_services_rag_service_ts_RagService cls;
    admin_app_services_rag_service_ts --> admin_app_services_rag_service_ts_RagService
    admin_app_services_rag_service_ts_if["if"]
    class admin_app_services_rag_service_ts_if cls;
    admin_app_services_rag_service_ts --> admin_app_services_rag_service_ts_if
    admin_app_services_map_service_ts["map_service.ts (ts)"]
    class admin_app_services_map_service_ts mod;
    admin_app_services_map_service_ts_getHost["getHost"]
    class admin_app_services_map_service_ts_getHost fn;
    admin_app_services_map_service_ts --> admin_app_services_map_service_ts_getHost
    admin_app_services_map_service_ts_specifiedHostOrDefault["specifiedHostOrDefault"]
    class admin_app_services_map_service_ts_specifiedHostOrDefault fn;
    admin_app_services_map_service_ts --> admin_app_services_map_service_ts_specifiedHostOrDefault
    admin_app_services_map_service_ts_findExactGroupMatch["findExactGroupMatch"]
    class admin_app_services_map_service_ts_findExactGroupMatch fn;
    admin_app_services_map_service_ts --> admin_app_services_map_service_ts_findExactGroupMatch
    admin_app_services_map_service_ts_files["files"]
    class admin_app_services_map_service_ts_files fn;
    admin_app_services_map_service_ts --> admin_app_services_map_service_ts_files
    admin_app_services_map_service_ts_regions["regions"]
    class admin_app_services_map_service_ts_regions fn;
    admin_app_services_map_service_ts --> admin_app_services_map_service_ts_regions
    admin_app_services_zim_service_ts["zim_service.ts (ts)"]
    class admin_app_services_zim_service_ts mod;
    admin_app_services_zim_service_ts_ZimService["ZimService"]
    class admin_app_services_zim_service_ts_ZimService cls;
    admin_app_services_zim_service_ts --> admin_app_services_zim_service_ts_ZimService
    admin_app_services_system_service_ts["system_service.ts (ts)"]
    class admin_app_services_system_service_ts mod;
    admin_app_services_system_service_ts_buf["buf"]
    class admin_app_services_system_service_ts_buf fn;
    admin_app_services_system_service_ts --> admin_app_services_system_service_ts_buf
    admin_app_services_system_service_ts_actualImage["actualImage"]
    class admin_app_services_system_service_ts_actualImage fn;
    admin_app_services_system_service_ts --> admin_app_services_system_service_ts_actualImage
    admin_app_services_system_service_ts_isDiscreteGpuVendor["isDiscreteGpuVendor"]
    class admin_app_services_system_service_ts_isDiscreteGpuVendor fn;
    admin_app_services_system_service_ts --> admin_app_services_system_service_ts_isDiscreteGpuVendor
    admin_app_services_system_service_ts_isBogusDgpuVram["isBogusDgpuVram"]
    class admin_app_services_system_service_ts_isBogusDgpuVram fn;
    admin_app_services_system_service_ts --> admin_app_services_system_service_ts_isBogusDgpuVram
    admin_app_services_system_service_ts_hasLspciBogusDgpuVram["hasLspciBogusDgpuVram"]
    class admin_app_services_system_service_ts_hasLspciBogusDgpuVram fn;
    admin_app_services_system_service_ts --> admin_app_services_system_service_ts_hasLspciBogusDgpuVram
    admin_app_services_docker_service_ts["docker_service.ts (ts)"]
    class admin_app_services_docker_service_ts mod;
    admin_app_services_docker_service_ts_used["used"]
    class admin_app_services_docker_service_ts_used fn;
    admin_app_services_docker_service_ts --> admin_app_services_docker_service_ts_used
    admin_app_services_docker_service_ts_is["is"]
    class admin_app_services_docker_service_ts_is fn;
    admin_app_services_docker_service_ts --> admin_app_services_docker_service_ts_is
    admin_app_services_docker_service_ts_marker["marker"]
    class admin_app_services_docker_service_ts_marker fn;
    admin_app_services_docker_service_ts --> admin_app_services_docker_service_ts_marker
    admin_app_services_docker_service_ts_gfx["gfx"]
    class admin_app_services_docker_service_ts_gfx fn;
    admin_app_services_docker_service_ts --> admin_app_services_docker_service_ts_gfx
    admin_app_services_docker_service_ts_DockerService["DockerService"]
    class admin_app_services_docker_service_ts_DockerService cls;
    admin_app_services_docker_service_ts --> admin_app_services_docker_service_ts_DockerService
    admin_inertia_pages_easy_setup_index_tsx["index.tsx (tsx)"]
    class admin_inertia_pages_easy_setup_index_tsx mod;
    admin_inertia_pages_easy_setup_index_tsx_buildCoreCapabilities["buildCoreCapabilities"]
    class admin_inertia_pages_easy_setup_index_tsx_buildCoreCapabilities fn;
    admin_inertia_pages_easy_setup_index_tsx --> admin_inertia_pages_easy_setup_index_tsx_buildCoreCapabilities
    admin_inertia_pages_easy_setup_index_tsx_EasySetupWizard["EasySetupWizard"]
    class admin_inertia_pages_easy_setup_index_tsx_EasySetupWizard fn;
    admin_inertia_pages_easy_setup_index_tsx --> admin_inertia_pages_easy_setup_index_tsx_EasySetupWizard
    admin_inertia_pages_easy_setup_index_tsx_toggleMapCollection["toggleMapCollection"]
    class admin_inertia_pages_easy_setup_index_tsx_toggleMapCollection fn;
    admin_inertia_pages_easy_setup_index_tsx --> admin_inertia_pages_easy_setup_index_tsx_toggleMapCollection
    admin_inertia_pages_easy_setup_index_tsx_toggleAiModel["toggleAiModel"]
    class admin_inertia_pages_easy_setup_index_tsx_toggleAiModel fn;
    admin_inertia_pages_easy_setup_index_tsx --> admin_inertia_pages_easy_setup_index_tsx_toggleAiModel
    admin_inertia_pages_easy_setup_index_tsx_handleCategoryClick["handleCategoryClick"]
    class admin_inertia_pages_easy_setup_index_tsx_handleCategoryClick fn;
    admin_inertia_pages_easy_setup_index_tsx --> admin_inertia_pages_easy_setup_index_tsx_handleCategoryClick
    admin_inertia_pages_settings_zim_remote_explorer_tsx["remote-explorer.tsx (tsx)"]
    class admin_inertia_pages_settings_zim_remote_explorer_tsx mod;
    admin_inertia_pages_settings_zim_remote_explorer_tsx_ZimRemoteExplorer["ZimRemoteExplorer"]
    class admin_inertia_pages_settings_zim_remote_explorer_tsx_ZimRemoteExplorer fn;
    admin_inertia_pages_settings_zim_remote_explorer_tsx --> admin_inertia_pages_settings_zim_remote_explorer_tsx_ZimRemoteExplorer
    admin_inertia_pages_settings_zim_remote_explorer_tsx_confirmDownload["confirmDownload"]
    class admin_inertia_pages_settings_zim_remote_explorer_tsx_confirmDownload fn;
    admin_inertia_pages_settings_zim_remote_explorer_tsx --> admin_inertia_pages_settings_zim_remote_explorer_tsx_confirmDownload
    admin_inertia_pages_settings_zim_remote_explorer_tsx_confirmCustomDownload["confirmCustomDownload"]
    class admin_inertia_pages_settings_zim_remote_explorer_tsx_confirmCustomDownload fn;
    admin_inertia_pages_settings_zim_remote_explorer_tsx --> admin_inertia_pages_settings_zim_remote_explorer_tsx_confirmCustomDownload
    admin_inertia_pages_settings_zim_remote_explorer_tsx_downloadFile["downloadFile"]
    class admin_inertia_pages_settings_zim_remote_explorer_tsx_downloadFile fn;
    admin_inertia_pages_settings_zim_remote_explorer_tsx --> admin_inertia_pages_settings_zim_remote_explorer_tsx_downloadFile
    admin_inertia_pages_settings_zim_remote_explorer_tsx_downloadCustomFile["downloadCustomFile"]
    class admin_inertia_pages_settings_zim_remote_explorer_tsx_downloadCustomFile fn;
    admin_inertia_pages_settings_zim_remote_explorer_tsx --> admin_inertia_pages_settings_zim_remote_explorer_tsx_downloadCustomFile
    admin_inertia_pages_settings_models_tsx["models.tsx (tsx)"]
    class admin_inertia_pages_settings_models_tsx mod;
    admin_inertia_pages_settings_models_tsx_ModelsPage["ModelsPage"]
    class admin_inertia_pages_settings_models_tsx_ModelsPage fn;
    admin_inertia_pages_settings_models_tsx --> admin_inertia_pages_settings_models_tsx_ModelsPage
    admin_inertia_pages_settings_models_tsx_handleSaveRemoteOllama["handleSaveRemoteOllama"]
    class admin_inertia_pages_settings_models_tsx_handleSaveRemoteOllama fn;
    admin_inertia_pages_settings_models_tsx --> admin_inertia_pages_settings_models_tsx_handleSaveRemoteOllama
    admin_inertia_pages_settings_models_tsx_handleClearRemoteOllama["handleClearRemoteOllama"]
    class admin_inertia_pages_settings_models_tsx_handleClearRemoteOllama fn;
    admin_inertia_pages_settings_models_tsx --> admin_inertia_pages_settings_models_tsx_handleClearRemoteOllama
    admin_inertia_pages_settings_models_tsx_handleForceRefresh["handleForceRefresh"]
    class admin_inertia_pages_settings_models_tsx_handleForceRefresh fn;
    admin_inertia_pages_settings_models_tsx --> admin_inertia_pages_settings_models_tsx_handleForceRefresh
    admin_inertia_pages_settings_models_tsx_handleInstallModel["handleInstallModel"]
    class admin_inertia_pages_settings_models_tsx_handleInstallModel fn;
    admin_inertia_pages_settings_models_tsx --> admin_inertia_pages_settings_models_tsx_handleInstallModel
    admin_app_controllers_ollama_controller_ts["ollama_controller.ts (ts)"]
    class admin_app_controllers_ollama_controller_ts mod;
    admin_app_controllers_ollama_controller_ts_OllamaController["OllamaController"]
    class admin_app_controllers_ollama_controller_ts_OllamaController cls;
    admin_app_controllers_ollama_controller_ts --> admin_app_controllers_ollama_controller_ts_OllamaController
    admin_inertia_app_app_tsx["app.tsx (tsx)"]
    class admin_inertia_app_app_tsx mod;
    admin_inertia_app_app_tsx_environment["environment"]
    class admin_inertia_app_app_tsx_environment fn;
    admin_inertia_app_app_tsx --> admin_inertia_app_app_tsx_environment
    admin_inertia_components_TierSelectionModal_tsx["TierSelectionModal.tsx (tsx)"]
    class admin_inertia_components_TierSelectionModal_tsx mod;
    admin_inertia_components_TierSelectionModal_tsx_resourceFilename["resourceFilename"]
    class admin_inertia_components_TierSelectionModal_tsx_resourceFilename fn;
    admin_inertia_components_TierSelectionModal_tsx --> admin_inertia_components_TierSelectionModal_tsx_resourceFilename
    admin_inertia_components_TierSelectionModal_tsx_getAllResourcesForTier["getAllResourcesForTier"]
    class admin_inertia_components_TierSelectionModal_tsx_getAllResourcesForTier fn;
    admin_inertia_components_TierSelectionModal_tsx --> admin_inertia_components_TierSelectionModal_tsx_getAllResourcesForTier
    admin_inertia_components_TierSelectionModal_tsx_getTierTotalSize["getTierTotalSize"]
    class admin_inertia_components_TierSelectionModal_tsx_getTierTotalSize fn;
    admin_inertia_components_TierSelectionModal_tsx --> admin_inertia_components_TierSelectionModal_tsx_getTierTotalSize
    admin_inertia_components_TierSelectionModal_tsx_handleTierClick["handleTierClick"]
    class admin_inertia_components_TierSelectionModal_tsx_handleTierClick fn;
    admin_inertia_components_TierSelectionModal_tsx --> admin_inertia_components_TierSelectionModal_tsx_handleTierClick
    admin_inertia_components_TierSelectionModal_tsx_finalizeSubmit["finalizeSubmit"]
    class admin_inertia_components_TierSelectionModal_tsx_finalizeSubmit fn;
    admin_inertia_components_TierSelectionModal_tsx --> admin_inertia_components_TierSelectionModal_tsx_finalizeSubmit
    admin_inertia_pages_settings_system_tsx["system.tsx (tsx)"]
    class admin_inertia_pages_settings_system_tsx mod;
    admin_inertia_pages_settings_system_tsx_SettingsPage["SettingsPage"]
    class admin_inertia_pages_settings_system_tsx_SettingsPage fn;
    admin_inertia_pages_settings_system_tsx --> admin_inertia_pages_settings_system_tsx_SettingsPage
    admin_inertia_pages_settings_system_tsx_handleDismissGpuBanner["handleDismissGpuBanner"]
    class admin_inertia_pages_settings_system_tsx_handleDismissGpuBanner fn;
    admin_inertia_pages_settings_system_tsx --> admin_inertia_pages_settings_system_tsx_handleDismissGpuBanner
    admin_inertia_pages_settings_system_tsx_handleForceReinstallOllama["handleForceReinstallOllama"]
    class admin_inertia_pages_settings_system_tsx_handleForceReinstallOllama fn;
    admin_inertia_pages_settings_system_tsx --> admin_inertia_pages_settings_system_tsx_handleForceReinstallOllama
    admin_app_jobs_run_download_job_ts["run_download_job.ts (ts)"]
    class admin_app_jobs_run_download_job_ts mod;
    admin_app_jobs_run_download_job_ts_progressPercent["progressPercent"]
    class admin_app_jobs_run_download_job_ts_progressPercent fn;
    admin_app_jobs_run_download_job_ts --> admin_app_jobs_run_download_job_ts_progressPercent
    admin_app_jobs_run_download_job_ts_RunDownloadJob["RunDownloadJob"]
    class admin_app_jobs_run_download_job_ts_RunDownloadJob cls;
    admin_app_jobs_run_download_job_ts --> admin_app_jobs_run_download_job_ts_RunDownloadJob
    admin_app_jobs_run_extract_pmtiles_job_ts["run_extract_pmtiles_job.ts (ts)"]
    class admin_app_jobs_run_extract_pmtiles_job_ts mod;
    admin_app_jobs_run_extract_pmtiles_job_ts_RunExtractPmtilesJob["RunExtractPmtilesJob"]
    class admin_app_jobs_run_extract_pmtiles_job_ts_RunExtractPmtilesJob cls;
    admin_app_jobs_run_extract_pmtiles_job_ts --> admin_app_jobs_run_extract_pmtiles_job_ts_RunExtractPmtilesJob
    admin_app_services_download_service_ts["download_service.ts (ts)"]
    class admin_app_services_download_service_ts mod;
    admin_app_services_download_service_ts_DownloadService["DownloadService"]
    class admin_app_services_download_service_ts_DownloadService cls;
    admin_app_services_download_service_ts --> admin_app_services_download_service_ts_DownloadService
    admin_commands_queue_work_ts["work.ts (ts)"]
    class admin_commands_queue_work_ts mod;
    admin_commands_queue_work_ts_QueueWork["QueueWork"]
    class admin_commands_queue_work_ts_QueueWork cls;
    admin_commands_queue_work_ts --> admin_commands_queue_work_ts_QueueWork
    admin_inertia_lib_api_ts["api.ts (ts)"]
    class admin_inertia_lib_api_ts mod;
    admin_inertia_lib_api_ts_API["API"]
    class admin_inertia_lib_api_ts_API cls;
    admin_inertia_lib_api_ts --> admin_inertia_lib_api_ts_API
    admin_inertia_pages_settings_apps_tsx["apps.tsx (tsx)"]
    class admin_inertia_pages_settings_apps_tsx mod;
    admin_inertia_pages_settings_apps_tsx_extractTag["extractTag"]
    class admin_inertia_pages_settings_apps_tsx_extractTag fn;
    admin_inertia_pages_settings_apps_tsx --> admin_inertia_pages_settings_apps_tsx_extractTag
    admin_inertia_pages_settings_apps_tsx_SettingsPage["SettingsPage"]
    class admin_inertia_pages_settings_apps_tsx_SettingsPage fn;
    admin_inertia_pages_settings_apps_tsx --> admin_inertia_pages_settings_apps_tsx_SettingsPage
    admin_inertia_pages_settings_apps_tsx_handleCheckUpdates["handleCheckUpdates"]
    class admin_inertia_pages_settings_apps_tsx_handleCheckUpdates fn;
    admin_inertia_pages_settings_apps_tsx --> admin_inertia_pages_settings_apps_tsx_handleCheckUpdates
    admin_inertia_pages_settings_apps_tsx_installService["installService"]
    class admin_inertia_pages_settings_apps_tsx_installService fn;
    admin_inertia_pages_settings_apps_tsx --> admin_inertia_pages_settings_apps_tsx_installService
    admin_inertia_pages_settings_apps_tsx_handleAffectAction["handleAffectAction"]
    class admin_inertia_pages_settings_apps_tsx_handleAffectAction fn;
    admin_inertia_pages_settings_apps_tsx --> admin_inertia_pages_settings_apps_tsx_handleAffectAction
    admin_inertia_pages_settings_maps_tsx["maps.tsx (tsx)"]
    class admin_inertia_pages_settings_maps_tsx mod;
    admin_inertia_pages_settings_maps_tsx_MapsManager["MapsManager"]
    class admin_inertia_pages_settings_maps_tsx_MapsManager fn;
    admin_inertia_pages_settings_maps_tsx --> admin_inertia_pages_settings_maps_tsx_MapsManager
    admin_inertia_pages_settings_maps_tsx_downloadBaseAssets["downloadBaseAssets"]
    class admin_inertia_pages_settings_maps_tsx_downloadBaseAssets fn;
    admin_inertia_pages_settings_maps_tsx --> admin_inertia_pages_settings_maps_tsx_downloadBaseAssets
    admin_inertia_pages_settings_maps_tsx_downloadCollection["downloadCollection"]
    class admin_inertia_pages_settings_maps_tsx_downloadCollection fn;
    admin_inertia_pages_settings_maps_tsx --> admin_inertia_pages_settings_maps_tsx_downloadCollection
    admin_inertia_pages_settings_maps_tsx_downloadCustomFile["downloadCustomFile"]
    class admin_inertia_pages_settings_maps_tsx_downloadCustomFile fn;
    admin_inertia_pages_settings_maps_tsx --> admin_inertia_pages_settings_maps_tsx_downloadCustomFile
    admin_inertia_pages_settings_maps_tsx_deleteFile["deleteFile"]
    class admin_inertia_pages_settings_maps_tsx_deleteFile fn;
    admin_inertia_pages_settings_maps_tsx --> admin_inertia_pages_settings_maps_tsx_deleteFile
    admin_inertia_pages_settings_update_tsx["update.tsx (tsx)"]
    class admin_inertia_pages_settings_update_tsx mod;
    admin_inertia_pages_settings_update_tsx_ContentUpdatesSection["ContentUpdatesSection"]
    class admin_inertia_pages_settings_update_tsx_ContentUpdatesSection fn;
    admin_inertia_pages_settings_update_tsx --> admin_inertia_pages_settings_update_tsx_ContentUpdatesSection
    admin_inertia_pages_settings_update_tsx_SystemUpdatePage["SystemUpdatePage"]
    class admin_inertia_pages_settings_update_tsx_SystemUpdatePage fn;
    admin_inertia_pages_settings_update_tsx --> admin_inertia_pages_settings_update_tsx_SystemUpdatePage
    admin_inertia_pages_settings_update_tsx_handleCheck["handleCheck"]
    class admin_inertia_pages_settings_update_tsx_handleCheck fn;
    admin_inertia_pages_settings_update_tsx --> admin_inertia_pages_settings_update_tsx_handleCheck
    admin_inertia_pages_settings_update_tsx_handleApply["handleApply"]
    class admin_inertia_pages_settings_update_tsx_handleApply fn;
    admin_inertia_pages_settings_update_tsx --> admin_inertia_pages_settings_update_tsx_handleApply
    admin_inertia_pages_settings_update_tsx_handleApplyAll["handleApplyAll"]
    class admin_inertia_pages_settings_update_tsx_handleApplyAll fn;
    admin_inertia_pages_settings_update_tsx --> admin_inertia_pages_settings_update_tsx_handleApplyAll
    admin_inertia_pages_settings_benchmark_tsx["benchmark.tsx (tsx)"]
    class admin_inertia_pages_settings_benchmark_tsx mod;
    admin_inertia_pages_settings_benchmark_tsx_BenchmarkPage["BenchmarkPage"]
    class admin_inertia_pages_settings_benchmark_tsx_BenchmarkPage fn;
    admin_inertia_pages_settings_benchmark_tsx --> admin_inertia_pages_settings_benchmark_tsx_BenchmarkPage
    admin_inertia_pages_settings_benchmark_tsx_handleFullBenchmarkClick["handleFullBenchmarkClick"]
    class admin_inertia_pages_settings_benchmark_tsx_handleFullBenchmarkClick fn;
    admin_inertia_pages_settings_benchmark_tsx --> admin_inertia_pages_settings_benchmark_tsx_handleFullBenchmarkClick
    admin_inertia_pages_settings_benchmark_tsx_advanceStage["advanceStage"]
    class admin_inertia_pages_settings_benchmark_tsx_advanceStage fn;
    admin_inertia_pages_settings_benchmark_tsx --> admin_inertia_pages_settings_benchmark_tsx_advanceStage
    admin_inertia_pages_settings_benchmark_tsx_formatBytes["formatBytes"]
    class admin_inertia_pages_settings_benchmark_tsx_formatBytes fn;
    admin_inertia_pages_settings_benchmark_tsx --> admin_inertia_pages_settings_benchmark_tsx_formatBytes
    admin_inertia_pages_settings_benchmark_tsx_getScoreColor["getScoreColor"]
    class admin_inertia_pages_settings_benchmark_tsx_getScoreColor fn;
    admin_inertia_pages_settings_benchmark_tsx --> admin_inertia_pages_settings_benchmark_tsx_getScoreColor
    admin_inertia_pages_settings_zim_index_tsx["index.tsx (tsx)"]
    class admin_inertia_pages_settings_zim_index_tsx mod;
    admin_inertia_pages_settings_zim_index_tsx_ZimPage["ZimPage"]
    class admin_inertia_pages_settings_zim_index_tsx_ZimPage fn;
    admin_inertia_pages_settings_zim_index_tsx --> admin_inertia_pages_settings_zim_index_tsx_ZimPage
    admin_inertia_pages_settings_zim_index_tsx_getFiles["getFiles"]
    class admin_inertia_pages_settings_zim_index_tsx_getFiles fn;
    admin_inertia_pages_settings_zim_index_tsx --> admin_inertia_pages_settings_zim_index_tsx_getFiles
    admin_inertia_pages_settings_zim_index_tsx_toggleSort["toggleSort"]
    class admin_inertia_pages_settings_zim_index_tsx_toggleSort fn;
    admin_inertia_pages_settings_zim_index_tsx --> admin_inertia_pages_settings_zim_index_tsx_toggleSort
    admin_inertia_pages_settings_zim_index_tsx_renderSortHeader["renderSortHeader"]
    class admin_inertia_pages_settings_zim_index_tsx_renderSortHeader fn;
    admin_inertia_pages_settings_zim_index_tsx --> admin_inertia_pages_settings_zim_index_tsx_renderSortHeader
    admin_inertia_pages_settings_zim_index_tsx_confirmDeleteFile["confirmDeleteFile"]
    class admin_inertia_pages_settings_zim_index_tsx_confirmDeleteFile fn;
    admin_inertia_pages_settings_zim_index_tsx --> admin_inertia_pages_settings_zim_index_tsx_confirmDeleteFile
    admin_app_jobs_embed_file_job_ts["embed_file_job.ts (ts)"]
    class admin_app_jobs_embed_file_job_ts mod;
    admin_app_jobs_embed_file_job_ts_onProgress["onProgress"]
    class admin_app_jobs_embed_file_job_ts_onProgress fn;
    admin_app_jobs_embed_file_job_ts --> admin_app_jobs_embed_file_job_ts_onProgress
    admin_app_jobs_embed_file_job_ts_articlesDone["articlesDone"]
    class admin_app_jobs_embed_file_job_ts_articlesDone fn;
    admin_app_jobs_embed_file_job_ts --> admin_app_jobs_embed_file_job_ts_articlesDone
    admin_app_jobs_embed_file_job_ts_nextOffset["nextOffset"]
    class admin_app_jobs_embed_file_job_ts_nextOffset fn;
    admin_app_jobs_embed_file_job_ts --> admin_app_jobs_embed_file_job_ts_nextOffset
    admin_app_jobs_embed_file_job_ts_totalChunks["totalChunks"]
    class admin_app_jobs_embed_file_job_ts_totalChunks fn;
    admin_app_jobs_embed_file_job_ts --> admin_app_jobs_embed_file_job_ts_totalChunks
    admin_app_jobs_embed_file_job_ts_filePath["filePath"]
    class admin_app_jobs_embed_file_job_ts_filePath fn;
    admin_app_jobs_embed_file_job_ts --> admin_app_jobs_embed_file_job_ts_filePath
    admin_inertia_components_chat_index_tsx["index.tsx (tsx)"]
    class admin_inertia_components_chat_index_tsx mod;
    admin_inertia_components_chat_index_tsx_Chat["Chat"]
    class admin_inertia_components_chat_index_tsx_Chat fn;
    admin_inertia_components_chat_index_tsx --> admin_inertia_components_chat_index_tsx_Chat
    admin_app_services_ollama_service_ts["ollama_service.ts (ts)"]
    class admin_app_services_ollama_service_ts mod;
    admin_app_services_ollama_service_ts_partialTagSuffix["partialTagSuffix"]
    class admin_app_services_ollama_service_ts_partialTagSuffix fn;
    admin_app_services_ollama_service_ts --> admin_app_services_ollama_service_ts_partialTagSuffix
    admin_app_services_ollama_service_ts_customUrl["customUrl"]
    class admin_app_services_ollama_service_ts_customUrl fn;
    admin_app_services_ollama_service_ts --> admin_app_services_ollama_service_ts_customUrl
    admin_app_services_ollama_service_ts_onAbort["onAbort"]
    class admin_app_services_ollama_service_ts_onAbort fn;
    admin_app_services_ollama_service_ts --> admin_app_services_ollama_service_ts_onAbort
    admin_app_services_ollama_service_ts_stream["stream"]
    class admin_app_services_ollama_service_ts_stream fn;
    admin_app_services_ollama_service_ts --> admin_app_services_ollama_service_ts_stream
    admin_app_services_ollama_service_ts_parsePulls["parsePulls"]
    class admin_app_services_ollama_service_ts_parsePulls fn;
    admin_app_services_ollama_service_ts --> admin_app_services_ollama_service_ts_parsePulls
    admin_inertia_components_chat_KnowledgeBaseModal_tsx["KnowledgeBaseModal.tsx (tsx)"]
    class admin_inertia_components_chat_KnowledgeBaseModal_tsx mod;
    admin_inertia_components_chat_KnowledgeBaseModal_tsx_renderStatePill["renderStatePill"]
    class admin_inertia_components_chat_KnowledgeBaseModal_tsx_renderStatePill fn;
    admin_inertia_components_chat_KnowledgeBaseModal_tsx --> admin_inertia_components_chat_KnowledgeBaseModal_tsx_renderStatePill
    admin_inertia_components_chat_KnowledgeBaseModal_tsx_pickRowAction["pickRowAction"]
    class admin_inertia_components_chat_KnowledgeBaseModal_tsx_pickRowAction fn;
    admin_inertia_components_chat_KnowledgeBaseModal_tsx --> admin_inertia_components_chat_KnowledgeBaseModal_tsx_pickRowAction
    admin_inertia_components_chat_KnowledgeBaseModal_tsx_KnowledgeBaseModal["KnowledgeBaseModal"]
    class admin_inertia_components_chat_KnowledgeBaseModal_tsx_KnowledgeBaseModal fn;
    admin_inertia_components_chat_KnowledgeBaseModal_tsx --> admin_inertia_components_chat_KnowledgeBaseModal_tsx_KnowledgeBaseModal
    admin_inertia_components_chat_KnowledgeBaseModal_tsx_handleUpload["handleUpload"]
    class admin_inertia_components_chat_KnowledgeBaseModal_tsx_handleUpload fn;
    admin_inertia_components_chat_KnowledgeBaseModal_tsx --> admin_inertia_components_chat_KnowledgeBaseModal_tsx_handleUpload
    admin_inertia_components_chat_KnowledgeBaseModal_tsx_handleConfirmSync["handleConfirmSync"]
    class admin_inertia_components_chat_KnowledgeBaseModal_tsx_handleConfirmSync fn;
    admin_inertia_components_chat_KnowledgeBaseModal_tsx --> admin_inertia_components_chat_KnowledgeBaseModal_tsx_handleConfirmSync
    admin_app_services_benchmark_service_ts["benchmark_service.ts (ts)"]
    class admin_app_services_benchmark_service_ts mod;
    admin_app_services_benchmark_service_ts_totalTime["totalTime"]
    class admin_app_services_benchmark_service_ts_totalTime fn;
    admin_app_services_benchmark_service_ts --> admin_app_services_benchmark_service_ts_totalTime
    admin_app_services_benchmark_service_ts_BenchmarkService["BenchmarkService"]
    class admin_app_services_benchmark_service_ts_BenchmarkService cls;
    admin_app_services_benchmark_service_ts --> admin_app_services_benchmark_service_ts_BenchmarkService
    admin_inertia_pages_home_tsx["home.tsx (tsx)"]
    class admin_inertia_pages_home_tsx mod;
    admin_inertia_pages_home_tsx_Home["Home"]
    class admin_inertia_pages_home_tsx_Home fn;
    admin_inertia_pages_home_tsx --> admin_inertia_pages_home_tsx_Home
    admin_inertia_pages_home_tsx_tileContent["tileContent"]
    class admin_inertia_pages_home_tsx_tileContent fn;
    admin_inertia_pages_home_tsx --> admin_inertia_pages_home_tsx_tileContent
    admin_app_controllers_rag_controller_ts["rag_controller.ts (ts)"]
    class admin_app_controllers_rag_controller_ts mod;
    admin_app_controllers_rag_controller_ts_RagController["RagController"]
    class admin_app_controllers_rag_controller_ts_RagController cls;
    admin_app_controllers_rag_controller_ts --> admin_app_controllers_rag_controller_ts_RagController
    admin_app_controllers_system_controller_ts["system_controller.ts (ts)"]
    class admin_app_controllers_system_controller_ts mod;
    admin_app_controllers_system_controller_ts_SystemController["SystemController"]
    class admin_app_controllers_system_controller_ts_SystemController cls;
    admin_app_controllers_system_controller_ts --> admin_app_controllers_system_controller_ts_SystemController
    admin_inertia_components_chat_ChatInterface_tsx["ChatInterface.tsx (tsx)"]
    class admin_inertia_components_chat_ChatInterface_tsx mod;
    admin_inertia_components_chat_ChatInterface_tsx_ChatInterface["ChatInterface"]
    class admin_inertia_components_chat_ChatInterface_tsx_ChatInterface fn;
    admin_inertia_components_chat_ChatInterface_tsx --> admin_inertia_components_chat_ChatInterface_tsx_ChatInterface
    admin_inertia_components_chat_ChatInterface_tsx_handleDownloadModel["handleDownloadModel"]
    class admin_inertia_components_chat_ChatInterface_tsx_handleDownloadModel fn;
    admin_inertia_components_chat_ChatInterface_tsx --> admin_inertia_components_chat_ChatInterface_tsx_handleDownloadModel
    admin_inertia_components_chat_ChatInterface_tsx_scrollToBottom["scrollToBottom"]
    class admin_inertia_components_chat_ChatInterface_tsx_scrollToBottom fn;
    admin_inertia_components_chat_ChatInterface_tsx --> admin_inertia_components_chat_ChatInterface_tsx_scrollToBottom
    admin_inertia_components_chat_ChatInterface_tsx_handleSubmit["handleSubmit"]
    class admin_inertia_components_chat_ChatInterface_tsx_handleSubmit fn;
    admin_inertia_components_chat_ChatInterface_tsx --> admin_inertia_components_chat_ChatInterface_tsx_handleSubmit
    admin_inertia_components_chat_ChatInterface_tsx_handleKeyDown["handleKeyDown"]
    class admin_inertia_components_chat_ChatInterface_tsx_handleKeyDown fn;
    admin_inertia_components_chat_ChatInterface_tsx --> admin_inertia_components_chat_ChatInterface_tsx_handleKeyDown
    admin_inertia_components_StyledSidebar_tsx["StyledSidebar.tsx (tsx)"]
    class admin_inertia_components_StyledSidebar_tsx mod;
    admin_inertia_components_StyledSidebar_tsx_ListItem["ListItem"]
    class admin_inertia_components_StyledSidebar_tsx_ListItem fn;
    admin_inertia_components_StyledSidebar_tsx --> admin_inertia_components_StyledSidebar_tsx_ListItem
    admin_inertia_components_StyledSidebar_tsx_content["content"]
    class admin_inertia_components_StyledSidebar_tsx_content fn;
    admin_inertia_components_StyledSidebar_tsx --> admin_inertia_components_StyledSidebar_tsx_content
    admin_inertia_components_StyledSidebar_tsx_Sidebar["Sidebar"]
    class admin_inertia_components_StyledSidebar_tsx_Sidebar fn;
    admin_inertia_components_StyledSidebar_tsx --> admin_inertia_components_StyledSidebar_tsx_Sidebar
    admin_app_services_kiwix_library_service_ts["kiwix_library_service.ts (ts)"]
    class admin_app_services_kiwix_library_service_ts mod;
    admin_app_services_kiwix_library_service_ts_getMeta["getMeta"]
    class admin_app_services_kiwix_library_service_ts_getMeta fn;
    admin_app_services_kiwix_library_service_ts --> admin_app_services_kiwix_library_service_ts_getMeta
    admin_app_services_kiwix_library_service_ts_KiwixLibraryService["KiwixLibraryService"]
    class admin_app_services_kiwix_library_service_ts_KiwixLibraryService cls;
    admin_app_services_kiwix_library_service_ts --> admin_app_services_kiwix_library_service_ts_KiwixLibraryService
    admin_app_controllers_settings_controller_ts["settings_controller.ts (ts)"]
    class admin_app_controllers_settings_controller_ts mod;
    admin_app_controllers_settings_controller_ts_SettingsController["SettingsController"]
    class admin_app_controllers_settings_controller_ts_SettingsController cls;
    admin_app_controllers_settings_controller_ts --> admin_app_controllers_settings_controller_ts_SettingsController
    admin_app_jobs_check_service_updates_job_ts["check_service_updates_job.ts (ts)"]
    class admin_app_jobs_check_service_updates_job_ts mod;
    admin_app_jobs_check_service_updates_job_ts_CheckServiceUpdatesJob["CheckServiceUpdatesJob"]
    class admin_app_jobs_check_service_updates_job_ts_CheckServiceUpdatesJob cls;
    admin_app_jobs_check_service_updates_job_ts --> admin_app_jobs_check_service_updates_job_ts_CheckServiceUpdatesJob
    admin_app_services_collection_manifest_service_ts["collection_manifest_service.ts (ts)"]
    class admin_app_services_collection_manifest_service_ts mod;
    admin_app_services_collection_manifest_service_ts_CollectionManifestService["CollectionManifestService"]
    class admin_app_services_collection_manifest_service_ts_CollectionManifestService cls;
    admin_app_services_collection_manifest_service_ts --> admin_app_services_collection_manifest_service_ts_CollectionManifestService
    admin_app_services_zim_extraction_service_ts["zim_extraction_service.ts (ts)"]
    class admin_app_services_zim_extraction_service_ts mod;
    admin_app_services_zim_extraction_service_ts_ZIMExtractionService["ZIMExtractionService"]
    class admin_app_services_zim_extraction_service_ts_ZIMExtractionService cls;
    admin_app_services_zim_extraction_service_ts --> admin_app_services_zim_extraction_service_ts_ZIMExtractionService
    admin_app_utils_downloads_ts["downloads.ts (ts)"]
    class admin_app_utils_downloads_ts mod;
    admin_app_utils_downloads_ts_doResumableDownload["doResumableDownload"]
    class admin_app_utils_downloads_ts_doResumableDownload fn;
    admin_app_utils_downloads_ts --> admin_app_utils_downloads_ts_doResumableDownload
    admin_app_utils_downloads_ts_doResumableDownloadWithRetry["doResumableDownloadWithRetry"]
    class admin_app_utils_downloads_ts_doResumableDownloadWithRetry fn;
    admin_app_utils_downloads_ts --> admin_app_utils_downloads_ts_doResumableDownloadWithRetry
    admin_app_utils_downloads_ts_delay["delay"]
    class admin_app_utils_downloads_ts_delay fn;
    admin_app_utils_downloads_ts --> admin_app_utils_downloads_ts_delay
    admin_app_utils_downloads_ts_fetchStream["fetchStream"]
    class admin_app_utils_downloads_ts_fetchStream fn;
    admin_app_utils_downloads_ts --> admin_app_utils_downloads_ts_fetchStream
    admin_app_utils_downloads_ts_clearStallTimer["clearStallTimer"]
    class admin_app_utils_downloads_ts_clearStallTimer fn;
    admin_app_utils_downloads_ts --> admin_app_utils_downloads_ts_clearStallTimer
    admin_inertia_components_MarkdocRenderer_tsx["MarkdocRenderer.tsx (tsx)"]
    class admin_inertia_components_MarkdocRenderer_tsx mod;
    admin_inertia_components_MarkdocRenderer_tsx_Paragraph["Paragraph"]
    class admin_inertia_components_MarkdocRenderer_tsx_Paragraph fn;
    admin_inertia_components_MarkdocRenderer_tsx --> admin_inertia_components_MarkdocRenderer_tsx_Paragraph
    admin_inertia_components_MarkdocRenderer_tsx_Link["Link"]
    class admin_inertia_components_MarkdocRenderer_tsx_Link fn;
    admin_inertia_components_MarkdocRenderer_tsx --> admin_inertia_components_MarkdocRenderer_tsx_Link
    admin_inertia_components_MarkdocRenderer_tsx_InlineCode["InlineCode"]
    class admin_inertia_components_MarkdocRenderer_tsx_InlineCode fn;
    admin_inertia_components_MarkdocRenderer_tsx --> admin_inertia_components_MarkdocRenderer_tsx_InlineCode
    admin_inertia_components_MarkdocRenderer_tsx_CodeBlock["CodeBlock"]
    class admin_inertia_components_MarkdocRenderer_tsx_CodeBlock fn;
    admin_inertia_components_MarkdocRenderer_tsx --> admin_inertia_components_MarkdocRenderer_tsx_CodeBlock
    admin_inertia_components_MarkdocRenderer_tsx_HorizontalRule["HorizontalRule"]
    class admin_inertia_components_MarkdocRenderer_tsx_HorizontalRule fn;
    admin_inertia_components_MarkdocRenderer_tsx --> admin_inertia_components_MarkdocRenderer_tsx_HorizontalRule
    admin_inertia_components_CountryPickerModal_tsx["CountryPickerModal.tsx (tsx)"]
    class admin_inertia_components_CountryPickerModal_tsx mod;
    admin_inertia_components_CountryPickerModal_tsx_toggleCountry["toggleCountry"]
    class admin_inertia_components_CountryPickerModal_tsx_toggleCountry fn;
    admin_inertia_components_CountryPickerModal_tsx --> admin_inertia_components_CountryPickerModal_tsx_toggleCountry
    admin_inertia_components_CountryPickerModal_tsx_toggleGroup["toggleGroup"]
    class admin_inertia_components_CountryPickerModal_tsx_toggleGroup fn;
    admin_inertia_components_CountryPickerModal_tsx --> admin_inertia_components_CountryPickerModal_tsx_toggleGroup
    admin_inertia_components_CountryPickerModal_tsx_clearAll["clearAll"]
    class admin_inertia_components_CountryPickerModal_tsx_clearAll fn;
    admin_inertia_components_CountryPickerModal_tsx --> admin_inertia_components_CountryPickerModal_tsx_clearAll
    admin_inertia_components_CountryPickerModal_tsx_startDownload["startDownload"]
    class admin_inertia_components_CountryPickerModal_tsx_startDownload fn;
    admin_inertia_components_CountryPickerModal_tsx --> admin_inertia_components_CountryPickerModal_tsx_startDownload
    admin_inertia_components_CountryPickerModal_tsx_PreflightStatus["PreflightStatus"]
    class admin_inertia_components_CountryPickerModal_tsx_PreflightStatus fn;
    admin_inertia_components_CountryPickerModal_tsx --> admin_inertia_components_CountryPickerModal_tsx_PreflightStatus
    admin_app_controllers_benchmark_controller_ts["benchmark_controller.ts (ts)"]
    class admin_app_controllers_benchmark_controller_ts mod;
    admin_app_controllers_benchmark_controller_ts_statusCode["statusCode"]
    class admin_app_controllers_benchmark_controller_ts_statusCode fn;
    admin_app_controllers_benchmark_controller_ts --> admin_app_controllers_benchmark_controller_ts_statusCode
    admin_app_controllers_benchmark_controller_ts_BenchmarkController["BenchmarkController"]
    class admin_app_controllers_benchmark_controller_ts_BenchmarkController cls;
    admin_app_controllers_benchmark_controller_ts --> admin_app_controllers_benchmark_controller_ts_BenchmarkController
    admin_app_controllers_chats_controller_ts["chats_controller.ts (ts)"]
    class admin_app_controllers_chats_controller_ts mod;
    admin_app_controllers_chats_controller_ts_ChatsController["ChatsController"]
    class admin_app_controllers_chats_controller_ts_ChatsController cls;
    admin_app_controllers_chats_controller_ts --> admin_app_controllers_chats_controller_ts_ChatsController
    admin_app_services_chat_service_ts["chat_service.ts (ts)"]
    class admin_app_services_chat_service_ts mod;
    admin_app_services_chat_service_ts_ChatService["ChatService"]
    class admin_app_services_chat_service_ts_ChatService cls;
    admin_app_services_chat_service_ts --> admin_app_services_chat_service_ts_ChatService
    admin_inertia_components_file_uploader_index_tsx["index.tsx (tsx)"]
    class admin_inertia_components_file_uploader_index_tsx mod;
    admin_app_utils_fs_ts["fs.ts (ts)"]
    class admin_app_utils_fs_ts mod;
    admin_app_utils_fs_ts_listDirectoryContents["listDirectoryContents"]
    class admin_app_utils_fs_ts_listDirectoryContents fn;
    admin_app_utils_fs_ts --> admin_app_utils_fs_ts_listDirectoryContents
    admin_app_utils_fs_ts_listDirectoryContentsRecursive["listDirectoryContentsRecursive"]
    class admin_app_utils_fs_ts_listDirectoryContentsRecursive fn;
    admin_app_utils_fs_ts --> admin_app_utils_fs_ts_listDirectoryContentsRecursive
    admin_app_utils_fs_ts_ensureDirectoryExists["ensureDirectoryExists"]
    class admin_app_utils_fs_ts_ensureDirectoryExists fn;
    admin_app_utils_fs_ts --> admin_app_utils_fs_ts_ensureDirectoryExists
    admin_app_utils_fs_ts_getFile["getFile"]
    class admin_app_utils_fs_ts_getFile fn;
    admin_app_utils_fs_ts --> admin_app_utils_fs_ts_getFile
    admin_app_utils_fs_ts_getFile["getFile"]
    class admin_app_utils_fs_ts_getFile fn;
    admin_app_utils_fs_ts --> admin_app_utils_fs_ts_getFile
    admin_app_services_countries_service_ts["countries_service.ts (ts)"]
    class admin_app_services_countries_service_ts mod;
    admin_app_services_countries_service_ts_typeRank["typeRank"]
    class admin_app_services_countries_service_ts_typeRank fn;
    admin_app_services_countries_service_ts --> admin_app_services_countries_service_ts_typeRank
    admin_app_services_countries_service_ts_resolveIso2["resolveIso2"]
    class admin_app_services_countries_service_ts_resolveIso2 fn;
    admin_app_services_countries_service_ts --> admin_app_services_countries_service_ts_resolveIso2
    admin_app_services_countries_service_ts_bufferGeometry["bufferGeometry"]
    class admin_app_services_countries_service_ts_bufferGeometry fn;
    admin_app_services_countries_service_ts --> admin_app_services_countries_service_ts_bufferGeometry
    admin_app_services_countries_service_ts_bufferPolygonRings["bufferPolygonRings"]
    class admin_app_services_countries_service_ts_bufferPolygonRings fn;
    admin_app_services_countries_service_ts --> admin_app_services_countries_service_ts_bufferPolygonRings
    admin_app_services_countries_service_ts_bufferRing["bufferRing"]
    class admin_app_services_countries_service_ts_bufferRing fn;
    admin_app_services_countries_service_ts --> admin_app_services_countries_service_ts_bufferRing
    admin_inertia_components_ActiveModelDownloads_tsx["ActiveModelDownloads.tsx (tsx)"]
    class admin_inertia_components_ActiveModelDownloads_tsx mod;
    admin_inertia_components_ActiveModelDownloads_tsx_formatSpeed["formatSpeed"]
    class admin_inertia_components_ActiveModelDownloads_tsx_formatSpeed fn;
    admin_inertia_components_ActiveModelDownloads_tsx --> admin_inertia_components_ActiveModelDownloads_tsx_formatSpeed
    admin_inertia_components_ActiveModelDownloads_tsx_ActiveModelDownloads["ActiveModelDownloads"]
    class admin_inertia_components_ActiveModelDownloads_tsx_ActiveModelDownloads fn;
    admin_inertia_components_ActiveModelDownloads_tsx --> admin_inertia_components_ActiveModelDownloads_tsx_ActiveModelDownloads
    admin_inertia_components_ActiveModelDownloads_tsx_deltaSec["deltaSec"]
    class admin_inertia_components_ActiveModelDownloads_tsx_deltaSec fn;
    admin_inertia_components_ActiveModelDownloads_tsx --> admin_inertia_components_ActiveModelDownloads_tsx_deltaSec
    admin_inertia_components_ActiveModelDownloads_tsx_runCancel["runCancel"]
    class admin_inertia_components_ActiveModelDownloads_tsx_runCancel fn;
    admin_inertia_components_ActiveModelDownloads_tsx --> admin_inertia_components_ActiveModelDownloads_tsx_runCancel
    admin_inertia_components_ActiveModelDownloads_tsx_confirmCancel["confirmCancel"]
    class admin_inertia_components_ActiveModelDownloads_tsx_confirmCancel fn;
    admin_inertia_components_ActiveModelDownloads_tsx --> admin_inertia_components_ActiveModelDownloads_tsx_confirmCancel
    admin_inertia_providers_NotificationProvider_tsx["NotificationProvider.tsx (tsx)"]
    class admin_inertia_providers_NotificationProvider_tsx mod;
    admin_inertia_providers_NotificationProvider_tsx_NotificationsProvider["NotificationsProvider"]
    class admin_inertia_providers_NotificationProvider_tsx_NotificationsProvider fn;
    admin_inertia_providers_NotificationProvider_tsx --> admin_inertia_providers_NotificationProvider_tsx_NotificationsProvider
    admin_inertia_providers_NotificationProvider_tsx_addNotification["addNotification"]
    class admin_inertia_providers_NotificationProvider_tsx_addNotification fn;
    admin_inertia_providers_NotificationProvider_tsx --> admin_inertia_providers_NotificationProvider_tsx_addNotification
    admin_inertia_providers_NotificationProvider_tsx_removeNotification["removeNotification"]
    class admin_inertia_providers_NotificationProvider_tsx_removeNotification fn;
    admin_inertia_providers_NotificationProvider_tsx --> admin_inertia_providers_NotificationProvider_tsx_removeNotification
    admin_inertia_providers_NotificationProvider_tsx_removeAllNotifications["removeAllNotifications"]
    class admin_inertia_providers_NotificationProvider_tsx_removeAllNotifications fn;
    admin_inertia_providers_NotificationProvider_tsx --> admin_inertia_providers_NotificationProvider_tsx_removeAllNotifications
    admin_inertia_providers_NotificationProvider_tsx_Icon["Icon"]
    class admin_inertia_providers_NotificationProvider_tsx_Icon fn;
    admin_inertia_providers_NotificationProvider_tsx --> admin_inertia_providers_NotificationProvider_tsx_Icon
    admin_inertia_components_chat_ChatSidebar_tsx["ChatSidebar.tsx (tsx)"]
    class admin_inertia_components_chat_ChatSidebar_tsx mod;
    admin_inertia_components_chat_ChatSidebar_tsx_ChatSidebar["ChatSidebar"]
    class admin_inertia_components_chat_ChatSidebar_tsx_ChatSidebar fn;
    admin_inertia_components_chat_ChatSidebar_tsx --> admin_inertia_components_chat_ChatSidebar_tsx_ChatSidebar
    admin_inertia_components_chat_ChatSidebar_tsx_handleCloseKnowledgeBase["handleCloseKnowledgeBase"]
    class admin_inertia_components_chat_ChatSidebar_tsx_handleCloseKnowledgeBase fn;
    admin_inertia_components_chat_ChatSidebar_tsx --> admin_inertia_components_chat_ChatSidebar_tsx_handleCloseKnowledgeBase
    admin_app_controllers_easy_setup_controller_ts["easy_setup_controller.ts (ts)"]
    class admin_app_controllers_easy_setup_controller_ts mod;
    admin_app_controllers_easy_setup_controller_ts_EasySetupController["EasySetupController"]
    class admin_app_controllers_easy_setup_controller_ts_EasySetupController cls;
    admin_app_controllers_easy_setup_controller_ts --> admin_app_controllers_easy_setup_controller_ts_EasySetupController
    admin_app_controllers_zim_controller_ts["zim_controller.ts (ts)"]
    class admin_app_controllers_zim_controller_ts mod;
    admin_app_controllers_zim_controller_ts_ZimController["ZimController"]
    class admin_app_controllers_zim_controller_ts_ZimController cls;
    admin_app_controllers_zim_controller_ts --> admin_app_controllers_zim_controller_ts_ZimController
    admin_app_jobs_check_update_job_ts["check_update_job.ts (ts)"]
    class admin_app_jobs_check_update_job_ts mod;
    admin_app_jobs_check_update_job_ts_CheckUpdateJob["CheckUpdateJob"]
    class admin_app_jobs_check_update_job_ts_CheckUpdateJob cls;
    admin_app_jobs_check_update_job_ts --> admin_app_jobs_check_update_job_ts_CheckUpdateJob
    admin_app_jobs_download_model_job_ts["download_model_job.ts (ts)"]
    class admin_app_jobs_download_model_job_ts mod;
    admin_app_jobs_download_model_job_ts_DownloadModelJob["DownloadModelJob"]
    class admin_app_jobs_download_model_job_ts_DownloadModelJob cls;
    admin_app_jobs_download_model_job_ts --> admin_app_jobs_download_model_job_ts_DownloadModelJob
    admin_app_jobs_run_benchmark_job_ts["run_benchmark_job.ts (ts)"]
    class admin_app_jobs_run_benchmark_job_ts mod;
    admin_app_jobs_run_benchmark_job_ts_RunBenchmarkJob["RunBenchmarkJob"]
    class admin_app_jobs_run_benchmark_job_ts_RunBenchmarkJob cls;
    admin_app_jobs_run_benchmark_job_ts --> admin_app_jobs_run_benchmark_job_ts_RunBenchmarkJob
    admin_app_models_kv_store_ts["kv_store.ts (ts)"]
    class admin_app_models_kv_store_ts mod;
    admin_app_models_kv_store_ts_KVStore["KVStore"]
    class admin_app_models_kv_store_ts_KVStore cls;
    admin_app_models_kv_store_ts --> admin_app_models_kv_store_ts_KVStore
    admin_app_services_collection_update_service_ts["collection_update_service.ts (ts)"]
    class admin_app_services_collection_update_service_ts mod;
    admin_app_services_collection_update_service_ts_CollectionUpdateService["CollectionUpdateService"]
    class admin_app_services_collection_update_service_ts_CollectionUpdateService cls;
    admin_app_services_collection_update_service_ts --> admin_app_services_collection_update_service_ts_CollectionUpdateService
    admin_database_seeders_service_seeder_ts["service_seeder.ts (ts)"]
    class admin_database_seeders_service_seeder_ts mod;
    admin_database_seeders_service_seeder_ts_ServiceSeeder["ServiceSeeder"]
    class admin_database_seeders_service_seeder_ts_ServiceSeeder cls;
    admin_database_seeders_service_seeder_ts --> admin_database_seeders_service_seeder_ts_ServiceSeeder
    admin_inertia_components_Footer_tsx["Footer.tsx (tsx)"]
    class admin_inertia_components_Footer_tsx mod;
    admin_inertia_components_Footer_tsx_Footer["Footer"]
    class admin_inertia_components_Footer_tsx_Footer fn;
    admin_inertia_components_Footer_tsx --> admin_inertia_components_Footer_tsx_Footer
    admin_inertia_components_KbGuardrailModal_tsx["KbGuardrailModal.tsx (tsx)"]
    class admin_inertia_components_KbGuardrailModal_tsx mod;
    admin_inertia_components_KbGuardrailModal_tsx_KbGuardrailModal["KbGuardrailModal"]
    class admin_inertia_components_KbGuardrailModal_tsx_KbGuardrailModal fn;
    admin_inertia_components_KbGuardrailModal_tsx --> admin_inertia_components_KbGuardrailModal_tsx_KbGuardrailModal
    admin_inertia_components_chat_KbPolicyPromptBanner_tsx["KbPolicyPromptBanner.tsx (tsx)"]
    class admin_inertia_components_chat_KbPolicyPromptBanner_tsx mod;
    admin_inertia_components_chat_KbPolicyPromptBanner_tsx_KbPolicyPromptBanner["KbPolicyPromptBanner"]
    class admin_inertia_components_chat_KbPolicyPromptBanner_tsx_KbPolicyPromptBanner fn;
    admin_inertia_components_chat_KbPolicyPromptBanner_tsx --> admin_inertia_components_chat_KbPolicyPromptBanner_tsx_KbPolicyPromptBanner
    admin_inertia_components_maps_MapComponent_tsx["MapComponent.tsx (tsx)"]
    class admin_inertia_components_maps_MapComponent_tsx mod;
    admin_inertia_components_maps_MapComponent_tsx_MapComponent["MapComponent"]
    class admin_inertia_components_maps_MapComponent_tsx_MapComponent fn;
    admin_inertia_components_maps_MapComponent_tsx --> admin_inertia_components_maps_MapComponent_tsx_MapComponent
    admin_inertia_hooks_useServiceInstallationActivity_ts["useServiceInstallationActivity.ts (ts)"]
    class admin_inertia_hooks_useServiceInstallationActivity_ts mod;
    admin_inertia_hooks_useServiceInstallationActivity_ts_useServiceInstallationActivity["useServiceInstallationActivity"]
    class admin_inertia_hooks_useServiceInstallationActivity_ts_useServiceInstallationActivity fn;
    admin_inertia_hooks_useServiceInstallationActivity_ts --> admin_inertia_hooks_useServiceInstallationActivity_ts_useServiceInstallationActivity
    admin_inertia_layouts_AppLayout_tsx["AppLayout.tsx (tsx)"]
    class admin_inertia_layouts_AppLayout_tsx mod;
    admin_inertia_layouts_AppLayout_tsx_AppLayout["AppLayout"]
    class admin_inertia_layouts_AppLayout_tsx_AppLayout fn;
    admin_inertia_layouts_AppLayout_tsx --> admin_inertia_layouts_AppLayout_tsx_AppLayout
    admin_inertia_layouts_SettingsLayout_tsx["SettingsLayout.tsx (tsx)"]
    class admin_inertia_layouts_SettingsLayout_tsx mod;
    admin_inertia_layouts_SettingsLayout_tsx_SettingsLayout["SettingsLayout"]
    class admin_inertia_layouts_SettingsLayout_tsx_SettingsLayout fn;
    admin_inertia_layouts_SettingsLayout_tsx --> admin_inertia_layouts_SettingsLayout_tsx_SettingsLayout
    admin_inertia_pages_maps_tsx["maps.tsx (tsx)"]
    class admin_inertia_pages_maps_tsx mod;
    admin_inertia_pages_maps_tsx_Maps["Maps"]
    class admin_inertia_pages_maps_tsx_Maps fn;
    admin_inertia_pages_maps_tsx --> admin_inertia_pages_maps_tsx_Maps
    admin_inertia_components_ActiveDownloads_tsx["ActiveDownloads.tsx (tsx)"]
    class admin_inertia_components_ActiveDownloads_tsx mod;
    admin_inertia_components_ActiveDownloads_tsx_formatSpeed["formatSpeed"]
    class admin_inertia_components_ActiveDownloads_tsx_formatSpeed fn;
    admin_inertia_components_ActiveDownloads_tsx --> admin_inertia_components_ActiveDownloads_tsx_formatSpeed
    admin_inertia_components_ActiveDownloads_tsx_getDownloadStatus["getDownloadStatus"]
    class admin_inertia_components_ActiveDownloads_tsx_getDownloadStatus fn;
    admin_inertia_components_ActiveDownloads_tsx --> admin_inertia_components_ActiveDownloads_tsx_getDownloadStatus
    admin_inertia_components_ActiveDownloads_tsx_ActiveDownloads["ActiveDownloads"]
    class admin_inertia_components_ActiveDownloads_tsx_ActiveDownloads fn;
    admin_inertia_components_ActiveDownloads_tsx --> admin_inertia_components_ActiveDownloads_tsx_ActiveDownloads
    admin_inertia_components_ActiveDownloads_tsx_deltaSec["deltaSec"]
    class admin_inertia_components_ActiveDownloads_tsx_deltaSec fn;
    admin_inertia_components_ActiveDownloads_tsx --> admin_inertia_components_ActiveDownloads_tsx_deltaSec
    admin_inertia_components_ActiveDownloads_tsx_handleDismiss["handleDismiss"]
    class admin_inertia_components_ActiveDownloads_tsx_handleDismiss fn;
    admin_inertia_components_ActiveDownloads_tsx --> admin_inertia_components_ActiveDownloads_tsx_handleDismiss
    admin_inertia_components_BuilderTagSelector_tsx["BuilderTagSelector.tsx (tsx)"]
    class admin_inertia_components_BuilderTagSelector_tsx mod;
    admin_inertia_components_BuilderTagSelector_tsx_BuilderTagSelector["BuilderTagSelector"]
    class admin_inertia_components_BuilderTagSelector_tsx_BuilderTagSelector fn;
    admin_inertia_components_BuilderTagSelector_tsx --> admin_inertia_components_BuilderTagSelector_tsx_BuilderTagSelector
    admin_inertia_components_BuilderTagSelector_tsx_updateTag["updateTag"]
    class admin_inertia_components_BuilderTagSelector_tsx_updateTag fn;
    admin_inertia_components_BuilderTagSelector_tsx --> admin_inertia_components_BuilderTagSelector_tsx_updateTag
    admin_inertia_components_BuilderTagSelector_tsx_handleAdjectiveChange["handleAdjectiveChange"]
    class admin_inertia_components_BuilderTagSelector_tsx_handleAdjectiveChange fn;
    admin_inertia_components_BuilderTagSelector_tsx --> admin_inertia_components_BuilderTagSelector_tsx_handleAdjectiveChange
    admin_inertia_components_BuilderTagSelector_tsx_handleNounChange["handleNounChange"]
    class admin_inertia_components_BuilderTagSelector_tsx_handleNounChange fn;
    admin_inertia_components_BuilderTagSelector_tsx --> admin_inertia_components_BuilderTagSelector_tsx_handleNounChange
    admin_inertia_components_BuilderTagSelector_tsx_handleRandomize["handleRandomize"]
    class admin_inertia_components_BuilderTagSelector_tsx_handleRandomize fn;
    admin_inertia_components_BuilderTagSelector_tsx --> admin_inertia_components_BuilderTagSelector_tsx_handleRandomize
    admin_app_middleware_container_bindings_middleware_ts["container_bindings_middleware.ts (ts)"]
    class admin_app_middleware_container_bindings_middleware_ts mod;
    admin_app_middleware_container_bindings_middleware_ts_to["to"]
    class admin_app_middleware_container_bindings_middleware_ts_to cls;
    admin_app_middleware_container_bindings_middleware_ts --> admin_app_middleware_container_bindings_middleware_ts_to
    admin_app_middleware_container_bindings_middleware_ts_to["to"]
    class admin_app_middleware_container_bindings_middleware_ts_to cls;
    admin_app_middleware_container_bindings_middleware_ts --> admin_app_middleware_container_bindings_middleware_ts_to
    admin_app_middleware_container_bindings_middleware_ts_ContainerBindingsMiddleware["ContainerBindingsMiddleware"]
    class admin_app_middleware_container_bindings_middleware_ts_ContainerBindingsMiddleware cls;
    admin_app_middleware_container_bindings_middleware_ts --> admin_app_middleware_container_bindings_middleware_ts_ContainerBindingsMiddleware
    admin_inertia_components_UpdateServiceModal_tsx["UpdateServiceModal.tsx (tsx)"]
    class admin_inertia_components_UpdateServiceModal_tsx mod;
    admin_inertia_components_UpdateServiceModal_tsx_UpdateServiceModal["UpdateServiceModal"]
    class admin_inertia_components_UpdateServiceModal_tsx_UpdateServiceModal fn;
    admin_inertia_components_UpdateServiceModal_tsx --> admin_inertia_components_UpdateServiceModal_tsx_UpdateServiceModal
    admin_inertia_components_UpdateServiceModal_tsx_loadVersions["loadVersions"]
    class admin_inertia_components_UpdateServiceModal_tsx_loadVersions fn;
    admin_inertia_components_UpdateServiceModal_tsx --> admin_inertia_components_UpdateServiceModal_tsx_loadVersions
    admin_inertia_components_UpdateServiceModal_tsx_handleToggleAdvanced["handleToggleAdvanced"]
    class admin_inertia_components_UpdateServiceModal_tsx_handleToggleAdvanced fn;
    admin_inertia_components_UpdateServiceModal_tsx --> admin_inertia_components_UpdateServiceModal_tsx_handleToggleAdvanced
    admin_inertia_hooks_useDiskDisplayData_ts["useDiskDisplayData.ts (ts)"]
    class admin_inertia_hooks_useDiskDisplayData_ts mod;
    admin_inertia_hooks_useDiskDisplayData_ts_getAllDiskDisplayItems["getAllDiskDisplayItems"]
    class admin_inertia_hooks_useDiskDisplayData_ts_getAllDiskDisplayItems fn;
    admin_inertia_hooks_useDiskDisplayData_ts --> admin_inertia_hooks_useDiskDisplayData_ts_getAllDiskDisplayItems
    admin_inertia_hooks_useDiskDisplayData_ts_getPrimaryDiskInfo["getPrimaryDiskInfo"]
    class admin_inertia_hooks_useDiskDisplayData_ts_getPrimaryDiskInfo fn;
    admin_inertia_hooks_useDiskDisplayData_ts --> admin_inertia_hooks_useDiskDisplayData_ts_getPrimaryDiskInfo
    admin_app_controllers_downloads_controller_ts["downloads_controller.ts (ts)"]
    class admin_app_controllers_downloads_controller_ts mod;
    admin_app_controllers_downloads_controller_ts_DownloadsController["DownloadsController"]
    class admin_app_controllers_downloads_controller_ts_DownloadsController cls;
    admin_app_controllers_downloads_controller_ts --> admin_app_controllers_downloads_controller_ts_DownloadsController
    admin_app_controllers_maps_controller_ts["maps_controller.ts (ts)"]
    class admin_app_controllers_maps_controller_ts mod;
    admin_app_controllers_maps_controller_ts_MapsController["MapsController"]
    class admin_app_controllers_maps_controller_ts_MapsController cls;
    admin_app_controllers_maps_controller_ts --> admin_app_controllers_maps_controller_ts_MapsController
    admin_app_models_kb_ratio_registry_ts["kb_ratio_registry.ts (ts)"]
    class admin_app_models_kb_ratio_registry_ts mod;
    admin_app_models_kb_ratio_registry_ts_KbRatioRegistry["KbRatioRegistry"]
    class admin_app_models_kb_ratio_registry_ts_KbRatioRegistry cls;
    admin_app_models_kb_ratio_registry_ts --> admin_app_models_kb_ratio_registry_ts_KbRatioRegistry
    admin_app_services_system_update_service_ts["system_update_service.ts (ts)"]
    class admin_app_services_system_update_service_ts mod;
    admin_app_services_system_update_service_ts_SystemUpdateService["SystemUpdateService"]
    class admin_app_services_system_update_service_ts_SystemUpdateService cls;
    admin_app_services_system_update_service_ts --> admin_app_services_system_update_service_ts_SystemUpdateService
    admin_inertia_components_chat_ChatModal_tsx["ChatModal.tsx (tsx)"]
    class admin_inertia_components_chat_ChatModal_tsx mod;
    admin_inertia_components_chat_ChatModal_tsx_ChatModal["ChatModal"]
    class admin_inertia_components_chat_ChatModal_tsx_ChatModal fn;
    admin_inertia_components_chat_ChatModal_tsx --> admin_inertia_components_chat_ChatModal_tsx_ChatModal
    admin_inertia_components_maps_MarkerPanel_tsx["MarkerPanel.tsx (tsx)"]
    class admin_inertia_components_maps_MarkerPanel_tsx mod;
    admin_inertia_components_maps_MarkerPanel_tsx_MarkerPanel["MarkerPanel"]
    class admin_inertia_components_maps_MarkerPanel_tsx_MarkerPanel fn;
    admin_inertia_components_maps_MarkerPanel_tsx --> admin_inertia_components_maps_MarkerPanel_tsx_MarkerPanel
    admin_inertia_components_WikipediaSelector_tsx["WikipediaSelector.tsx (tsx)"]
    class admin_inertia_components_WikipediaSelector_tsx mod;
    admin_inertia_components_StorageProjectionBar_tsx["StorageProjectionBar.tsx (tsx)"]
    class admin_inertia_components_StorageProjectionBar_tsx mod;
    admin_inertia_components_StorageProjectionBar_tsx_StorageProjectionBar["StorageProjectionBar"]
    class admin_inertia_components_StorageProjectionBar_tsx_StorageProjectionBar fn;
    admin_inertia_components_StorageProjectionBar_tsx --> admin_inertia_components_StorageProjectionBar_tsx_StorageProjectionBar
    admin_inertia_components_StorageProjectionBar_tsx_currentPercent["currentPercent"]
    class admin_inertia_components_StorageProjectionBar_tsx_currentPercent fn;
    admin_inertia_components_StorageProjectionBar_tsx --> admin_inertia_components_StorageProjectionBar_tsx_currentPercent
    admin_inertia_components_StorageProjectionBar_tsx_projectedPercent["projectedPercent"]
    class admin_inertia_components_StorageProjectionBar_tsx_projectedPercent fn;
    admin_inertia_components_StorageProjectionBar_tsx --> admin_inertia_components_StorageProjectionBar_tsx_projectedPercent
    admin_inertia_components_StorageProjectionBar_tsx_projectedTotalPercent["projectedTotalPercent"]
    class admin_inertia_components_StorageProjectionBar_tsx_projectedTotalPercent fn;
    admin_inertia_components_StorageProjectionBar_tsx --> admin_inertia_components_StorageProjectionBar_tsx_projectedTotalPercent
    admin_inertia_components_StorageProjectionBar_tsx_getProjectedColor["getProjectedColor"]
    class admin_inertia_components_StorageProjectionBar_tsx_getProjectedColor fn;
    admin_inertia_components_StorageProjectionBar_tsx --> admin_inertia_components_StorageProjectionBar_tsx_getProjectedColor
    admin_inertia_components_StyledButton_tsx["StyledButton.tsx (tsx)"]
    class admin_inertia_components_StyledButton_tsx mod;
    admin_inertia_components_StyledButton_tsx_getIconSize["getIconSize"]
    class admin_inertia_components_StyledButton_tsx_getIconSize fn;
    admin_inertia_components_StyledButton_tsx --> admin_inertia_components_StyledButton_tsx_getIconSize
    admin_inertia_components_StyledButton_tsx_getSizeClasses["getSizeClasses"]
    class admin_inertia_components_StyledButton_tsx_getSizeClasses fn;
    admin_inertia_components_StyledButton_tsx --> admin_inertia_components_StyledButton_tsx_getSizeClasses
    admin_inertia_components_StyledButton_tsx_getVariantClasses["getVariantClasses"]
    class admin_inertia_components_StyledButton_tsx_getVariantClasses fn;
    admin_inertia_components_StyledButton_tsx --> admin_inertia_components_StyledButton_tsx_getVariantClasses
    admin_inertia_components_StyledButton_tsx_getLoadingSpinner["getLoadingSpinner"]
    class admin_inertia_components_StyledButton_tsx_getLoadingSpinner fn;
    admin_inertia_components_StyledButton_tsx --> admin_inertia_components_StyledButton_tsx_getLoadingSpinner
    admin_inertia_components_StyledButton_tsx_onClickHandler["onClickHandler"]
    class admin_inertia_components_StyledButton_tsx_onClickHandler fn;
    admin_inertia_components_StyledButton_tsx --> admin_inertia_components_StyledButton_tsx_onClickHandler
    admin_inertia_providers_ModalProvider_tsx["ModalProvider.tsx (tsx)"]
    class admin_inertia_providers_ModalProvider_tsx mod;
    admin_inertia_providers_ModalProvider_tsx_openModal["openModal"]
    class admin_inertia_providers_ModalProvider_tsx_openModal fn;
    admin_inertia_providers_ModalProvider_tsx --> admin_inertia_providers_ModalProvider_tsx_openModal
    admin_inertia_providers_ModalProvider_tsx_closeModal["closeModal"]
    class admin_inertia_providers_ModalProvider_tsx_closeModal fn;
    admin_inertia_providers_ModalProvider_tsx --> admin_inertia_providers_ModalProvider_tsx_closeModal
    admin_inertia_providers_ModalProvider_tsx_closeAllModals["closeAllModals"]
    class admin_inertia_providers_ModalProvider_tsx_closeAllModals fn;
    admin_inertia_providers_ModalProvider_tsx --> admin_inertia_providers_ModalProvider_tsx_closeAllModals
    admin_inertia_providers_ModalProvider_tsx__getCurrentModals["_getCurrentModals"]
    class admin_inertia_providers_ModalProvider_tsx__getCurrentModals fn;
    admin_inertia_providers_ModalProvider_tsx --> admin_inertia_providers_ModalProvider_tsx__getCurrentModals
    admin_config_inertia_ts["inertia.ts (ts)"]
    class admin_config_inertia_ts mod;
    admin_config_inertia_ts_invalidateAssistantNameCache["invalidateAssistantNameCache"]
    class admin_config_inertia_ts_invalidateAssistantNameCache fn;
    admin_config_inertia_ts --> admin_config_inertia_ts_invalidateAssistantNameCache
    admin_config_inertia_ts_value["value"]
    class admin_config_inertia_ts_value fn;
    admin_config_inertia_ts --> admin_config_inertia_ts_value
    admin_inertia_components_DebugInfoModal_tsx["DebugInfoModal.tsx (tsx)"]
    class admin_inertia_components_DebugInfoModal_tsx mod;
    admin_inertia_components_DebugInfoModal_tsx_DebugInfoModal["DebugInfoModal"]
    class admin_inertia_components_DebugInfoModal_tsx_DebugInfoModal fn;
    admin_inertia_components_DebugInfoModal_tsx --> admin_inertia_components_DebugInfoModal_tsx_DebugInfoModal
    admin_inertia_components_DebugInfoModal_tsx_handleCopy["handleCopy"]
    class admin_inertia_components_DebugInfoModal_tsx_handleCopy fn;
    admin_inertia_components_DebugInfoModal_tsx --> admin_inertia_components_DebugInfoModal_tsx_handleCopy
    admin_inertia_hooks_useDownloads_ts["useDownloads.ts (ts)"]
    class admin_inertia_hooks_useDownloads_ts mod;
    admin_inertia_hooks_useDownloads_ts_useDownloads["useDownloads"]
    class admin_inertia_hooks_useDownloads_ts_useDownloads fn;
    admin_inertia_hooks_useDownloads_ts --> admin_inertia_hooks_useDownloads_ts_useDownloads
    admin_inertia_hooks_useDownloads_ts_invalidate["invalidate"]
    class admin_inertia_hooks_useDownloads_ts_invalidate fn;
    admin_inertia_hooks_useDownloads_ts --> admin_inertia_hooks_useDownloads_ts_invalidate
    admin_inertia_hooks_useEmbedJobs_ts["useEmbedJobs.ts (ts)"]
    class admin_inertia_hooks_useEmbedJobs_ts mod;
    admin_inertia_hooks_useEmbedJobs_ts_useEmbedJobs["useEmbedJobs"]
    class admin_inertia_hooks_useEmbedJobs_ts_useEmbedJobs fn;
    admin_inertia_hooks_useEmbedJobs_ts --> admin_inertia_hooks_useEmbedJobs_ts_useEmbedJobs
    admin_inertia_hooks_useEmbedJobs_ts_invalidate["invalidate"]
    class admin_inertia_hooks_useEmbedJobs_ts_invalidate fn;
    admin_inertia_hooks_useEmbedJobs_ts --> admin_inertia_hooks_useEmbedJobs_ts_invalidate
    admin_inertia_providers_ThemeProvider_tsx["ThemeProvider.tsx (tsx)"]
    class admin_inertia_providers_ThemeProvider_tsx mod;
    admin_inertia_providers_ThemeProvider_tsx_ThemeProvider["ThemeProvider"]
    class admin_inertia_providers_ThemeProvider_tsx_ThemeProvider fn;
    admin_inertia_providers_ThemeProvider_tsx --> admin_inertia_providers_ThemeProvider_tsx_ThemeProvider
```

---

## Architecture Reference

### JS (2 files)

#### `ace.js`
**Path:** `admin/ace.js`

*No symbols extracted*

#### `eslint.config.js`
**Path:** `admin/eslint.config.js`

*No symbols extracted*

### SH (11 files)

#### `collect_disk_info.sh`
**Path:** `install/collect_disk_info.sh`

*No symbols extracted*

#### `entrypoint.sh`
**Path:** `install/entrypoint.sh`

*No symbols extracted*

#### `install_nomad.sh`
**Path:** `install/install_nomad.sh`

**Functions:**
- `header` (line 47)
- `header_red` (line 52)
- `check_has_sudo` (line 57)
- `check_is_bash` (line 69)
- `check_is_debian_based` (line 79)
- `check_is_x86_64` (line 89)
- `ensure_dependencies_installed` (line 104)
- `check_is_debug_mode` (line 140)
- `generateRandomPass` (line 149)
- `ensure_docker_installed` (line 159)
- `check_docker_compose` (line 220)
- `setup_nvidia_container_toolkit` (line 230)
- `get_install_confirmation` (line 355)
- `accept_terms` (line 370)
- `create_nomad_directory` (line 391)
- `download_management_compose_file` (line 410)
- `download_helper_scripts` (line 445)
- `start_management_containers` (line 472)
- `get_local_ip` (line 481)
- `verify_gpu_setup` (line 488)
- `success_message` (line 598)

#### `migrate-disk-collector.sh`
**Path:** `install/migrate-disk-collector.sh`

**Functions:**
- `check_is_bash` (line 46)
- `check_has_sudo` (line 55)
- `check_confirmation` (line 65)
- `check_docker_running` (line 81)
- `check_compose_file` (line 93)
- `stop_old_host_process` (line 103) - *Step 1: Stop old host process*
- `backup_compose_file` (line 122) - *Step 2: Backup compose.yml*
- `remove_old_bind_mount` (line 134) - *Step 3: Remove old bind-mount from admin volumes*
- `add_disk_collector_service` (line 153) - *Step 4: Add disk-collector service block*
- `restart_stack` (line 186) - *Step 5 — Pull new image and restart the full stack This will re-create the admin container and drop the old /tmp bind, and also starts the new disk...*
- `verify_disk_collector_running` (line 203) - *Step 6: Verify*

#### `run_updater_fixes.sh`
**Path:** `install/run_updater_fixes.sh`

**Functions:**
- `check_is_bash` (line 55)
- `check_confirmation` (line 64)
- `check_has_sudo` (line 75)
- `check_docker_running` (line 85)
- `check_compose_file` (line 97)
- `check_sidecar_dir` (line 106)
- `backup_compose_file` (line 119)
- `fix_sidecar_volume_mount` (line 130)
- `download_updated_sidecar_files` (line 153)
- `rebuild_sidecar` (line 170)
- `restart_sidecar` (line 179)
- `verify_sidecar_running` (line 197)

#### `collect-disk-info.sh`
**Path:** `install/sidecar-disk-collector/collect-disk-info.sh`

**Functions:**
- `log` (line 9)

#### `update-watcher.sh`
**Path:** `install/sidecar-updater/update-watcher.sh`

**Functions:**
- `log` (line 12)
- `write_status` (line 16)
- `perform_update` (line 31)
- `cleanup` (line 111)

#### `start_nomad.sh`
**Path:** `install/start_nomad.sh`

*No symbols extracted*

#### `stop_nomad.sh`
**Path:** `install/stop_nomad.sh`

*No symbols extracted*

#### `uninstall_nomad.sh`
**Path:** `install/uninstall_nomad.sh`

**Functions:**
- `check_has_sudo` (line 27)
- `check_current_directory` (line 39)
- `ensure_management_compose_file_exists` (line 46)
- `get_uninstall_confirmation` (line 53)
- `ensure_docker_installed` (line 71)
- `check_docker_compose` (line 78)
- `storage_cleanup` (line 88)
- `uninstall_nomad` (line 105)

#### `update_nomad.sh`
**Path:** `install/update_nomad.sh`

**Functions:**
- `check_has_sudo` (line 31)
- `check_is_bash` (line 43)
- `check_is_debian_based` (line 53)
- `get_update_confirmation` (line 63)
- `ensure_docker_installed_and_running` (line 81)
- `check_docker_compose` (line 97)
- `ensure_docker_compose_file_exists` (line 107)
- `force_recreate` (line 114)
- `get_local_ip` (line 128)
- `success_message` (line 136)

### TS (197 files)

#### `adonisrc.ts`
**Path:** `admin/adonisrc.ts`

*No symbols extracted*

#### `benchmark_controller.ts`
**Path:** `admin/app/controllers/benchmark_controller.ts`

**Classes:**
- `BenchmarkController` (line 11)

**Functions:**
- `statusCode` (line 185) - *Pass through the status code from the service if available, otherwise default to 400*

#### `chats_controller.ts`
**Path:** `admin/app/controllers/chats_controller.ts`

**Classes:**
- `ChatsController` (line 11)

#### `collection_updates_controller.ts`
**Path:** `admin/app/controllers/collection_updates_controller.ts`

**Classes:**
- `CollectionUpdatesController` (line 9)

#### `docs_controller.ts`
**Path:** `admin/app/controllers/docs_controller.ts`

**Classes:**
- `DocsController` (line 6)

#### `downloads_controller.ts`
**Path:** `admin/app/controllers/downloads_controller.ts`

**Classes:**
- `DownloadsController` (line 7)

#### `easy_setup_controller.ts`
**Path:** `admin/app/controllers/easy_setup_controller.ts`

**Classes:**
- `EasySetupController` (line 9)

#### `home_controller.ts`
**Path:** `admin/app/controllers/home_controller.ts`

**Classes:**
- `HomeController` (line 6)

#### `maps_controller.ts`
**Path:** `admin/app/controllers/maps_controller.ts`

**Classes:**
- `MapsController` (line 17)

#### `ollama_controller.ts`
**Path:** `admin/app/controllers/ollama_controller.ts`

**Classes:**
- `OllamaController` (line 18)

#### `rag_controller.ts`
**Path:** `admin/app/controllers/rag_controller.ts`

**Classes:**
- `RagController` (line 14)

#### `settings_controller.ts`
**Path:** `admin/app/controllers/settings_controller.ts`

**Classes:**
- `SettingsController` (line 11)

#### `system_controller.ts`
**Path:** `admin/app/controllers/system_controller.ts`

**Classes:**
- `SystemController` (line 12)

#### `zim_controller.ts`
**Path:** `admin/app/controllers/zim_controller.ts`

**Classes:**
- `ZimController` (line 14)

#### `handler.ts`
**Path:** `admin/app/exceptions/handler.ts`

**Classes:**
- `HttpExceptionHandler` (line 5)

#### `internal_server_error_exception.ts`
**Path:** `admin/app/exceptions/internal_server_error_exception.ts`

**Classes:**
- `InternalServerErrorException` (line 3)

#### `check_service_updates_job.ts`
**Path:** `admin/app/jobs/check_service_updates_job.ts`

**Classes:**
- `CheckServiceUpdatesJob` (line 11)

#### `check_update_job.ts`
**Path:** `admin/app/jobs/check_update_job.ts`

**Classes:**
- `CheckUpdateJob` (line 8)

#### `download_model_job.ts`
**Path:** `admin/app/jobs/download_model_job.ts`

**Classes:**
- `DownloadModelJob` (line 11)

#### `embed_file_job.ts`
**Path:** `admin/app/jobs/embed_file_job.ts`

**Classes:**
- `EmbedFileJob` (line 23)

**Functions:**
- `onProgress` (line 116) - *Progress callback. For multi-batch ZIM ingestions, scale the service-reported 0-100% (which is % through the current batch's chunks) into the overa...*
- `articlesDone` (line 119)
- `nextOffset` (line 144)
- `totalChunks` (line 196) - *Final batch or non-batched file - mark as complete*
- `filePath` (line 394)

#### `run_benchmark_job.ts`
**Path:** `admin/app/jobs/run_benchmark_job.ts`

**Classes:**
- `RunBenchmarkJob` (line 8)

#### `run_download_job.ts`
**Path:** `admin/app/jobs/run_download_job.ts`

**Classes:**
- `RunDownloadJob` (line 11)

**Functions:**
- `progressPercent` (line 86)

#### `run_extract_pmtiles_job.ts`
**Path:** `admin/app/jobs/run_extract_pmtiles_job.ts`

**Classes:**
- `RunExtractPmtilesJob` (line 29)

#### `compression_middleware.ts`
**Path:** `admin/app/middleware/compression_middleware.ts`

**Classes:**
- `CompressionMiddleware` (line 22)

#### `container_bindings_middleware.ts`
**Path:** `admin/app/middleware/container_bindings_middleware.ts`

**Classes:**
- `to` (line 9)
- `to` (line 10)
- `ContainerBindingsMiddleware` (line 12) - *The container bindings middleware binds classes to their request specific value using the container resolver.  - We bind "HttpContext" class to the...*

#### `force_json_response_middleware.ts`
**Path:** `admin/app/middleware/force_json_response_middleware.ts`

**Classes:**
- `ForceJsonResponseMiddleware` (line 9) - *Updating the "Accept" header to always accept "application/json" response from the server. This will force the internals of the framework like vali...*

#### `maps_static_middleware.ts`
**Path:** `admin/app/middleware/maps_static_middleware.ts`

**Classes:**
- `MapsStaticMiddleware` (line 10) - *See #providers/map_static_provider.ts for explanation of why this middleware exists.*

#### `benchmark_result.ts`
**Path:** `admin/app/models/benchmark_result.ts`

**Classes:**
- `BenchmarkResult` (line 5)

#### `benchmark_setting.ts`
**Path:** `admin/app/models/benchmark_setting.ts`

**Classes:**
- `BenchmarkSetting` (line 5)

#### `chat_message.ts`
**Path:** `admin/app/models/chat_message.ts`

**Classes:**
- `ChatMessage` (line 6)

#### `chat_session.ts`
**Path:** `admin/app/models/chat_session.ts`

**Classes:**
- `ChatSession` (line 6)

#### `collection_manifest.ts`
**Path:** `admin/app/models/collection_manifest.ts`

**Classes:**
- `CollectionManifest` (line 5)

#### `custom_library_source.ts`
**Path:** `admin/app/models/custom_library_source.ts`

**Classes:**
- `CustomLibrarySource` (line 4)

#### `installed_resource.ts`
**Path:** `admin/app/models/installed_resource.ts`

**Classes:**
- `InstalledResource` (line 4)

#### `kb_ingest_state.ts`
**Path:** `admin/app/models/kb_ingest_state.ts`

**Classes:**
- `KbIngestState` (line 15) - *Tracks the per-file decision and outcome of AI knowledge-base ingestion.  The row exists for any embeddable file the scanner has seen and is indepe...*

#### `kb_ratio_registry.ts`
**Path:** `admin/app/models/kb_ratio_registry.ts`

**Classes:**
- `KbRatioRegistry` (line 21) - *Self-calibrating registry of `{filename-prefix → chunks_per_mb}` ratios used for disk-footprint and time-to-embed estimates surfaced in the KB pane...*

#### `kv_store.ts`
**Path:** `admin/app/models/kv_store.ts`

**Classes:**
- `KVStore` (line 10) - *Generic key-value store model for storing various settings that don't necessitate their own dedicated models.*

#### `map_marker.ts`
**Path:** `admin/app/models/map_marker.ts`

**Classes:**
- `MapMarker` (line 4)

#### `service.ts`
**Path:** `admin/app/models/service.ts`

**Classes:**
- `Service` (line 5)

#### `wikipedia_selection.ts`
**Path:** `admin/app/models/wikipedia_selection.ts`

**Classes:**
- `WikipediaSelection` (line 4)

#### `benchmark_service.ts`
**Path:** `admin/app/services/benchmark_service.ts`

**Classes:**
- `BenchmarkService` (line 67)

**Functions:**
- `totalTime` (line 504)

#### `chat_service.ts`
**Path:** `admin/app/services/chat_service.ts`

**Classes:**
- `ChatService` (line 11)

#### `collection_manifest_service.ts`
**Path:** `admin/app/services/collection_manifest_service.ts`

**Classes:**
- `CollectionManifestService` (line 39)

#### `collection_update_service.ts`
**Path:** `admin/app/services/collection_update_service.ts`

**Classes:**
- `CollectionUpdateService` (line 20)

#### `container_registry_service.ts`
**Path:** `admin/app/services/container_registry_service.ts`

**Classes:**
- `ContainerRegistryService` (line 28)

**Functions:**
- `data` (line 104)
- `data` (line 137)
- `manifest` (line 177)
- `manifest` (line 236)
- `childManifest` (line 256)
- `config` (line 278)

#### `countries_service.ts`
**Path:** `admin/app/services/countries_service.ts`

**Classes:**
- `CountriesService` (line 74)

**Functions:**
- `typeRank` (line 215)
- `resolveIso2` (line 225)
- `bufferGeometry` (line 242)
- `bufferPolygonRings` (line 258)
- `bufferRing` (line 262)
- `signedArea` (line 290)
- `resolveIso3` (line 298)
- `codes` (line 144)
- `n1x` (line 278)
- `n1y` (line 279)
- `n2x` (line 280)
- `n2y` (line 281)

#### `docker_service.ts`
**Path:** `admin/app/services/docker_service.ts`

**Classes:**
- `DockerService` (line 19)

**Functions:**
- `used` (line 548)
- `is` (line 826)
- `marker` (line 934)
- `gfx` (line 1043)

#### `docs_service.ts`
**Path:** `admin/app/services/docs_service.ts`

**Classes:**
- `DocsService` (line 8)

#### `download_service.ts`
**Path:** `admin/app/services/download_service.ts`

**Classes:**
- `DownloadService` (line 18)

#### `kiwix_library_service.ts`
**Path:** `admin/app/services/kiwix_library_service.ts`

**Classes:**
- `KiwixLibraryService` (line 31)

**Functions:**
- `getMeta` (line 65)

#### `map_service.ts`
**Path:** `admin/app/services/map_service.ts`

**Classes:**
- `MapService` (line 73)

**Functions:**
- `getHost` (line 839)
- `specifiedHostOrDefault` (line 851)
- `findExactGroupMatch` (line 877)
- `files` (line 84)
- `regions` (line 326)
- `unit` (line 768)

#### `ollama_service.ts`
**Path:** `admin/app/services/ollama_service.ts`

**Classes:**
- `OllamaService` (line 51)

**Functions:**
- `partialTagSuffix` (line 370) - *Returns how many trailing chars of `text` could be the start of `tag`*
- `customUrl` (line 64) - *Check KVStore for a custom base URL (remote Ollama, LM Studio, llama.cpp, etc.)*
- `onAbort` (line 187) - *If the abort fires after headers are received but mid-stream, axios's signal handling destroys the stream which surfaces as an 'error' event — wire...*
- `stream` (line 367)
- `parsePulls` (line 860)
- `parseSize` (line 879)

#### `queue_service.ts`
**Path:** `admin/app/services/queue_service.ts`

**Classes:**
- `QueueService` (line 9) - *Process-wide singleton. Each `Queue` opens two ioredis connections (one for commands, one blocking). Instantiating a fresh QueueService per dispatc...*

#### `rag_service.ts`
**Path:** `admin/app/services/rag_service.ts`

**Classes:**
- `RagService` (line 41)
- `if` (line 208)

**Functions:**
- `progress` (line 373)

#### `system_service.ts`
**Path:** `admin/app/services/system_service.ts`

**Classes:**
- `SystemService` (line 26)

**Functions:**
- `buf` (line 131)
- `actualImage` (line 251)
- `isDiscreteGpuVendor` (line 440)
- `isBogusDgpuVram` (line 442)
- `hasLspciBogusDgpuVram` (line 452) - *Clear the bogus value up front. If a probe replaces the entry below we get the real VRAM; if no probe succeeds (Ollama not installed, passthrough_f...*
- `earlyAccess` (line 630)

#### `system_update_service.ts`
**Path:** `admin/app/services/system_update_service.ts`

**Classes:**
- `SystemUpdateService` (line 14)

#### `zim_extraction_service.ts`
**Path:** `admin/app/services/zim_extraction_service.ts`

**Classes:**
- `ZIMExtractionService` (line 10)

#### `zim_service.ts`
**Path:** `admin/app/services/zim_service.ts`

**Classes:**
- `ZimService` (line 39)

#### `downloads.ts`
**Path:** `admin/app/utils/downloads.ts`

**Functions:**
- `doResumableDownload` (line 18) - *Perform a resumable download with progress tracking @param param0 - Download parameters. Leave allowedMimeTypes empty to skip mime type checking. O...*
- `doResumableDownloadWithRetry` (line 226)
- `delay` (line 284)
- `fetchStream` (line 96)
- `clearStallTimer` (line 128)
- `resetStallTimer` (line 135)
- `cleanup` (line 171)

#### `fs.ts`
**Path:** `admin/app/utils/fs.ts`

**Functions:**
- `listDirectoryContents` (line 10)
- `listDirectoryContentsRecursive` (line 31)
- `ensureDirectoryExists` (line 50)
- `getFile` (line 60)
- `getFile` (line 61)
- `getFile` (line 65)
- `getFile` (line 66)
- `getFileStatsIfExists` (line 85)
- `isValidZimFile` (line 108) - *Validates that a file has the ZIM magic number (0x44D495A). Must be called before passing a file to @openzim/libzim Archive, because a corrupted ZI...*
- `deleteFileIfExists` (line 124)
- `getAllFilesystems` (line 134)
- `traverse` (line 141)
- `matchesDevice` (line 160)
- `determineFileType` (line 177)
- `sanitizeFilename` (line 199) - *Sanitize a filename by removing potentially dangerous characters. @param filename The original filename @returns The sanitized filename*

#### `kb_ingest_decision.ts`
**Path:** `admin/app/utils/kb_ingest_decision.ts`

**Functions:**
- `decideScanAction` (line 44) - *Decide what scanAndSyncStorage should do for a single embeddable file.  Replaces the earlier `!sourcesInQdrant.has(filePath)` binary check, which c...*

#### `kb_job_health.ts`
**Path:** `admin/app/utils/kb_job_health.ts`

**Functions:**
- `computeJobHealth` (line 32)

#### `kb_ratio_lookup.ts`
**Path:** `admin/app/utils/kb_ratio_lookup.ts`

**Functions:**
- `estimateBatch` (line 38) - *Aggregate an embedding-disk-cost estimate across a batch of files (curated tier add, multi-upload, sync preview, etc). `hasUnknown` is true when at...*
- `findChunksPerMb` (line 70) - *Pick the chunks_per_mb estimate for a filename by longest-prefix match.  Patterns are filename prefixes (`devdocs_`, `wikipedia_en_simple_`, ...). ...*
- `estimateChunkCount` (line 88) - *Estimate the number of embedding chunks a ZIM-style file will produce given its size on disk in bytes. Returns `null` when the registry has nothing...*

#### `kb_warning_decision.ts`
**Path:** `admin/app/utils/kb_warning_decision.ts`

**Functions:**
- `decideWarnings` (line 41)

#### `misc.ts`
**Path:** `admin/app/utils/misc.ts`

**Functions:**
- `formatSpeed` (line 1)
- `toTitleCase` (line 7)
- `parseBoolean` (line 15)

#### `version.ts`
**Path:** `admin/app/utils/version.ts`

**Functions:**
- `isNewerVersion` (line 7) - *Compare two semantic version strings to determine if the first is newer than the second. @param version1 - The version to check (e.g., "1.25.0") @p...*
- `parseMajorVersion` (line 45) - *Parse the major version number from a tag string. Strips the 'v' prefix if present. @param tag - Version tag (e.g., "v3.8.1", "10.19.4") @returns T...*
- `normalize` (line 8)

#### `zim_filename.ts`
**Path:** `admin/app/utils/zim_filename.ts`

**Functions:**
- `zimFilenameStem` (line 7) - *Strip the trailing `_YYYY-MM(-DD).zim` date suffix from a Kiwix-style ZIM filename so different release dates of the same variant share a stem (e.g...*
- `findReplacedWikipediaFiles` (line 17) - *Of the existing files, return only those that are prior-version replacements of `currentFilename` — same Wikipedia variant stem, different release....*

#### `benchmark.ts`
**Path:** `admin/app/validators/benchmark.ts`

*No symbols extracted*

#### `chat.ts`
**Path:** `admin/app/validators/chat.ts`

*No symbols extracted*

#### `common.ts`
**Path:** `admin/app/validators/common.ts`

**Functions:**
- `assertNotPrivateUrl` (line 15) - *Checks whether a URL points to a loopback or link-local address. Used to prevent SSRF — the server should not fetch from localhost or link-local/me...*
- `assertNotCloudMetadataUrl` (line 61)

#### `curated_collections.ts`
**Path:** `admin/app/validators/curated_collections.ts`

*No symbols extracted*

#### `download.ts`
**Path:** `admin/app/validators/download.ts`

*No symbols extracted*

#### `ollama.ts`
**Path:** `admin/app/validators/ollama.ts`

*No symbols extracted*

#### `rag.ts`
**Path:** `admin/app/validators/rag.ts`

*No symbols extracted*

#### `settings.ts`
**Path:** `admin/app/validators/settings.ts`

*No symbols extracted*

#### `system.ts`
**Path:** `admin/app/validators/system.ts`

*No symbols extracted*

#### `zim.ts`
**Path:** `admin/app/validators/zim.ts`

*No symbols extracted*

#### `results.ts`
**Path:** `admin/commands/benchmark/results.ts`

**Classes:**
- `BenchmarkResults` (line 4)

#### `run.ts`
**Path:** `admin/commands/benchmark/run.ts`

**Classes:**
- `BenchmarkRun` (line 4)

#### `submit.ts`
**Path:** `admin/commands/benchmark/submit.ts`

**Classes:**
- `BenchmarkSubmit` (line 4)

#### `work.ts`
**Path:** `admin/commands/queue/work.ts`

**Classes:**
- `QueueWork` (line 13)

#### `app.ts`
**Path:** `admin/config/app.ts`

*No symbols extracted*

#### `bodyparser.ts`
**Path:** `admin/config/bodyparser.ts`

*No symbols extracted*

#### `cors.ts`
**Path:** `admin/config/cors.ts`

*No symbols extracted*

#### `database.ts`
**Path:** `admin/config/database.ts`

*No symbols extracted*

#### `hash.ts`
**Path:** `admin/config/hash.ts`

*No symbols extracted*

#### `inertia.ts`
**Path:** `admin/config/inertia.ts`

**Functions:**
- `invalidateAssistantNameCache` (line 8)
- `value` (line 30)

#### `logger.ts`
**Path:** `admin/config/logger.ts`

*No symbols extracted*

#### `queue.ts`
**Path:** `admin/config/queue.ts`

*No symbols extracted*

#### `session.ts`
**Path:** `admin/config/session.ts`

*No symbols extracted*

#### `shield.ts`
**Path:** `admin/config/shield.ts`

*No symbols extracted*

#### `static.ts`
**Path:** `admin/config/static.ts`

*No symbols extracted*

#### `transmit.ts`
**Path:** `admin/config/transmit.ts`

*No symbols extracted*

#### `vite.ts`
**Path:** `admin/config/vite.ts`

*No symbols extracted*

#### `broadcast.ts`
**Path:** `admin/constants/broadcast.ts`

*No symbols extracted*

#### `kiwix.ts`
**Path:** `admin/constants/kiwix.ts`

*No symbols extracted*

#### `kv_store.ts`
**Path:** `admin/constants/kv_store.ts`

*No symbols extracted*

#### `map_regions.ts`
**Path:** `admin/constants/map_regions.ts`

**Functions:**
- `buildPmtilesExtractArgs` (line 24)

#### `misc.ts`
**Path:** `admin/constants/misc.ts`

*No symbols extracted*

#### `ollama.ts`
**Path:** `admin/constants/ollama.ts`

*No symbols extracted*

#### `service_names.ts`
**Path:** `admin/constants/service_names.ts`

*No symbols extracted*

#### `zim_extraction.ts`
**Path:** `admin/constants/zim_extraction.ts`

*No symbols extracted*

#### `1751086751801_create_services_table.ts`
**Path:** `admin/database/migrations/1751086751801_create_services_table.ts`

**Classes:**
- `extends` (line 3)

#### `1763499145832_update_services_table.ts`
**Path:** `admin/database/migrations/1763499145832_update_services_table.ts`

**Classes:**
- `extends` (line 3)

#### `1764912210741_create_curated_collections_table.ts`
**Path:** `admin/database/migrations/1764912210741_create_curated_collections_table.ts`

**Classes:**
- `extends` (line 3)

#### `1764912270123_create_curated_collection_resources_table.ts`
**Path:** `admin/database/migrations/1764912270123_create_curated_collection_resources_table.ts`

**Classes:**
- `extends` (line 3)

#### `1768170944482_update_services_add_installation_statuses_table.ts`
**Path:** `admin/database/migrations/1768170944482_update_services_add_installation_statuses_table.ts`

**Classes:**
- `extends` (line 3)

#### `1768453747522_update_services_add_icon.ts`
**Path:** `admin/database/migrations/1768453747522_update_services_add_icon.ts`

**Classes:**
- `extends` (line 3)

#### `1769097600001_create_benchmark_results_table.ts`
**Path:** `admin/database/migrations/1769097600001_create_benchmark_results_table.ts`

**Classes:**
- `extends` (line 3)

#### `1769097600002_create_benchmark_settings_table.ts`
**Path:** `admin/database/migrations/1769097600002_create_benchmark_settings_table.ts`

**Classes:**
- `extends` (line 3)

#### `1769300000001_add_powered_by_and_display_order_to_services.ts`
**Path:** `admin/database/migrations/1769300000001_add_powered_by_and_display_order_to_services.ts`

**Classes:**
- `extends` (line 3)

#### `1769300000002_update_services_friendly_names.ts`
**Path:** `admin/database/migrations/1769300000002_update_services_friendly_names.ts`

**Classes:**
- `extends` (line 3)

#### `1769324448000_add_builder_tag_to_benchmark_results.ts`
**Path:** `admin/database/migrations/1769324448000_add_builder_tag_to_benchmark_results.ts`

**Classes:**
- `extends` (line 3)

#### `1769400000001_create_installed_tiers_table.ts`
**Path:** `admin/database/migrations/1769400000001_create_installed_tiers_table.ts`

**Classes:**
- `extends` (line 3)

#### `1769400000002_create_kv_store_table.ts`
**Path:** `admin/database/migrations/1769400000002_create_kv_store_table.ts`

**Classes:**
- `extends` (line 3)

#### `1769500000001_create_wikipedia_selection_table.ts`
**Path:** `admin/database/migrations/1769500000001_create_wikipedia_selection_table.ts`

**Classes:**
- `extends` (line 3)

#### `1769646771604_create_create_chat_sessions_table.ts`
**Path:** `admin/database/migrations/1769646771604_create_create_chat_sessions_table.ts`

**Classes:**
- `extends` (line 3)

#### `1769646798266_create_create_chat_messages_table.ts`
**Path:** `admin/database/migrations/1769646798266_create_create_chat_messages_table.ts`

**Classes:**
- `extends` (line 3)

#### `1769700000001_create_zim_file_metadata_table.ts`
**Path:** `admin/database/migrations/1769700000001_create_zim_file_metadata_table.ts`

**Classes:**
- `extends` (line 3)

#### `1770269324176_add_unique_constraint_to_curated_collection_resources_table.ts`
**Path:** `admin/database/migrations/1770269324176_add_unique_constraint_to_curated_collection_resources_table.ts`

**Classes:**
- `extends` (line 3)

#### `1770273423670_drop_installed_tiers_table.ts`
**Path:** `admin/database/migrations/1770273423670_drop_installed_tiers_table.ts`

**Classes:**
- `extends` (line 3)

#### `1770849108030_create_create_collection_manifests_table.ts`
**Path:** `admin/database/migrations/1770849108030_create_create_collection_manifests_table.ts`

**Classes:**
- `extends` (line 3)

#### `1770849119787_create_create_installed_resources_table.ts`
**Path:** `admin/database/migrations/1770849119787_create_create_installed_resources_table.ts`

**Classes:**
- `extends` (line 3)

#### `1770850092871_create_drop_legacy_curated_tables_table.ts`
**Path:** `admin/database/migrations/1770850092871_create_drop_legacy_curated_tables_table.ts`

**Classes:**
- `extends` (line 3)

#### `1771000000001_add_update_fields_to_services.ts`
**Path:** `admin/database/migrations/1771000000001_add_update_fields_to_services.ts`

**Classes:**
- `extends` (line 3)

#### `1771000000002_pin_latest_service_images.ts`
**Path:** `admin/database/migrations/1771000000002_pin_latest_service_images.ts`

**Classes:**
- `extends` (line 3)

#### `1771100000001_migrate_kiwix_to_library_mode.ts`
**Path:** `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`

**Classes:**
- `extends` (line 3)

#### `1771200000001_create_map_markers_table.ts`
**Path:** `admin/database/migrations/1771200000001_create_map_markers_table.ts`

**Classes:**
- `extends` (line 3)

#### `1775100000001_create_custom_library_sources_table.ts`
**Path:** `admin/database/migrations/1775100000001_create_custom_library_sources_table.ts`

**Classes:**
- `extends` (line 3)

#### `1776000000001_create_kb_ingest_state_table.ts`
**Path:** `admin/database/migrations/1776000000001_create_kb_ingest_state_table.ts`

**Classes:**
- `extends` (line 3)

#### `1776100000001_create_kb_ratio_registry_table.ts`
**Path:** `admin/database/migrations/1776100000001_create_kb_ratio_registry_table.ts`

**Classes:**
- `extends` (line 38)

#### `service_seeder.ts`
**Path:** `admin/database/seeders/service_seeder.ts`

**Classes:**
- `ServiceSeeder` (line 8)

#### `ModalContext.ts`
**Path:** `admin/inertia/context/ModalContext.ts`

**Functions:**
- `useModals` (line 13)

#### `NotificationContext.ts`
**Path:** `admin/inertia/context/NotificationContext.ts`

**Functions:**
- `useNotifications` (line 20)

#### `useDebounce.ts`
**Path:** `admin/inertia/hooks/useDebounce.ts`

**Functions:**
- `useDebounce` (line 3)
- `debounce` (line 6)

#### `useDiskDisplayData.ts`
**Path:** `admin/inertia/hooks/useDiskDisplayData.ts`

**Functions:**
- `getAllDiskDisplayItems` (line 16) - *import { Systeminformation } from 'systeminformation' import { formatBytes } from '~/lib/util' type DiskDisplayItem = { label: string value: number...*
- `getPrimaryDiskInfo` (line 88) - *value: fs.use || 0, total: formatBytes(fs.size), used: formatBytes(fs.used), subtext: `${formatBytes(fs.used)} / ${formatBytes(fs.size)}`, totalByt...*

#### `useDownloads.ts`
**Path:** `admin/inertia/hooks/useDownloads.ts`

**Functions:**
- `useDownloads` (line 10)
- `invalidate` (line 29)

#### `useEmbedJobs.ts`
**Path:** `admin/inertia/hooks/useEmbedJobs.ts`

**Functions:**
- `useEmbedJobs` (line 5)
- `invalidate` (line 29)

#### `useErrorNotification.ts`
**Path:** `admin/inertia/hooks/useErrorNotification.ts`

**Functions:**
- `useErrorNotification` (line 4)
- `showError` (line 7)

#### `useInternetStatus.ts`
**Path:** `admin/inertia/hooks/useInternetStatus.ts`

**Functions:**
- `useInternetStatus` (line 6)

#### `useMapMarkers.ts`
**Path:** `admin/inertia/hooks/useMapMarkers.ts`

**Functions:**
- `useMapMarkers` (line 25)

#### `useMapRegionFiles.ts`
**Path:** `admin/inertia/hooks/useMapRegionFiles.ts`

**Functions:**
- `useMapRegionFiles` (line 5)

#### `useOllamaModelDownloads.ts`
**Path:** `admin/inertia/hooks/useOllamaModelDownloads.ts`

**Functions:**
- `useOllamaModelDownloads` (line 25)

#### `useServiceInstallationActivity.ts`
**Path:** `admin/inertia/hooks/useServiceInstallationActivity.ts`

**Functions:**
- `useServiceInstallationActivity` (line 6)

#### `useSystemInfo.ts`
**Path:** `admin/inertia/hooks/useSystemInfo.ts`

**Functions:**
- `useSystemInfo` (line 10)

#### `useSystemSetting.ts`
**Path:** `admin/inertia/hooks/useSystemSetting.ts`

**Functions:**
- `useSystemSetting` (line 12)

#### `useTheme.ts`
**Path:** `admin/inertia/hooks/useTheme.ts`

**Functions:**
- `getInitialTheme` (line 7)
- `useTheme` (line 16)

#### `useUpdateAvailable.ts`
**Path:** `admin/inertia/hooks/useUpdateAvailable.ts`

**Functions:**
- `useUpdateAvailable` (line 6)

#### `api.ts`
**Path:** `admin/inertia/lib/api.ts`

**Classes:**
- `API` (line 15)

#### `builderTagWords.ts`
**Path:** `admin/inertia/lib/builderTagWords.ts`

**Functions:**
- `generateRandomNumber` (line 113)
- `generateRandomBuilderTag` (line 117)
- `parseBuilderTag` (line 124)
- `buildBuilderTag` (line 143)

#### `classNames.ts`
**Path:** `admin/inertia/lib/classNames.ts`

**Functions:**
- `classNames` (line 2)

#### `collections.ts`
**Path:** `admin/inertia/lib/collections.ts`

**Functions:**
- `resolveTierResources` (line 7) - *Resolve all resources for a tier, including inherited resources from includesTier chain. Shared between frontend components (TierSelectionModal, Ca...*
- `resolveTierResourcesInner` (line 11)

#### `global_map_banner.ts`
**Path:** `admin/inertia/lib/global_map_banner.ts`

**Functions:**
- `hasDownloadedGlobalMap` (line 1)

#### `icons.ts`
**Path:** `admin/inertia/lib/icons.ts`

*No symbols extracted*

#### `kb_file_grouping.ts`
**Path:** `admin/inertia/lib/kb_file_grouping.ts`

**Functions:**
- `classifyKbFile` (line 21)
- `sourceToDisplayName` (line 34)
- `groupAndSortKbFiles` (line 67) - *Group stored-file rows into table rows for the Stored Files panel.  - Admin docs (`/app/docs/*`, README) collapse into a single "Project NOMAD docu...*

#### `kb_guardrail.ts`
**Path:** `admin/inertia/lib/kb_guardrail.ts`

**Functions:**
- `evaluateGuardrail` (line 47) - *Decide whether a bulk indexing action should be gated behind the guardrail modal. Caller passes the precomputed embedding-storage estimate (from `K...*

#### `kb_job_health_display.ts`
**Path:** `admin/inertia/lib/kb_job_health_display.ts`

**Functions:**
- `formatTimeAgo` (line 45) - *Format a relative timestamp as "Xs ago", "Xm ago", "Xh ago" with sensible thresholds for the KB Processing Queue's "Last activity" line.*
- `computeJobHealthNow` (line 59) - *Convenience wrapper that resolves a job's health status without the caller having to remember to pass `now`. Mostly for ergonomic frontend use.*

#### `navigation.ts`
**Path:** `admin/inertia/lib/navigation.ts`

**Functions:**
- `getServiceLink` (line 3)

#### `util.ts`
**Path:** `admin/inertia/lib/util.ts`

**Functions:**
- `setGlobalNotificationCallback` (line 6)
- `capitalizeFirstLetter` (line 10)
- `formatBytes` (line 15)
- `generateRandomString` (line 24)
- `generateUUID` (line 33)
- `that` (line 69)
- `to` (line 69)
- `to` (line 70)
- `that` (line 71)
- `and` (line 71)
- `catchInternal` (line 73) - *A higher-order function that wraps an asynchronous function to catch and log internal errors. @param fn The asynchronous function to be wrapped. @r...*
- `extractFileName` (line 57) - *Extracts the file name from a given path while handling both forward and backward slashes. @param path The full file path. @returns The extracted f...*

#### `gpu_passthrough_remediation_provider.ts`
**Path:** `admin/providers/gpu_passthrough_remediation_provider.ts`

**Classes:**
- `GpuPassthroughRemediationProvider` (line 23) - *the container is torn. `nvidia-smi` inside the container returns "Failed to initialize NVML: Unknown Error" and Ollama silently falls back to CPU i...*

**Functions:**
- `KVStore` (line 31)
- `Docker` (line 34)

#### `kiwix_migration_provider.ts`
**Path:** `admin/providers/kiwix_migration_provider.ts`

**Classes:**
- `KiwixMigrationProvider` (line 12) - *Checks whether the installed kiwix container is still using the legacy glob-pattern command (`*.zim --address=all`) and, if so, migrates it to libr...*

**Functions:**
- `Service` (line 22)

#### `map_static_provider.ts`
**Path:** `admin/providers/map_static_provider.ts`

**Classes:**
- `MapStaticProvider` (line 16) - *This is a bit of a hack to serve static files from the /storage/maps directory using AdonisJS static middleware because the middleware does not all...*

#### `qdrant_restart_policy_provider.ts`
**Path:** `admin/providers/qdrant_restart_policy_provider.ts`

**Classes:**
- `QdrantRestartPolicyProvider` (line 14) - *Ensures the nomad_qdrant container has the `unless-stopped` restart policy.  Existing installations may have been created before this policy was en...*

**Functions:**
- `Service` (line 22)
- `Docker` (line 24)

#### `version_check_provider.ts`
**Path:** `admin/providers/version_check_provider.ts`

**Classes:**
- `VersionCheckProvider` (line 22) - *carries pre-update values for `system.updateAvailable` and `system.latestVersion`. Without intervention the UI keeps showing the "update available"...*

**Functions:**
- `KVStore` (line 30)
- `cachedLatest` (line 42)
- `earlyAccess` (line 43)

#### `env.ts`
**Path:** `admin/start/env.ts`

*No symbols extracted*

#### `kernel.ts`
**Path:** `admin/start/kernel.ts`

*No symbols extracted*

#### `routes.ts`
**Path:** `admin/start/routes.ts`

*No symbols extracted*

#### `tailwind.config.ts`
**Path:** `admin/tailwind.config.ts`

*No symbols extracted*

#### `bootstrap.ts`
**Path:** `admin/tests/bootstrap.ts`

**Functions:**
- `to` (line 18)

#### `cloud_metadata_url.spec.ts`
**Path:** `admin/tests/unit/cloud_metadata_url.spec.ts`

**Functions:**
- `expectBlocked` (line 6)
- `expectAllowed` (line 10)

#### `global_map_banner.spec.ts`
**Path:** `admin/tests/unit/global_map_banner.spec.ts`

*No symbols extracted*

#### `kb_file_grouping.spec.ts`
**Path:** `admin/tests/unit/kb_file_grouping.spec.ts`

**Functions:**
- `asInfos` (line 15) - *Wrap source paths into the minimal StoredFileInfo shape that `groupAndSortKbFiles` now expects. State + chunk count are irrelevant to grouping/sort...*

#### `kb_guardrail.spec.ts`
**Path:** `admin/tests/unit/kb_guardrail.spec.ts`

*No symbols extracted*

#### `kb_ingest_decision.spec.ts`
**Path:** `admin/tests/unit/kb_ingest_decision.spec.ts`

*No symbols extracted*

#### `kb_job_health.spec.ts`
**Path:** `admin/tests/unit/kb_job_health.spec.ts`

*No symbols extracted*

#### `kb_ratio_lookup.spec.ts`
**Path:** `admin/tests/unit/kb_ratio_lookup.spec.ts`

*No symbols extracted*

#### `kb_warning_decision.spec.ts`
**Path:** `admin/tests/unit/kb_warning_decision.spec.ts`

*No symbols extracted*

#### `zim_filename.spec.ts`
**Path:** `admin/tests/unit/zim_filename.spec.ts`

*No symbols extracted*

#### `benchmark.ts`
**Path:** `admin/types/benchmark.ts`

*No symbols extracted*

#### `chat.ts`
**Path:** `admin/types/chat.ts`

*No symbols extracted*

#### `collections.ts`
**Path:** `admin/types/collections.ts`

*No symbols extracted*

#### `docker.ts`
**Path:** `admin/types/docker.ts`

*No symbols extracted*

#### `downloads.ts`
**Path:** `admin/types/downloads.ts`

*No symbols extracted*

#### `files.ts`
**Path:** `admin/types/files.ts`

*No symbols extracted*

#### `kb_ingest_state.ts`
**Path:** `admin/types/kb_ingest_state.ts`

*No symbols extracted*

#### `kv_store.ts`
**Path:** `admin/types/kv_store.ts`

*No symbols extracted*

#### `maps.ts`
**Path:** `admin/types/maps.ts`

*No symbols extracted*

#### `ollama.ts`
**Path:** `admin/types/ollama.ts`

*No symbols extracted*

#### `rag.ts`
**Path:** `admin/types/rag.ts`

*No symbols extracted*

#### `services.ts`
**Path:** `admin/types/services.ts`

*No symbols extracted*

#### `system.ts`
**Path:** `admin/types/system.ts`

*No symbols extracted*

#### `util.ts`
**Path:** `admin/types/util.ts`

*No symbols extracted*

#### `zim.ts`
**Path:** `admin/types/zim.ts`

*No symbols extracted*

#### `docs.ts`
**Path:** `admin/util/docs.ts`

**Functions:**
- `streamToString` (line 2)

#### `files.ts`
**Path:** `admin/util/files.ts`

**Functions:**
- `chmodRecursive` (line 4)
- `chownRecursive` (line 30)

#### `zim.ts`
**Path:** `admin/util/zim.ts`

**Functions:**
- `isRawListRemoteZimFilesResponse` (line 3)
- `isRawRemoteZimFileEntry` (line 21)

#### `vite.config.ts`
**Path:** `admin/vite.config.ts`

*No symbols extracted*

### TSX (85 files)

#### `app.tsx`
**Path:** `admin/inertia/app/app.tsx`

**Functions:**
- `environment` (line 38)

#### `ActiveDownloads.tsx`
**Path:** `admin/inertia/components/ActiveDownloads.tsx`

**Functions:**
- `formatSpeed` (line 12)
- `getDownloadStatus` (line 21)
- `ActiveDownloads` (line 38)
- `deltaSec` (line 56)
- `handleDismiss` (line 81)
- `handleCancel` (line 86)

#### `ActiveEmbedJobs.tsx`
**Path:** `admin/inertia/components/ActiveEmbedJobs.tsx`

**Functions:**
- `ActiveEmbedJobs` (line 15)

#### `ActiveModelDownloads.tsx`
**Path:** `admin/inertia/components/ActiveModelDownloads.tsx`

**Functions:**
- `formatSpeed` (line 13)
- `ActiveModelDownloads` (line 21)
- `deltaSec` (line 39)
- `runCancel` (line 62)
- `confirmCancel` (line 85)

#### `Alert.tsx`
**Path:** `admin/inertia/components/Alert.tsx`

**Functions:**
- `Alert` (line 17)
- `getDefaultIcon` (line 29)
- `getIconColor` (line 44)
- `getVariantStyles` (line 60)
- `getTitleColor` (line 113)
- `getMessageColor` (line 132)
- `getCloseButtonStyles` (line 149)

#### `BouncingDots.tsx`
**Path:** `admin/inertia/components/BouncingDots.tsx`

**Functions:**
- `BouncingDots` (line 9)

#### `BouncingLogo.tsx`
**Path:** `admin/inertia/components/BouncingLogo.tsx`

**Functions:**
- `FadingImage` (line 4) - *Fading Image Component*

#### `BuilderTagSelector.tsx`
**Path:** `admin/inertia/components/BuilderTagSelector.tsx`

**Functions:**
- `BuilderTagSelector` (line 18)
- `updateTag` (line 50) - *Update parent when selections change*
- `handleAdjectiveChange` (line 55)
- `handleNounChange` (line 60)
- `handleRandomize` (line 65)

#### `CategoryCard.tsx`
**Path:** `admin/inertia/components/CategoryCard.tsx`

**Functions:**
- `getTierTotalSize` (line 15) - *Calculate total size range across all tiers*

#### `CountryPickerModal.tsx`
**Path:** `admin/inertia/components/CountryPickerModal.tsx`

**Functions:**
- `toggleCountry` (line 100)
- `toggleGroup` (line 109)
- `clearAll` (line 122)
- `startDownload` (line 164)
- `PreflightStatus` (line 392)

#### `CuratedCollectionCard.tsx`
**Path:** `admin/inertia/components/CuratedCollectionCard.tsx`

*No symbols extracted*

#### `DebugInfoModal.tsx`
**Path:** `admin/inertia/components/DebugInfoModal.tsx`

**Functions:**
- `DebugInfoModal` (line 11)
- `handleCopy` (line 36)

#### `DownloadURLModal.tsx`
**Path:** `admin/inertia/components/DownloadURLModal.tsx`

**Functions:**
- `runPreflightCheck` (line 23)

#### `DynamicIcon.tsx`
**Path:** `admin/inertia/components/DynamicIcon.tsx`

*No symbols extracted*

#### `Footer.tsx`
**Path:** `admin/inertia/components/Footer.tsx`

**Functions:**
- `Footer` (line 8)

#### `HorizontalBarChart.tsx`
**Path:** `admin/inertia/components/HorizontalBarChart.tsx`

**Functions:**
- `HorizontalBarChart` (line 19)
- `getBarColor` (line 26)
- `getGlowColor` (line 34)
- `getStatusLabel` (line 41)
- `getStatusColor` (line 51)

#### `InfoTooltip.tsx`
**Path:** `admin/inertia/components/InfoTooltip.tsx`

**Functions:**
- `InfoTooltip` (line 9)

#### `InstallActivityFeed.tsx`
**Path:** `admin/inertia/components/InstallActivityFeed.tsx`

*No symbols extracted*

#### `KbGuardrailModal.tsx`
**Path:** `admin/inertia/components/KbGuardrailModal.tsx`

**Functions:**
- `KbGuardrailModal` (line 22)

#### `LoadingSpinner.tsx`
**Path:** `admin/inertia/components/LoadingSpinner.tsx`

*No symbols extracted*

#### `MarkdocRenderer.tsx`
**Path:** `admin/inertia/components/MarkdocRenderer.tsx`

**Functions:**
- `Paragraph` (line 10) - *Paragraph component*
- `Link` (line 15) - *Link component*
- `InlineCode` (line 38) - *Inline code component*
- `CodeBlock` (line 47) - *Code block component*
- `HorizontalRule` (line 74) - *Horizontal rule component*
- `Callout` (line 81) - *Callout component*

#### `ProgressBar.tsx`
**Path:** `admin/inertia/components/ProgressBar.tsx`

**Functions:**
- `ProgressBar` (line 1)

#### `StorageProjectionBar.tsx`
**Path:** `admin/inertia/components/StorageProjectionBar.tsx`

**Functions:**
- `StorageProjectionBar` (line 11)
- `currentPercent` (line 17)
- `projectedPercent` (line 18)
- `projectedTotalPercent` (line 19)
- `getProjectedColor` (line 24) - *Determine warning level based on projected total*
- `getProjectedGlow` (line 31)

#### `StyledButton.tsx`
**Path:** `admin/inertia/components/StyledButton.tsx`

**Functions:**
- `getIconSize` (line 30)
- `getSizeClasses` (line 41)
- `getVariantClasses` (line 52)
- `getLoadingSpinner` (line 131)
- `onClickHandler` (line 140)

#### `StyledModal.tsx`
**Path:** `admin/inertia/components/StyledModal.tsx`

*No symbols extracted*

#### `StyledSectionHeader.tsx`
**Path:** `admin/inertia/components/StyledSectionHeader.tsx`

**Functions:**
- `StyledSectionHeader` (line 10)

#### `StyledSidebar.tsx`
**Path:** `admin/inertia/components/StyledSidebar.tsx`

**Functions:**
- `ListItem` (line 34)
- `content` (line 41)
- `Sidebar` (line 62)

#### `StyledTable.tsx`
**Path:** `admin/inertia/components/StyledTable.tsx`

**Functions:**
- `StyledTable` (line 33)
- `isRowExpanded` (line 59)
- `toggleRowExpansion` (line 64)

#### `ThemeToggle.tsx`
**Path:** `admin/inertia/components/ThemeToggle.tsx`

**Functions:**
- `ThemeToggle` (line 8)

#### `TierSelectionModal.tsx`
**Path:** `admin/inertia/components/TierSelectionModal.tsx`

**Functions:**
- `resourceFilename` (line 21)
- `getAllResourcesForTier` (line 55) - *Get all resources for a tier (including inherited resources). Defined as a hook-safe closure (always callable, returns [] when no category) so the ...*
- `getTierTotalSize` (line 116)
- `handleTierClick` (line 120)
- `finalizeSubmit` (line 134) - *Runs the original onSelectTier-then-onClose flow. Pulled out of handleSubmit so the guardrail modal's confirm path can call it after the user has c...*
- `handleSubmit` (line 143)

#### `UpdateServiceModal.tsx`
**Path:** `admin/inertia/components/UpdateServiceModal.tsx`

**Functions:**
- `UpdateServiceModal` (line 17)
- `loadVersions` (line 30)
- `handleToggleAdvanced` (line 45)

#### `WikipediaSelector.tsx`
**Path:** `admin/inertia/components/WikipediaSelector.tsx`

*No symbols extracted*

#### `ChatAssistantAvatar.tsx`
**Path:** `admin/inertia/components/chat/ChatAssistantAvatar.tsx`

**Functions:**
- `ChatAssistantAvatar` (line 3)

#### `ChatButton.tsx`
**Path:** `admin/inertia/components/chat/ChatButton.tsx`

**Functions:**
- `ChatButton` (line 7)

#### `ChatInterface.tsx`
**Path:** `admin/inertia/components/chat/ChatInterface.tsx`

**Functions:**
- `ChatInterface` (line 24)
- `handleDownloadModel` (line 41)
- `scrollToBottom` (line 54)
- `handleSubmit` (line 62)
- `handleKeyDown` (line 73)
- `handleInput` (line 80)

#### `ChatMessageBubble.tsx`
**Path:** `admin/inertia/components/chat/ChatMessageBubble.tsx`

**Functions:**
- `ChatMessageBubble` (line 10)

#### `ChatModal.tsx`
**Path:** `admin/inertia/components/chat/ChatModal.tsx`

**Functions:**
- `ChatModal` (line 11)

#### `ChatSidebar.tsx`
**Path:** `admin/inertia/components/chat/ChatSidebar.tsx`

**Functions:**
- `ChatSidebar` (line 18)
- `handleCloseKnowledgeBase` (line 31)

#### `KbPolicyPromptBanner.tsx`
**Path:** `admin/inertia/components/chat/KbPolicyPromptBanner.tsx`

**Functions:**
- `KbPolicyPromptBanner` (line 27) - *(`rag.defaultIngestPolicy` unset). Two buttons let the user decide once, after which the prompt never returns:  - "Index existing content" → sets p...*

#### `KnowledgeBaseModal.tsx`
**Path:** `admin/inertia/components/chat/KnowledgeBaseModal.tsx`

**Functions:**
- `renderStatePill` (line 32)
- `pickRowAction` (line 77)
- `KnowledgeBaseModal` (line 96)
- `handleUpload` (line 282)
- `handleConfirmSync` (line 313)

#### `index.tsx`
**Path:** `admin/inertia/components/chat/index.tsx`

**Functions:**
- `Chat` (line 24)

#### `index.tsx`
**Path:** `admin/inertia/components/file-uploader/index.tsx`

*No symbols extracted*

#### `Input.tsx`
**Path:** `admin/inertia/components/inputs/Input.tsx`

*No symbols extracted*

#### `Switch.tsx`
**Path:** `admin/inertia/components/inputs/Switch.tsx`

**Functions:**
- `Switch` (line 12)

#### `BackToHomeHeader.tsx`
**Path:** `admin/inertia/components/layout/BackToHomeHeader.tsx`

**Functions:**
- `BackToHomeHeader` (line 10)

#### `CoordinateOverlay.tsx`
**Path:** `admin/inertia/components/maps/CoordinateOverlay.tsx`

**Functions:**
- `CoordinateOverlay` (line 8)

#### `MapComponent.tsx`
**Path:** `admin/inertia/components/maps/MapComponent.tsx`

**Functions:**
- `MapComponent` (line 31)

#### `MarkerPanel.tsx`
**Path:** `admin/inertia/components/maps/MarkerPanel.tsx`

**Functions:**
- `MarkerPanel` (line 14)

#### `MarkerPin.tsx`
**Path:** `admin/inertia/components/maps/MarkerPin.tsx`

**Functions:**
- `MarkerPin` (line 8)

#### `ScaleUnitToggle.tsx`
**Path:** `admin/inertia/components/maps/ScaleUnitToggle.tsx`

**Functions:**
- `ScaleUnitToggle` (line 9)

#### `Heading.tsx`
**Path:** `admin/inertia/components/markdoc/Heading.tsx`

**Functions:**
- `Heading` (line 3)

#### `Image.tsx`
**Path:** `admin/inertia/components/markdoc/Image.tsx`

**Functions:**
- `Image` (line 1)

#### `List.tsx`
**Path:** `admin/inertia/components/markdoc/List.tsx`

**Functions:**
- `List` (line 1)

#### `ListItem.tsx`
**Path:** `admin/inertia/components/markdoc/ListItem.tsx`

**Functions:**
- `ListItem` (line 1)

#### `Table.tsx`
**Path:** `admin/inertia/components/markdoc/Table.tsx`

**Functions:**
- `Table` (line 1)
- `TableHead` (line 11)
- `TableBody` (line 15)
- `TableRow` (line 19)
- `TableHeader` (line 23)
- `TableCell` (line 31)

#### `CircularGauge.tsx`
**Path:** `admin/inertia/components/systeminfo/CircularGauge.tsx`

**Functions:**
- `CircularGauge` (line 14)
- `getColor` (line 63)
- `angle` (line 118)

#### `InfoCard.tsx`
**Path:** `admin/inertia/components/systeminfo/InfoCard.tsx`

**Functions:**
- `InfoCard` (line 13)
- `getVariantStyles` (line 14)

#### `StatusCard.tsx`
**Path:** `admin/inertia/components/systeminfo/StatusCard.tsx`

**Functions:**
- `StatusCard` (line 6)

#### `useServiceInstalledStatus.tsx`
**Path:** `admin/inertia/hooks/useServiceInstalledStatus.tsx`

**Functions:**
- `useServiceInstalledStatus` (line 5)

#### `AppLayout.tsx`
**Path:** `admin/inertia/layouts/AppLayout.tsx`

**Functions:**
- `AppLayout` (line 11)

#### `DocsLayout.tsx`
**Path:** `admin/inertia/layouts/DocsLayout.tsx`

**Functions:**
- `DocsLayout` (line 6)

#### `MapsLayout.tsx`
**Path:** `admin/inertia/layouts/MapsLayout.tsx`

**Functions:**
- `MapsLayout` (line 3)

#### `SettingsLayout.tsx`
**Path:** `admin/inertia/layouts/SettingsLayout.tsx`

**Functions:**
- `SettingsLayout` (line 20)

#### `about.tsx`
**Path:** `admin/inertia/pages/about.tsx`

**Functions:**
- `About` (line 3)

#### `chat.tsx`
**Path:** `admin/inertia/pages/chat.tsx`

**Functions:**
- `Chat` (line 4)

#### `show.tsx`
**Path:** `admin/inertia/pages/docs/show.tsx`

**Functions:**
- `Show` (line 5)

#### `complete.tsx`
**Path:** `admin/inertia/pages/easy-setup/complete.tsx`

**Functions:**
- `EasySetupWizardComplete` (line 11)

#### `index.tsx`
**Path:** `admin/inertia/pages/easy-setup/index.tsx`

**Functions:**
- `buildCoreCapabilities` (line 35)
- `EasySetupWizard` (line 115)
- `toggleMapCollection` (line 215)
- `toggleAiModel` (line 221)
- `handleCategoryClick` (line 228) - *Category/tier handlers*
- `handleTierSelect` (line 234)
- `closeTierModal` (line 247)
- `getSelectedTierResources` (line 253) - *Get all resources from selected tiers for storage projection*
- `unit` (line 293)
- `canProceedToNextStep` (line 334)
- `handleNext` (line 340)
- `handleBack` (line 347)
- `handleFinish` (line 354)
- `msg` (line 385)
- `markAsVisited` (line 460)
- `renderStepIndicator` (line 472)
- `isCapabilitySelected` (line 562) - *Check if a capability is selected (all its services are in selectedServices)*
- `isCapabilityInstalled` (line 567) - *Check if a capability is already installed (all its services are installed)*
- `capabilityExists` (line 574) - *Check if a capability exists in the system (has at least one matching service)*
- `toggleCapability` (line 581) - *Toggle all services for a capability (only if not already installed)*
- `renderCapabilityCard` (line 621)
- `renderStep1` (line 723)
- `renderStep2` (line 843)
- `renderStep3` (line 889)
- `renderStep4` (line 991)
- `renderStep5` (line 1134)

#### `not_found.tsx`
**Path:** `admin/inertia/pages/errors/not_found.tsx`

**Functions:**
- `NotFound` (line 1)

#### `server_error.tsx`
**Path:** `admin/inertia/pages/errors/server_error.tsx`

**Functions:**
- `ServerError` (line 1)

#### `home.tsx`
**Path:** `admin/inertia/pages/home.tsx`

**Functions:**
- `Home` (line 87)
- `tileContent` (line 160)

#### `maps.tsx`
**Path:** `admin/inertia/pages/maps.tsx`

**Functions:**
- `Maps` (line 12)

#### `apps.tsx`
**Path:** `admin/inertia/pages/settings/apps.tsx`

**Functions:**
- `extractTag` (line 20)
- `SettingsPage` (line 27)
- `handleCheckUpdates` (line 60)
- `installService` (line 103)
- `handleAffectAction` (line 126)
- `handleForceReinstall` (line 149)
- `handleUpdateService` (line 172)
- `handleInstallService` (line 78)
- `AppActions` (line 202)
- `ForceReinstallButton` (line 203)

#### `benchmark.tsx`
**Path:** `admin/inertia/pages/settings/benchmark.tsx`

**Functions:**
- `BenchmarkPage` (line 30)
- `handleFullBenchmarkClick` (line 198) - *Handle Full Benchmark click with pre-flight check*
- `advanceStage` (line 277)
- `formatBytes` (line 321)
- `getScoreColor` (line 326)
- `getProgressPercent` (line 332)
- `getAIScore` (line 353) - *Calculate AI score from tokens per second (normalized to 0-100) Reference: 30 tok/s = 50 score, 60 tok/s = 100 score*
- `score` (line 355)

#### `legal.tsx`
**Path:** `admin/inertia/pages/settings/legal.tsx`

**Functions:**
- `LegalPage` (line 4)

#### `maps.tsx`
**Path:** `admin/inertia/pages/settings/maps.tsx`

**Functions:**
- `MapsManager` (line 26)
- `downloadBaseAssets` (line 83)
- `downloadCollection` (line 110)
- `downloadCustomFile` (line 123)
- `deleteFile` (line 136)
- `confirmDeleteFile` (line 159)
- `confirmDownload` (line 179)
- `confirmGlobalMapDownload` (line 213)
- `openCountryPickerModal` (line 236)
- `openDownloadModal` (line 254)

#### `models.tsx`
**Path:** `admin/inertia/pages/settings/models.tsx`

**Functions:**
- `ModelsPage` (line 25)
- `handleSaveRemoteOllama` (line 108)
- `handleClearRemoteOllama` (line 125)
- `handleForceRefresh` (line 175)
- `handleInstallModel` (line 183)
- `handleDeleteModel` (line 201)
- `confirmDeleteModel` (line 221)
- `handleDismissGpuBanner` (line 48)
- `handleForceReinstallOllama` (line 55)

#### `support.tsx`
**Path:** `admin/inertia/pages/settings/support.tsx`

**Functions:**
- `SupportPage` (line 5)

#### `system.tsx`
**Path:** `admin/inertia/pages/settings/system.tsx`

**Functions:**
- `SettingsPage` (line 19)
- `handleDismissGpuBanner` (line 37)
- `handleForceReinstallOllama` (line 44)

#### `update.tsx`
**Path:** `admin/inertia/pages/settings/update.tsx`

**Functions:**
- `ContentUpdatesSection` (line 43)
- `SystemUpdatePage` (line 260)
- `handleCheck` (line 52)
- `handleApply` (line 70)
- `handleApplyAll` (line 99)
- `handleStartUpdate` (line 338)
- `handleViewLogs` (line 353)
- `getProgressBarColor` (line 394)
- `getStatusIcon` (line 400)

#### `index.tsx`
**Path:** `admin/inertia/pages/settings/zim/index.tsx`

**Functions:**
- `ZimPage` (line 20)
- `getFiles` (line 31)
- `toggleSort` (line 55)
- `renderSortHeader` (line 64)
- `confirmDeleteFile` (line 79)
- `aName` (line 46)
- `bName` (line 47)

#### `remote-explorer.tsx`
**Path:** `admin/inertia/pages/settings/zim/remote-explorer.tsx`

**Functions:**
- `ZimRemoteExplorer` (line 54)
- `confirmDownload` (line 238)
- `confirmCustomDownload` (line 263)
- `downloadFile` (line 288)
- `downloadCustomFile` (line 302)
- `handleSourceChange` (line 210) - *When selecting a custom library, navigate to its root*
- `navigateToDirectory` (line 227)
- `navigateToBreadcrumb` (line 232)
- `handleCategoryClick` (line 323) - *Category/tier handlers*
- `handleTierSelect` (line 329)
- `closeTierModal` (line 350)
- `handleWikipediaSelect` (line 356) - *Wikipedia selection handlers*
- `handleWikipediaSubmit` (line 361)

#### `ModalProvider.tsx`
**Path:** `admin/inertia/providers/ModalProvider.tsx`

**Functions:**
- `openModal` (line 12)
- `closeModal` (line 20)
- `closeAllModals` (line 31)
- `_getCurrentModals` (line 36)

#### `NotificationProvider.tsx`
**Path:** `admin/inertia/providers/NotificationProvider.tsx`

**Functions:**
- `NotificationsProvider` (line 6)
- `addNotification` (line 9)
- `removeNotification` (line 29)
- `removeAllNotifications` (line 33)
- `Icon` (line 37)

#### `ThemeProvider.tsx`
**Path:** `admin/inertia/providers/ThemeProvider.tsx`

**Functions:**
- `ThemeProvider` (line 16)
- `useThemeContext` (line 25)
