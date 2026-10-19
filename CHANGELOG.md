# Changelog

What changed in each version of Postmatch (called LastRound up to 1.0.6). To update, use the
Update button in the dashboard, or download the newest `Postmatch-Setup.exe` and run it over
your current version; your settings and recordings are kept.

## 1.1.0 - 2026-10-19

- **LastRound is now Postmatch.** New name and a new logo: an 8-bit P with a play button in
  purple and cyan. Installing Postmatch replaces LastRound: it stops it, removes its program
  folder and shortcuts, and brings your settings, games, logs and thumbnails over on the first
  start. Your recordings are not moved: if you never picked a recordings folder, Postmatch keeps
  recording into `Videos\LastRound` so everything you have still shows in the dashboard.
- **Updating from LastRound works as usual.** LastRound's Update button (1.0.4 and later) offers
  this version and installs Postmatch over it in one click. The releases now live at
  `FauziFuzzy/PostmatchRelease`; old LastRound links still lead there.
- **A new dashboard.** A fresh look throughout, and the window opens at a comfortable size.
  New **Record** page: the live recording, today's matches and your capture settings at a glance.
- **Matches, side by side.** Your matches on the left, grouped by day; click one to see it on
  the right with Review, Make clips and Discord, plus every clip made from it. Clicking a match
  responds straight away. With more than five games, the game chips become one Game menu with
  a count per game.
- **Clips as a list.** One row per clip with its game, length, size and date, and its own
  Delete button. Tick several to make Discord copies or move them to the Recycle Bin together.
  Search and sort work on Clips too.
- **Game icons.** Every game shows its own icon, taken from the game's program file (or Steam's
  icon when the program has none). Pick your own picture for a game in Settings > Games.
- **Setup when you first install.** Five quick steps: your games (Postmatch scans your PC for
  installed ones), your microphone, video quality, which drive to record to, and a summary.
- **Settings, redesigned** into clear sections, with the recordings folder picked by button.
- **Coming soon, marked as such:** match results (win/loss, K/D/A), auto-clipped moments,
  hotkeys, team review and public clip links show in the app with a "Soon" tag.

## 1.0.6 - 2026-10-19

- **Fixed:** Settings > Change... closed LastRound's dashboard instead of opening the folder
  picker (1.0.5).

## 1.0.5 - 2026-10-19

- **Discord size.** A Discord button on every clip (and on recordings up to 2 minutes) makes a
  copy under Discord's 10 MB upload limit and shows it in Explorer, ready to drag into a chat.
  A 45-second clip comes out around 9 MB in a few seconds.
- **Send logs.** Settings > Send logs saves LastRound's logs and your PC's details (Windows
  version, graphics encoders, microphones, settings) in one zip to send to whoever helps you.
  Nothing is uploaded.
- **Choose the recordings folder with a button.** Settings > Change... opens Windows' folder
  picker instead of typing a path.

## 1.0.4 - 2026-10-19

- **Update button.** The dashboard tells you when a new version is out (sidebar icon and
  Settings > Updates) and installs it in one click: it downloads the installer, checks it
  matches the release, installs it and reopens LastRound. It never updates while a game is
  recording. This is the only thing LastRound fetches from the internet: one small request to
  GitHub when the dashboard opens and every 6 hours.
- **Choose your microphone.** Settings > Microphone: Windows' default, a specific mic, or off.
  If the chosen mic is unplugged, Windows' default is used until it's back.
- **No yellow border on Windows 10.** Windows 10 always draws a yellow border around a window
  that's being captured. On Windows 10 LastRound now records the game's area of the screen
  instead, without a border. While the game isn't in front (alt-tab), that part of the video
  is black, so nothing else on your screen is recorded. Windows 11 keeps recording the game
  window, with the border hidden.

## 1.0.3 - 2026-10-19

- **Recordings play in every player**, including Windows Media Player. LastRound saves the
  smallest format (HEVC) only on PCs that can play it (with Microsoft's HEVC Video
  Extensions), and H.264 otherwise: about a third bigger at the same quality.
  Settings > Video format lets you choose.
- **Your games are found automatically.** No built-in game list any more: play a game
  fullscreen once and it's added to Settings, then recorded in any window mode. Games are
  recognised from Steam, Epic, Riot, Xbox, EA, Ubisoft, GOG, Amazon and Rockstar folders, and
  from Windows' own list of games, wherever they're installed.

## 1.0.2 - 2026-10-19

- **Clips work again.** Every clip failed in 1.0.0 and 1.0.1.
- **Yellow border on Windows 11:** LastRound now asks Windows for permission to hide it. If
  it still shows, allow desktop apps under Settings > Privacy & security > Screenshot borders.

## 1.0.1 - 2026-10-19

- Clips are cut and framed 9:16 without captions. Captions needed Python, which most PCs
  don't have.

## 1.0.0 - 2026-10-19

- First public release: automatic recording of every game, HEVC compression on your GPU, a
  game-library dashboard, and 9:16 clips of your loudest moments.
