# Support & Frequently Asked Questions

Welcome to the **Vzon Launcher** support guide. Here you will find answers to frequently asked questions, configuration tips, and channels for troubleshooting.

---

## 🚀 Quick Setup & Best Practices

### 1. Setting Vzon as Your Default Launcher
1. Install the latest signed APK from [GitHub Releases](https://github.com/SeNsXD/Vzon-Launcher/releases).
2. Open Android **Settings → Apps → Default Apps → Home App**.
3. Select **Vzon Launcher**.
4. (Optional) For swipe-down notification shade access, enable the Vzon Accessibility Service when prompted.

### 2. Enabling the Hero Media Card
1. Navigate to Android **Settings → Apps → Special app access → Notification access**.
2. Toggle on **Vzon Launcher media card**.
3. *Note:* Vzon only reads active media playback sessions (Spotify, YouTube Music, Apple Music, etc.) to show track title, artist, and playback controls. It never reads or records your private messages.

### 3. Enabling Live Weather
1. In Vzon Home, tap the Weather hero card or grant **Location (Coarse/Approximate)** permission.
2. Vzon connects directly to the Open-Meteo API (free, open, no personal telemetry). Weather data updates quietly every 30 minutes via Android WorkManager without draining your battery.

---

## ❓ Frequently Asked Questions (FAQ)

### Is Vzon Launcher open source?
**No.** Vzon Launcher is developed as a closed-source, proprietary application by [xdNOT Labs](https://github.com/SeNsXD). This repository serves as our public release hub, documentation showcase, and community feedback center. Source code is not publicly distributed.

### Does Vzon Launcher have ads or track my data?
**Never.** Vzon Launcher contains zero advertising SDKs and zero telemetry libraries. Your app usage habits, notifications, and location stay 100% on your device.

### Which Android versions are supported?
Vzon Launcher is built with modern Jetpack Compose and is compatible with **Android 8.0 Oreo (API 26) through Android 16 (API 36)**. For optimal 120Hz animations and predictive back gestures, Android 13 or newer is recommended.

### How do I backup or transfer my layout?
Open **Launcher Settings → Backup & Restore** to export your setup (dock apps, pinned pages, custom folder arrangements, and feed widgets) into a lightweight JSON file. You can import this file onto any other device running Vzon Launcher.

---

## 💬 Community & Help Channels

- **Bug Reports:** Open an issue via our [GitHub Bug Tracker](https://github.com/SeNsXD/Vzon-Launcher/issues).
- **Feature Requests:** Share ideas in [GitHub Discussions](https://github.com/SeNsXD/Vzon-Launcher/discussions).
- **Beta Community:** Join our Telegram updates channel at [@xdNOT_Labs](https://t.me/xdNOT_Labs).
