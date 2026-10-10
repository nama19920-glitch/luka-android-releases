# Luka Companion — Android releases

Official Android APK distribution for Luka Companion. Source code and signing keys remain private.

## Latest: 2.6.30 (290)

Android 8+. Updates current production-signed installations (2.6.21+).

Successful official shop cards/previews clear stale shop and cooldown notices. Navigation restarts the verified reader after a failed page. Main-frame HTTP 429 still respects Retry-After without automatic network or transaction retries.

Centered version, clearer button borders and visible touch feedback in both themes. Enable update notifications in Settings and allow Android notification permission. A persisted background job checks the public release feed every six hours and notifies once per newer version. Delivery can be delayed by Android power management; notifications have not been tested on a physical handset.

Retains official website wallet, account-specific ownership, gift cancellation, Epic/console friend labels, New metadata, purple dashboard, light/dark themes, bundle contents, previews, creator controls and update download progress.

Eleven Node tests, Java navigation/cooldown checks, fixture UI regressions including status recovery, Android release build and lint passed on run 38012799533. No live gifting or purchase performed.

Signing remains unchanged from 2.6.21 onward. Legacy 1.4.0 uses a different debug key whose original private key is unavailable and cannot be updated in place with this signer. In-app updates validate SHA-256, package, version and certificate.

Download the APK from the latest release assets. android-update.json and SHA256SUMS.txt accompany every release.
