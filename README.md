<h1 align="center">🎬 Playlist Studio 5.1</h1>

<p align="center"><b>Windows IPTV Playlist Manager · M3U/M3U8 Editor · XMLTV EPG Tool · Stream Scanner · Player</b><br>Portable Windows application · No installer · No Python or separate VLC installation required to run</p>

<p align="center"><a href="https://github.com/saeidrahmanbd/Playlist-Studio/releases/download/v5.1/Playlist-Studio-5.1.exe"><img src="https://img.shields.io/badge/⬇%20DOWNLOAD%20PLAYLIST%20STUDIO%205.1-2ea44f?style=for-the-badge" alt="Download Playlist Studio 5.1 for Windows"></a></p>

<p align="center">
<a href="https://github.com/saeidrahmanbd/Playlist-Studio/releases/tag/v5.1"><img src="https://img.shields.io/github/v/release/saeidrahmanbd/Playlist-Studio?style=for-the-badge&logo=github&label=Release&color=0969da" alt="Latest release"></a>
<a href="https://github.com/saeidrahmanbd/Playlist-Studio/stargazers"><img src="https://img.shields.io/github/stars/saeidrahmanbd/Playlist-Studio?style=for-the-badge&logo=github&color=f5c542" alt="GitHub stars"></a>
<a href="LICENSE"><img src="https://img.shields.io/badge/License-Proprietary-8250df?style=for-the-badge" alt="Proprietary license"></a>
<a href="https://github.com/saeidrahmanbd/Playlist-Studio/commits/main"><img src="https://img.shields.io/github/last-commit/saeidrahmanbd/Playlist-Studio?style=for-the-badge&color=e5534b" alt="Latest update"></a>
</p>

<p align="center">
<img src="https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011-0078D6?style=flat-square&logo=windows&logoColor=white" alt="Windows 10 and 11">
<img src="https://img.shields.io/badge/Formats-M3U%20%2F%20M3U8-6f42c1?style=flat-square" alt="M3U and M3U8">
<img src="https://img.shields.io/badge/EPG-XMLTV-2ea44f?style=flat-square" alt="XMLTV EPG">
<img src="https://img.shields.io/badge/Providers-Xtream%20%2F%20Stalker-00b4d8?style=flat-square" alt="Xtream Codes and Stalker Portal">
</p>

<p align="center"><a href="#overview">Overview</a> · <a href="#features">Features</a> · <a href="#download">Download</a> · <a href="#documentation">Documentation</a> · <a href="docs/FAQ.md">FAQ</a></p>

---

## Overview

Playlist Studio is a portable Windows desktop application for managing, editing, organizing, testing and playing M3U and M3U8 playlists. It combines playlist editing, channel metadata, XMLTV electronic programme guide (EPG) management, stream diagnostics and playback in one workspace.

It is a general-purpose playlist utility for authorized IPTV subscriptions, personal media playlists and compatible M3U/M3U8 sources. It does not provide television channels, subscriptions or access credentials.

<p align="center"><img src="https://raw.githubusercontent.com/saeidrahmanbd/BDIX-IPTV/main/assets/Playlist-Studio-5.1.JPG" alt="Playlist Studio 5.1 Windows application showing playlist management, XMLTV EPG centre, stream scanner and built-in player" width="100%"></p>
<p align="center"><sub>Manage playlists, review programme-guide coverage, inspect stream status and play channels in one workspace.</sub></p>

## Download

