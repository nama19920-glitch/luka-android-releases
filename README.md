# Luka Companion — Android releases

Official Android APK distribution for Luka Companion. Source code and signing keys remain private.

## Latest: 2.6.29 (289)

Android 8+. Updates current production-signed installations (2.6.21+).

Fixes gift-picker Cancel independently of earlier confirmations. Reads Epic or console friend names with a labeled fallback when unavailable. Settings shows the version. Shop cards retain official New metadata; returning items are not marked new merely because they enter a fresh local cache.

Retains official website wallet, account-specific ownership, purple dashboard, light/dark themes, bundle contents, previews, creator controls, update download size/progress and HTTP 429 Retry-After cooldown without automatic retry.

Node tests, Java navigation/cooldown regressions, UI fixtures including gift cancellation, Android release build and lint passed. No live gifting or purchase performed.

Signing: uploaded Luka-Companion-1.4.0-Android.apk uses a different ephemeral Android Debug key. Its original private key is unavailable, so this release cannot update that APK in place. Do not uninstall before ensuring account access can be relinked. Production signing remains unchanged from 2.6.21 onward. In-app updates validate SHA-256, package, version and certificate.

Download the APK from the latest release assets. android-update.json and SHA256SUMS.txt accompany every release.
