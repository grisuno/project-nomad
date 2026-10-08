# Subsystem: providers

## admin/providers/gpu_passthrough_remediation_provider.ts
- Doc: GpuPassthroughRemediationProvider: the container is torn.
- Layer: infrastructure
- Language: ts
- Symbols:
  - `KVStore` (function, line 31)
  - `Docker` (function, line 34)
  - `GpuPassthroughRemediationProvider` (class, line 23)

## admin/providers/kiwix_migration_provider.ts
- Doc: KiwixMigrationProvider: Checks whether the installed kiwix container is still using the legacy...
- Layer: data_access
- Language: ts
- Symbols:
  - `Service` (function, line 22)
  - `KiwixMigrationProvider` (class, line 12)

## admin/providers/map_static_provider.ts
- Doc: MapStaticProvider: This is a bit of a hack to serve static files from the /storage/maps...
- Layer: infrastructure
- Language: ts
- Symbols:
  - `MapStaticProvider` (class, line 16)
- Depends on: `admin/config/static.ts`

## admin/providers/qdrant_restart_policy_provider.ts
- Doc: QdrantRestartPolicyProvider: Ensures the nomad_qdrant container has the `unless-stopped` restart...
- Layer: presentation
- Language: ts
- Symbols:
  - `Service` (function, line 22)
  - `Docker` (function, line 24)
  - `QdrantRestartPolicyProvider` (class, line 14)
- Depends on: `admin/inertia/pages/settings/update.tsx`

## admin/providers/version_check_provider.ts
- Doc: VersionCheckProvider: carries pre-update values for `system.updateAvailable` and...
- Layer: infrastructure
- Language: ts
- Symbols:
  - `KVStore` (function, line 30)
  - `cachedLatest` (function, line 42)
  - `earlyAccess` (function, line 43)
  - `VersionCheckProvider` (class, line 22)
