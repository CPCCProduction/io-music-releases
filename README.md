# IO Music — downloads

Installers for **IO Music**, the walk-in / walk-out music player for live shows.

## Install

1. Open the [latest release](https://github.com/CPCCProduction/io-music-releases/releases/latest).
2. Download **`IO-Music-Setup-X.Y.Z.exe`** (Windows 10/11, 64-bit) and run it.
3. Windows may say *"Windows protected your PC"* because the installer isn't code-signed yet —
   click **More info → Run anyway**.

Everything the app needs (ffmpeg, the Rubber Band pitch/tempo engine, etc.) is included.

## Updates

IO Music checks this page once a day and shows **Update available** in its status bar.
Go to **Settings → Updates**, press **Download**, then **Restart & install**. It never updates on
its own, so a show is never interrupted, and your playlists, settings and library are kept.

## Bitfocus Companion

The Companion module (`iomusic-player-X.Y.Z.tgz`) is attached to releases as well. In Companion:
**Modules → Import module package**, then add an **IO Music** connection (port 7700).

**On a Mac:** Safari unpacks `.tgz` downloads into a `.tar` that Companion rejects. Download
`iomusic-player-X.Y.Z-mac.zip` instead: Safari unzips it and leaves the `.tgz` ready to import.
(Or, in Terminal, re-pack a `.tar` with `gzip -c iomusic-player-X.Y.Z.tar > iomusic-player-X.Y.Z.tgz`.)
