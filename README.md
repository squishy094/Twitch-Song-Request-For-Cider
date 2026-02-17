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

### 1. Connect to Twitch & Cider
* Click **"Login with Twitch"** to authorize the bot.
* Open **Cider** and ensure music is playing or paused (not closed).
* Wait for both status lights in the footer to turn **Green**.

### 2. Choose Your Request Mode
You can use this bot in two ways: **Free Commands** or **Channel Points**.

#### Option A: Free Commands (Default)
* **How it works:** Any viewer can type `!sr [song name]` in chat to request a song for free.
* **Setup:** No extra setup required. This is enabled by default.

#### Option B: Channel Points Mode
* **How it works:** Viewers must spend Channel Points to request a song. The `!sr` command will be **disabled** for normal users so they cannot bypass the cost.
* **Setup:**
    1. Open the **Cider Song Request App** and go to the **Settings** tab.
    2. Check the box **"Use Channel Points"**.
    3. Enter the **Title** you want for the reward (e.g., "Song Request") and the **Cost** (e.g., 500).
    4. Click the **"Create Reward"** (or "Save") button.
    5. The app will automatically communicate with Twitch to create the reward for you.
    > **Note:** If you ever delete the reward from your Twitch Dashboard, you can recreate it here.

### 3. Managing the Queue
* The app interface shows the current list of requested songs.
* You can **Skip**, **Remove**, or **Clear** the queue directly from the app.

## 💡 Feedback & Support
I welcome suggestions for new features or improvements! However, please keep in mind:
* I **cannot commit to or promise** that I will fix every issue or implement every suggestion.
* This is a side project I maintain in my free time.
* Pull requests are welcome if you would like to contribute a fix yourself!

## 📄 License
This project is licensed under the **MIT License** - see the LICENSE file for details. You are free to use and modify this, but I accept no liability for any issues that arise from its use.
