# LastRound

**Every match recorded. Every highlight ready.**

LastRound records every game you play on Windows, automatically: it starts when your game
starts, and when you quit, the match is waiting in your library, compressed and named. It can
also cut your loudest moments into 9:16 clips, ready for Shorts and TikTok.

## Download

**[Download LastRound for Windows](https://github.com/FauziFuzzy/LastRoundRelease/releases/latest/download/LastRound-Setup.exe)**
(always the newest version) - or pick a version from [Releases](https://github.com/FauziFuzzy/LastRoundRelease/releases).
What's new: [CHANGELOG](CHANGELOG.md).

Run `LastRound-Setup.exe`. It installs for your user only (no admin prompt), can start with
Windows, and records to `Videos\LastRound`.

**Windows may warn you** because LastRound is new and not yet code-signed:

- the browser may say the file "isn't commonly downloaded" - choose **Keep**;
- Windows may show "Windows protected your PC" - click **More info**, then **Run anyway**.

## Requirements

- Windows 10 (version 1903) or Windows 11, 64-bit
- A GPU with a hardware video encoder (NVIDIA, AMD or Intel) for the smallest files; without one,
  recordings are kept as H.264

Recordings play in any player, including Windows Media Player: LastRound saves the smallest
format (HEVC) only on PCs that can play it, and H.264 otherwise. Settings > Video format lets you
choose.

## Why LastRound

Measured recording the same 60 seconds of a Dota 2 match at 1080p (one NVIDIA PC):

| | LastRound | OBS Studio | Medal | Outplayed |
|---|---|---|---|---|
| RAM while recording | **113 MB** | 326 MB | 1,156 MB | 1,073 MB |
| CPU while recording | **0.5%** | 1.6% | 1.8% | 1.0% |
| Disk per minute | **17.7 MB** | 34 MB | 87 MB | - |
| Account needed | **No** | No | Yes | Yes |

- No account, no uploads, no ads - your recordings stay on your PC.
- Anti-cheat safe: nothing is injected into your games and no keys are sent to them.
- Crash-safe recordings; a resolution change or launcher-to-fullscreen never crops the video.

## Updating and uninstalling

Run a newer `LastRound-Setup.exe` over the old one - your settings and recordings are kept.
Uninstall from Windows Settings > Apps; your recordings are never deleted.

This repository only hosts the installer downloads.
