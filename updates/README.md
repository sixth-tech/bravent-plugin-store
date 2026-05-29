# Updates Directory

Contains the auto-update manifest used by Bravent Hub to check for new plugin versions.

## manifest.json

This file lists all available plugins with their:

- `uuid` - Plugin UUID
- `name` - Display name
- `version` - Latest version
- `download_url` - Where to download the .sdPlugin.zip
- `sha256` - Integrity checksum
- `min_hub_version` - Minimum Bravent Hub version required
- `changelog` - What's new in this version

## Note for Developers

When releasing a new plugin version:

1. Upload the .sdPlugin.zip to `plugins/` or as a GitHub Release
2. Update `manifest.json` with the new version info
3. Tag the release in GitHub

The Bravent Hub will automatically detect and prompt users to update.