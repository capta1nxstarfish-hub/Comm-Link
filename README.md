# Comm-Link

Comm-Link is a dark, scmdb-styled app for RSI's Spectrum community chat, for Android and Windows. It is simply RSI's own Spectrum website (robertsspaceindustries.com/spectrum) shown in an app window with a cleaner theme. Comm-Link collects no data: there are no analytics or trackers, and your login goes straight to RSI. It never passes through Comm-Link or any other server.

> **Unofficial fan project, not affiliated with or endorsed by Cloud Imperium Games / Roberts Space Industries. Star Citizen and Spectrum are trademarks of CIG.**

## Download

Get the latest builds from the [Releases page](../../releases).

- **Android:** `Comm-Link-Android-vX.XX.apk`
- **Windows:** `Comm-Link-Windows-X.X.X.zip`

## Install

### Android
1. Download the APK from the Releases page on your phone.
2. Open it. If prompted, allow your browser or file manager to **install unknown apps** (Settings > Apps > Special app access > Install unknown apps).
3. Tap **Install**. Future versions install over the top, and you stay signed in.

### Windows
1. Download the zip from the Releases page.
2. Extract it anywhere, for example `C:\Users\<you>\AppData\Local\Programs\Comm-Link`.
3. Run `Comm-Link.exe`.
4. The app isn't code-signed, so Windows SmartScreen may warn you. Click **More info > Run anyway**.

## Verify your download

Each release includes `SHA256SUMS.txt`. Check that your file's hash matches:

- Windows (PowerShell): `Get-FileHash .\Comm-Link-Windows-1.3.10.zip -Algorithm SHA256`
- Linux/macOS: `sha256sum -c SHA256SUMS.txt`

Android APKs are always signed with the same key, with certificate SHA-256 `2086b23a21cb0663f3b3eda7a353a82a21ea8bb3cd96c920f51d9b3981024422`.

## Free, forever

Comm-Link is free and made for the community. It isn't sold, there are no ads, and it makes no profit. o7 from Captain Starfish.
