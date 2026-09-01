# OpenHDS Pro 2.0.111

## Changes

- Fixed HDSS entity synchronization after the OpenHDS Server URL was moved to encrypted device storage.
- Fixed extra-form synchronization to use the protected server URL.
- Restores hierarchy levels, rounds, locations, compounds, households and visits on newly configured tablets.
- Prevents automatic inactivity sign-out while a supervisor synchronization is actively running.
- Retains all existing dashboard, field-quality, listing, assignment and protected data-relay functionality.

## Recovery after the earlier failure

Install this update, sign in as supervisor and run **Sync HDSS Data** again. The hierarchy will appear after a successful download. Then run **Sync Fieldworkers** and **Sync Extra Forms**.

## Installation

Install this APK over the existing OpenHDS Pro application. Do **not** uninstall first because uninstalling can remove ongoing fieldwork.
