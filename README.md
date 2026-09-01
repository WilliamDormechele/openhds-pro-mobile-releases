# OpenHDS Pro Mobile Releases

This public repository hosts official signed OpenHDS Pro Android release APKs for field tablets.

## Safe field updates

- Install a newer APK over the existing app; do not uninstall the current app first.
- Android preserves the app's ongoing fieldwork data during an in-place update.
- OpenHDS Pro accepts only a newer APK with the expected package name and the same trusted release signature.
- Back up and synchronise field data according to programme procedures whenever connectivity permits.

Release signing credentials and private recovery material are never stored in this repository.

## Current release

OpenHDS Pro 2.0.112 fixes fieldworker synchronization on tablets configured with the encrypted server URL. It also improves synchronization feedback and retains visit-scoped enforcement, allowing multiple distinct visits to the same household while preventing accidental duplicate work within one visit.
