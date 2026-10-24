# WillieVision 📺

**Every channel. Anywhere. Anytime.**

WillieVision is a TiviMate-style IPTV player for Android TV boxes (NVIDIA Shield, Google TV, Fire TV, and similar). It works with **Xtream Codes** IPTV logins.

> **You need your own IPTV subscription.** WillieVision is only the player. It doesn't come with any channels or content.

---

## 1. Install

**Requirements:** an Android TV / Google TV / Fire TV box running **Android 7 or newer**.

1. Install the free **Downloader** app (by AFTVnews) from your box's app store.
2. Allow Downloader to install apps:
   - **Android TV / Google TV:** Settings → Apps → Security & restrictions → Unknown sources → turn on **Downloader**
   - **Fire TV:** Settings → My Fire TV → Developer options → Install unknown apps → **Downloader**
3. Open Downloader, enter this link and press **Go**:
   **`tinyurl.com/willievision`**
   (Full link, if the short one ever fails: `https://github.com/Willie259x/willievision-updates/raw/main/WillieVision.apk`)
4. Choose **Install**, then **Open**.

## 2. Log in

Enter the details from your IPTV provider:

- **Playlist name:** optional, anything you like
- **Server URL:** for example `http://example.com:8080`. Include `http://` and the port.
- **Username** and **Password**

Then press **Connect**. The first time, loading the channels and TV guide can take a minute.

---

## 3. The home screen

The TV guide is the home screen:

- **Top left:** details of the selected show (time, progress, description, what's on next)
- **Top right:** a live preview of the channel you last watched
- **Left column:**
  - Quick buttons: 🎬 **Movies**, 📺 **Series**, 🔍 **Search**, ⚙ **Settings**
  - Your categories: 🏆 My Games, ★ Favorites, All channels, and your provider's groups
- **Guide grid:** channels down the side, shows across, with a line marking *now*

### Remote in the guide

| Button | What it does |
|---|---|
| ▲ ▼ | Move between channels |
| ◀ ▶ | Move through the shows. ◀ at the start of a row goes to the categories. |
| **OK** | **Show on now:** watch full screen<br>**Earlier show (⟲):** watch it from the start (catch-up)<br>**Later show:** Remind / Record / Watch menu |
| **Hold OK** (or Menu) | Options: remind, record, watch from the beginning, add/remove favourite, move favourite, hide channel or category, multi-view, manage |
| **Back** | Jump back to *now* → go to the categories → press twice to exit |

---

## 4. Watching live TV

| Button | What it does |
|---|---|
| ▲ ▼ / CH+ CH− | Next or previous channel |
| **OK** | Channel list |
| 0–9 | Type a channel number |
| ◀ ▶ / Info | Now and next info bar |
| Last | Flip back to the previous channel |
| ⏺ Record (or red button) | Record this channel now |
| Menu / Guide | Back to the guide |

### ⏸ Pause & rewind live TV

While you watch, WillieVision keeps the last **30 minutes** of the channel. It saves to a USB drive if one is plugged in, otherwise to the box.

- **⏯** pauses and resumes. **OK** also resumes while paused.
- **⏪ / ⏩** jumps back or forward 30 seconds.
- Once you're behind live, **◀ / ▶** jumps 10 seconds and **Back** returns to live.
- A box at the top left shows how far behind live you are.
- Changing channel starts a fresh buffer.

### ⟲ Catch-up

On channels marked **⟲**, if your provider offers catch-up, choose an earlier show in the guide to watch it from the beginning.

- **◀ ▶** skips 30 seconds.
- **CH+ / CH−** skips 5 minutes.
- **OK** pauses.

---

## 5. Favourites & tidying up

- **Add a favourite:** hold OK on a channel → ★ Favorite. It then appears in the **★ Favorites** category.
- **Reorder favourites:**
  1. In Favorites, hold OK on a channel → **↕ Move**.
  2. Use ▲▼ to move it.
  3. Press OK to drop it.
- **Hide a channel or category:** hold OK → Hide. Use **⚙ Settings → Manage channels** to see everything with checkboxes and bring things back.

## 6. 🔍 Search

Search finds channels by name, and shows by title from the TV guide.

## 7. 🎬 Movies & 📺 Series

- Browse your provider's on-demand titles as a poster wall.
- **Continue watching** remembers where you stopped.
- **Series** play the next episode automatically.

## 8. 🔔 Reminders

- For a later show, press OK (or hold OK) → **🔔 Remind me**.
- A pop-up with a **Watch** button appears when it starts.
- Shows with a reminder have a bell in the guide.

## 9. ⏺ Recording

- **Record now:** press the Record button while watching, or hold OK in the guide → Record.
- **Record later:** press OK on a later show → ⏺ Record. It records even if you leave the app.
- **Where recordings are saved:** a USB drive if one is plugged in, otherwise the box.
- **To watch or delete them:** go to **⚙ Settings → ⏺ Recordings**. Hold OK there to delete one.
- Recordings live in WillieVision's own folder and are **deleted if you uninstall the app**.

## 10. ⧉ Multi-view

Hold OK on a channel → **⧉ Multi-view** to watch two channels side by side. This needs an IPTV plan that allows at least 2 connections.

## 11. 🏆 My Games

1. Open **🏆 My Games** (top of the categories) → **✎ Edit teams**.
2. Tick quick picks (Jets, Blue Bombers, Blue Jays, Moose, Oilers, Roughriders), or use **＋ Type a team** to add any team.

WillieVision then:
- finds your teams' games in the guide
- lists them by date
- shows the best channel to watch on
- sets a reminder for each new game automatically

Games show up once they're in your provider's guide, usually 1–3 days ahead.

---

## 12. ⚙ Settings

| Setting | What it does |
|---|---|
| ⏺ Recordings | Your recordings library |
| 🎨 Appearance | Choose a style (**Modern Glass**, **Clean Flat**, **WillieVision Retro**) and an accent colour |
| Playlists | Add more IPTV logins and switch between them |
| Manage channels | Show or hide channels and categories with checkboxes |
| EPG source | Use a different TV guide (XMLTV link) if your provider's guide is empty |
| 🎞 Match TV frame rate | Switches the TV to suit each show or movie (smoother motion). The screen blinks for a second when it switches. |
| ⏸ Pause & rewind live TV | Turn the 30-minute live buffer on or off |
| 💾 Backup & copy | Copy your whole setup to another box on your home network, or save/restore a backup file |
| ⬆ Check for updates | Downloads and installs the newest WillieVision |
| Reload channels & guide | Refresh everything from your provider |

### 💾 Copying your setup to a second box

1. On the box that's already set up: **⚙ Settings → 💾 Backup & copy → Send my setup to another Shield**. A 4-digit code appears.
2. On the new box: **Backup & copy → Receive setup from another Shield**. Pick the first box and type the code.

Your logins, favourites, hidden channels, reminders and look are copied over.

### ⬆ Updates

WillieVision checks for a new version once a day. You can also check any time from **⚙ Settings → ⬆ Check for updates**.

The first update asks you to allow WillieVision to install apps. Turn on **Allow from this source**, press Back, and choose Update again.

---

## Troubleshooting

- **Login failed:** check the server address includes `http://` and the port (often `:8080` or `:80`), and that the username and password are exactly as your provider gave them.
- **No TV guide:** wait a minute after first login. If it stays empty, ask your provider for an **XMLTV / EPG link** and add it in **⚙ Settings → EPG source**.
- **A channel won't play:** press ▲ then ▼ to retune. Some channels are simply down at the provider.
- **Black screen for a second when playback starts:** that's **Match TV frame rate** switching the TV. Turn it off in Settings if you prefer.
- **Multi-view or recording stops the other stream:** your plan probably allows only 1 connection at a time.
