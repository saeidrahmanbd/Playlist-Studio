# Playlist Studio — Downloads (v5.1)

## Recommended: download the portable app

**[⬇️ Download Playlist-Studio-5.1.exe](https://github.com/saeidrahmanbd/Playlist-Studio/releases/download/v5.1/Playlist-Studio-5.1.exe)**

1. Download the EXE from the official release.
2. Open `Playlist-Studio-5.1.exe`.
3. Open your playlist and start working.

No traditional installation is needed. Python and VLC do not need to be installed separately. The first launch may take a few seconds while the single-file app unpacks.

**Windows SmartScreen:** Verify the download came from this official release. Windows may warn because the executable is unsigned. If you trust the source, select **More info → Run anyway**.

## Build Kit r2 — only if you want to rebuild the application

**[📦 Download Playlist-Studio-5_1-Windows-Build-Kit-r2.zip](https://github.com/saeidrahmanbd/Playlist-Studio/releases/download/v5.1/Playlist-Studio-5_1-Windows-Build-Kit-r2.zip)**

Requirements:
- Windows 10/11, 64-bit.
- 64-bit Python 3.10–3.13; Python 3.13 recommended.
- Internet access for Python package installation and VLC download.
- Python 3.14/3.15 are not supported by the current pinned PyInstaller dependencies.

Build:
1. Extract the ZIP to a folder.
2. Run `BUILD-WINDOWS.cmd`.
3. Wait for **BUILD COMPLETE**.
4. Find `Playlist-Studio-5.1.exe` and the setup ZIP in the kit folder.

The builder creates an isolated `.venv-build` environment and uses it for dependency installation, tests, packaging and checks. Use `BUILD-WINDOWS.cmd --fresh` to recreate that environment.

### Python Launcher is optional

If the `py` launcher is unavailable, set `PS_PYTHON` to the full path of a compatible Python executable. Run in one Command Prompt window (adjust the paths):

    set "PS_PYTHON=C:\Program Files\Python313\python.exe"
    cd /d "D:\Software\Playlist-Studio-5_1-Windows-Build-Kit-r2"
    BUILD-WINDOWS.cmd --fresh

`PS_PYTHON` is temporary and applies only to that Command Prompt session. If the build fails, inspect `BUILD-LOG.txt` beside the builder. The kit's `README.txt` explains the build stages and log; `KNOWN-LIMITATIONS.md` lists known limitations.

## Official release

[View Playlist Studio v5.1 and all release files](https://github.com/saeidrahmanbd/Playlist-Studio/releases/tag/v5.1) · [View all releases](https://github.com/saeidrahmanbd/Playlist-Studio/releases)
