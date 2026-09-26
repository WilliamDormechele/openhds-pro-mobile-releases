# OpenHDS Pro Mobile Releases

This public repository hosts official signed OpenHDS Pro Android release APKs for field tablets.

## Safe field updates

- Install a newer APK over the existing app; do not uninstall the current app first.
- Android preserves the app's ongoing fieldwork data during an in-place update.
- OpenHDS Pro accepts only a newer APK with the expected package name and the same trusted release signature.
- Back up and synchronise field data according to programme procedures whenever connectivity permits.

Release signing credentials and private recovery material are never stored in this repository.

## Current release

OpenHDS Pro 2.0.206 is the current production field release.

- Fixes the live HDSS visit synchronization failure seen on 2.0.205.
- Preserves existing local HDSS snapshots if an export cannot be parsed or inserted safely.
- Restores the fieldworker **Check app update** control for future in-app updates.
- Requires the official production APK, GitHub SHA-256 integrity metadata, the OpenHDS Pro package name, a newer version code, and the trusted production signing certificate.
- Existing 2.0.205 tablets require one controlled in-place installation of 2.0.206. Do not uninstall the app or clear application data.
- From 2.0.206 onward, fieldworkers can check for and install newer production releases from the dashboard.

Current production APK: `OpenHDS-Pro-2.0.206.apk`

SHA-256: `022DA69D259CCC765D75D7AC22BEAEF206A52B93AA5261B3DE3A297B19CBA006`
