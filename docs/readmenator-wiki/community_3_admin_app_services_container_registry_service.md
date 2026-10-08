# admin/app/services: container_registry_service

*Community 3 | 18 files | cohesion 0.45*

## Definition

This community groups 18 file(s) rooted at `admin/app/services` with dominant language ts (cohesion 0.45). Central symbols: `BenchmarkController`, `BenchmarkResults`, `BenchmarkRun`, `BenchmarkService`, `BenchmarkSubmit`, `CheckServiceUpdatesJob`, `ContainerRegistryService`, `DockerService`. Core file: `admin/app/services/container_registry_service.ts` (7 symbols).

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/ace.js` | js | utility | 0 | no |
| `admin/app/controllers/benchmark_controller.ts` | ts | presentation | 2 | no |
| `admin/app/controllers/system_controller.ts` | ts | presentation | 1 | no |
| `admin/app/jobs/check_service_updates_job.ts` | ts | business_logic | 1 | no |
| `admin/app/jobs/run_benchmark_job.ts` | ts | utility | 1 | no |
| `admin/app/models/service.ts` | ts | business_logic | 1 | no |
| `admin/app/services/benchmark_service.ts` | ts | business_logic | 2 | no |
| `admin/app/services/container_registry_service.ts` | ts | business_logic | 7 | no |
| `admin/app/services/docker_service.ts` | ts | business_logic | 5 | no |
| `admin/app/services/system_update_service.ts` | ts | business_logic | 1 | no |
| `admin/app/utils/version.ts` | ts | utility | 3 | no |
| `admin/commands/benchmark/results.ts` | ts | utility | 1 | no |
| `admin/commands/benchmark/run.ts` | ts | utility | 1 | no |
| `admin/commands/benchmark/submit.ts` | ts | utility | 1 | no |
| `admin/commands/queue/work.ts` | ts | infrastructure | 1 | no |
| `admin/constants/broadcast.ts` | ts | utility | 0 | no |
| `admin/constants/kiwix.ts` | ts | utility | 0 | no |
| `admin/database/seeders/service_seeder.ts` | ts | data_access | 1 | no |

## Key Symbols

- `BenchmarkController` (class, `admin/app/controllers/benchmark_controller.ts:11`)
- `statusCode` (function, `admin/app/controllers/benchmark_controller.ts:185`) - Pass through the status code from the service if available, otherwise default to 400
- `SystemController` (class, `admin/app/controllers/system_controller.ts:12`)
- `CheckServiceUpdatesJob` (class, `admin/app/jobs/check_service_updates_job.ts:11`)
- `RunBenchmarkJob` (class, `admin/app/jobs/run_benchmark_job.ts:8`)
- `Service` (class, `admin/app/models/service.ts:5`)
- `BenchmarkService` (class, `admin/app/services/benchmark_service.ts:67`)
- `totalTime` (function, `admin/app/services/benchmark_service.ts:504`)
- `ContainerRegistryService` (class, `admin/app/services/container_registry_service.ts:28`)
- `data` (function, `admin/app/services/container_registry_service.ts:104`)
- `data` (function, `admin/app/services/container_registry_service.ts:137`)
- `manifest` (function, `admin/app/services/container_registry_service.ts:177`)
- `manifest` (function, `admin/app/services/container_registry_service.ts:236`)
- `childManifest` (function, `admin/app/services/container_registry_service.ts:256`)
- `config` (function, `admin/app/services/container_registry_service.ts:278`)
- `DockerService` (class, `admin/app/services/docker_service.ts:19`)
- `used` (function, `admin/app/services/docker_service.ts:548`)
- `is` (function, `admin/app/services/docker_service.ts:826`)
- `marker` (function, `admin/app/services/docker_service.ts:934`)
- `gfx` (function, `admin/app/services/docker_service.ts:1043`)
- `SystemUpdateService` (class, `admin/app/services/system_update_service.ts:14`)
- `isNewerVersion` (function, `admin/app/utils/version.ts:7`) - Compare two semantic version strings to determine if the first is newer than the second. @param vers
- `normalize` (function, `admin/app/utils/version.ts:8`)
- `parseMajorVersion` (function, `admin/app/utils/version.ts:45`) - Parse the major version number from a tag string. Strips the 'v' prefix if present. @param tag - Ver
- `BenchmarkResults` (class, `admin/commands/benchmark/results.ts:4`)
- `BenchmarkRun` (class, `admin/commands/benchmark/run.ts:4`)
- `BenchmarkSubmit` (class, `admin/commands/benchmark/submit.ts:4`)
- `QueueWork` (class, `admin/commands/queue/work.ts:13`)
- `ServiceSeeder` (class, `admin/database/seeders/service_seeder.ts:8`)

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 36
- Cross-boundary resolved imports (EXTRACTED): 42

## Connections

- [EXTRACTED] depends_on community 3 <-> 8 (strength 0.9): Extracted import edge crosses communities: admin/app/controllers/benchmark_controller.ts imports admin/inertia/pages/docs/show.tsx.
- [EXTRACTED] depends_on community 3 <-> 6 (strength 0.9): Extracted import edge crosses communities: admin/app/controllers/benchmark_controller.ts imports admin/app/validators/settings.ts.
- [EXTRACTED] depends_on community 2 <-> 3 (strength 0.9): Extracted import edge crosses communities: admin/app/controllers/ollama_controller.ts imports admin/app/services/docker_service.ts.
- [EXTRACTED] depends_on community 3 <-> 1 (strength 0.9): Extracted import edge crosses communities: admin/app/jobs/check_service_updates_job.ts imports admin/app/services/queue_service.ts.
- [EXTRACTED] depends_on community 3 <-> 7 (strength 0.9): Extracted import edge crosses communities: admin/app/services/benchmark_service.ts imports admin/inertia/pages/settings/update.tsx.

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- Why do 18 file(s) lack file-level docs (e.g. `admin/ace.js`)? What purpose do they serve?
- What would break if the most connected file in admin/app/services: container_registry_service changed?
- Should admin/app/services: container_registry_service be split, given cohesion 0.45?

## Sources

- `admin/ace.js`
- `admin/app/controllers/benchmark_controller.ts`
- `admin/app/controllers/system_controller.ts`
- `admin/app/jobs/check_service_updates_job.ts`
- `admin/app/jobs/run_benchmark_job.ts`
- `admin/app/models/service.ts`
- `admin/app/services/benchmark_service.ts`
- `admin/app/services/container_registry_service.ts`
- `admin/app/services/docker_service.ts`
- `admin/app/services/system_update_service.ts`
- `admin/app/utils/version.ts`
- `admin/commands/benchmark/results.ts`
- `admin/commands/benchmark/run.ts`
- `admin/commands/benchmark/submit.ts`
- `admin/commands/queue/work.ts`
- `admin/constants/broadcast.ts`
- `admin/constants/kiwix.ts`
- `admin/database/seeders/service_seeder.ts`
