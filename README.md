# 📱 Mafia Master APK (Android Releases)

This repository contains the official pre-compiled Android APK releases for the **Mafia Master (Moderator Console)**. 

Mafia Master is a premium, mobile-first companion app for the classic party game Mafia / Werewolf. It allows game moderators to secretly assign roles, guide players through Night & Day rounds, and track actions efficiently.

---

### How to Install on Android
1. Download the `.apk` file using your mobile browser.
2. Tap the downloaded file to install it.
3. If prompted with *"Blocked by Play Protect"* or *"Install from Unknown Sources"*:
   - Tap **Settings** / **Install Anyway** to enable installation.
   - (Rest assured, this is a self-signed package and contains no trackers or malicious code).
4. Launch **Mafia Master** from your app drawer and enjoy your game!

---

## ✨ Features in the Android App

- **Full Offline Support**: Run games anywhere, even without an internet connection.
- **Haptic/Vibration Feedback**: Micro-feedback during button presses and reveals.
- **Ambient SFX**: Direct audio output for sound guides.
- **Auto Game Save**: If the app is closed, resuming it brings back the current round and player configurations instantly.

---

## 🛠️ Build & Development Info

This APK was built from the source repository using **Capacitor** and **Android Studio**.

### How this APK was built:
1. Compiled the React & Tailwind webapp into static files:
   ```bash
   npm run build:mobile
   ```
2. Synced assets to the Android platform folder:
   ```bash
   npx cap sync android
   ```
3. Compiled the release APK inside Android Studio using Gradle wrapper.

Source Repository: [mafia-master](https://github.com/jishnupl07/mafia-master)
