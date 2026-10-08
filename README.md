# StockFlow Automator — Production downloads

This repository contains **public Production version records and approved installers**. It contains no application source, Test builds, business data or backup versions.

**Current Production version record: v3.4.11**, recorded on 2026-10-08. See [the record](records/production-v3.4.11.json) and [record release](https://github.com/Shiv110599/Stock-Flow-Automator-Releases/releases/tag/record-production-v3.4.11). No installer was supplied or published with this record. Recording a version does not change installed applications. A first updater-enabled installer will require a one-time installation; subsequent approved versions can display an update notification in the application.

When a release is available, download its signed `StockFlow-production-<version>-Setup.exe` from [Releases](https://github.com/Shiv110599/Stock-Flow-Automator-Releases/releases). Verify the publisher shown by Windows and install using the same Windows account. Updates preserve application settings and reports.

`channels/production.json` is the Production update feed. Only published, approved Production packages are advertised. Source commits and Test releases do not trigger updates for users. Earlier approved installers remain in Releases for support and controlled recovery.

Update address for the checker's `UPDATE_MANIFEST_URL`:

```text
https://raw.githubusercontent.com/Shiv110599/Stock-Flow-Automator-Releases/main/channels/production.json
```

The feed supports the existing checker's `latest_version`, `download_url`, and `release_notes` fields. The feed records `current_production_version: 3.4.11` and `status: not-published`. Until a real approved installer exists, compatibility `latest_version` remains v3.4.8 so older clients cannot offer a nonexistent upgrade. Existing EXEs with an empty compiled address need a one-time rebuilt installation to connect.

Metadata-only records use `record-production-vX.Y.Z` tags; downloadable installer releases use `production-vX.Y.Z`. A version record does not reserve or advertise an installer.
