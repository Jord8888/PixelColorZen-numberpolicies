# Privacy Policy — Pixel Color Zen

_Last updated: May 14, 2026_

Pixel Color Zen is a single-player coloring game published by Jordan
Petersen. This policy describes, in plain language, what the app does
and does not do with your information. It is written to be accurate
for the Google Play "Data safety" form.

## Short version

**Pixel Color Zen does not collect, transmit, or share any personal
information.** Every piece of data the app creates — puzzle progress,
streak counts, perfect-run badges, play-mode preferences — lives on
your device in Android's standard app-private `SharedPreferences`
storage. It never leaves your device through the app.

The app makes no network requests, runs no analytics, includes no
advertising SDKs, and integrates with no third-party services.

## What is stored, where, and why

The app uses Android's `SharedPreferences` (private to ColorFlow
Number — no other app on the device can read it) to remember:

- **Per-puzzle fill state** — which cells you've painted in each
  puzzle, so you can pick up where you left off after closing the
  app.
- **Per-puzzle play mode** — whether you started the puzzle in
  Kids, Zen, or Speed mode.
- **Per-puzzle run statistics** — wrong-fill count and whether the
  Undo button was used, for awarding the perfect-run gold-border
  badge.
- **Daily streak** — number of consecutive days you've completed
  at least one puzzle, plus the last day you completed on
  (stored as a local-midnight epoch-day integer).
- **Easter-egg unlock state** — purely in-memory for the current
  session; not persisted.

All of this is purely local. The app never reads from or writes to
any server.

## Cloud backup and device transfer

- **Cloud backup is disabled.** Pixel Color Zen opts out of Google
  Drive auto-backup on every supported Android version (6.0
  through 15+). If you uninstall the app or wipe your device,
  your progress will not be restored from the cloud — because
  it was never sent there.
- **Device-to-device transfer is allowed** on Android 12 and
  newer. If you set up a new phone using Google's wireless
  device-transfer flow, your puzzle progress, streak, and
  badges travel with you. This transfer is between your devices
  only and does not pass through any server controlled by us.

## Permissions

Pixel Color Zen requests no Android runtime permissions. The
manifest declares no internet, location, camera, microphone,
contacts, storage, or other sensitive capability. (The app
literally cannot make a network request — no `INTERNET`
permission is declared.)

## Sharing your completed images

When you finish a puzzle, a "Share image" button appears on the
completion dialog. Tapping it renders the completed picture as a
PNG in the app's internal cache directory, then opens Android's
standard share chooser so you can send the image to another app
(Photos, Messages, social media, etc.). The choice of recipient
app and what happens to the image after that is entirely yours.

The PNG never leaves your device through this app. We do not
receive a copy, do not log that you shared, and do not see which
app you chose. The cache file is a normal app-private file that
gets cleared along with the rest of the app cache.

## Ads and analytics

There are no ads. There is no analytics. There is no telemetry.
There are no SDKs from Google, Meta, Unity, Firebase, AppsFlyer,
Adjust, Sentry, Crashlytics, or any other third party.

## Children's privacy

Pixel Color Zen is family-friendly and suitable for children.
Because the app collects no information and makes no network
requests, it does not knowingly or unknowingly collect data
from anyone, including children under 13. The app should comply
with COPPA and Google Play's Families Policy on this basis.

## Changes to this policy

If the app ever starts collecting data, integrating with a
network service, or adding any feature that would change the
statements above, this policy will be updated and the app's
version on the Play Store will reflect the change. The
"Last updated" date at the top of this document is the
canonical signal.

## Contact

For questions about this policy, contact:
**jpetersen@pgtek.com**
