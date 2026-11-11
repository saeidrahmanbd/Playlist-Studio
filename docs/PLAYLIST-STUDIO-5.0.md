# Playlist Studio — User Guide (v5.1)

This guide describes the main workflows and the v5.1 additions. For the official feature list, downloads and build instructions, see the [root README](../README.md) and the [v5.1 release](https://github.com/saeidrahmanbd/Playlist-Studio/releases/tag/v5.1).

## 1. Open or import a playlist

- Open one or more `.m3u` or `.m3u8` files.
- Drag a playlist file onto the application window.
- Use **Import URL** to download a playlist link.
- Connect through a compatible Xtream Codes account or Stalker Portal / MAC login.

When importing into a non-empty playlist, choose **Append** to add the imported channels or **Replace** to replace the current list.

## 2. Organize and edit

Select a category and channel to edit channel name, group, stream URL, logo, EPG fields and playback directives. You can add, duplicate, delete, move and reorder channels; add, rename, delete and reorder categories; and select multiple categories with Ctrl/Shift-click.

Use Search to find channels. Sort a category A–Z when needed. Undo / Redo covers recent changes.

## 3. EPG Centre (new in 5.1)

Open **Settings > EPG centre** or use the EPG button.

- Load XMLTV guides from URLs or local `.xml`, `.gz`, `.xz` and `.zip` files.
- Load multiple sources; a damaged source is reported while other sources continue to load.
- Cancel a long-running guide load.
- Review coverage totals, category/source breakdowns and the guide horizon.
- Inspect per-channel statuses, including matched, guide ending soon, expired, no programmes, ID not in guide, missing `tvg-id` and duplicate IDs.
- See Now / Next with `tvg-shift` applied in your local timezone.
- Suggested IDs are suggestions only; nothing changes until you approve it.
- Edit the visible `tvg-id` column, or use the bulk metadata editor with preview and one-step Undo.
- Manage remembered manual EPG corrections in Settings. Corrections can be reviewed, edited, disabled or removed and are reapplied after refresh and re-import operations.

## 4. Scan streams

Use **Scan** to scan all channels, the selected category or the current view. You can pause, resume or cancel. Per-server limits, timeouts, retries and player identity can be configured. HLS freshness checks and optional deep diagnostics are available.

Statuses include Responsive, Dead, Unreachable, Restricted, Stale, Unavailable, Unverified and Error. A timeout or blocked request is not automatically a Dead result. Your own Good / Bad / Review verdicts and notes are remembered between sessions; a scan does not overwrite your verdict. Export scan results to Excel or JSON.

## 5. Play a channel

Select a channel and start playback in the built-in VLC player. Use the volume, seek, fit/fill/stretch and full-screen controls. Alt+Right / Alt+Left moves to the next or previous channel.

DRM-protected streams or streams that do not respond may show an explanation in the player. A stream that does not start within the configured startup period can be stopped with a Retry hint.

## 6. Xtream Codes and Stalker / MAC

Provider login and imports run in the background and can be cancelled. Xtream can fall back to an M3U download if its API route fails. Stalker imports can be undone, and failed imports leave the existing playlist untouched.

Remembered provider credentials are protected with Windows DPAPI and are not written in plain text. You can mask credentials in the channel list. Only connect to services you are authorized to access.

## 7. Save and recover

- **Save** writes changes to the current playlist.
- **Save As** writes a separate copy.
- Saving is atomic; backups are made before overwriting.
- Autosave and recovery data help restore unsaved changes after a crash.
- UTF-8 without BOM is the default; an optional BOM setting is available.
- Playlist directives, comments and unknown header keys are preserved.

## 8. Settings and data locations

Settings includes General, Themes, Player, Xtream / Stalker, GitHub Integration, Open backups folder and About. The application keeps its settings, backups and recovery files under `%APPDATA%\Playlist Studio 5.0\` for compatibility with existing 5.0 data. The first-start diagnostic log is under `%TEMP%\Playlist Studio 5.0-startup.log`.

## Downloads

- [Playlist Studio 5.1 portable EXE](https://github.com/saeidrahmanbd/Playlist-Studio/releases/download/v5.1/Playlist-Studio-5.1.exe)
- [Windows Build Kit r2](https://github.com/saeidrahmanbd/Playlist-Studio/releases/download/v5.1/Playlist-Studio-5_1-Windows-Build-Kit-r2.zip)
- [Official v5.1 release page](https://github.com/saeidrahmanbd/Playlist-Studio/releases/tag/v5.1)
