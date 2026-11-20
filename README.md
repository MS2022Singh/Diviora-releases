# Installing DIVIORA Music

Everything is on one page: **https://github.com/MS2022Singh/Diviora-releases/releases/latest**. Open it and tap or click the
file for your device (scroll down to **Assets** if the files are not visible). No GitHub account is needed.

## Android phone or tablet
1. On the phone, open the page above in **Chrome**.
2. Tap **DIVIORA-Music-Android.apk**. If Chrome warns "File might be harmful", tap **Download anyway**.
3. When it finishes, tap **Open** (or find it in **Files → Downloads**).
4. If the phone says "For your security, your phone is not allowed to install unknown apps from this source",
   tap **Settings**, switch on **Allow from this source**, then press **Back**.
5. Tap **Install**, then **Open**.
6. Allow **Music and audio**, **Photos and videos** and **Notifications** when asked.
7. For routines that start on the exact minute: in DIVIORA open **Settings → Routine reliability check**. Every line
   should show a green tick. Tap **Open** next to any red line and switch it on (see the phone-brand tips in the
   [user guide](USER_GUIDE.md#routines-did-not-play)).

**Updating:** DIVIORA checks for new versions by itself. When one is out, Home shows **"Update available"** (and you get a notification) → tap it → **Download** → **Install**. The first time, Android asks you to allow DIVIORA to install apps: tap **Allow**, switch on **Allow from this source**, go back and tap **Install**. Your library, playlists and routines are kept. You can also check in **Settings → App updates → Check now**.
**Uninstalling:** long-press the DIVIORA icon → **App info → Uninstall**.

## Windows 10 / 11
1. Click **DIVIORA-Music-Windows.msi** on the download page.
2. Open the downloaded file. If **"Windows protected your PC"** appears, click **More info → Run anyway**. This appears
   because the installer is not code-signed yet.
3. Click **Next**, choose a folder if you want, then **Install → Finish**.
4. Start **DIVIORA Music** from the Start menu.
   **Update:** when DIVIORA shows *"… is available"*, click **Download update** and run it. **Uninstall:** Settings → Apps → DIVIORA Music → Uninstall.

## macOS
1. Click **DIVIORA-Music-macOS.dmg** and open it.
2. Drag **DIVIORA Music** into **Applications**.
3. First launch only: in Applications **right-click DIVIORA Music → Open → Open**, because the app is not notarised by Apple
   yet. If macOS still blocks it: **System Settings → Privacy & Security → Open Anyway**.

## Linux (Ubuntu, Debian, Mint)
1. Download **DIVIORA-Music-Linux.deb**.
2. Double-click it and choose **Install**, or in a terminal:
   ```bash
   sudo apt install ./DIVIORA-Music-Linux.deb
   ```
3. Start **DIVIORA Music** from the applications menu.
   **Uninstall:** `sudo apt remove diviora-music`

## Desktop notes
- Closing the window keeps DIVIORA running in the **system tray** (near the clock), so routines can still play. To quit,
  right-click the tray icon → **Quit**.
- Desktop plays MP3, M4A/AAC, WAV, AIFF, MP4 and HLS streams. YouTube and Spotify links open in your browser on desktop.
