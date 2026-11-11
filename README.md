<h1 align="center">🎬 Playlist Studio 5.1</h1>

<p align="center">
  <b>Windows Playlist Manager, Editor, EPG Tool &amp; Player.</b><br>
  Portable · No installer · No Python or separate VLC required to run
</p>

<p align="center">
  <a href="https://github.com/saeidrahmanbd/Playlist-Studio/releases/download/v5.1/Playlist-Studio-5.1.exe"><img src="https://img.shields.io/badge/⬇%20DOWNLOAD%20PLAYLIST%20STUDIO%205.1-2ea44f?style=for-the-badge" alt="Download Playlist Studio 5.1"></a>
</p>

<p align="center">
  <a href="https://github.com/saeidrahmanbd/Playlist-Studio/releases/tag/v5.1"><img src="https://img.shields.io/github/v/release/saeidrahmanbd/Playlist-Studio?style=for-the-badge&logo=github&label=Release&color=0969da" alt="Release"></a>
  <a href="https://github.com/saeidrahmanbd/Playlist-Studio/stargazers"><img src="https://img.shields.io/github/stars/saeidrahmanbd/Playlist-Studio?style=for-the-badge&logo=github&color=f5c542" alt="Stars"></a>
  <a href="LICENSE"><img src="https://img.shields.io/github/license/saeidrahmanbd/Playlist-Studio?style=for-the-badge&color=8250df" alt="License"></a>
  <a href="https://github.com/saeidrahmanbd/Playlist-Studio/commits/main"><img src="https://img.shields.io/github/last-commit/saeidrahmanbd/Playlist-Studio?style=for-the-badge&color=e5534b" alt="Last commit"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows-0078D6?style=flat-square&logo=windows&logoColor=white" alt="Windows">
  <img src="https://img.shields.io/badge/Formats-M3U%20%2F%20M3U8-6f42c1?style=flat-square" alt="M3U / M3U8">
  <img src="https://img.shields.io/badge/EPG-XMLTV-2ea44f?style=flat-square" alt="XMLTV EPG">
  <img src="https://img.shields.io/badge/Xtream%20%2F%20Stalker-Supported-00b4d8?style=flat-square" alt="Xtream and Stalker support">
  <img src="https://img.shields.io/badge/Portable-Yes-success?style=flat-square" alt="Portable">
</p>

<p align="center">
  <a href="#product-glimpse">Preview</a> ·
  <a href="#start-here">Get Started</a> ·
  <a href="#whats-new-in-51">What's New</a> ·
  <a href="#guides">Guides</a> ·
  <a href="#build-kit">Build Kit</a>
</p>

---

## Product Glimpse

<p align="center">
  <img src="https://raw.githubusercontent.com/saeidrahmanbd/BDIX-IPTV/main/assets/Playlist-Studio-5.1.JPG" alt="Playlist Studio 5.1 — Windows playlist manager, EPG centre, scanner and built-in player" width="100%">
</p>

<p align="center"><sub>Manage playlists, inspect programme-guide coverage, scan streams and play channels in one workspace.</sub></p>

---

<a id="start-here"></a>
## 🚀 Start here — 3 easy steps

