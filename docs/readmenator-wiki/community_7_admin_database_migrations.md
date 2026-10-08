# admin/database/migrations

*Community 7 | 9 files | cohesion 0.35*

## Definition

This community groups 9 file(s) rooted at `admin/database/migrations` with dominant language ts (cohesion 0.35). Central symbols: `ChatModal`, `ContentUpdatesSection`, `CountriesService`, `Docker`, `QdrantRestartPolicyProvider`, `Service`, `SystemUpdatePage`, `bufferGeometry`. Core file: `admin/app/services/countries_service.ts` (13 symbols).

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/app/services/countries_service.ts` | ts | business_logic | 13 | no |
| `admin/app/utils/misc.ts` | ts | utility | 3 | no |
| `admin/database/migrations/1771000000002_pin_latest_service_images.ts` | ts | data_access | 1 | no |
| `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts` | ts | data_access | 1 | no |
| `admin/inertia/components/chat/ChatModal.tsx` | tsx | presentation | 1 | no |
| `admin/inertia/hooks/useSystemSetting.ts` | ts | utility | 1 | no |
| `admin/inertia/pages/settings/update.tsx` | tsx | presentation | 9 | no |
| `admin/providers/qdrant_restart_policy_provider.ts` | ts | presentation | 3 | no |
| `admin/types/kv_store.ts` | ts | data_access | 0 | no |

## Key Symbols

- `CountriesService` (class, `admin/app/services/countries_service.ts:74`)
- `codes` (function, `admin/app/services/countries_service.ts:144`)
- `typeRank` (function, `admin/app/services/countries_service.ts:215`)
- `resolveIso2` (function, `admin/app/services/countries_service.ts:225`)
- `bufferGeometry` (function, `admin/app/services/countries_service.ts:242`)
- `bufferPolygonRings` (function, `admin/app/services/countries_service.ts:258`)
- `bufferRing` (function, `admin/app/services/countries_service.ts:262`)
- `n1x` (function, `admin/app/services/countries_service.ts:278`)
- `n1y` (function, `admin/app/services/countries_service.ts:279`)
- `n2x` (function, `admin/app/services/countries_service.ts:280`)
- `n2y` (function, `admin/app/services/countries_service.ts:281`)
- `signedArea` (function, `admin/app/services/countries_service.ts:290`)
- `resolveIso3` (function, `admin/app/services/countries_service.ts:298`)
- `formatSpeed` (function, `admin/app/utils/misc.ts:1`)
- `toTitleCase` (function, `admin/app/utils/misc.ts:7`)
- `parseBoolean` (function, `admin/app/utils/misc.ts:15`)
- `extends` (class, `admin/database/migrations/1771000000002_pin_latest_service_images.ts:3`)
- `extends` (class, `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts:3`)
- `ChatModal` (function, `admin/inertia/components/chat/ChatModal.tsx:11`)
- `useSystemSetting` (function, `admin/inertia/hooks/useSystemSetting.ts:12`)
- `ContentUpdatesSection` (function, `admin/inertia/pages/settings/update.tsx:43`)
- `handleCheck` (function, `admin/inertia/pages/settings/update.tsx:52`)
- `handleApply` (function, `admin/inertia/pages/settings/update.tsx:70`)
- `handleApplyAll` (function, `admin/inertia/pages/settings/update.tsx:99`)
- `SystemUpdatePage` (function, `admin/inertia/pages/settings/update.tsx:260`)
- `handleStartUpdate` (function, `admin/inertia/pages/settings/update.tsx:338`)
- `handleViewLogs` (function, `admin/inertia/pages/settings/update.tsx:353`)
- `getProgressBarColor` (function, `admin/inertia/pages/settings/update.tsx:394`)
- `getStatusIcon` (function, `admin/inertia/pages/settings/update.tsx:400`)
- `QdrantRestartPolicyProvider` (class, `admin/providers/qdrant_restart_policy_provider.ts:14`) - Ensures the nomad_qdrant container has the `unless-stopped` restart policy.  Existing installations

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 18
- Cross-boundary resolved imports (EXTRACTED): 18

## Connections

- [EXTRACTED] depends_on community 2 <-> 7 (strength 0.9): Extracted import edge crosses communities: admin/app/controllers/chats_controller.ts imports admin/inertia/pages/settings/update.tsx.
- [EXTRACTED] depends_on community 6 <-> 7 (strength 0.9): Extracted import edge crosses communities: admin/app/controllers/settings_controller.ts imports admin/inertia/pages/settings/update.tsx.
- [EXTRACTED] depends_on community 1 <-> 7 (strength 0.9): Extracted import edge crosses communities: admin/app/jobs/download_model_job.ts imports admin/inertia/pages/settings/update.tsx.
- [EXTRACTED] depends_on community 3 <-> 7 (strength 0.9): Extracted import edge crosses communities: admin/app/services/benchmark_service.ts imports admin/inertia/pages/settings/update.tsx.
- [EXTRACTED] depends_on community 4 <-> 7 (strength 0.9): Extracted import edge crosses communities: admin/inertia/components/chat/index.tsx imports admin/inertia/hooks/useSystemSetting.ts.

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- Why do 9 file(s) lack file-level docs (e.g. `admin/app/services/countries_service.ts`)? What purpose do they serve?
- What would break if the most connected file in admin/database/migrations changed?
- Should admin/database/migrations be split, given cohesion 0.35?

## Sources

- `admin/app/services/countries_service.ts`
- `admin/app/utils/misc.ts`
- `admin/database/migrations/1771000000002_pin_latest_service_images.ts`
- `admin/database/migrations/1771100000001_migrate_kiwix_to_library_mode.ts`
- `admin/inertia/components/chat/ChatModal.tsx`
- `admin/inertia/hooks/useSystemSetting.ts`
- `admin/inertia/pages/settings/update.tsx`
- `admin/providers/qdrant_restart_policy_provider.ts`
- `admin/types/kv_store.ts`
