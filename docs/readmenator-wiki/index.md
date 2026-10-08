# Second Brain

*Last synthesized: 2026-10-07 | 294 files | 17 concept pages | offline, zero tokens*

> Raw sources -> readmenator wiki -> links (Karpathy LLM Wiki Pattern, deterministic).
> Start here, then open one community page. Prefer grep over full reads.

## Vault Overview

The codebase centres on `classNames.ts`, `docker_service.ts`, `service_names.ts`. Architecturally it is 6 layers, dominant presentation (112 files) across 17 import-based communities. Recorded risk surface: 0 security findings and 5 dependency cycles.

Surprising tissue lives between admin/types, admin/app/services: fs, admin/app/services: ollama_service: 20 extracted cross-community imports and 0 inferred bridges. Follow `connections.json` sorted by strength before refactoring.

Open work clusters around documentation (4% file coverage), 0 security findings, 0 taint paths, and 5 suggested exploration questions in `queries.md`.

## Stats

| Metric | Value |
|--------|-------|
| Files | 294 |
| Symbols | 563 |
| Resolved imports | 422 |
| Languages | js, sh, ts, tsx |
| Communities | 17 |
| Doc coverage | 4% (13/294 files) |
| Security findings | 0 |
| Estimated read cost | ~10674 tokens (chars/4, offline so $0) |

## Reading Order

1. Skim Stats and God Nodes below for blast radius.
2. Open the largest community page first, then follow Connections.
3. Use `queries.md` for the next question; log the answer there.

```
grep -rn '<keyword>' index.md community_*.md
readmenator query "<question>" --target readmenator_project-nomad_zbxlyvee
```

## Concept Wiki

- [admin/types (30 files, cohesion 0.62)](./community_0_admin_types.md)
- [admin/app/services: fs (26 files, cohesion 0.56)](./community_1_admin_app_services_fs.md)
- [admin/app/services: ollama_service (23 files, cohesion 0.45)](./community_2_admin_app_services_ollama_service.md)
- [admin/app/services: container_registry_service (18 files, cohesion 0.45)](./community_3_admin_app_services_container_registry_service.md)
- [admin/inertia/components: Alert (18 files, cohesion 0.68)](./community_4_admin_inertia_components_alert.md)
- [admin/inertia/components: TierSelectionModal (13 files, cohesion 0.60)](./community_5_admin_inertia_components_tierselectionmodal.md)
- [admin/inertia/pages/settings (11 files, cohesion 0.32)](./community_6_admin_inertia_pages_settings.md)
- [admin/database/migrations (9 files, cohesion 0.35)](./community_7_admin_database_migrations.md)
- [admin/inertia/components/chat (7 files, cohesion 0.50)](./community_8_admin_inertia_components_chat.md)
- [admin/inertia/components/markdoc (6 files, cohesion 1.00)](./community_9_admin_inertia_components_markdoc.md)
- [admin/inertia/components: useEmbedJobs (5 files, cohesion 1.00)](./community_10_admin_inertia_components_useembedjobs.md)
- [admin/app/models (3 files, cohesion 1.00)](./community_11_admin_app_models.md)
- [admin/inertia/components/maps (3 files, cohesion 1.00)](./community_12_admin_inertia_components_maps.md)
- [admin/app/middleware (2 files, cohesion 1.00)](./community_13_admin_app_middleware.md)
- [admin/providers (2 files, cohesion 1.00)](./community_14_admin_providers.md)
- [admin/config (2 files, cohesion 1.00)](./community_15_admin_config.md)
- [orphans (116 files, cohesion 0.00)](./community_16_orphans.md)

## God Nodes

| File | Score |
|------|-------|
| `admin/inertia/lib/classNames.ts` | 40.1 |
| `admin/app/services/docker_service.ts` | 36.5 |
| `admin/constants/service_names.ts` | 36.0 |
| `admin/inertia/pages/settings/update.tsx` | 34.9 |
| `admin/app/utils/fs.ts` | 31.5 |

## Strongest Connections

- 3 -> 8: depends_on (strength 0.9, EXTRACTED)
- 3 -> 6: depends_on (strength 0.9, EXTRACTED)
- 2 -> 8: depends_on (strength 0.9, EXTRACTED)
- 2 -> 7: depends_on (strength 0.9, EXTRACTED)
- 1 -> 2: depends_on (strength 0.9, EXTRACTED)
- 1 -> 6: depends_on (strength 0.9, EXTRACTED)
- 2 -> 3: depends_on (strength 0.9, EXTRACTED)
- 6 -> 2: depends_on (strength 0.9, EXTRACTED)
- 6 -> 0: depends_on (strength 0.9, EXTRACTED)
- 6 -> 7: depends_on (strength 0.9, EXTRACTED)

## Navigation Tips

- Obsidian Graph View works: every community page links back here.
- `connections.json` is machine-readable for GraphRAG pipelines.
- `REPORT.md` states what was extracted vs inferred and current limits.
- Regenerate offline: `readmenator . --rebuild` (no network, no tokens).
