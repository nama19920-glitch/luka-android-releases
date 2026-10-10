# Luka Companion — Android releases

Official Android APK distribution. Source and signing keys remain private.

## Latest: 2.6.35 (306)

[Download Luka 2.6.35 for Android](https://github.com/nama19920-glitch/luka-android-releases/releases/download/android-v2.6.35/Luka-2.6.35-Android.apk)

Android 8+. Install over the current production-signed version without removing the app or its saved accounts. The signing certificate is checked against the currently published 2.6.33 APK before publication.

- Daily STW alerts with actual mission power, bundled map symbols, region names and reward rarity; V-Bucks rewards use Mythic styling.
- Notifications when daily alert data changes, with duplicate prevention and a shortcut to the alert page.
- Automatic shop refresh on launch and a refresh button beside the home V-Bucks wallet.
- A blue V-Bucks balance bar stays visible while scrolling the item shop.
- Custom vector icons, a dimmed account-linking wait screen with animated progress, and a language-change transition.
- Empty daily quests show a clear message and disable daily login until the next reset.

The latest `android-update.json` feed offers this release inside the app. Background update notifications appear when the device performs its scheduled check; Android notification permissions and power management apply.

Validation covers 37 data tests, Java notification/navigation checks, Arabic/English UI fixtures, production signing, APK build/lint and Android 14 startup with notification-job scheduling. Fixture purchase/gift checks do not execute live transactions.

Every release includes its APK, `android-update.json` and `SHA256SUMS.txt`. The updater verifies package, version, installed signer and SHA-256 before installation.
