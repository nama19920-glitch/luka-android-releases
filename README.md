# Luka Companion — Android releases

Official Android APK distribution for Luka Companion. Source code and signing keys remain private.

## Latest: 2.6.31 (291)

Android 8+. Updates current production-signed installations (2.6.21+).

Fixes Android 14+ startup failure by declaring ACCESS_NETWORK_STATE for the network-constrained update job. Background job scheduling failures cannot prevent app startup. Install over the current version without removing application data.

Retains official shop wallet, account-specific ownership, gifts, cancellation, bundle contents, previews, creator controls, themes, button feedback, centered version and download progress. Background update notifications remain optional and may be delayed by Android power management.

Node tests, Java navigation/cooldown checks, fixture UI regressions, release build and lint passed. The production-signed APK launched twice on an Android 14 emulator and its update job scheduled successfully on run 38014629695. No live purchases or gifting performed; no physical-handset notification test.

Signing remains unchanged from 2.6.21 onward. Legacy 1.4.0 uses a different debug key whose original private key is unavailable. In-app updates validate SHA-256, package, version and certificate.

Download the APK from the latest release assets. android-update.json and SHA256SUMS.txt accompany every release.
