# OpenHDS Pro 2.0.202

- Fixed Sync HDSS Data compatibility with the legacy OpenHDS server.
- Added safe fallback when optional compressed HDSS export endpoints are unavailable.
- Improved handling of slow legacy HDSS exports so valid synchronisation can complete without premature timeout.
- Preserves existing local HDSS entities until replacement server data has been received successfully.
- Prevents a failed or incomplete HDSS response from unnecessarily removing the tablet's previously usable local data.
- Preserves the established household, Listing and normal fieldwork workflows.
- Restored Phone and NHIS information on household member cards after the demographic details.
- Validated with 144 release tests with 0 failures and 0 errors, followed by tablet field UAT.
- Preserves existing field data during an in-place upgrade.

Source release: v2.0.202
Source commit: 948cad10de1d174b4d26e9be9f89f3ea412b9890
SHA256: 48EA8971EFA475753739CB416D6915E0C053748A2336F491F5AF917E6E516A6E

Install this APK over the existing OpenHDS Pro app. Do not uninstall the app or clear application data.