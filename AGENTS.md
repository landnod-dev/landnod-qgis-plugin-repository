# Distribution catalogue instructions

Read CURRENT.md. This is a public catalogue, not a monorepo of plugin sources.
The user activated publication on 2026-11-24. Keep source repositories independent.

- Publish one explicit plugin using the shared landnod-automation/scripts/qgis_plugins.py publish command.
- Upload and verify its immutable ZIP before updating catalog/plugins.json and docs/plugins.xml.
- Preserve all other plugin entries. Never overwrite released versions or force-push conflicts.
- Audit all reachable Git history before changing visibility from private to public.
- Never commit credentials, local configuration, profiles, backups or live data.
- GitHub Pages serves main:/docs; ZIPs are attached to GitHub Releases.
- No coding agents, unattended releases or unsolicited changes to source plugins.