| Step | What to do |
|:---:|---|
| **1** | **[⬇️ Download Playlist Studio 5.1](https://github.com/saeidrahmanbd/Playlist-Studio/releases/download/v5.1/Playlist-Studio-5.1.exe)** |
| **2** | Open your Downloads folder and double-click `Playlist-Studio-5.1.exe`. |
| **3** | Open an M3U/M3U8 playlist, make your changes, and click **Save**. |

> **No installer, Python or separate VLC installation is needed to run the portable application.** The first launch may take a few seconds while the single-file executable unpacks.

> **Windows SmartScreen:** Verify that you downloaded the file from the official release linked above. Windows may warn because the executable is unsigned. If you trust the source, choose **More info → Run anyway**.

---

<a id="whats-new-in-51"></a>
## ✨ What's new in 5.1

### 📺 EPG Centre
- Load XMLTV guides from URLs or local files: `.xml`, `.gz`, `.xz` and `.zip`; load multiple sources in one session.
- A damaged guide is reported while other sources continue loading; long loads can be cancelled.
- Coverage dashboard with totals, category/source breakdowns and guide horizon.
- Channel guide statuses: matched, guide ending soon, expired, no programmes, ID not in guide, missing `tvg-id` and duplicate IDs.
- Now / Next display applies the channel time shift and shows times in your local timezone.
- Suggested IDs require user approval; they are not applied automatically.
- Visible, sortable, searchable and editable `tvg-id` column.
- Bulk metadata editor with preview and one-step Undo.
- Manual EPG corrections can be reviewed, edited, disabled or removed and are reapplied after Refresh, re-import and Xtream / Stalker updates.

### 🔍 Smarter Stream Scanner
- Statuses: **Responsive, Dead, Unreachable, Restricted, Stale, Unavailable, Unverified and Error**.
- Timeouts and blocked requests are never labelled Dead automatically.
- Pause, resume and cancel scans; configure per-server limits, timeouts, retries and player identity.
- HLS freshness checks and optional deep diagnostics.
- Scan selected channels, the current category or the current view.
- Good / Bad / Review verdicts, notes and scan history persist between sessions. New scans do not overwrite your verdicts.
- Export scan results to Excel or JSON.

### ☁️ Xtream Codes & MAC / Stalker
- Background logins and imports with a Cancel option.
- Xtream falls back to M3U download if the API route fails.
- Stalker / MAC imports can be undone; a failed import leaves the playlist untouched.
- Remembered credentials are protected with Windows DPAPI and are not stored in plain text.

### 💾 Safer Saving & Editing
- UTF-8 saving without BOM by default; optional BOM setting.
- Preserve directives, comments and unknown playlist header keys.
- Malformed channel lines can be repaired on import instead of aborting the import.
- If a backup cannot be made, the app asks before overwriting.
- Credentials can be masked in the channel list.
- Alt+Right / Alt+Left next/previous channel shortcuts, player buffering setting and single-instance operation.

### ✅ Core features
M3U/M3U8 playlist management · Channel and category editing · Multi-selection · Duplicate detection · Built-in playback with fullscreen and volume · Import from files or URLs · Save / Save As · Multiple themes · GitHub integration.

---

<a id="guides"></a>
## 📖 Guides

| Guide | Description |
|---|---|
| 🚀 [Quick Start](docs/QUICK-START.md) | Download, open a playlist, edit and save |
| ⚙️ [User Guide](docs/PLAYLIST-STUDIO-5.0.md) | Core workflow and feature usage (some screenshots or labels may reflect 5.0) |
| 📥 [Downloads & Build Kit](docs/DOWNLOADS.md) | Official downloads and build requirements |
| 📝 [Changelog](docs/CHANGELOG.md) | Version history |

---

<a id="build-kit"></a>
## 🔧 Windows Build Kit r2

> Most users only need the portable EXE above. The Build Kit is for developers or advanced users who want to rebuild the application.

**Requirements:** Windows 10/11 x64 and 64-bit Python **3.10–3.13** (Python 3.13 recommended), plus an internet connection for Python packages and the VLC download. **Python 3.14 and 3.15 are not supported** by the current pinned PyInstaller dependency set. You may keep newer Python versions installed alongside Python 3.13.

<p align="center">
  <a href="https://github.com/saeidrahmanbd/Playlist-Studio/releases/download/v5.1/Playlist-Studio-5_1-Windows-Build-Kit-r2.zip"><img src="https://img.shields.io/badge/📦%20DOWNLOAD%20WINDOWS%20BUILD%20KIT%20r2-6e7681?style=for-the-badge" alt="Download Playlist Studio 5.1 Windows Build Kit r2"></a>
</p>

### Build in four steps

1. Download and extract **Playlist-Studio-5_1-Windows-Build-Kit-r2.zip**.
2. Run `BUILD-WINDOWS.cmd`.
3. Wait for **BUILD COMPLETE**.
4. Run `Playlist-Studio-5.1.exe` from the build kit folder.

The kit creates its own `.venv-build` environment, installs the pinned dependencies, runs automated tests, generates assets, checks the application, downloads and verifies VLC, builds the EXE and packages the output ZIP.

### No Python Launcher?

The Python Launcher is recommended but **not required**. Set `PS_PYTHON` to the full path of a compatible Python executable. Run the commands in the same Command Prompt window and adjust the paths to your computer:

```cmd
set "PS_PYTHON=C:\Program Files\Python313\python.exe"
cd /d "D:\Software\Playlist-Studio-5_1-Windows-Build-Kit-r2"
BUILD-WINDOWS.cmd --fresh
```

- `PS_PYTHON` applies only to that Command Prompt session.
- `--fresh` recreates the build virtual environment.
- If a step fails, inspect `BUILD-LOG.txt` beside the builder.
- The Build Kit's `README.txt` explains the steps and log; `KNOWN-LIMITATIONS.md` documents known limitations.

---

## 💻 System Requirements

| Item | Details |
|---|---|
| Application platform | Windows 10 / 11 |
| Architecture | x64 |
| Application type | Portable single-file EXE |
| Playlist formats | M3U / M3U8 |
| EPG | XMLTV — URL and local XML/GZ/XZ/ZIP |
| Playback | Built-in player with bundled VLC engine |
| Python to run app | Not required |
| Python to rebuild | 64-bit 3.10–3.13; 3.13 recommended |

---

## 📦 Release Files

- **[Playlist-Studio-5.1.exe](https://github.com/saeidrahmanbd/Playlist-Studio/releases/download/v5.1/Playlist-Studio-5.1.exe)** — portable Windows application.
- **[Playlist-Studio-5_1-Windows-Build-Kit-r2.zip](https://github.com/saeidrahmanbd/Playlist-Studio/releases/download/v5.1/Playlist-Studio-5_1-Windows-Build-Kit-r2.zip)** — Windows build kit.

**[View the official Playlist Studio v5.1 release](https://github.com/saeidrahmanbd/Playlist-Studio/releases/tag/v5.1)**

### Verify your download

GitHub publishes SHA-256 digests for both release assets. The published values are:

| Asset | SHA-256 |
|---|---|
| `Playlist-Studio-5.1.exe` | `ef0b58e0108dc76d886b92a88170ff5fd231704604150d6283feb6f1b9f48412` |
| `Playlist-Studio-5_1-Windows-Build-Kit-r2.zip` | `66d1de92f3d2285c38afae767697dae71e74a842266ce644700f8cd745453335` |

In PowerShell, calculate a local file hash with:

```powershell
Get-FileHash .\Playlist-Studio-5.1.exe -Algorithm SHA256
Get-FileHash .\Playlist-Studio-5_1-Windows-Build-Kit-r2.zip -Algorithm SHA256
```

Compare the result with the corresponding release asset digest. The release page is authoritative if an asset is replaced.

---

## 🔗 Related Project

📺 **[BDIX-IPTV](https://github.com/saeidrahmanbd/BDIX-IPTV)** is a separate playlist project. Playlist Studio is a general-purpose application and can be used with other M3U/M3U8 playlists and compatible services.

> Use only playlists and IPTV services you are authorized to access and use.

---

<p align="center">
  ⭐ <b>If Playlist Studio helps you, consider starring the repository.</b><br><br>
  <sub>Made with ❤️ by <a href="https://github.com/saeidrahmanbd">Saeid Rahman</a></sub>
</p>