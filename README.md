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
   If the short link ever fails, use the full one: `https://github.com/Willie259x/willievision-updates/raw/main/WillieVision.apk`
4. Choose **Install**, then **Open**.

## 2. Log in

Choose how your provider gave you your service:

**● Xtream login** (best: channels, movies & series, catch-up)
- **Playlist name:** optional, anything you like
- **Server URL:** for example `http://example.com:8080`. Include `http://` and the port.
- **Username** and **Password**

**● M3U link** (live channels)
- Paste the **M3U playlist link** your provider gave you.
- **TV guide link** is optional. Many M3U playlists already include one, and WillieVision uses it automatically.
- If the link is an Xtream-style link (it contains `username=` and `password=`), WillieVision switches to the full Xtream login for you, so you also get movies and series.

Then press **Connect**. The first time, loading the channels and TV guide can take a minute. You can add more playlists, or edit one, any time under **⚙ Settings → Playlists**.

---

## 3. The home screen

The TV guide is the home screen:

- **Top left:** details of the selected show and the clock
- **Top right:** a live preview of the channel you last watched, with its quality, for example **1080p · 5.1**
- **Left column:**
  - Quick buttons: 🎬 **Movies**, 📺 **Series**, 🔍 **Search**, ⚙ **Settings**
  - Your **playlist name** button, to switch playlists in one press
  - Your categories: 🏆 **My Games**, ★ **Favorites**, 🕘 **Recent**, your own 📁 groups, and your provider's groups
- **Guide grid:** channel logos and names down the side, shows across, with a line marking *now*

### Remote in the guide

| Button | What it does |
|---|---|
| ▲ ▼ | Move between channels |
| ◀ ▶ | Move through the shows. ◀ at the start of a row goes to the categories. |
| **OK** | **Show on now:** watch full screen<br>**Earlier show (⟲):** watch it from the start (catch-up)<br>**Later show:** Remind / Record / Record every episode / Watch menu |
| **Hold OK** (or Menu) | Channel options (see section 5) |
| **Back** | Jump back to *now* → go to the categories → press twice to exit |
| **Hold Back** | Straight back to the channel you were last watching, full screen |

---

## 4. Watching live TV

| Button | What it does |
|---|---|
| ▲ ▼ / CH+ CH− | Next or previous channel |
| **OK** | Channel list |
| **Hold OK** | Options: 🔊 audio track, 💬 subtitles / closed captions, 😴 sleep timer, stream info, record |
| ◀ ▶ / Info | Now and next info bar |
| **◀ twice** | Flip back to the previous channel |
| **▶ twice** | Stream info: resolution, frame rate, codec, bitrate, buffer and dropped frames |
| ⏺ Record (or red button) | Record this channel now |
| Menu / Guide | Back to the guide. With picture-in-picture on, the channel keeps playing in a corner. |

While a channel loads, a card shows its logo, name and what's on, instead of a black screen.

### 🔊 Audio, 💬 subtitles & 😴 sleep timer

**Hold OK** while watching anything (live TV, catch-up, movies or episodes; **Menu** also works in movies):

- **Audio:** pick another audio track, like French or English commentary, or 5.1 vs stereo. WillieVision remembers the language for everything you watch next.
- **Subtitles:** turn closed captions or subtitles on or off. Your choice stays on (or off) across channels.
- **Sleep timer:** 15 minutes to 2 hours, or **at the end of this show / movie**. A minute before, a warning pops up with **Keep watching**. Otherwise WillieVision closes so the TV can go to sleep. Recordings keep going.

### ⏸ Pause & rewind live TV

While you watch, WillieVision keeps the last **30 minutes** of the channel. It saves to a USB drive if one is plugged in, otherwise to the box.

- **⏯** pauses and resumes. **OK** also resumes while paused.
- **⏪ / ⏩** jumps back or forward 30 seconds.
- Once you're behind live, **◀ / ▶** jumps 10 seconds and **Back** returns to live.
- A box at the top left shows how far behind live you are.

### ⟲ Catch-up

On channels marked **⟲**, if your provider offers catch-up, choose an earlier show in the guide to watch it from the beginning.

- **◀ ▶** skips 30 seconds.
- **CH+ / CH−** skips 5 minutes.
- **OK** pauses.

