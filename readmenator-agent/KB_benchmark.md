# Subsystem: benchmark

## admin/commands/benchmark/results.ts
- Layer: utility
- Language: ts
- Symbols:
  - `BenchmarkResults` (class, line 4)
- Depends on: `admin/ace.js`, `admin/commands/benchmark/run.ts`
- Imported by: `admin/app/controllers/benchmark_controller.ts`

## admin/commands/benchmark/run.ts
- Layer: utility
- Language: ts
- Symbols:
  - `BenchmarkRun` (class, line 4)
- Depends on: `admin/ace.js`
- Imported by: `admin/app/controllers/benchmark_controller.ts`, `admin/app/controllers/benchmark_controller.ts`, `admin/commands/benchmark/results.ts`, `admin/commands/benchmark/submit.ts`, `admin/commands/queue/work.ts`, `admin/database/seeders/service_seeder.ts`

## admin/commands/benchmark/submit.ts
- Layer: utility
- Language: ts
- Symbols:
  - `BenchmarkSubmit` (class, line 4)
- Depends on: `admin/ace.js`, `admin/commands/benchmark/run.ts`
- Imported by: `admin/app/controllers/benchmark_controller.ts`, `admin/inertia/pages/easy-setup/index.tsx`
