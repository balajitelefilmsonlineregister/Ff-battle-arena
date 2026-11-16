# FF Battle Arena

Black-theme Android app starter with Home, tournaments, player registration, social links and organizer panel. The supplied YouTube, Telegram, Facebook and Instagram links are included.

## Important
This is a local preview starter, not yet a production multi-user app. Data is stored only in the device/browser localStorage and does not sync across users. Admin preview code is `ARENA-ADMIN-CHANGE-ME`; change it in `www/app.js` and do not treat it as secure authentication. Before public launch, connect Firebase Authentication and Firestore, configure server-side admin roles and security rules, and test them. Social follow/subscribe is self-attested, not automatically verified. No fees, wallet, betting or prize payout feature is enabled. Do not request game passwords or OTPs. This is independent and not affiliated with Garena/Free Fire.

## Build APK
Upload all files and folders in this ZIP to a GitHub repository, preserving `.github/workflows/android.yml`. GitHub Actions builds a debug APK; download `ff-battle-arena-debug-apk` from the completed workflow run. A debug APK is for testing, not a Play Store signed release.
