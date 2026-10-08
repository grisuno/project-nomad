# admin/inertia/components: TierSelectionModal

*Community 5 | 13 files | cohesion 0.60*

## Definition

This community groups 13 file(s) rooted at `admin/inertia/components` with dominant language tsx (cohesion 0.60). Central symbols: `Footer`, `ListItem`, `SettingsPage`, `Sidebar`, `ThemeProvider`, `ThemeToggle`, `content`, `environment`. Core file: `admin/inertia/components/TierSelectionModal.tsx` (6 symbols). Documented purpose: <reference path="../../adonisrc.ts" /> <reference path="../../config/inertia.ts" />.

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/app/app.tsx` | tsx | presentation | 1 | yes |
| `admin/inertia/components/Footer.tsx` | tsx | presentation | 1 | no |
| `admin/inertia/components/StyledSidebar.tsx` | tsx | presentation | 3 | no |
| `admin/inertia/components/ThemeToggle.tsx` | tsx | presentation | 1 | no |
| `admin/inertia/components/TierSelectionModal.tsx` | tsx | presentation | 6 | no |
| `admin/inertia/hooks/useDiskDisplayData.ts` | ts | data_access | 2 | no |
| `admin/inertia/hooks/useSystemInfo.ts` | ts | utility | 1 | no |
| `admin/inertia/hooks/useTheme.ts` | ts | presentation | 2 | no |
| `admin/inertia/lib/kb_guardrail.ts` | ts | utility | 1 | no |
| `admin/inertia/pages/settings/system.tsx` | tsx | presentation | 3 | no |
| `admin/inertia/providers/ThemeProvider.tsx` | tsx | presentation | 2 | no |
| `admin/tests/unit/kb_guardrail.spec.ts` | ts | testing | 0 | no |
| `admin/types/system.ts` | ts | utility | 0 | no |

## Key Symbols

- `environment` (function, `admin/inertia/app/app.tsx:38`)
- `Footer` (function, `admin/inertia/components/Footer.tsx:8`)
- `ListItem` (function, `admin/inertia/components/StyledSidebar.tsx:34`)
- `content` (function, `admin/inertia/components/StyledSidebar.tsx:41`)
- `Sidebar` (function, `admin/inertia/components/StyledSidebar.tsx:62`)
- `ThemeToggle` (function, `admin/inertia/components/ThemeToggle.tsx:8`)
- `resourceFilename` (function, `admin/inertia/components/TierSelectionModal.tsx:21`)
- `getAllResourcesForTier` (function, `admin/inertia/components/TierSelectionModal.tsx:55`) - Get all resources for a tier (including inherited resources). Defined as a hook-safe closure (always
- `getTierTotalSize` (function, `admin/inertia/components/TierSelectionModal.tsx:116`)
- `handleTierClick` (function, `admin/inertia/components/TierSelectionModal.tsx:120`)
- `finalizeSubmit` (function, `admin/inertia/components/TierSelectionModal.tsx:134`) - Runs the original onSelectTier-then-onClose flow. Pulled out of handleSubmit so the guardrail modal'
- `handleSubmit` (function, `admin/inertia/components/TierSelectionModal.tsx:143`)
- `getAllDiskDisplayItems` (function, `admin/inertia/hooks/useDiskDisplayData.ts:16`) - import { Systeminformation } from 'systeminformation' import { formatBytes } from '~/lib/util' type
- `getPrimaryDiskInfo` (function, `admin/inertia/hooks/useDiskDisplayData.ts:88`) - value: fs.use \|\| 0, total: formatBytes(fs.size), used: formatBytes(fs.used), subtext: `${formatBytes
- `useSystemInfo` (function, `admin/inertia/hooks/useSystemInfo.ts:10`)
- `getInitialTheme` (function, `admin/inertia/hooks/useTheme.ts:7`)
- `useTheme` (function, `admin/inertia/hooks/useTheme.ts:16`)
- `evaluateGuardrail` (function, `admin/inertia/lib/kb_guardrail.ts:47`) - Decide whether a bulk indexing action should be gated behind the guardrail modal. Caller passes the
- `SettingsPage` (function, `admin/inertia/pages/settings/system.tsx:19`)
- `handleDismissGpuBanner` (function, `admin/inertia/pages/settings/system.tsx:37`)
- `handleForceReinstallOllama` (function, `admin/inertia/pages/settings/system.tsx:44`)
- `ThemeProvider` (function, `admin/inertia/providers/ThemeProvider.tsx:16`)
- `useThemeContext` (function, `admin/inertia/providers/ThemeProvider.tsx:25`)

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 18
- Cross-boundary resolved imports (EXTRACTED): 13

## Connections

- [EXTRACTED] depends_on community 5 <-> 4 (strength 0.9): Extracted import edge crosses communities: admin/inertia/components/StyledSidebar.tsx imports admin/inertia/lib/classNames.ts.

## Risks

- [layer strict] `admin/inertia/components/TierSelectionModal.tsx` (presentation) -> `admin/inertia/hooks/useDiskDisplayData.ts` (data_access)
- [layer strict] `admin/inertia/pages/easy-setup/index.tsx` (presentation) -> `admin/inertia/hooks/useDiskDisplayData.ts` (data_access)
- [layer strict] `admin/inertia/pages/settings/system.tsx` (presentation) -> `admin/inertia/hooks/useDiskDisplayData.ts` (data_access)

## Open Questions

- Why do 12 file(s) lack file-level docs (e.g. `admin/inertia/components/Footer.tsx`)? What purpose do they serve?
- What would break if the most connected file in admin/inertia/components: TierSelectionModal changed?
- Should admin/inertia/components: TierSelectionModal be split, given cohesion 0.60?

## Sources

- `admin/inertia/app/app.tsx`
- `admin/inertia/components/Footer.tsx`
- `admin/inertia/components/StyledSidebar.tsx`
- `admin/inertia/components/ThemeToggle.tsx`
- `admin/inertia/components/TierSelectionModal.tsx`
- `admin/inertia/hooks/useDiskDisplayData.ts`
- `admin/inertia/hooks/useSystemInfo.ts`
- `admin/inertia/hooks/useTheme.ts`
- `admin/inertia/lib/kb_guardrail.ts`
- `admin/inertia/pages/settings/system.tsx`
- `admin/inertia/providers/ThemeProvider.tsx`
- `admin/tests/unit/kb_guardrail.spec.ts`
- `admin/types/system.ts`
