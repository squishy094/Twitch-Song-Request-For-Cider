# Twitch-Song-Request-For-Cider

**A Twitch Song Request bot for the Cider (Apple Music) Client.**

> **⚠️ Note:** This is a personal hobby application that I built for myself and my husband. It was coded entirely using **Jules AI**. I am sharing it publicly in case others find it useful, but please understand it is provided "as-is" without advanced support.

## 🖥️ Compatibility & Requirements
* **Operating System:** This application was developed and tested exclusively on **Windows 11**. It may not work on other versions of Windows or macOS.
* **Music Player:** This bot is designed strictly for **Cider** (Apple Music).
* **No External Links:** The bot **does not** accept Spotify, YouTube, or SoundCloud URLs. It only searches the Apple Music library via Cider.

## 🎵 What This App Does
This application bridges the gap between your **Twitch Chat** and your **Cider Music Player**. It allows your viewers to request songs directly from chat, which are then added to your playback queue.

* **!sr [song name]** - Viewers use this command to request songs.
* **Twitch Integration** - Connects seamlessly to your chat as a bot.
* **Cider Integration** - Controls your local Cider client to queue tracks.
* **Visual Status** - Clear Red/Green indicators to show if Twitch and Cider are connected.

## 📥 Installation

1.  Go to the **[Releases](../../releases)** page of this repository.
2.  Download the latest `CiderSongRequest_Installer.exe`.
3.  Run the installer.
4.  The app will launch automatically after installation.

## ⚙️ How to Use

### 1. Connect to Twitch
* Click the **"Login with Twitch"** button in the app.
* A browser window will open asking you to authorize the application.
* Once authorized, the **Twitch Status** light in the footer will turn **Green**.

### 2. Connect to Cider
* Open your **Cider** music app on your computer.
* Start playing music or ensure the app is active.
* The **Cider Status** light in the footer will turn **Green** once it detects Cider is running.

### 3. Let Chat Request Songs!
* Your viewers can now type `!sr [Song Name]` (e.g., `!sr Hotel California`) in your chat.
* The bot will search Apple Music, find the best match, and add it to your Cider queue.

## 💡 Feedback & Support
I welcome suggestions for new features or improvements! However, please keep in mind:
* I **cannot commit to or promise** that I will fix every issue or implement every suggestion.
* This is a side project I maintain in my free time.
* Pull requests are welcome if you would like to contribute a fix yourself!

## 📄 License
This project is licensed under the **MIT License** - see the LICENSE file for details. You are free to use and modify this, but I accept no liability for any issues that arise from its use.
