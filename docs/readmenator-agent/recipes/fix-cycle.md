# Recipe: Fix a Dependency Cycle

Target cycle: `admin/app/jobs/run_download_job.ts` -> `admin/app/services/zim_service.ts` -> `admin/app/services/collection_manifest_service.ts` -> `admin/app/jobs/run_download_job.ts`

1. Read the imports between these files: `grep -n '^import\|^from\|#include' admin/app/jobs/run_download_job.ts`, `grep -n '^import\|^from\|#include' admin/app/services/zim_service.ts`, `grep -n '^import\|^from\|#include' admin/app/services/collection_manifest_service.ts`
2. Move the shared symbols into a new leaf module both sides import
3. Verify: `readmenator . && grep -c 'Dependency Cycles' readmenator-agent/GOTCHAS.md`
