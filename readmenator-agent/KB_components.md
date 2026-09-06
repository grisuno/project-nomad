# Subsystem: components

## admin/inertia/components/ActiveDownloads.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `formatSpeed` (function, line 12)
  - `getDownloadStatus` (function, line 21)
  - `ActiveDownloads` (function, line 38)
  - `deltaSec` (function, line 56)
  - `handleDismiss` (function, line 81)
  - `handleCancel` (function, line 86)
- Depends on: `admin/inertia/hooks/useDownloads.ts`

## admin/inertia/components/ActiveEmbedJobs.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `ActiveEmbedJobs` (function, line 15)
- Depends on: `admin/inertia/hooks/useEmbedJobs.ts`, `admin/inertia/lib/kb_job_health_display.ts`

## admin/inertia/components/ActiveModelDownloads.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `formatSpeed` (function, line 13)
  - `ActiveModelDownloads` (function, line 21)
  - `deltaSec` (function, line 39)
  - `runCancel` (function, line 62)
  - `confirmCancel` (function, line 85)
- Depends on: `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useOllamaModelDownloads.ts`

## admin/inertia/components/Alert.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `Alert` (function, line 17)
  - `getDefaultIcon` (function, line 29)
  - `getIconColor` (function, line 44)
  - `getVariantStyles` (function, line 60)
  - `getTitleColor` (function, line 113)
  - `getMessageColor` (function, line 132)
  - `getCloseButtonStyles` (function, line 149)
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/BouncingDots.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `BouncingDots` (function, line 9)

## admin/inertia/components/BouncingLogo.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `FadingImage` (function, line 4)

## admin/inertia/components/BuilderTagSelector.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `BuilderTagSelector` (function, line 18)
  - `updateTag` (function, line 50)
  - `handleAdjectiveChange` (function, line 55)
  - `handleNounChange` (function, line 60)
  - `handleRandomize` (function, line 65)

## admin/inertia/components/CategoryCard.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `getTierTotalSize` (function, line 15)

## admin/inertia/components/CountryPickerModal.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `toggleCountry` (function, line 100)
  - `toggleGroup` (function, line 109)
  - `clearAll` (function, line 122)
  - `startDownload` (function, line 164)
  - `PreflightStatus` (function, line 392)
- Depends on: `admin/constants/map_regions.ts`, `admin/inertia/lib/classNames.ts`

## admin/inertia/components/CuratedCollectionCard.tsx
- Layer: presentation
- Language: tsx

## admin/inertia/components/DebugInfoModal.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `DebugInfoModal` (function, line 11)
  - `handleCopy` (function, line 36)

## admin/inertia/components/DownloadURLModal.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `runPreflightCheck` (function, line 23)

## admin/inertia/components/DynamicIcon.tsx
- Layer: presentation
- Language: tsx
- Depends on: `admin/inertia/lib/classNames.ts`, `admin/inertia/lib/icons.ts`

## admin/inertia/components/Footer.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `Footer` (function, line 8)

## admin/inertia/components/HorizontalBarChart.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `HorizontalBarChart` (function, line 19)
  - `getBarColor` (function, line 26)
  - `getGlowColor` (function, line 34)
  - `getStatusLabel` (function, line 41)
  - `getStatusColor` (function, line 51)
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/InfoTooltip.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `InfoTooltip` (function, line 9)

## admin/inertia/components/InstallActivityFeed.tsx
- Layer: presentation
- Language: tsx
- Depends on: `admin/inertia/lib/classNames.ts`
- Imported by: `admin/inertia/hooks/useServiceInstallationActivity.ts`

## admin/inertia/components/KbGuardrailModal.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `KbGuardrailModal` (function, line 22)

## admin/inertia/components/LoadingSpinner.tsx
- Layer: presentation
- Language: tsx

## admin/inertia/components/MarkdocRenderer.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `Paragraph` (function, line 10)
  - `Link` (function, line 15)
  - `InlineCode` (function, line 38)
  - `CodeBlock` (function, line 47)
  - `HorizontalRule` (function, line 74)
  - `Callout` (function, line 81)
- Depends on: `admin/inertia/components/markdoc/Heading.tsx`, `admin/inertia/components/markdoc/Image.tsx`, `admin/inertia/components/markdoc/List.tsx`, `admin/inertia/components/markdoc/ListItem.tsx`, `admin/inertia/components/markdoc/Table.tsx`

## admin/inertia/components/ProgressBar.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `ProgressBar` (function, line 1)

## admin/inertia/components/StorageProjectionBar.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `StorageProjectionBar` (function, line 11)
  - `currentPercent` (function, line 17)
  - `projectedPercent` (function, line 18)
  - `projectedTotalPercent` (function, line 19)
  - `getProjectedColor` (function, line 24)
  - `getProjectedGlow` (function, line 31)
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/StyledButton.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `getIconSize` (function, line 30)
  - `getSizeClasses` (function, line 41)
  - `getVariantClasses` (function, line 52)
  - `getLoadingSpinner` (function, line 131)
  - `onClickHandler` (function, line 140)

## admin/inertia/components/StyledModal.tsx
- Layer: presentation
- Language: tsx
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/StyledSectionHeader.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `StyledSectionHeader` (function, line 10)

## admin/inertia/components/StyledSidebar.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `ListItem` (function, line 34)
  - `content` (function, line 41)
  - `Sidebar` (function, line 62)
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/StyledTable.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `StyledTable` (function, line 33)
  - `isRowExpanded` (function, line 59)
  - `toggleRowExpansion` (function, line 64)
- Depends on: `admin/inertia/lib/classNames.ts`

## admin/inertia/components/ThemeToggle.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `ThemeToggle` (function, line 8)
- Depends on: `admin/inertia/providers/ThemeProvider.tsx`

## admin/inertia/components/TierSelectionModal.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `resourceFilename` (function, line 21)
  - `getAllResourcesForTier` (function, line 55)
  - `getTierTotalSize` (function, line 116)
  - `handleTierClick` (function, line 120)
  - `finalizeSubmit` (function, line 134)
  - `handleSubmit` (function, line 143)
- Depends on: `admin/inertia/hooks/useDiskDisplayData.ts`, `admin/inertia/hooks/useSystemInfo.ts`, `admin/inertia/lib/classNames.ts`, `admin/inertia/lib/kb_guardrail.ts`

## admin/inertia/components/UpdateServiceModal.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `UpdateServiceModal` (function, line 17)
  - `loadVersions` (function, line 30)
  - `handleToggleAdvanced` (function, line 45)
- Depends on: `admin/app/utils/version.ts`, `admin/types/services.ts`

## admin/inertia/components/WikipediaSelector.tsx
- Layer: presentation
- Language: tsx
- Depends on: `admin/inertia/lib/classNames.ts`
