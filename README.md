<div align="center">

<img src="assets/logo.png" width="96" alt="DIABLE logo">

# DIABLE

Music lighting, a Dynamic Island and live lyrics for Windows.

[![Download for Windows](https://img.shields.io/github/v/release/ayaanoski/diable-by-vinsmoke?label=Download%20for%20Windows&style=for-the-badge&color=E8A34D&labelColor=1a1a1d)](https://github.com/ayaanoski/diable-by-vinsmoke/releases/latest)

<sub>Windows 10 (1903+) and 11 · 64-bit · free · no account</sub>

<br>


</div>

<br>

DIABLE sits in your tray:

| | |
|---|---|
| **Edge glow** | A soft light around the edge of your screen, in the colours of the album cover, split across the edges by what the song is doing. |
| **Dynamic Island** | A pill at the top of the screen with your music, notifications and a set of small tools. |
| **Lyrics** | Words that light up as they're sung, in 15 styles, in a window, full screen, on your desktop or in a tiny pill. |
| **Your phone** | Its battery, a way to find it, files sent to it over Wi-Fi, and QR codes for anything you copy — or for a photo, to open on the phone. |
| **Your PC at a glance** | CPU, memory, GPU, temperatures and network on the island, a badge on every window when you hold Right Alt, and a heads-up for calls, a full drive, updates and print jobs. |
| **Live info** | Today's scores, the prices you follow with their charts, sunrise, sunset and prayer times, parcels and flights. |
| **The camera** | Look at a window and the keyboard follows you there, walk away and your PC locks itself, nod at a banner to take it. Off until you ask for it, and the picture never leaves your PC. |
| **Ask it things** | Copy an error and the island offers to fix it; copy a message and it drafts three replies. Ask about what's on your screen and the answer types itself out in the pill. A free model on your own PC, or your own key. |
| **Clean room** | One switch, or automatic with Zoom and OBS, that keeps your clipboard, notes and notifications off a shared screen. |
| **Your shortcuts** | A key of your own for any feature, and a terminal command for scripts and builds. |

It works with anything that shows up in Windows' media controls: Spotify, YouTube in Chrome or Edge, Apple Music, VLC and the rest.

## Install

1. Download `DIABLE-Setup-x.y.z.exe` from the [latest release](https://github.com/ayaanoski/diable-by-vinsmoke/releases/latest).
2. Run it. Windows may say *"Windows protected your PC"*: click **More info**, then **Run anyway**.
3. Play a song.

A one-minute tour runs on first launch. Settings open from the DIABLE icon in the tray. Updates install themselves with one click, and you'll see what changed.

<br>

## The edge glow

The glow takes its colours from the cover of whatever is playing and changes the moment the song does. It listens to your PC's sound output, so it keeps time with the music without touching your microphone.

- **Stem lighting:** the glow splits the song across the edges instead of pulsing as one. The lows hold the bottom edge, voices and guitars the sides, hi-hats and cymbals the top, and the sides lean whichever way the sound is panned, so a riff sweeping right sends the light with it.
- **Animations:** Music Sync, Trails, Breathe, Idle, a still glow, or Screen colours, which follows the edges of whatever is on screen (Ambilight for your monitor).
- **Your own colours** instead of the album's, from a colour wheel.
- **Notification flashes** in each app's colour: green for WhatsApp, blurple for Discord. Each app can be changed or muted.
- **Typing light.** Every keystroke sends a ripple of light out along the bottom edge, and the wheel sends one out from under your pointer; the faster you work, the higher the glow rests between them. Only the timing of a key is read, never which key, and it works with the rest of the glow switched off. Turn it off with **Typing light** on the tray panel.
- **Timers on the rim.** A running timer drains around the screen and turns red in its last minute.
- **Spotlight in focus mode.** Everything dims except the window you're working in, with a rim in the album's colour that follows you from window to window.
- **Tint Windows to the album.** Windows' own accent colour — title bars, Start and the taskbar — follows the album art, and the palette is written to `diable-theme.json` for Windows Terminal or VS Code to watch. Off until you ask for it; your colour and Windows' own settings are saved and put back when you switch it off or quit.
- **Room lights.** WLED, Govee and Philips Hue lights can follow the glow and the beat.

Clicks go straight through the glow, it never steals focus, and it steps aside for full-screen games.

<br>

## The Dynamic Island

Rest the pointer on the island to open it. It also opens by itself when something happens: a song changes, a notification arrives, the volume or brightness moves, your battery runs low, a download finishes, headphones connect, you copy something, or Caps Lock or Num Lock changes. A small dot appears while your camera or microphone is in use.

The buttons along the top of the open island:

| Button | What it opens |
|---|---|
| Search | The command bar (below) |
| System | CPU, memory, GPU, temperatures, network, battery health, the apps using the most power, free space, a speed test |
| Sound | Switch speakers and headphones, per-app volume, monitor brightness, a sleep timer, a volume limit |
| Live | The weather, scores, share and coin prices, sunrise, sunset and prayer times, parcels, flights |
| Timer | 5, 10, 15 minutes, a Pomodoro, a stopwatch, two minutes of guided breathing |
| Notes | Your notes, reminders, countdowns and snippets |
| ⋯ | Played today, the clipboard, the file shelf, your phone, settings and quit |

Six buttons and a ⋯, so the row stays readable. Everything behind ⋯ is one tap away — and anything in DIABLE can have a keyboard shortcut of its own instead.

### Drag a file to it

Drag a file onto the island and it opens the shelf to catch it. While you are still holding the file, pills appear for what else can be done with it there and then:

- **Compress** a picture: a JPEG is written beside the original at about half the size. What you dragged in is never touched.
- **Copy the text** out of a picture, using Windows' own text recognition. It lands on your clipboard.
- **Send to your phone**, when LocalSend is open on it and both are on the same Wi-Fi.

Drop onto a pill to do that instead; let go anywhere else on the island and the file is parked on the shelf, ready to drag back out anywhere.

### Make it yours

Settings › Island changes the island's colour (Liquid glass, Midnight, Graphite, Rose, Pure black, or the colour of the album playing) and its shape (pill, rounded or square).

Liquid glass is real glass: it takes what is behind the island, blurs it and leans it a little towards the album's colour, and keeps up with it — quickly while something back there is moving, and barely at all over a desktop that is sitting still, which is where the work would otherwise be wasted. The island itself moves on a spring, so opening it and changing your mind halfway carries the movement round the turn instead of stopping dead and starting again.

<img src="assets/ui/island-skins.png" width="680" alt="Four island skins">

When the island is resting it shows the time, date and weather, and every so often a **word of the day** or a **proverb**, your pick. Birthdays on your calendar get a tile in the morning and a burst of confetti on the glow.

The history button opens with **your week**: hours at the PC, hours listening and minutes in focus mode, with a bar for each day. It's counted on your PC and never leaves it.

### Quick actions

Scroll on the island for quick actions:

<img src="assets/ui/island-quick.png" width="460" alt="The island's quick actions">

**Focus mode** runs a 25-minute session: the glow slows to a calm breath and notifications skip the pop-up and wait in the island until you're done. **Pick colour** puts a magnifier by your pointer; click anywhere to copy that colour as `#RRGGBB`. **Record GIF** records the screen you're on, up to 30 seconds, into Videos › DIABLE.

**Keep awake** stops the screen and the PC from sleeping until you switch it off. **Night light** opens Windows' night light (Windows doesn't let apps flip it directly). **Game HUD** shows CPU, GPU, temperatures and RAM in a corner while a game is full screen. **Speed test** checks your ping, download and upload in about 15 seconds.

<br>

## Your PC at a glance

The chart button on the island opens a live view of your PC. It only measures while it's open.

<img src="assets/ui/island-system.png" width="460" alt="The island's system panel">

- **CPU, memory, GPU and network**, with temperatures where the PC reports them. On laptops with two graphics chips it shows whichever is busier.
- **Battery health**: how much of its original capacity your battery still holds.
- **The apps using the most CPU**, which are usually the ones draining your battery.
- **Free space** on your system drive, with Windows' Disk Cleanup one click away.
- **Internet speed**: ping, download and upload.

### Hold to peek

Hold **Right Alt by itself** for half a second. Every window on screen gets a glass badge in its top corner with the app's name, its share of the processor and the memory it is holding, and whatever is on your clipboard — with any running timer — floats by the pointer. Let go and it all vanishes at once.

Nothing on that overlay is clickable, so it never gets in the way of what you were doing. While clean room is on the badges still show but the clipboard is held back, since that is the part nobody else should see. Right Alt with any other key is still your shortcut, and AltGr still types what it always did.

The island also lets you know when:

| When | You get |
|---|---|
| You join a call in Zoom, Teams, Discord, Slack, WhatsApp or a browser (Meet) | A call timer in the island, and a mute button when you click it |
| C: is nearly full | A warning with **Clean up** |
| Windows Update needs a restart | **Restart tonight**: it restarts after 3 am, once the PC has been idle for 20 minutes, and never closes an app with unsaved work |
| You print something | The document's progress, page by page, and a warning if the printer needs attention |

<br>

## The camera

Three things can use your webcam. All three are off until you switch them on, the picture never leaves your PC, and the camera closes the moment nothing needs it — the light on it goes out with it.

### Gaze focus

Turn on **Head & eye gaze focus** in the tray panel and the keyboard follows where you look: look at another window, hold for a moment, and it's ready to type in.

It works across screens and within one. Split a screen left and right and look between the halves — the keyboard goes to the window you are actually looking at, not whichever happened to be on top. A window with another sitting over most of it counts as the same place to look, and the join between two windows is a dead strip, so a glance along it can't flick the keyboard back and forth. Windows split top and bottom count as one place: only side to side is read.

There is nothing to calibrate. It reads 478 points on your face, the irises among them, so a glance across counts as much as a turn of the head and leaning across your chair counts as neither, and it learns where you sit for each screen from the window you are typing in. A look down at your desk or your phone moves nothing, and it holds off while you are mid-sentence rather than taking your keystrokes with it. A glass eye beside the island glows while it is watching, with its pupil where you are looking; click it to see what the camera sees and the angles it is reading.

### Lock when you walk away

Leave your desk and five seconds later the music pauses, the edge glow goes quiet and Windows locks. Sit back down and the music comes back on the frame your face does.

Two things have to agree before it locks: the camera has seen nobody for five seconds **and** nobody has touched the keyboard or mouse in those same five seconds. If you are typing, you are there, whatever the camera thinks. It leaves anything playing full screen alone, where you sit still and may not be facing the camera at all.

### Nod to answer banners

When a banner is waiting for an answer — a reminder, a call, a reply — nod to take it and shake your head to send it away. It only listens while something is actually waiting, so nodding along to music can't dismiss anything, and a turn to the screen beside you is not a shake. The camera opens with the banner and closes with it.

<br>

## Live info

The globe button on the island keeps the things you check all day in one place. Everything here is free and needs no account, so there is nothing to set up.

<img src="assets/ui/island-live.png" width="460" alt="The island's Live panel: scores, prices with charts, sun and prayer times, a parcel">

- **Scores.** Today's football or cricket, with the score so far or the kick-off time. Switch sports (or turn them off) with the buttons under the list.
- **Shares and coins.** The ones you follow, each with its price, a week of movement as a chart, and the day's change. Add one from the command bar: `watch BTC`, `watch AAPL`.
- **Sunrise, sunset and prayer times** for where you are, using the same location as the weather (rounded to about 1 km).
- **Parcels.** `track 1Z999AA10123456784` in the command bar works out the carrier from the number and keeps it here; clicking the row opens that carrier's own tracking page.
- **Flights.** `flight AIC302` follows a flight by its callsign and shows whether it is in the air, how high and how fast.

The resting island can also show a **news headline** now and then, between the clock and the weather. Turn it on in Settings › Island › News in island.

<br>

## The pet

A small creature can live in the island, drawn by DIABLE itself, so it costs nothing to download and takes the colour of whatever album is playing. Turn it on in Settings › Island › Desktop pet.

<img src="assets/ui/pet.png" width="680" alt="The pet: cat, duck, ghost and slime, singing along, in focus mode, under an umbrella and being petted">

It dances to the beat, **mouths the words** of the song as they are sung, watches your pointer, hops when a notification arrives, cheers when a timer finishes, covers its ears during focus mode, puts an umbrella up when it is raining where you are, and dozes off when the music stops. Click it for a fuss.

Switch on **Let the pet roam** and it leaves the island to live along the bottom of your screens: it strolls, sits, takes a proper nap with Zzz over its head, comes over to your pointer, and dances where it stands while music plays. With more than one monitor it walks off the edge of one and onto the next, and now and then sprints across to another screen. Drag it anywhere, even between monitors, click it to pet it, right-click to send it back to the island. It never takes focus, stays out of Alt+Tab, and steps aside for full-screen games.

<br>

## Your day, as a picture

The history button opens your week. **Share your day** turns it into a picture: the song you have had on, your hours at the PC, listening and in focus, the last seven days as bars, and a line you saved from the lyrics. It lands on your clipboard and in Pictures › DIABLE.

<img src="assets/ui/day-card.png" width="420" alt="A day card: the song, the hours, the week and a saved lyric">

<br>

## Your phone

The phone button on the island:

<img src="assets/ui/island-phone.png" width="460" alt="The island's phone panel">

- **Battery.** If your phone is linked with Phone Link, it stays connected over Bluetooth, and most phones report their battery that way.
- **Calls.** Phone Link's call alerts show in the island with a button to answer in Phone Link. They get through even in focus mode.
- **Find my phone.** With [KDE Connect](https://kdeconnect.kde.org) on both the PC and the phone, a **Ring** button rings it at full volume. Otherwise one click opens Google's Find My Device or Apple's Find My, which can ring it too.
- **Send files.** Open [LocalSend](https://localsend.org) on your phone (free, on the same Wi-Fi) and it shows up here. Send any file, or everything on your shelf. The phone asks you to accept, and the island shows the progress. Files go straight over your Wi-Fi.
- **QR codes.** Copied a link? The **QR** button on its tile shows a code to scan with your phone's camera, drawn big enough to catch from across the room.
- **A photo on your phone.** **QR of a photo…** here, or **To phone** on a screenshot tile, shows a code that opens the picture on your phone — any phone, on any network, whether or not it is on your Wi-Fi, with nothing to set up. Cloudflare gives this PC a temporary web address for it (DIABLE fetches Cloudflare's tunnel program, about 55 MB, the first time you agree, and keeps it). It opens on a small glass page with **Save** and **Copy** on it, and the copy that travels is stamped *sent via DIABLE* — the file on your PC is left alone. The island shows **Generating QR…** while the link comes up. The picture is never uploaded to a file host: it is served from your PC, for 2 hours, while DIABLE is open. If you would rather not, it falls back to a link straight to this PC, which needs the phone on the same Wi-Fi and Windows Firewall letting DIABLE in.

<br>

## The command bar

Press **Right Alt + Space** anywhere and start typing.

<img src="assets/ui/command-bar.png" width="620" alt="The command bar">

| Type | You get |
|---|---|
| `spotify`, `downloads`, `vsc` | The app or file, ready to open. Initials work. |
| `github.com` | Opens the site. Anything else searches the web. |
| `12 * (3 + 4) / 2`, `20% of 150`, `sqrt 2` | The answer. Enter copies it. |
| `5 km to mi`, `100 f to c`, `2 gb to mb` | The converted value. |
| `100 usd to inr` | Live exchange rates. |
| `note buy milk` | Saves a note. |
| `remind me in 20 min to stretch` | A reminder in the island, with a glow flash and a snooze button. `at 5pm` and `tomorrow at 9` work too. |
| `countdown Exams 15 Dec` | A countdown. The nearest one shows on the resting island. |
| `snip ;addr = 12 Park Road, City` | A snippet. Type `;addr` in any app and it turns into your address. |
| `clip invoice` | Searches what you've copied. |
| `watch BTC`, `watch AAPL` | Adds a coin or a share to the Live panel. |
| `track 1Z999AA10123456784` | Works out the carrier and keeps the parcel in the Live panel. |
| `flight AIC302` | Follows a flight by its callsign. |
| any word | Finds your notes, reminders, countdowns and the songs you played this week. |

<img src="assets/ui/command-calc.png" width="620" alt="The calculator in the command bar">

<br>

## Copy and paste, improved

When you copy text, the island offers:

- **Translate** into your language.
- **Clean up** copies a plain-text version with tidy spacing and straight quotes, and turns ALL-CAPS text back into normal sentences.
- **Pin** keeps it at the top of your clipboard, even after a restart. You can also right-click anything in the clipboard list to pin it.
- **QR** turns it into a code to scan with your phone.

With [a model set up](#ask-the-island), one more button appears first, and which one depends on what you copied: **Fix error** on a stack trace, **TL;DR** on a wall of text, **Reply** on a message, **Explain** on a query, a cron line or a pattern.

When you take a screenshot, **Copy text** reads the words in it and copies them, using Windows' own text recognition.

<br>

## Ask the island

Point DIABLE at a model and the island answers things, without a chat window anywhere. The answer types itself out in the pill with a **Copy** button, and goes away when you click away.

**What you copy** gets one button, picked from what it looks like: a stack trace or a compiler error gets **Fix error** (the cause, then the fix, in two lines), a long article **TL;DR**, a message **Reply** with three drafts — casual, direct and polite — and a SQL query, a cron line or a regex **Explain**, in plain English.

**What's on your screen**: open the command bar and say what you want, in your own words.

```
explain this chart on my screen
read this email and draft a reply
give me a summary of this page
convert this table to CSV
what is this error about?
```

It takes a picture of the window you were just in, asks about it, and streams the answer back into the island. The picture is never saved to your disk. *Ask about the screen* can have a key of its own under Settings › Shortcuts.

Typing a name still opens the app — `spotify`, `downloads`, `12 * (3 + 4)` and the rest are never read as questions. Only a line that is plainly about what's on screen goes to the model, one that could be either is offered *below* your apps and files, and putting `ask` at the front forces it when you want to be sure.

**Every answer is kept.** Scroll on the island for quick actions and open **AI**: what you asked, what came back, and when. Click one to copy the answer again, right-click to forget it. Clean room blanks them like anything else personal.

### Setting it up

Tray icon › **AI**. Pick where the answers come from:

| Provider | |
|---|---|
| **On this PC** · Ollama or LM Studio | Free, private, nothing leaves the machine |
| **OpenAI** · **Anthropic** · **Google Gemini** · **Groq** · **OpenRouter** | Your own key. The panel links straight to the page where that provider keeps its keys |
| **Another server** | Anything else that speaks the OpenAI API — give it an address |

Then open the **Model** list: it fills itself with what your key or your server actually serves, so there is no model name to look up or get wrong.

**On this PC, in one button.** *Install a free model on this PC* fetches Ollama and a small model that can read pictures — about 4 GB in one go. Choose the folder it all goes in first, and the models go there too, not onto your C: drive. A pill appears in the island's row with the percentage while it comes down, so you can carry on working and still see where it is up to; click it for the full tile.

Already have Ollama? DIABLE finds it — in your chosen folder, in its own, wherever its uninstall entry points, or on your PATH — so it is never installed twice, and a model you already downloaded is used as it is. An Ollama that is installed but not running still counts as set up: it stays closed until you ask something, and is started then.

Leave it on *On this PC* with nothing installed and the feature simply stays off, as it ships.

<br>

## Lyrics

Lyrics light up word by word, in time with the song, and take their colours from the album cover. Open them from the tray, the island or settings. With a second monitor they can run full screen there while you work on the first.

Every shot below is the same play of **Travis Scott — HIGHEST IN THE ROOM**, caught at a different second of the track. The blues come out of that cover on their own.

| | |
|:-:|:-:|
| <img src="assets/styles/aura.jpg" alt="Aura"><br>**Aura** | <img src="assets/styles/neon.jpg" alt="Neon"><br>**Neon** |
| <img src="assets/styles/imessage.jpg" alt="iMessage"><br>**iMessage** | <img src="assets/styles/maps.jpg" alt="Maps"><br>**Maps**: places in the song fly in on a map |
| <img src="assets/styles/codestyle.jpg" alt="Codestyle"><br>**Codestyle** | <img src="assets/styles/kinetic_space.jpg" alt="Kinetic Space"><br>**Kinetic Space** |
| <img src="assets/styles/fisheye.jpg" alt="Fisheye"><br>**Fisheye** | <img src="assets/styles/karaoke.jpg" alt="Karaoke"><br>**Karaoke**: scores your timing if you sing |
| <img src="assets/styles/branches.jpg" alt="Branches"><br>**Branches** | <img src="assets/styles/constellation.jpg" alt="Constellation"><br>**Constellation** |

**Notifications** is the quiet one: each line arrives as a banner from your own system — the album art as its icon, "now" beside it — slides in from the right, sits while it is sung and slides out to the left as the next one lands. Two at a time, neutral white on near-black glass, so the colour in the room stays with the edge glow.

Also Cover, Orbit, Cinema, Kinetic Stack and Echo Stack.

The lyrics menu can also:

- translate the lyrics line by line
- shift the highlight warmer in a loud chorus and cooler in a quiet verse
- nudge the timing with `[` and `]` when a song runs early or late
- put lyrics on your desktop behind your windows, in a floating pill, or on as a screensaver
- **Falling words** (Extras): each line that is sung drops out of the island a word at a time, lands on whatever windows you have open, slides off their edges and piles up at the bottom of the screen. Drag a window and the words resting on it come along and scatter. A line that names rain, snow, fire, love or stars brings a few of those down with it. Off until you switch it on
- save a line with `F`, turn it into a picture to share or set as your wallpaper, and search with `Ctrl + F` to jump the song to a line
- make a **postcard** of the line being sung: six seconds of liquid metal in the album's colour with the words riding over it, saved as a looping GIF in Pictures › DIABLE, ready to post

<br>

## Shortcuts

Every feature can have a keyboard shortcut of its own: the island, the command bar, lyrics, "What's this song?", focus mode, each of the island's panels, the colour picker, the GIF recorder, the microphone, keep awake and the clean room.

| Keys | Does |
|---|---|
| `Right Alt` `Space` | Open the command bar |
| `Right Alt` `L` | Hide or show the island |
| `Right Alt` held | Peek: badges on every window, the clipboard and any timer by the pointer |
| `Right Ctrl` `L` | What's this song? |
| `F` | Save the line being sung (lyrics window) |
| `Ctrl` `F` | Search the lyrics |
| `[` `]` | Lyrics earlier or later |

**Settings › Shortcuts** lists them all. Click one, press the keys you want: Esc cancels, Backspace turns it off. Left and right Ctrl, Alt and Shift count as different keys, and if another feature already holds a combination it says which one rather than quietly taking it.

<br>

## Sharing your screen

**Clean room** keeps what is nobody else's business off the screen while you share it: clipboard previews turn to dots, your notes and reminders are held back, notifications stop popping up and wait in the island instead.

It comes on by itself while Zoom, Teams, Discord, Slack, Webex or OBS is running, and there is a quick tile (and a shortcut) for switching it on any time. A sharing app that is still running holds it on, so it is never dropped early by accident.

**Pause music on calls** is a separate switch: while a call app holds your microphone the music pauses, and it starts again when the call ends. It only restarts what DIABLE paused, so hanging up never overrides your own decision to stop the music.

<br>

## From a terminal

Scripts, builds and CI can talk to the island:

```
DIABLE notify "Build" "Tests passed"
DIABLE progress 40 "Deploy" "Uploading"
DIABLE flash #22c55e
DIABLE confetti
```

The installer puts DIABLE on your PATH, so this works in any terminal opened afterwards. The command goes straight to the copy of DIABLE running as you on this PC — nothing is sent over the network, and nothing but these four commands is accepted.

<br>

## What leaves your PC

| Feature | Sends | To |
|---|---|---|
| Lyrics | Song title and artist | [LRCLIB](https://lrclib.net), a free lyrics library |
| Weather | Your location, rounded to about 1 km | Open-Meteo |
| Song recognition | An audio fingerprint, not the audio | Shazam |
| Translation | The text you asked to translate | Google Translate |
| Currency | Nothing about you, just a request for today's rates | open.er-api.com |
| Speed test | Test data, nothing about you | Cloudflare's speed test (speed.cloudflare.com) |
| Scores | Nothing about you, just today's fixtures | TheSportsDB |
| Share and coin prices | The symbols you follow | Yahoo Finance and CoinGecko |
| Sunrise, sunset and prayer times | Your location, rounded to about 1 km | aladhan.com |
| Flights | The callsign you asked about | adsb.lol |
| Parcels | Nothing. The carrier is worked out on your PC and the number only leaves it when you open their page | — |
| News headlines | Nothing about you, just a request for the feed | BBC News (the Times of India in India) |
| Sending to your phone | The files you choose | Your phone, directly over your Wi-Fi |
| A photo by QR | The picture you choose, as it is opened | Through Cloudflare's tunnel, to whoever has the link. Served from your PC, never stored by them |
| Tint Windows to the album | Nothing. The colour is written to your own Windows settings | — |
| Gaze focus, walk away, nod to answer | Nothing. The camera is read on your PC, frame by frame, and no picture is kept or sent | — |
| Ask the island, with a model on your PC | Nothing. The model runs on your PC, and what you copied or looked at never leaves it | — |
| Ask the island, with your own key | Only what you asked about: the text you copied, or a picture of the window you asked about | The provider whose key you pasted |
| Clean room, focus spotlight, stem lighting | Nothing | — |
| Terminal commands | Nothing. They go to DIABLE on this PC, over a pipe only your Windows account can open | — |

Nothing else. No account, no analytics. Your microphone is only used by Karaoke's *Sing along*, while it's on, and never leaves the PC. Text recognition runs on your PC. Snippets watch only the last few characters you type, in memory, and only while you have at least one snippet.

<br>

## Questions

**My player isn't picked up.** DIABLE follows whatever shows in the box that appears when you press a volume key. If your player doesn't show there, it doesn't tell Windows what it's playing.

**A song has no lyrics.** Not every song has synced lyrics in the library yet, especially very new or rare ones.

**Does it slow down games?** The glow and island pause for full-screen games and never take focus.

**Why doesn't the Game HUD show FPS?** Reading another app's frame rate needs a system trace that only works as administrator. The HUD also can't draw over games in exclusive full screen, only borderless or windowed ones.

**My phone doesn't show up for sending.** LocalSend has to be open on the phone, both devices on the same Wi-Fi, and "Require PIN" off in LocalSend's settings. Then press **Look again**.

**The QR of a photo won't open on my phone.** It should work on any network. If it fails, you are most likely on the Wi-Fi fallback — say yes to the Cloudflare link when DIABLE offers it, and check this PC is online.

**My webcam light is on.** Gaze focus and *Lock when you walk away* have to watch continuously, so the light stays on while either is switched on. *Nod to answer banners* is different: it only opens the camera while a banner is waiting for you, and closes it again straight after. With all three off the camera is closed and the light is out.

**Gaze focus doesn't move the keyboard.** It holds off when nobody has touched the PC for a while, when you struck a key a moment ago, and while one of DIABLE's own windows has the keyboard — all so it can't take your typing somewhere you didn't mean. Open **Preview & calibrate** under the switch to see what it is reading.

**A snippet doesn't expand in one app.** Windows doesn't let normal apps type into programs running as administrator.

**Windows didn't change colour.** Tint Windows to the album turns on Windows' two "show accent colour" settings for you. If your colour looks stuck after turning it off, it is restored when DIABLE closes normally — force-quitting it leaves the colour until DIABLE next starts.

**DIABLE isn't a command my terminal knows.** The PATH entry only applies to terminals opened after installing. Open a new one.

**How do I uninstall?** Windows Settings › Apps › DIABLE › Uninstall.

<br>

<div align="center">
<sub>Made by Vinsmoke · <a href="https://github.com/ayaanoski/diable-by-vinsmoke/issues">Report a bug or suggest something</a></sub>
</div>
