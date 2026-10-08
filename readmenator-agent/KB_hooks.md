# Subsystem: hooks

## admin/inertia/hooks/useDebounce.ts
- Layer: presentation
- Language: ts
- Symbols:
  - `useDebounce` (function, line 3)
  - `debounce` (function, line 6)
- Imported by: `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`

## admin/inertia/hooks/useDiskDisplayData.ts
- Doc: getAllDiskDisplayItems: import { Systeminformation } from 'systeminformation' import {...
- Layer: data_access
- Language: ts
- Symbols:
  - `getAllDiskDisplayItems` (function, line 16)
  - `getPrimaryDiskInfo` (function, line 88)
- Depends on: `admin/types/system.ts`
- Imported by: `admin/inertia/components/TierSelectionModal.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/settings/system.tsx`

## admin/inertia/hooks/useDownloads.ts
- Layer: presentation
- Language: ts
- Symbols:
  - `useDownloads` (function, line 10)
  - `invalidate` (function, line 29)
- Imported by: `admin/inertia/components/ActiveDownloads.tsx`, `admin/inertia/pages/settings/maps.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`

## admin/inertia/hooks/useEmbedJobs.ts
- Layer: presentation
- Language: ts
- Symbols:
  - `useEmbedJobs` (function, line 5)
  - `invalidate` (function, line 29)
- Imported by: `admin/inertia/components/ActiveEmbedJobs.tsx`

## admin/inertia/hooks/useErrorNotification.ts
- Doc: Helper hook to show error notifications
- Layer: utility
- Language: ts
- Symbols:
  - `useErrorNotification` (function, line 4)
  - `showError` (function, line 7)
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/pages/settings/apps.tsx`

## admin/inertia/hooks/useInternetStatus.ts
- Doc: Helper hook to check internet connection status
- Layer: presentation
- Language: ts
- Symbols:
  - `useInternetStatus` (function, line 6)
- Imported by: `admin/inertia/pages/easy-setup/complete.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/settings/apps.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`

## admin/inertia/hooks/useMapMarkers.ts
- Layer: presentation
- Language: ts
- Symbols:
  - `useMapMarkers` (function, line 25)
- Imported by: `admin/inertia/components/maps/MapComponent.tsx`, `admin/inertia/components/maps/MarkerPanel.tsx`

## admin/inertia/hooks/useMapRegionFiles.ts
- Layer: utility
- Language: ts
- Symbols:
  - `useMapRegionFiles` (function, line 5)
- Depends on: `admin/types/files.ts`

## admin/inertia/hooks/useOllamaModelDownloads.ts
- Layer: presentation
- Language: ts
- Symbols:
  - `useOllamaModelDownloads` (function, line 25)
- Imported by: `admin/inertia/components/ActiveModelDownloads.tsx`

## admin/inertia/hooks/useServiceInstallationActivity.ts
- Layer: presentation
- Language: ts
- Symbols:
  - `useServiceInstallationActivity` (function, line 6)
- Depends on: `admin/constants/broadcast.ts`, `admin/inertia/components/InstallActivityFeed.tsx`
- Imported by: `admin/inertia/pages/easy-setup/complete.tsx`, `admin/inertia/pages/settings/apps.tsx`

## admin/inertia/hooks/useServiceInstalledStatus.tsx
- Layer: business_logic
- Language: tsx
- Symbols:
  - `useServiceInstalledStatus` (function, line 5)
- Depends on: `admin/types/services.ts`
- Imported by: `admin/inertia/layouts/AppLayout.tsx`, `admin/inertia/layouts/SettingsLayout.tsx`, `admin/inertia/pages/settings/benchmark.tsx`, `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/zim/index.tsx`, `admin/inertia/pages/settings/zim/remote-explorer.tsx`

## admin/inertia/hooks/useSystemInfo.ts
- Layer: utility
- Language: ts
- Symbols:
  - `useSystemInfo` (function, line 10)
- Depends on: `admin/types/system.ts`
- Imported by: `admin/inertia/components/TierSelectionModal.tsx`, `admin/inertia/pages/easy-setup/index.tsx`, `admin/inertia/pages/settings/models.tsx`, `admin/inertia/pages/settings/system.tsx`

## admin/inertia/hooks/useSystemSetting.ts
- Layer: utility
- Language: ts
- Symbols:
  - `useSystemSetting` (function, line 12)
- Depends on: `admin/types/kv_store.ts`
- Imported by: `admin/inertia/components/chat/ChatModal.tsx`, `admin/inertia/components/chat/index.tsx`, `admin/inertia/pages/home.tsx`, `admin/inertia/pages/settings/update.tsx`

## admin/inertia/hooks/useTheme.ts
- Layer: presentation
- Language: ts
- Symbols:
  - `getInitialTheme` (function, line 7)
  - `useTheme` (function, line 16)
- Imported by: `admin/inertia/providers/ThemeProvider.tsx`

## admin/inertia/hooks/useUpdateAvailable.ts
- Layer: utility
- Language: ts
- Symbols:
  - `useUpdateAvailable` (function, line 6)
- Depends on: `admin/types/system.ts`
- Imported by: `admin/inertia/pages/home.tsx`
