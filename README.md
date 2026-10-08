# StockFlow Automator — Production downloads

**Current version: v3.4.11.** Download the full [Windows x64 portable application](https://github.com/Shiv110599/Stock-Flow-Automator-Releases/releases/tag/portable-production-v3.4.11). Displayed publisher: **Shivam**. The application is **unsigned**; **automatic installation is disabled**.

1. Download `StockFlow-production-3.4.11-windows-x64-portable.zip` from the release and verify its SHA-256 using `SHA256SUMS.txt`.
2. Close existing copies, suspend scheduled launches and back up the old app folder and settings.
3. Extract the entire ZIP to a new local folder. Keep `StockFlow Automator.exe` and `_internal` together; read `READ-ME-FIRST.txt`.
4. Run the new app, verify settings/reports, and update shortcuts and scheduled-task paths. Preserve the old folder for recovery. Existing Production settings and reports are retained.

The download includes pinned runtime dependencies (Pillow 12.3.0). Its packaged self-test and isolated launch checks passed. This repository contains public Production metadata and download assets. Application source trees, Test editions, backup versions, credentials, private build records and business data stay private; required third-party runtime files accompany the EXE.

## Existing update URL

```text
https://raw.githubusercontent.com/Shiv110599/Stock-Flow-Automator-Releases/main/channels/production.json
```

The feed lists `latest_version: 3.4.11` and points `download_url` to the manual release page. Compatible older native clients can offer the update and open that page in a browser. It never downloads/executes the standalone EXE as an installer. Apps already on v3.4.11 have no newer version to offer. Old EXEs with no configured URL require this first manual installation.

Trusted automatic installation requires a code-signing certificate, a tested signed installer and initial installation of an updater-enabled package. It remains disabled here. Source commits and private Test releases do not deploy anything to users' systems.

The [machine-readable version record](records/production-v3.4.11.json) links the published portable download. Portable tags use `portable-production-vX.Y.Z`; metadata-only tags use `record-production-vX.Y.Z`; future signed installers use `production-vX.Y.Z`. These tags retain separate records without duplicating private backup folders.
