# admin/inertia/pages/settings

*Community 6 | 11 files | cohesion 0.32*

## Definition

This community groups 11 file(s) rooted at `admin/inertia/pages/settings` with dominant language tsx (cohesion 0.32). Central symbols: `AppActions`, `EasySetupWizard`, `EasySetupWizardComplete`, `ForceReinstallButton`, `LegalPage`, `SettingsController`, `SettingsPage`, `SupportPage`. Core file: `admin/inertia/pages/easy-setup/index.tsx` (26 symbols). Documented purpose: Helper hook to show error notifications.

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/app/controllers/settings_controller.ts` | ts | presentation | 1 | no |
| `admin/app/validators/settings.ts` | ts | infrastructure | 0 | no |
| `admin/inertia/components/InstallActivityFeed.tsx` | tsx | presentation | 0 | no |
| `admin/inertia/hooks/useErrorNotification.ts` | ts | utility | 2 | yes |
| `admin/inertia/hooks/useInternetStatus.ts` | ts | presentation | 1 | yes |
| `admin/inertia/hooks/useServiceInstallationActivity.ts` | ts | presentation | 1 | no |
| `admin/inertia/pages/easy-setup/complete.tsx` | tsx | presentation | 1 | no |
| `admin/inertia/pages/easy-setup/index.tsx` | tsx | presentation | 26 | no |
| `admin/inertia/pages/settings/apps.tsx` | tsx | presentation | 10 | no |
| `admin/inertia/pages/settings/legal.tsx` | tsx | presentation | 1 | no |
| `admin/inertia/pages/settings/support.tsx` | tsx | presentation | 1 | no |

## Key Symbols

- `SettingsController` (class, `admin/app/controllers/settings_controller.ts:11`)
- `useErrorNotification` (function, `admin/inertia/hooks/useErrorNotification.ts:4`)
- `showError` (function, `admin/inertia/hooks/useErrorNotification.ts:7`)
- `useInternetStatus` (function, `admin/inertia/hooks/useInternetStatus.ts:6`)
- `useServiceInstallationActivity` (function, `admin/inertia/hooks/useServiceInstallationActivity.ts:6`)
- `EasySetupWizardComplete` (function, `admin/inertia/pages/easy-setup/complete.tsx:11`)
- `buildCoreCapabilities` (function, `admin/inertia/pages/easy-setup/index.tsx:35`)
- `EasySetupWizard` (function, `admin/inertia/pages/easy-setup/index.tsx:115`)
- `toggleMapCollection` (function, `admin/inertia/pages/easy-setup/index.tsx:215`)
- `toggleAiModel` (function, `admin/inertia/pages/easy-setup/index.tsx:221`)
- `handleCategoryClick` (function, `admin/inertia/pages/easy-setup/index.tsx:228`) - Category/tier handlers
- `handleTierSelect` (function, `admin/inertia/pages/easy-setup/index.tsx:234`)
- `closeTierModal` (function, `admin/inertia/pages/easy-setup/index.tsx:247`)
- `getSelectedTierResources` (function, `admin/inertia/pages/easy-setup/index.tsx:253`) - Get all resources from selected tiers for storage projection
- `unit` (function, `admin/inertia/pages/easy-setup/index.tsx:293`)
- `canProceedToNextStep` (function, `admin/inertia/pages/easy-setup/index.tsx:334`)
- `handleNext` (function, `admin/inertia/pages/easy-setup/index.tsx:340`)
- `handleBack` (function, `admin/inertia/pages/easy-setup/index.tsx:347`)
- `handleFinish` (function, `admin/inertia/pages/easy-setup/index.tsx:354`)
- `msg` (function, `admin/inertia/pages/easy-setup/index.tsx:385`)
- `markAsVisited` (function, `admin/inertia/pages/easy-setup/index.tsx:460`)
- `renderStepIndicator` (function, `admin/inertia/pages/easy-setup/index.tsx:472`)
- `isCapabilitySelected` (function, `admin/inertia/pages/easy-setup/index.tsx:562`) - Check if a capability is selected (all its services are in selectedServices)
- `isCapabilityInstalled` (function, `admin/inertia/pages/easy-setup/index.tsx:567`) - Check if a capability is already installed (all its services are installed)
- `capabilityExists` (function, `admin/inertia/pages/easy-setup/index.tsx:574`) - Check if a capability exists in the system (has at least one matching service)
- `toggleCapability` (function, `admin/inertia/pages/easy-setup/index.tsx:581`) - Toggle all services for a capability (only if not already installed)
- `renderCapabilityCard` (function, `admin/inertia/pages/easy-setup/index.tsx:621`)
- `renderStep1` (function, `admin/inertia/pages/easy-setup/index.tsx:723`)
- `renderStep2` (function, `admin/inertia/pages/easy-setup/index.tsx:843`)
- `renderStep3` (function, `admin/inertia/pages/easy-setup/index.tsx:889`)

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 11
- Cross-boundary resolved imports (EXTRACTED): 39

## Connections

- [EXTRACTED] depends_on community 3 <-> 6 (strength 0.9): Extracted import edge crosses communities: admin/app/controllers/benchmark_controller.ts imports admin/app/validators/settings.ts.
- [EXTRACTED] depends_on community 1 <-> 6 (strength 0.9): Extracted import edge crosses communities: admin/app/controllers/easy_setup_controller.ts imports admin/inertia/pages/easy-setup/complete.tsx.
- [EXTRACTED] depends_on community 6 <-> 2 (strength 0.9): Extracted import edge crosses communities: admin/app/controllers/settings_controller.ts imports admin/app/services/ollama_service.ts.
- [EXTRACTED] depends_on community 6 <-> 0 (strength 0.9): Extracted import edge crosses communities: admin/app/controllers/settings_controller.ts imports admin/inertia/pages/settings/models.tsx.
- [EXTRACTED] depends_on community 6 <-> 7 (strength 0.9): Extracted import edge crosses communities: admin/app/controllers/settings_controller.ts imports admin/inertia/pages/settings/update.tsx.
- [EXTRACTED] depends_on community 6 <-> 4 (strength 0.9): Extracted import edge crosses communities: admin/inertia/components/InstallActivityFeed.tsx imports admin/inertia/lib/classNames.ts.

## Risks

- [layer strict] `admin/inertia/pages/easy-setup/index.tsx` (presentation) -> `admin/inertia/hooks/useDiskDisplayData.ts` (data_access)

## Open Questions

- Why do 9 file(s) lack file-level docs (e.g. `admin/app/controllers/settings_controller.ts`)? What purpose do they serve?
- What would break if the most connected file in admin/inertia/pages/settings changed?
- Should admin/inertia/pages/settings be split, given cohesion 0.32?

## Sources

- `admin/app/controllers/settings_controller.ts`
- `admin/app/validators/settings.ts`
- `admin/inertia/components/InstallActivityFeed.tsx`
- `admin/inertia/hooks/useErrorNotification.ts`
- `admin/inertia/hooks/useInternetStatus.ts`
- `admin/inertia/hooks/useServiceInstallationActivity.ts`
- `admin/inertia/pages/easy-setup/complete.tsx`
- `admin/inertia/pages/easy-setup/index.tsx`
- `admin/inertia/pages/settings/apps.tsx`
- `admin/inertia/pages/settings/legal.tsx`
- `admin/inertia/pages/settings/support.tsx`
