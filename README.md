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

**On a Mac:** Safari turns `.tgz` downloads into a `.tar` that Companion can't import. Download
the module with Terminal instead (replace X.Y.Z with the version shown on the release):

```
curl -L -o ~/Downloads/iomusic-player-X.Y.Z.tgz https://github.com/CPCCProduction/io-music-releases/releases/latest/download/iomusic-player-X.Y.Z.tgz
```

Or turn off Safari → Settings → General → "Open safe files after downloading", or use Chrome.
