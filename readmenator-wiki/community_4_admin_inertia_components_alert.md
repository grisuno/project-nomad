# admin/inertia/components: Alert

*Community 4 | 18 files | cohesion 0.68*

## Definition

This community groups 18 file(s) rooted at `admin/inertia/components` with dominant language tsx (cohesion 0.68). Central symbols: `Alert`, `Chat`, `ChatInterface`, `ChatMessageBubble`, `ChatSidebar`, `CircularGauge`, `HorizontalBarChart`, `InfoCard`. Core file: `admin/inertia/components/Alert.tsx` (7 symbols).

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/constants/ollama.ts` | ts | utility | 0 | no |
| `admin/inertia/components/Alert.tsx` | tsx | presentation | 7 | no |
| `admin/inertia/components/CountryPickerModal.tsx` | tsx | presentation | 5 | no |
| `admin/inertia/components/DynamicIcon.tsx` | tsx | presentation | 0 | no |
| `admin/inertia/components/HorizontalBarChart.tsx` | tsx | presentation | 5 | no |
| `admin/inertia/components/StorageProjectionBar.tsx` | tsx | presentation | 6 | no |
| `admin/inertia/components/StyledModal.tsx` | tsx | presentation | 0 | no |
| `admin/inertia/components/StyledTable.tsx` | tsx | presentation | 3 | no |
| `admin/inertia/components/chat/ChatInterface.tsx` | tsx | presentation | 6 | no |
| `admin/inertia/components/chat/ChatMessageBubble.tsx` | tsx | presentation | 1 | no |
| `admin/inertia/components/chat/ChatSidebar.tsx` | tsx | presentation | 2 | no |
| `admin/inertia/components/chat/index.tsx` | tsx | presentation | 1 | no |
| `admin/inertia/components/inputs/Input.tsx` | tsx | presentation | 0 | no |
| `admin/inertia/components/systeminfo/CircularGauge.tsx` | tsx | presentation | 3 | no |
| `admin/inertia/components/systeminfo/InfoCard.tsx` | tsx | presentation | 2 | no |
| `admin/inertia/lib/classNames.ts` | ts | utility | 1 | no |
| `admin/inertia/lib/icons.ts` | ts | presentation | 0 | no |
| `admin/types/chat.ts` | ts | utility | 0 | no |

## Key Symbols

- `Alert` (function, `admin/inertia/components/Alert.tsx:17`)
- `getDefaultIcon` (function, `admin/inertia/components/Alert.tsx:29`)
- `getIconColor` (function, `admin/inertia/components/Alert.tsx:44`)
- `getVariantStyles` (function, `admin/inertia/components/Alert.tsx:60`)
- `getTitleColor` (function, `admin/inertia/components/Alert.tsx:113`)
- `getMessageColor` (function, `admin/inertia/components/Alert.tsx:132`)
- `getCloseButtonStyles` (function, `admin/inertia/components/Alert.tsx:149`)
- `toggleCountry` (function, `admin/inertia/components/CountryPickerModal.tsx:100`)
- `toggleGroup` (function, `admin/inertia/components/CountryPickerModal.tsx:109`)
- `clearAll` (function, `admin/inertia/components/CountryPickerModal.tsx:122`)
- `startDownload` (function, `admin/inertia/components/CountryPickerModal.tsx:164`)
- `PreflightStatus` (function, `admin/inertia/components/CountryPickerModal.tsx:392`)
- `HorizontalBarChart` (function, `admin/inertia/components/HorizontalBarChart.tsx:19`)
- `getBarColor` (function, `admin/inertia/components/HorizontalBarChart.tsx:26`)
- `getGlowColor` (function, `admin/inertia/components/HorizontalBarChart.tsx:34`)
- `getStatusLabel` (function, `admin/inertia/components/HorizontalBarChart.tsx:41`)
- `getStatusColor` (function, `admin/inertia/components/HorizontalBarChart.tsx:51`)
- `StorageProjectionBar` (function, `admin/inertia/components/StorageProjectionBar.tsx:11`)
- `currentPercent` (function, `admin/inertia/components/StorageProjectionBar.tsx:17`)
- `projectedPercent` (function, `admin/inertia/components/StorageProjectionBar.tsx:18`)
- `projectedTotalPercent` (function, `admin/inertia/components/StorageProjectionBar.tsx:19`)
- `getProjectedColor` (function, `admin/inertia/components/StorageProjectionBar.tsx:24`) - Determine warning level based on projected total
- `getProjectedGlow` (function, `admin/inertia/components/StorageProjectionBar.tsx:31`)
- `StyledTable` (function, `admin/inertia/components/StyledTable.tsx:33`)
- `isRowExpanded` (function, `admin/inertia/components/StyledTable.tsx:59`)
- `toggleRowExpansion` (function, `admin/inertia/components/StyledTable.tsx:64`)
- `ChatInterface` (function, `admin/inertia/components/chat/ChatInterface.tsx:24`)
- `handleDownloadModel` (function, `admin/inertia/components/chat/ChatInterface.tsx:41`)
- `scrollToBottom` (function, `admin/inertia/components/chat/ChatInterface.tsx:54`)
- `handleSubmit` (function, `admin/inertia/components/chat/ChatInterface.tsx:62`)

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 49
- Cross-boundary resolved imports (EXTRACTED): 30

## Connections

- [EXTRACTED] depends_on community 4 <-> 1 (strength 0.9): Extracted import edge crosses communities: admin/inertia/components/CountryPickerModal.tsx imports admin/constants/map_regions.ts.
- [EXTRACTED] depends_on community 6 <-> 4 (strength 0.9): Extracted import edge crosses communities: admin/inertia/components/InstallActivityFeed.tsx imports admin/inertia/lib/classNames.ts.
- [EXTRACTED] depends_on community 5 <-> 4 (strength 0.9): Extracted import edge crosses communities: admin/inertia/components/StyledSidebar.tsx imports admin/inertia/lib/classNames.ts.
- [EXTRACTED] depends_on community 0 <-> 4 (strength 0.9): Extracted import edge crosses communities: admin/inertia/components/WikipediaSelector.tsx imports admin/inertia/lib/classNames.ts.
- [EXTRACTED] depends_on community 4 <-> 7 (strength 0.9): Extracted import edge crosses communities: admin/inertia/components/chat/index.tsx imports admin/inertia/hooks/useSystemSetting.ts.

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- Why do 18 file(s) lack file-level docs (e.g. `admin/constants/ollama.ts`)? What purpose do they serve?
- What would break if the most connected file in admin/inertia/components: Alert changed?
- Should admin/inertia/components: Alert be split, given cohesion 0.68?

## Sources

- `admin/constants/ollama.ts`
- `admin/inertia/components/Alert.tsx`
- `admin/inertia/components/CountryPickerModal.tsx`
- `admin/inertia/components/DynamicIcon.tsx`
- `admin/inertia/components/HorizontalBarChart.tsx`
- `admin/inertia/components/StorageProjectionBar.tsx`
- `admin/inertia/components/StyledModal.tsx`
- `admin/inertia/components/StyledTable.tsx`
- `admin/inertia/components/chat/ChatInterface.tsx`
- `admin/inertia/components/chat/ChatMessageBubble.tsx`
- `admin/inertia/components/chat/ChatSidebar.tsx`
- `admin/inertia/components/chat/index.tsx`
- `admin/inertia/components/inputs/Input.tsx`
- `admin/inertia/components/systeminfo/CircularGauge.tsx`
- `admin/inertia/components/systeminfo/InfoCard.tsx`
- `admin/inertia/lib/classNames.ts`
- `admin/inertia/lib/icons.ts`
- `admin/types/chat.ts`
