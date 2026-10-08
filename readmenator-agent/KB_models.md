# Subsystem: models

## admin/app/models/benchmark_result.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `BenchmarkResult` (class, line 5)

## admin/app/models/benchmark_setting.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `BenchmarkSetting` (class, line 5)

## admin/app/models/chat_message.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `ChatMessage` (class, line 6)

## admin/app/models/chat_session.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `ChatSession` (class, line 6)

## admin/app/models/collection_manifest.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `CollectionManifest` (class, line 5)

## admin/app/models/custom_library_source.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `CustomLibrarySource` (class, line 4)

## admin/app/models/installed_resource.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `InstalledResource` (class, line 4)

## admin/app/models/kb_ingest_state.ts
- Doc: KbIngestState: Tracks the per-file decision and outcome of AI knowledge-base ingestion.
- Layer: business_logic
- Language: ts
- Symbols:
  - `KbIngestState` (class, line 15)

## admin/app/models/kb_ratio_registry.ts
- Doc: KbRatioRegistry: Self-calibrating registry of `{filename-prefix → chunks_per_mb}` ratios used...
- Layer: business_logic
- Language: ts
- Symbols:
  - `KbRatioRegistry` (class, line 21)
- Depends on: `admin/app/utils/kb_ratio_lookup.ts`

## admin/app/models/kv_store.ts
- Doc: KVStore: Generic key-value store model for storing various settings that don't necessitate their...
- Layer: business_logic
- Language: ts
- Symbols:
  - `KVStore` (class, line 10)

## admin/app/models/map_marker.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `MapMarker` (class, line 4)

## admin/app/models/service.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `Service` (class, line 5)
- Imported by: `admin/app/jobs/check_service_updates_job.ts`

## admin/app/models/wikipedia_selection.ts
- Layer: business_logic
- Language: ts
- Symbols:
  - `WikipediaSelection` (class, line 4)
