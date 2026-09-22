# FTL Multiplayer: client downloads

This repository hosts the **public download files** for FTL Multiplayer, a free
1v1 versus mode for *FTL: Faster Than Light*. There is no source code here.

## Download

Get the latest build from **[ftlmultiplayer.com/download](https://ftlmultiplayer.com/download)**,
or pick it from the [Releases](../../releases) page. Each release has one file,
`FTL-PvP-Setup-v<version>.zip`.

## What you need

- **A Mac.** The client is macOS only for now. Intel and Apple Silicon both
  work; on Apple Silicon it runs through Rosetta. There is no Windows or Linux
  build yet.
- **FTL: Advanced Edition, version 1.6.13.** It is built and tested against the
  [Steam copy](https://store.steampowered.com/app/212680/). A GOG copy has not
  been tested.
- **Outgoing UDP on port 27888**, to reach the match server in Europe.

You don't need an account to play: you type a name in-game and queue.

## Install

1. Unzip the download and double-click `install.command`.
2. It is unsigned, so macOS will warn about it. Right-click it and choose
   **Open**; on newer macOS use **System Settings → Privacy & Security → Open
   Anyway**.
3. The installer patches your FTL install, keeps an untouched copy of the game
   data, and puts an **FTL Multiplayer** launcher on your Desktop.
4. Open **FTL Multiplayer**, press **MULTIPLAYER**, pick a ship, spend your
   10,000 scrap, then press **QUEUE** and accept when the match is found.

No game content is included; the installer patches the copy you already own.
Starting FTL from Steam still runs normal FTL.

To uninstall, open Terminal, drag `install.command` into it, type a space and
`--uninstall`, then press return.

## Issues

This repository is only a download host, so issues are disabled here. See
[ftlmultiplayer.com](https://ftlmultiplayer.com) for news.

## Legal

A fan project. The client is built on
[FTL: Hyperspace](https://github.com/FTL-Hyperspace/FTL-Hyperspace)
(CC BY-SA 4.0). *FTL: Faster Than Light* is a trademark of
[Subset Games](https://subsetgames.com/ftl.html); this project is not affiliated
with or endorsed by them.
