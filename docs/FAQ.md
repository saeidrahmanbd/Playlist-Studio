# Playlist Studio — Frequently Asked Questions

Answers about this Windows M3U/M3U8 playlist editor, XMLTV EPG manager, stream checker and IPTV playlist player.

## What is Playlist Studio?

Playlist Studio is a portable Windows desktop application for opening, editing, organizing, testing and playing M3U and M3U8 playlists. It combines playlist editing, channel metadata, XMLTV EPG tools, stream diagnostics and playback in one application.

## Is Playlist Studio available for Windows 10 and Windows 11?

The released portable application is intended for 64-bit Windows 10 and Windows 11.

## Do I need Python or VLC installed?

No separate Python or VLC installation is required to run the released portable application. Python 3.10–3.13 (64-bit) is needed only if you want to rebuild the application using the Windows Build Kit. Python 3.13 is recommended.

## Which playlist formats can I open?

Playlist Studio supports M3U and M3U8 playlists from local files and URLs. It can edit channel names, groups, stream URLs, logos, EPG identifiers and other playlist metadata.

## Can I manage XMLTV EPG data?

The EPG Centre loads XMLTV guides from URLs and local XML, GZ, XZ and ZIP files. It provides coverage and channel matching information, Now / Next, editable tvg-id values, bulk metadata editing and management of manual EPG corrections.

## Does the stream scanner always know whether a channel is dead?

No. A timeout, network restriction or blocked request does not prove that a stream is dead. Playlist Studio distinguishes Dead from Unreachable, Restricted, Stale, Unavailable, Unverified and Error so users can interpret results more carefully.

## Does Playlist Studio support Xtream Codes and Stalker Portal?

The application supports compatible Xtream Codes and Stalker Portal / MAC import workflows. Use credentials only for services you are authorized to access.

## Does Playlist Studio include TV channels or an IPTV subscription?

No. Playlist Studio is a playlist management and playback utility. It does not provide channels, subscriptions or access credentials. Users must supply their own authorized playlists and services.

## Where can I download the latest version?

Download the portable app and Windows Build Kit from the [official Playlist Studio v5.1 release](https://github.com/saeidrahmanbd/Playlist-Studio/releases/tag/v5.1). Verify downloaded files against the SHA-256 digests published with the release.

## Where can I find instructions?

- [Quick Start](QUICK-START.md)
- [User Guide](PLAYLIST-STUDIO-5.0.md)
- [Downloads and Build Kit](DOWNLOADS.md)
- [Changelog](CHANGELOG.md)

For updates, visit the [Playlist Studio repository](https://github.com/saeidrahmanbd/Playlist-Studio).
