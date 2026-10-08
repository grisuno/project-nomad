# Subsystem: lib

## admin/inertia/lib/api.ts
- Layer: presentation
- Language: ts
- Symbols:
  - `API` (class, line 15)
- Depends on: `admin/inertia/lib/util.ts`, `admin/types/benchmark.ts`, `admin/types/downloads.ts`, `admin/types/files.ts`, `admin/types/ollama.ts`, `admin/types/rag.ts`, `admin/types/services.ts`, `admin/types/system.ts`, `admin/types/zim.ts`

## admin/inertia/lib/classNames.ts
- Layer: utility
- Language: ts
- Symbols:
  - `classNames` (function, line 2)
- Imported by: `admin/inertia/components/Alert.tsx`, `admin/inertia/components/CountryPickerModal.tsx`, `admin/inertia/components/DynamicIcon.tsx`, `admin/inertia/components/HorizontalBarChart.tsx`, `admin/inertia/components/InstallActivityFeed.tsx`, `admin/inertia/components/StorageProjectionBar.tsx`, `admin/inertia/components/StyledModal.tsx`, `admin/inertia/components/StyledSidebar.tsx`, `admin/inertia/components/StyledTable.tsx`, `admin/inertia/components/TierSelectionModal.tsx`, `admin/inertia/components/WikipediaSelector.tsx`, `admin/inertia/components/chat/ChatInterface.tsx`, `admin/inertia/components/chat/ChatMessageBubble.tsx`, `admin/inertia/components/chat/ChatSidebar.tsx`, `admin/inertia/components/chat/index.tsx`, `admin/inertia/components/inputs/Input.tsx`, `admin/inertia/components/systeminfo/CircularGauge.tsx`, `admin/inertia/components/systeminfo/InfoCard.tsx`, `admin/inertia/layouts/AppLayout.tsx`, `admin/inertia/pages/easy-setup/index.tsx`

## admin/inertia/lib/collections.ts
- Doc: resolveTierResources: Resolve all resources for a tier, including inherited resources from...
- Layer: utility
- Language: ts
- Symbols:
  - `resolveTierResources` (function, line 7)
  - `resolveTierResourcesInner` (function, line 11)

## admin/inertia/lib/global_map_banner.ts
- Layer: utility
- Language: ts
- Symbols:
  - `hasDownloadedGlobalMap` (function, line 1)
- Imported by: `admin/inertia/pages/settings/maps.tsx`, `admin/tests/unit/global_map_banner.spec.ts`

## admin/inertia/lib/icons.ts
- Layer: presentation
- Language: ts
- Imported by: `admin/inertia/components/DynamicIcon.tsx`

## admin/inertia/lib/kb_file_grouping.ts
- Doc: groupAndSortKbFiles: Group stored-file rows into table rows for the Stored Files panel.  - Admin...
- Layer: utility
- Language: ts
- Symbols:
  - `classifyKbFile` (function, line 21)
  - `sourceToDisplayName` (function, line 34)
  - `groupAndSortKbFiles` (function, line 67)
- Depends on: `admin/util/docs.ts`
- Imported by: `admin/inertia/components/chat/KnowledgeBaseModal.tsx`, `admin/tests/unit/kb_file_grouping.spec.ts`

## admin/inertia/lib/kb_guardrail.ts
- Doc: evaluateGuardrail: Decide whether a bulk indexing action should be gated behind the guardrail modal.
- Layer: utility
- Language: ts
- Symbols:
  - `evaluateGuardrail` (function, line 47)
- Imported by: `admin/inertia/components/TierSelectionModal.tsx`, `admin/tests/unit/kb_guardrail.spec.ts`

## admin/inertia/lib/kb_job_health_display.ts
- Doc: formatTimeAgo: Format a relative timestamp as "Xs ago", "Xm ago", "Xh ago" with sensible...
- Layer: utility
- Language: ts
- Symbols:
  - `formatTimeAgo` (function, line 45)
  - `computeJobHealthNow` (function, line 59)
- Depends on: `admin/app/utils/kb_job_health.ts`
- Imported by: `admin/inertia/components/ActiveEmbedJobs.tsx`

## admin/inertia/lib/navigation.ts
- Layer: utility
- Language: ts
- Symbols:
  - `getServiceLink` (function, line 3)
- Imported by: `admin/inertia/layouts/SettingsLayout.tsx`, `admin/inertia/pages/home.tsx`, `admin/inertia/pages/settings/apps.tsx`

## admin/inertia/lib/util.ts
- Doc: catchInternal: A higher-order function that wraps an asynchronous function to catch and log...
- Layer: utility
- Language: ts
- Symbols:
  - `setGlobalNotificationCallback` (function, line 6)
  - `capitalizeFirstLetter` (function, line 10)
  - `formatBytes` (function, line 15)
  - `generateRandomString` (function, line 24)
  - `generateUUID` (function, line 33)
  - `that` (function, line 69)
  - `to` (function, line 69)
  - `to` (function, line 70)
  - `that` (function, line 71)
  - `and` (function, line 71)
  - `catchInternal` (function, line 73)
  - `extractFileName` (function, line 57)
- Depends on: `admin/inertia/context/NotificationContext.ts`
- Imported by: `admin/inertia/lib/api.ts`
