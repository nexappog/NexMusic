<div align="center">
  <img src="assets/NexMusic-logo.png" alt="NexMusic Logo" width="140"/>

  <h1>NexMusic</h1>

  <p><strong>A modern Android music app with ad-free streaming, synced lyrics, offline playback, and an intuitive user experience.
</strong></p>

  [![GitHub Release](https://img.shields.io/github/v/release/nexappog/NexMusic?style=for-the-badge&color=6f42c1)](https://github.com/nexappog/NexMusic/releases)
  [![GitHub Stars](https://img.shields.io/github/stars/nexappog/NexMusic?style=for-the-badge&color=e3b341)](https://github.com/nexappog/NexMusic/stargazers)
  [![License](https://img.shields.io/github/license/nexappog/NexMusic?style=for-the-badge&color=28a745)](LICENSE)
  [![Telegram](https://img.shields.io/badge/Telegram-Join-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/nexappog)
  [![Discord](https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/P44QdHPtKg)
</div>

---

## Overview

NexMusic delivers a seamless, premium listening experience by leveraging YouTube Music's vast library — without the ads. It adds powerful extras including offline downloads, real-time synchronized lyrics, and environment-aware music recognition.

---

## Table of Contents

- [Overview](#overview)
- [Screenshots](#screenshots)
- [Features](#features)
  - [What's New](#whats-new)
  - [Streaming & Playback](#streaming--playback)
  - [Discovery & Nex Find](#discovery--nex-find)
  - [Lyrics](#lyrics)
  - [Integrations](#integrations)
  - [Smart Playback](#smart-playback)
  - [Customization](#customization)
- [Installation & Setup](#installation--setup)
  - [Android Installation](#android-installation)
  - [Building from Source](#building-from-source)
- [Community & Support](#community--support)
- [Special Thanks](#special-thanks)
- [Star History](#star-history)

---

## Screenshots

<div align="center">
  <table style="margin: 0 auto; border-collapse: collapse;">
    <tr>
      <td align="center" style="padding: 10px; border: none;">
        <strong>Home Screen</strong><br><br>
        <img src="Screenshots/sc_1.png" alt="Home Screen" width="200" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);"/>
      </td>
      <td align="center" style="padding: 10px; border: none;">
        <strong>Music Player</strong><br><br>
        <img src="Screenshots/sc_2.png" alt="Music Player" width="200" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);"/>
      </td>
      <td align="center" style="padding: 10px; border: none;">
        <strong>Synchronized Lyrics</strong><br><br>
        <img src="Screenshots/sc_3.png" alt="Synchronized Lyrics" width="200" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);"/>
      </td>
    </tr>
    <tr>
      <td align="center" style="padding: 10px; border: none;">
        <strong>Search & Explore</strong><br><br>
        <img src="Screenshots/sc_4.png" alt="Search & Explore" width="200" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);"/>
      </td>
      <td align="center" style="padding: 10px; border: none;">
        <strong>Music Library</strong><br><br>
        <img src="Screenshots/sc_5.png" alt="Music Library" width="200" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);"/>
      </td>
      <td align="center" style="padding: 10px; border: none;">
        <strong>Nex Find (Recognition)</strong><br><br>
        <img src="Screenshots/sc_6.png" alt="Nex Find" width="200" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);"/>
      </td>
    </tr>
  </table>
</div>

---

## Features

### What's New
- **Redesigned UI** — Cleaner, faster, and more intuitive interface from the ground up.
- **Import from Spotify** — Bring your playlists and tracks over with ease.
- **Listen Together** — Sync music in real time, similar to Spotify Jam.
- **Podcast Support** — Listen to podcasts alongside your music library.
- **Local Media Support** — Play music files stored directly on your device.
- **Dynamic Island Support** — Enhanced playback notifications on supported Android devices.

### Streaming & Playback
- **Ad-Free** — Stream without any interruptions.
- **Seamless Playback** — Switch effortlessly between audio-only and video modes.
- **Background Playback** — Listen while using other apps or with the screen off.
- **Offline Mode** — Download tracks, albums, and playlists via a dedicated download manager.
- **Crossfade** — Smooth transitions between tracks.
- **Canvas Animations** — Visual animations while playing music.

### Discovery & Nex Find
- **Nex Find** — Identify songs playing around you using advanced audio recognition.
- **Nex Brain** — An intelligent, on-device engine that analyzes your listening momentum and auto-injects perfectly aligned tracks into your queue. Read more in the [Nex Brain Documentation](NEX_BRAIN_DOCS.md).
- **Smart Recommendations** — Personalized suggestions based on your listening history.
- **Comprehensive Browsing** — Explore Charts, Podcasts, Moods, and Genres.

### Lyrics
- **Multiple Lyric Animations** — Choose from various lyric display styles.
- **Word-by-Word Lyrics** — Precise per-word synchronization.
- **Lyrics+** — New lyrics provider for improved accuracy and coverage.
- **AI Translation** — Built-in Google Translate integration for lyrics in any language.

### Integrations
- **Music Sharing via Odesli** — Share songs as Song.link for cross-platform listening.
- **Set as Ringtone** — Directly set any song as your device ringtone.

### Smart Playback
- **Pause on Mute** — Auto-pause when your device is muted.
- **Resume on Bluetooth** — Playback resumes when headphones or earbuds reconnect.

### Customization
- **UI Density Scale** — Adjust interface spacing to your preference.
- **High Refresh Rate Support** — Smoother UI and animations on supported displays.
- **Hide Player Thumbnail** — Keep the player minimal without album art.
- **Crop Album Art** — Adjust album art display to fit your style.
- **Hide Video Songs** — Filter out video content from your feed.
- **Hide YouTube Shorts** — Keep Shorts out of your music browsing.

---

## Installation & Setup

### Android Installation

Download the latest pre-compiled APK from the [Releases Page](https://github.com/nexappog/NexMusic/releases/latest).

### Building from Source

1. **Clone the Repository**
   ```bash
   git clone https://github.com/nexappog/NexMusic.git
   cd NexMusic
   ```

2. **Configure Android SDK**
   Create a `local.properties` file:
   ```bash
   echo "sdk.dir=/path/to/your/android/sdk" > local.properties
   ```
   *(For detailed paths on Windows/macOS/Linux, refer to [SETUP.md](SETUP.md))*

3. **Firebase Configuration (Optional)**
   Firebase is required for analytics and crash reporting. See the instructions in [SETUP.md](SETUP.md#3-configure-firebase-optional) for adding your `google-services.json`.

4. **Build the Application**
   NexMusic has two build variants: **FOSS** (without Google Play Services / Cast) and **GMS** (with Cast support).
   
   To build the FOSS Universal Debug variant:
   ```bash
   ./gradlew assembleUniversalFossDebug
   ```
   To build the GMS Universal Debug variant:
   ```bash
   ./gradlew assembleUniversalGmsDebug
   ```
   *(For optimized ARM64 builds, release builds, or other options, refer to [SETUP.md](SETUP.md))*

---

## Community & Support

Join the community for updates, discussions, and help.

<div align="center">
  <a href="https://discord.gg/P44QdHPtKg" style="text-decoration:none;"><img src="assets/discord.png" alt="Discord Logo" width="140" style="margin: 0 10px;"/></a>
  <a href="https://t.me/nexappog" style="text-decoration:none;"><img src="assets/telegram.png" alt="Telegram Logo" width="130" style="margin: 0 10px;"/></a>
</div>

Need direct support? Email **nexapp.support@gmail.com** or [book a support session](https://arabiislam.odoo.com/appointment/1).

---

## Special Thanks

NexMusic is a fork of [Echo Music](https://github.com/iad1tya/Echo-Music) by **echodh**, and stands on the shoulders of several excellent open-source projects. Sincere thanks to:

| Project | Description |
| :--- | :--- |
| [Echo Music](https://github.com/iad1tya/Echo-Music) | The original project NexMusic is forked from |
| [Metrolist](https://github.com/MetrolistGroup/Metrolist) & [Vivi Music](https://github.com/vivizzz007/vivi-music) | Foundational inspiration and architecture reference |
| [ArchiveTune](https://github.com/koiverse/ArchiveTune) | Material You UI inspiration |
| [Better Lyrics](https://better-lyrics.boidu.dev/) | Lyrics enhancement and synchronization |
| [SimpMusic](https://github.com/maxrave-dev/SimpMusic) | Lyrics implementation reference |
| [Music Recognizer](https://github.com/aleksey-saenko/MusicRecognizer) | Audio recognition (Nex Find) |
| [Flow](https://github.com/a-edev/Flow) | AI queue generation engine (Nex Brain) |
| [zemer-cipher](hhttps://github.com/ZemerTeam/zemer-cipher) | YouTube cipher deobfuscation and PoToken generation |

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=nexappog/NexMusic&type=timeline&legend=top-left)](https://www.star-history.com/#nexappog/NexMusic&type=timeline&legend=top-left)

---

<div align="center">
  Licensed under <a href="LICENSE">GPL-3.0</a>
</div>
