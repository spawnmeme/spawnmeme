# 51. Install SPAWN for Android

**Open:** [SPAWN for Android](https://spawnmeme.com/android).

SPAWN has an Android app that opens the website in a full-screen app window and connects to an installed Solana wallet. The October 12 release is **1.0.0**, for **Android 9 or newer**. The Solana dApp Store submission is **under review** in this edition; an APK download is not evidence of store approval.

## Install and connect

1. Open the official Android page on your phone and check the version and file details.
2. Choose **Download APK**. Only continue past a download warning after checking that the download came from the official page.
3. Open the downloaded file. If Android asks, allow installation from the browser you used, then return to the installer.
4. Choose **Install**, then **Open**. You can disable that browser's install permission afterwards.
5. Choose **Connect**, then **Mobile wallet**. Approve the connection in your supported installed wallet, such as Phantom, Solflare or Seed Vault on Seeker.
6. Return to SPAWN and compare the connected address. Trading and launching require separate wallet-approved transactions.

## Verify the download

The package name is `com.spawnmeme.app`. The official download page provides the current APK's SHA-256 fingerprint and a copy button. Compare the complete hash for the same release. On Windows use `certutil -hashfile <downloaded-file.apk> SHA256`; on macOS or Linux use `shasum -a 256 <downloaded-file.apk>`, replacing the placeholder with the actual filename.

## Browser alternatives and recovery

**Mobile wallet** also supports Android Chrome through Solana Mobile Wallet Adapter. If no wallet is found, install or unlock a compatible Solana wallet and retry. Keep the original SPAWN screen open while switching apps. On iPhone, continue using the website in a supported wallet browser; the Android APK does not install on iOS.

If approval is interrupted, inspect any transaction signature before trying again. The app does not require a seed phrase. **Success:** SPAWN opens and displays the intended connected Solana address.

***

[Guide home](../README.md) · [Get help](https://spawnmeme.com/help)
