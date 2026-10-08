# Recipe: Reduce File Complexity

Target hotspot: `admin/inertia/pages/easy-setup/index.tsx`
(complexity 1.0, centrality 0.5)

1. Read dependents: `grep -n 'admin/inertia/pages/easy-setup/index.tsx' readmenator-agent/ARCHITECTURE*.md`
2. Extract functions/classes into new files in the same subsystem
3. Update imports
4. Regenerate: `readmenator .`