---

## 5. Making the channel list your own

**Hold OK on a channel** for:

- **★ Add to / remove from Favorites**
- **↕ Move:** reorder Favorites. Use ▲▼ to move, then OK to drop.
- **📁 Add to a group:** make your own groups like "Hockey" or "Kids". Hold OK on a group in the left column to rename, move or delete it.
- **✎ Rename channel**, with an **Original name** button to undo
- **🖼 Change logo:** use the TV guide's logo, a picture link, no logo, or the original
- **📺 Fix the guide for this channel:** if a channel shows the wrong listings, search for and pick the right guide entry
- **Hide channel / hide category**
- **⧉ Multi-view:** choose **2 channels side by side** or **4 channels in a 2×2 grid**. The sound follows the window you're on. With 4, use ◀▶▲▼ to move between windows and OK to pick a channel. Each window uses one connection, so your plan needs to allow 2 or 4.

**Hold OK on a category** in the left column for:

- **↕ Move category** up or down the list
- **✎ Rename category**
- **Hide this category**
- **☑ Choose which categories to show:** a tick list with an **ALL** box at the top, so you can untick everything, then tick just what you want
- **Hide all "US" categories** or **Keep only "US" categories**, for providers with country prefixes

**⚙ Settings → Manage channels** shows every category and channel with tick boxes.

The guide remembers where you were in each category (channel and scroll position), even after the app restarts.

## 6. 🔍 Search

- Find channels by name, and shows by title in the TV guide.
- **Hold OK** on a result to add it to (or remove it from) ★ Favorites.
- **🎤 Voice:** press the Voice button, or **hold OK on 🔍 Search** on the home screen, then say a channel or show.

## 7. 🎬 Movies & 📺 Series

- Browse your provider's on-demand titles as a poster wall.
- Each title has its own page with a big backdrop, the rating ★, age rating, year, runtime, plot and cast, plus **▶ Play / Resume**, **Play from start** and **🎬 Trailer** (opens in the YouTube app, when the provider includes one).
- **🔍 Search movies / series** at the top of the categories finds any title.
- **Continue watching** remembers where you stopped.
- **Series** play the next episode automatically.

### ✔ Trakt.tv

