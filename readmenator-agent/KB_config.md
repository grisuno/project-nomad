# Subsystem: config

## admin/config/app.ts
- Layer: infrastructure
- Language: ts

## admin/config/bodyparser.ts
- Layer: infrastructure
- Language: ts

## admin/config/cors.ts
- Layer: infrastructure
- Language: ts

## admin/config/database.ts
- Layer: data_access
- Language: ts

## admin/config/hash.ts
- Layer: infrastructure
- Language: ts

## admin/config/inertia.ts
- Layer: infrastructure
- Language: ts
- Symbols:
  - `invalidateAssistantNameCache` (function, line 8)
  - `value` (function, line 30)
- Depends on: `admin/app/services/system_service.ts`
- Imported by: `admin/app/controllers/chats_controller.ts`, `admin/app/services/system_service.ts`

## admin/config/logger.ts
- Layer: infrastructure
- Language: ts
- Imported by: `admin/app/middleware/container_bindings_middleware.ts`

## admin/config/queue.ts
- Layer: infrastructure
- Language: ts
- Imported by: `admin/app/jobs/check_service_updates_job.ts`, `admin/app/jobs/check_update_job.ts`, `admin/app/jobs/download_model_job.ts`, `admin/app/jobs/embed_file_job.ts`, `admin/app/jobs/run_benchmark_job.ts`, `admin/app/jobs/run_download_job.ts`, `admin/app/jobs/run_extract_pmtiles_job.ts`

## admin/config/session.ts
- Layer: infrastructure
- Doc: import env from '#start/env' import app from '@adonisjs/core/services/app' import { defineConfig, stores } from '@adonis
- Language: ts

## admin/config/shield.ts
- Layer: infrastructure
- Language: ts

## admin/config/static.ts
- Layer: infrastructure
- Language: ts
- Imported by: `admin/providers/map_static_provider.ts`

## admin/config/transmit.ts
- Layer: infrastructure
- Language: ts

## admin/config/vite.ts
- Layer: infrastructure
- Language: ts
- Imported by: `admin/vite.config.ts`
