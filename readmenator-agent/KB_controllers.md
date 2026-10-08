# Subsystem: controllers

## admin/app/controllers/benchmark_controller.ts
- Doc: statusCode: Pass through the status code from the service if available, otherwise default to 400
- Layer: presentation
- Language: ts
- Symbols:
  - `statusCode` (function, line 185)
  - `BenchmarkController` (class, line 11)
- Depends on: `admin/app/jobs/run_benchmark_job.ts`, `admin/app/services/benchmark_service.ts`, `admin/app/validators/settings.ts`, `admin/commands/benchmark/results.ts`, `admin/commands/benchmark/run.ts`, `admin/commands/benchmark/submit.ts`, `admin/inertia/pages/docs/show.tsx`

## admin/app/controllers/chats_controller.ts
- Layer: presentation
- Language: ts
- Symbols:
  - `ChatsController` (class, line 11)
- Depends on: `admin/app/services/chat_service.ts`, `admin/app/services/system_service.ts`, `admin/config/inertia.ts`, `admin/constants/service_names.ts`, `admin/inertia/pages/docs/show.tsx`, `admin/inertia/pages/settings/update.tsx`

## admin/app/controllers/collection_updates_controller.ts
- Layer: presentation
- Language: ts
- Symbols:
  - `CollectionUpdatesController` (class, line 9)
- Depends on: `admin/app/services/collection_update_service.ts`, `admin/app/validators/common.ts`

## admin/app/controllers/docs_controller.ts
- Layer: presentation
- Language: ts
- Symbols:
  - `DocsController` (class, line 6)
- Depends on: `admin/app/services/docs_service.ts`, `admin/inertia/pages/docs/show.tsx`

## admin/app/controllers/downloads_controller.ts
- Layer: presentation
- Language: ts
- Symbols:
  - `DownloadsController` (class, line 7)
- Depends on: `admin/app/services/download_service.ts`, `admin/app/validators/download.ts`

## admin/app/controllers/easy_setup_controller.ts
- Layer: presentation
- Language: ts
- Symbols:
  - `EasySetupController` (class, line 9)
- Depends on: `admin/app/services/collection_manifest_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/zim_service.ts`, `admin/inertia/pages/easy-setup/complete.tsx`

## admin/app/controllers/home_controller.ts
- Layer: presentation
- Language: ts
- Symbols:
  - `HomeController` (class, line 6)
- Depends on: `admin/app/services/system_service.ts`, `admin/inertia/pages/home.tsx`

## admin/app/controllers/maps_controller.ts
- Layer: presentation
- Language: ts
- Symbols:
  - `MapsController` (class, line 17)
- Depends on: `admin/app/services/map_service.ts`, `admin/app/validators/common.ts`

## admin/app/controllers/ollama_controller.ts
- Layer: presentation
- Language: ts
- Symbols:
  - `OllamaController` (class, line 18)
- Depends on: `admin/app/services/chat_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/ollama_service.ts`, `admin/app/services/rag_service.ts`, `admin/app/validators/common.ts`, `admin/app/validators/download.ts`, `admin/constants/service_names.ts`

## admin/app/controllers/rag_controller.ts
- Layer: presentation
- Language: ts
- Symbols:
  - `RagController` (class, line 14)
- Depends on: `admin/app/jobs/embed_file_job.ts`, `admin/app/services/rag_service.ts`, `admin/app/utils/fs.ts`

## admin/app/controllers/settings_controller.ts
- Layer: presentation
- Language: ts
- Symbols:
  - `SettingsController` (class, line 11)
- Depends on: `admin/app/services/benchmark_service.ts`, `admin/app/services/map_service.ts`, `admin/app/services/ollama_service.ts`, `admin/app/services/system_service.ts`, `admin/app/validators/settings.ts`, `admin/inertia/pages/settings/apps.tsx`, `admin/inertia/pages/settings/legal.tsx`, `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/support.tsx`, `admin/inertia/pages/settings/update.tsx`

## admin/app/controllers/system_controller.ts
- Layer: presentation
- Language: ts
- Symbols:
  - `SystemController` (class, line 12)
- Depends on: `admin/app/jobs/check_service_updates_job.ts`, `admin/app/services/container_registry_service.ts`, `admin/app/services/docker_service.ts`, `admin/app/services/system_service.ts`, `admin/app/services/system_update_service.ts`

## admin/app/controllers/zim_controller.ts
- Layer: presentation
- Language: ts
- Symbols:
  - `ZimController` (class, line 14)
- Depends on: `admin/app/services/zim_service.ts`, `admin/app/validators/common.ts`
