# OpenHDS Pro 2.0.112

## Fixed

- Fieldworker synchronization now checks the protected server URL instead of the removed legacy plain-text preference.
- The synchronization connection allowance was increased from 3 to 15 seconds for slower field networks.
- Synchronization feedback is now clear and no longer labels every failure as an HDSS entity failure.

## Household visits

- Multiple distinct visits to the same household remain supported.
- Required-work and duplicate protections remain scoped to the individual visit identifier, so completing one visit does not block a later visit to that household.

## Safe update

Install this APK over the existing OpenHDS Pro installation. Do not uninstall the current app, because uninstalling can remove locally stored fieldwork.
