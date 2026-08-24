# FileShare downloads

This repository is the public, generated distribution surface for FileShare.
It contains only Developer ID signed and Apple-notarized release artifacts,
the public download page, checksums, and the signed Tauri updater feed.

Application source code and release credentials are kept in the private
`guanxiong/fileshare-desktop` repository. Do not edit generated release files
here by hand; the private release workflow replaces the site atomically.

Public endpoints:

- `/downloads/FileShare.dmg`
- `/updates/latest.json`
- `/updates/FileShare.app.tar.gz`
- `/health.json`
- `/version.json`
