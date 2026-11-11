# Changelog

## 5.1 — 2026-11-11

### EPG Centre
- Load multiple XMLTV guides from URLs and local XML, GZ, XZ and ZIP files; damaged sources are reported while other sources continue loading, and long loads can be cancelled.
- Coverage dashboard with totals, category/source breakdowns and guide horizon.
- Channel statuses for matched, guide ending soon, expired, no programmes, ID not in guide, missing `tvg-id` and duplicate IDs.
- Local-time Now / Next with channel time shift applied.
- Suggested IDs require approval; editable `tvg-id`, bulk metadata edit with preview and Undo.
- Manual EPG corrections persist through Refresh, re-import and Xtream / Stalker updates and can be reviewed, edited, disabled or removed.

### Stream scanner
- Statuses: Responsive, Dead, Unreachable, Restricted, Stale, Unavailable, Unverified and Error.
- Timeouts and blocked requests are not automatically labelled Dead.
- Pause, resume and cancel; per-server limits, timeouts, retries and player identity.
- HLS freshness, optional deep diagnostics, selected/category/current-view scans.
- Persistent Good / Bad / Review verdicts, notes and scan history; Excel and JSON export.

### Providers and security
- Background Xtream and Stalker / MAC login and imports with cancellation.
- Xtream M3U fallback and undoable Stalker imports.
- Remembered provider credentials protected with Windows DPAPI, not stored in plain text.

### Editing, saving and playback
- UTF-8 save without BOM by default, preserving playlist directives, comments and unknown header keys.
- Safer backup handling, credential masking and malformed-line import repair.
- Alt+Right / Alt+Left channel navigation, player buffering setting and single-instance operation.

### Release assets
- [Playlist-Studio-5.1.exe](https://github.com/saeidrahmanbd/Playlist-Studio/releases/download/v5.1/Playlist-Studio-5.1.exe) — portable Windows x64 application.
- [Playlist-Studio-5_1-Windows-Build-Kit-r2.zip](https://github.com/saeidrahmanbd/Playlist-Studio/releases/download/v5.1/Playlist-Studio-5_1-Windows-Build-Kit-r2.zip) — Windows build kit.

[View the official v5.1 release](https://github.com/saeidrahmanbd/Playlist-Studio/releases/tag/v5.1).

---

## 5.0.0 — 2026-10 (historical)

- Published Playlist Studio as a standalone Windows application.
- M3U / M3U8 playlists, Xtream Codes and Stalker Portal / MAC services.
- Built-in playback and stream scanning.
- EPG, channel metadata, logo and category management.
- Duplicate channel and stream detection; multi-channel and multi-category selection.
- GitHub integration, Save / Save As and multiple interface themes.
- Published portable Windows executable and Windows Build Kit.

The v5.0 release and its older Build Kit are historical. Use the [v5.1 release](https://github.com/saeidrahmanbd/Playlist-Studio/releases/tag/v5.1) for current downloads.

## Build Kit r2 — 2026-11-11

- Reworked Windows build process for explicit Python compatibility and isolated `.venv-build` environment.
- Supported base Python versions: 3.10–3.13, 64-bit; Python 3.13 recommended.
- Python 3.14 / 3.15 are not supported by the currently pinned PyInstaller dependency set.
- Added `PS_PYTHON` override for selecting a specific interpreter without the Python Launcher.
- Added `--fresh` to recreate the build environment, clearer dependency diagnostics and complete `BUILD-LOG.txt` output.
- Build kit documentation clarifies that Python Launcher is recommended but optional.
