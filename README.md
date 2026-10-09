# Luka Companion — Android releases

Official Android APK distribution for Luka Companion. Source code and signing keys remain private.

## Latest: 2.6.25 (285)

Requires Android 8 or newer. Install over the existing signed application without uninstalling to keep saved accounts.

2.6.25 fixes the verified shop bootstrap: after confirming the account, a fresh exchange code targets the Fortnite shop rather than the identity-verification redirect page. Authentication redirects are allowed only during this bootstrap, and stale callbacks are rejected.

The app retains website-only V-Bucks, direct shop reads, button press animation, update download size/percentage, the purple dashboard, light/dark themes, account tabs, item previews, ownership indicators, bundle contents and creator-code controls.

Android build, lint, ten automated tests and interface fixtures passed. Live-account/device behavior still requires verification.

The APK uses the permanent production certificate from 2.6.21 onward. In-app updates validate SHA-256, package, version and signing certificate before installation.

Download the APK from the latest release assets. `android-update.json` and `SHA256SUMS.txt` accompany every release.
