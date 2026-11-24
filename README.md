# Landnod QGIS plugin repository

Public distribution catalogue for independent Landnod plugins for QGIS 4.
Plugin sources remain in separate repositories. This repository contains release metadata and immutable ZIP assets.

In QGIS open **Plugins → Manage and Install Plugins → Settings → Plugin Repositories → Add**:

```text
Name: Landnod
URL: https://landnod-dev.github.io/landnod-qgis-plugin-repository/plugins.xml
```

Plugin identities: Landnod Analyze Terrain, Landnod Share Layer Styles, Landnod Focus Filter,
Landnod Plotline, Landnod Polygonizer and Landnod Pricing and Planning.
All use the Landnod menu and toolbar. The interface is Slovak and prepared for Qt localization;
plugin and menu identities are English.

Releases contain no passwords, tokens, database dumps, working projects or user settings.
Configure your own connection through QGIS Authentication Manager and protect its encrypted local database with a master password.
Some functions require the corresponding Landnod PostgreSQL tables and permissions; installation never provisions database access.

Only uploaded, checksum-verified packages are listed. Releases are manual and versioned per plugin.
See [structure](docs/structure.md) and [current status](CURRENT.md). Updates are offered through QGIS, not installed unattended.
