# Distribution structure

- catalog/plugins.json: one entry per published plugin, source SHA, version and ZIP SHA256.
- docs/plugins.xml: generated QGIS index served by GitHub Pages from main:/docs.
- docs/index.html: installation instructions and catalogue link.
- GitHub Releases: immutable, versioned ZIPs, uploaded and verified before XML publication.

Runtime source is developed in six independent repositories, each with its own manifest, tests and local commit hook.
Shared tools live in landnod-automation. Source repositories remain private; released Python code is publicly readable in ZIPs.

ZIPs contain runtime Python, icons, required static JSON, metadata and translation catalogues.
Tests, SQL, standalone updater utilities, private inputs, databases, caches and old archives are excluded.
First releases are checked on Linux with QGIS 4.4 and Qt 6; no other platform is claimed as tested.
