# Luka Companion — Android releases

Official Android APK distribution for Luka Companion. Source code and signing keys remain private.

## Latest: 2.6.24 (284)

Requires Android 8 or newer. Install over the existing signed application without uninstalling to keep saved accounts.

- Reads the verified official shop browser directly when page messaging is unavailable.
- Displays V-Bucks from the official website only, without account-profile fallback.
- Adds button press feedback and update download size, downloaded bytes, percentage, and verification status.
- Preserves the purple dashboard, light/dark themes, saved-account tab, shop previews, ownership indicators, bundle contents and creator-code controls.

Android build, lint, eight snapshot tests and interface fixtures passed. Live-account shop behavior still needs device verification. The download progress display works for future updates after installing 2.6.24.

The APK uses the same permanent production certificate as 2.6.21 onward. In-app updates validate the SHA-256, package, version and signing certificate before installation.

Download the APK from the latest release assets. `android-update.json` and `SHA256SUMS.txt` accompany every release.