**[Download Playlist Studio 5.1 Portable for Windows](https://github.com/saeidrahmanbd/Playlist-Studio/releases/download/v5.1/Playlist-Studio-5.1.exe)**

1. Download the EXE from the official release.
2. Double-click `Playlist-Studio-5.1.exe`.
3. Open an M3U/M3U8 playlist, edit it and select **Save** or **Save As**.

No traditional installer, Python runtime or separate VLC installation is required to run the released application. The first launch may take a few seconds while the single-file executable unpacks.

**Windows SmartScreen:** The executable is unsigned and Windows may display a warning. Verify that the download came from the official GitHub release before deciding whether to run it.

## Features

### M3U / M3U8 Playlist Editor
- Open playlists from local files or URLs.
- Edit channel names, groups, stream URLs, logos, EPG identifiers and metadata.
- Organize categories, select multiple channels, detect duplicates and manage playlist entries.
- Save changes or create a separate copy with Save As.
- Preserve playlist directives, comments and unknown header keys.

### XMLTV EPG Centre
- Load XMLTV guides from URLs or local XML, GZ, XZ and ZIP files; multiple sources can be loaded together.
- Review programme coverage, guide horizon, category/source breakdowns and channel matching statuses.
- Inspect Now / Next with channel time shifts applied and times shown in local time.
- Search, sort and edit `tvg-id` values; preview bulk metadata changes and undo.
- Review and manage manual EPG corrections. Suggested IDs require user approval.

### Stream Scanner and Built-in Player
- Distinguish Responsive, Dead, Unreachable, Restricted, Stale, Unavailable, Unverified and Error statuses.
- Timeouts and blocked requests are not automatically treated as confirmed Dead streams.
- Pause, resume or cancel scans; configure per-server limits, timeouts, retries and player identity.
- Run HLS freshness checks and optional deeper diagnostics.
- Keep Good / Bad / Review verdicts, notes and scan history between sessions.
- Export scan results to Excel or JSON and play compatible streams in the built-in player.

### Xtream Codes and Stalker Portal / MAC
- Import from supported Xtream Codes and Stalker Portal / MAC connections.
- Run login and import operations in the background with cancellation.
- Fall back to M3U download when the Xtream API route fails.
- Undo Stalker imports; failed imports leave the existing playlist untouched.
- Remembered provider credentials are protected using Windows DPAPI rather than stored in plain text.

### Safer Editing and Saving
- UTF-8 saving without BOM by default, with an optional BOM setting.
- Preserve directives, comments and unknown playlist header keys.
- Handle malformed channel lines during import without aborting the entire import.
- Backups and recovery support, credential masking and next/previous channel shortcuts.

## Documentation

| Resource | Description |
|---|---|
| [Quick Start](docs/QUICK-START.md) | Download, open, edit, scan and save a playlist |
| [User Guide](docs/PLAYLIST-STUDIO-5.0.md) | Detailed workflows; some screenshots or labels may reflect the earlier 5.0 interface |
| [Downloads and Build Kit](docs/DOWNLOADS.md) | Official files, requirements and build instructions |
| [FAQ](docs/FAQ.md) | Questions about formats, EPG, scanning, providers and troubleshooting |
| [Changelog](docs/CHANGELOG.md) | Version history |
| [Documentation Index](docs/README.md) | All help resources |

## Build Kit

Most users only need the portable EXE. The Windows Build Kit is for developers and advanced users who want to rebuild the application.

**[Download Playlist Studio 5.1 Windows Build Kit r2](https://github.com/saeidrahmanbd/Playlist-Studio/releases/download/v5.1/Playlist-Studio-5_1-Windows-Build-Kit-r2.zip)**

Requirements: Windows 10/11 x64 and 64-bit Python 3.10–3.13 (Python 3.13 recommended), plus internet access for package installation and the VLC download. Python 3.14 and 3.15 are not supported by the current pinned PyInstaller dependency set.

1. Extract the Build Kit ZIP.
2. Run `BUILD-WINDOWS.cmd`.
3. Wait for **BUILD COMPLETE**.
4. Run `Playlist-Studio-5.1.exe` from the build output.

The kit creates an isolated `.venv-build` environment, installs pinned dependencies, runs automated tests, verifies the VLC download and packages the application. See [Build Kit instructions](docs/DOWNLOADS.md).

## Release Files and Integrity

- [Playlist-Studio-5.1.exe](https://github.com/saeidrahmanbd/Playlist-Studio/releases/download/v5.1/Playlist-Studio-5.1.exe) — portable Windows application.
- [Playlist-Studio-5_1-Windows-Build-Kit-r2.zip](https://github.com/saeidrahmanbd/Playlist-Studio/releases/download/v5.1/Playlist-Studio-5_1-Windows-Build-Kit-r2.zip) — Windows Build Kit.
- [Official v5.1 release](https://github.com/saeidrahmanbd/Playlist-Studio/releases/tag/v5.1) — release notes and published asset digests.

SHA-256 values published for the v5.1 assets:

| File | SHA-256 |
|---|---|
| `Playlist-Studio-5.1.exe` | `9ff254ce20124aba7b2802fa707c8f79df058b9760038ad72ec6cd5df1f0ada8` |
| `Playlist-Studio-5_1-Windows-Build-Kit-r2.zip` | `b74cba0ff13481f626af9a82607b8cd9eb1a5b1da93bc5b620a1c027ce414dfa` |

Verify a local download in PowerShell:

```powershell
Get-FileHash .\Playlist-Studio-5.1.exe -Algorithm SHA256
Get-FileHash .\Playlist-Studio-5_1-Windows-Build-Kit-r2.zip -Algorithm SHA256
```

Compare the local result with the corresponding digest published on the official release.

## Related Projects

- [BDIX-IPTV](https://github.com/saeidrahmanbd/BDIX-IPTV) — separate curated IPTV playlist and XMLTV EPG project.
- [Playlist Studio product page](https://saeidrahmanbd.github.io/BDIX-IPTV/playlist-studio.html) — product overview and downloads.
- [Saeid Rahman on GitHub](https://github.com/saeidrahmanbd) — profile and featured projects.

Playlist Studio is independent of any particular playlist collection and can be used with other compatible M3U/M3U8 sources.

## License and Responsible Use

Original software, binaries, artwork, documentation and other project materials are proprietary unless a separate license is explicitly provided for a specific component. See [LICENSE](LICENSE).

Use only playlists and IPTV services you are authorized to access and use.

---

<p align="center">⭐ <b>If Playlist Studio is useful to you, consider starring this repository.</b><br><sub>Made with ❤️ by <a href="https://github.com/saeidrahmanbd">Saeid Rahman</a></sub></p>
