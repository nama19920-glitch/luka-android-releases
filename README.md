# Luka Companion — Android releases

Official Android APK distribution for Luka Companion. Source code and signing keys remain private.

## Latest: 2.6.28 (288)

Android 8+. Install over the existing signed application without uninstalling to keep saved accounts.

2.6.28 honors the official shop's HTTP 429 Retry-After cooldown, blocks navigation/reconnect during that interval, stops failed-page scans and preserves the same account's loaded website wallet, ownership and cards on retry. No automatic retry is performed. The trusted authentication-route fix from 2.6.27 remains included.

Retains the purple dashboard, light/dark themes, account tabs, item previews, bundle contents, creator controls, button feedback and update download size/progress. Wallet reads remain website-only.

Node tests, Java navigation/cooldown regressions, interface fixtures, Android build and lint passed. Live-device behavior requires verification.

The APK uses the permanent production certificate from 2.6.21 onward. In-app updates validate SHA-256, package, version and signing certificate before installation.

Download the APK from the latest release assets. `android-update.json` and `SHA256SUMS.txt` accompany every release.