If you use [Trakt](https://trakt.tv), connect it under **⚙ Settings → Trakt.tv**. The TV shows a code: go to **trakt.tv/activate** on your phone or computer and type it in. Each box connects separately.

- **Watched history:** movies and episodes you watch are marked watched on Trakt automatically. Posters show a **✓** for movies you've watched anywhere, and episodes show ✓ too.
- **Resume anywhere:** stop partway and Trakt remembers where. Another box, or any Trakt app, offers **Resume from 52% (Trakt)**.
- **New rows:** Series has **⏭ Up next (Trakt)** and **🔖 Trakt watchlist**. Movies has **⏯ Paused on Trakt** and **🔖 Trakt watchlist**. Only titles your provider actually has are shown.
- **Ratings:** each title's page shows Trakt's rating (♥ %). When a movie or the last episode you're watching ends, you can rate it 1–10. Turn that off in **Settings → Trakt.tv**.

## 8. 🔔 Reminders & 🏆 My Games

- For a later show, choose **🔔 Remind me**. A pop-up with a **Watch** button appears when it starts.
- **🏆 My Games:** open it from the top of the categories, then **✎ Edit teams**. Tick quick picks (Jets, Blue Bombers, Blue Jays, Moose, Oilers, Roughriders) or type any team. WillieVision finds their games in the guide, lists them, and sets a reminder for each new one.

## 9. ⏺ Recording

- **Record now:** press Record while watching, or hold OK in the guide → Record now.
- **Record later:** OK on a later show → **⏺ Record**.
- **Record every episode:** OK on a show → **⏺ Record every episode (series)**. New episodes are booked automatically as the guide fills in.
- **Where recordings are saved:** a USB drive if plugged in, otherwise the box. They're **deleted if you uninstall the app**.
- **⚙ Settings → Recordings:** watch or delete recordings.
- **⚙ Settings → Recording:** start early or end late by a few minutes (good for sports), and manage series recordings.

---

## 10. ⚙ Settings

Settings opens as a panel on the right, in sections: **Look**, **Channels & guide**, **Playback**, **Recording**, **Account** and **System**. Each row shows a short description and its current setting.

| Setting | What it does |
|---|---|
| Recordings | Your recordings library |
| Appearance | Style, colours, fonts, background and layout (see section 11) |
| Playlists | Add, switch, **edit** (server, username, password) or remove playlists |
| Manage channels | Show or hide channels and categories with tick boxes |
| TV guide sources | Use a different guide, or **add extra guides** for channels the main one misses |
| Match TV frame rate | Switches the TV to suit each show or movie for smoother motion. The screen blinks for a second when it switches. |
| Pause & rewind live TV | Turn the 30-minute live buffer on or off |
| Buffer size | Normal, Large or Extra large. Bigger means fewer stalls on a shaky connection, but a slower start. |
| Backup WillieVision | Copy your whole setup to another box on your network, or save/restore a backup file |
| Update TV guide | Refresh the channels and guide now |
| Check for updates | Download and install the newest WillieVision |
| Start-up screen | Open to the guide, to Favorites, or straight into the last channel full screen |
| Picture-in-picture | Keep the channel playing in a corner while you browse the guide (if your box supports it) |
| Auto-refresh | Refresh channels and guide every night (around 4 AM) or every 12 hours, even when the app is closed |
| Recording options | Start early or end late, and manage series recordings |
| Parental lock | A 4-digit PIN locks chosen categories (they show 🔒). The PIN unlocks them for 2 hours. |
| Trakt.tv | Connect your Trakt account: watched history, watchlist, up next, resume anywhere and ratings |

## 11. Appearance

| Option | Choices |
|---|---|
| Style | Modern Glass, Clean Flat, WillieVision Retro, Midnight OLED, Neon Synthwave, Classic TiviMate, Cinema, Aurora / Ocean, Black & Gold, Silver & Black |
| Accent colour | 10 presets, or **🎨 Any colour…** from 48 shades |
| Guide size | Compact, Normal, Large |
| Font | Standard, Modern, Rounded, Bold Condensed, Retro, Sporty, Futuristic, Elegant, Fun |
| Background picture | None, Northern lights, City at dusk, Prairie night, Waves, City lights blur |
| Home title | Playlist name, a greeting ("Good evening, …"), or your own text |
| Clock | 24-hour, show date, show seconds, big clock |
| Home screen parts | Show or hide the preview window, programme details and quick buttons. When the quick buttons are hidden, Movies, Series, Search and Playlists are in the **☰ Menu** button. |
| Card corners / spacing / see-through | Fine-tune the shape of the guide cards and how see-through the panels are |

### 💾 Copying your setup to a second box

1. On the box that's already set up: **⚙ Settings → Backup WillieVision → Send my setup to another Shield**. A 4-digit code appears.
2. On the new box: **Backup WillieVision → Receive setup from another Shield**. Pick the first box and type the code.

### Updates

WillieVision checks for a new version once a day. You can also check any time from **⚙ Settings → Check for updates**. After an update, a **✨ What's new** card lists the new features once.

The first update asks you to allow WillieVision to install apps. Turn on **Allow from this source**, press Back, and choose Update again.

---

## Troubleshooting

- **Login failed:** check the server address includes `http://` and the port (often `:8080` or `:80`), and that the username and password are exactly as your provider gave them.
- **No TV guide:** wait a minute after first login. If it stays empty, ask your provider for an **XMLTV / EPG link** and add it in **⚙ Settings → TV guide sources**.
- **Wrong listings on a channel:** hold OK on it → **📺 Fix the guide for this channel**.
- **A channel won't play:** press ▲ then ▼ to retune. Some channels are simply down at the provider.
- **Stuttering:** try **⚙ Settings → Buffer size → Large**, and use **▶ twice** to check the stream info.
- **Black screen for a second when playback starts:** that's **Match TV frame rate** switching the TV. Turn it off in Settings if you prefer.
- **Multi-view or recording stops the other stream:** your plan probably allows only 1 connection at a time.
- **Forgot the parental PIN:** clear WillieVision's data in the box's app settings. This also clears your logins and settings, so make a backup first.
