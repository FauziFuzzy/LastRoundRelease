# Postmatch

**Every match recorded. Every highlight ready.**

Postmatch records every game you play on Windows, automatically: it starts when your game
starts, and when you quit, the match is waiting in your library, compressed and named, with
your voice and the game in one track. Press **F8** to save the last 30 seconds into Clips,
**F9** to mark a moment. It can also cut your loudest moments into 9:16 clips, ready for Shorts
and TikTok, and make Discord-size copies.

## Download

**[Download Postmatch for Windows](https://github.com/FauziFuzzy/PostmatchRelease/releases/latest/download/Postmatch-Setup.exe)**
(always the newest version) - or pick a version from [Releases](https://github.com/FauziFuzzy/PostmatchRelease/releases).
What's new: [CHANGELOG](CHANGELOG.md).

Run `Postmatch-Setup.exe`. It installs for your user only (no admin prompt), can start with
Windows, and records to `Videos\Postmatch`.

**Windows may warn you** because Postmatch is new and not yet code-signed:

- the browser may say the file "isn't commonly downloaded" - choose **Keep**;
- Windows may show "Windows protected your PC" - click **More info**, then **Run anyway**.

## Requirements

- Windows 10 (version 1903) or Windows 11, 64-bit
- A GPU with a hardware video encoder (NVIDIA, AMD or Intel) for the smallest files; without one,
  recordings are kept as H.264

Setup checks your graphics card and memory and picks the quality that suits your PC: High (your
game's resolution), Balanced (up to 1080p) or Light (up to 720p). Recordings play in any player,
including Windows Media Player: Postmatch saves the smallest format (HEVC) only on PCs that can
play it, and H.264 otherwise. Both can be changed in Settings.

## Why Postmatch

Measured recording the same 60 seconds of a Dota 2 match at 1080p (one NVIDIA PC):

| | Postmatch | OBS Studio | Medal | Outplayed |
|---|---|---|---|---|
| RAM while recording | **113 MB** | 326 MB | 1,156 MB | 1,073 MB |
| CPU while recording | **0.5%** | 1.6% | 1.8% | 1.0% |
| Disk per minute | **17.7 MB** | 34 MB | 87 MB | - |
| Account needed | **No** | No | Yes | Yes |

- No account, no uploads, no ads - your recordings stay on your PC.
- Anti-cheat safe: nothing is injected into your games and no keys are sent to them.
- Keeps your FPS: recording runs on the graphics card, below your game, and never copies more
  frames than it needs - even at 600 fps.
- A ranked career: every minute you play earns rank points, from Rookie to Immortal.
- Crash-safe recordings; a resolution change or launcher-to-fullscreen never crops the video.

## Updating and uninstalling

The dashboard's Update button installs new versions in one click (or run a newer
`Postmatch-Setup.exe` over the old one) - your settings and recordings are kept.
Uninstall from Windows Settings > Apps; your recordings are never deleted.

This repository only hosts the installer downloads.
