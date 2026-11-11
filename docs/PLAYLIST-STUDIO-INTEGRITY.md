# Playlist Studio v5.1 — Release Integrity

The SHA-256 digests below are copied from the published GitHub release asset metadata for [Playlist Studio v5.1](https://github.com/saeidrahmanbd/Playlist-Studio/releases/tag/v5.1).

| Asset | Size | SHA-256 |
|---|---:|---|
| `Playlist-Studio-5.1.exe` | 102,526,298 bytes | `ef0b58e0108dc76d886b92a88170ff5fd231704604150d6283feb6f1b9f48412` |
| `Playlist-Studio-5_1-Windows-Build-Kit-r2.zip` | 688,328 bytes | `66d1de92f3d2285c38afae767697dae71e74a842266ce644700f8cd745453335` |

These digests identify the exact release assets reported by GitHub when this document was updated. Recheck the release page if an asset is replaced.

## Verify on Windows

In PowerShell, from the folder containing the downloaded files, run:

    Get-FileHash .\Playlist-Studio-5.1.exe -Algorithm SHA256
    Get-FileHash .\Playlist-Studio-5_1-Windows-Build-Kit-r2.zip -Algorithm SHA256

Compare the `Hash` value with the expected value above before running or extracting the file.
