# MPV Playlist Manager

This repository includes the **MpvPlaylistManager.exe** application, designed to enhance playlist handling in the **mpv** media player.  
Its design is inspired by the **Mirillis Splash Pro** playlist manager, offering a more user-friendly way to manage playlists.

## 🚀 Installation

1. Download or clone this repository.
2. Place the included `MpvPlaylistManager.exe` in your preferred mpv configuration folder (example: `portable_config/playmanager/MpvPlaylistManager.exe`).

## ⚙️ Configuration

To launch the Playlist Manager from mpv, add a **bind** in your `input.conf` file:

```conf
CTRL+p run ~portable_config/playmanager/MpvPlaylistManager.exe

