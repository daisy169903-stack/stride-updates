# Stride Android updates

Download signed Stride APKs from [Releases](https://github.com/daisy169903-stack/stride-updates/releases/latest).

This repository distributes the personal Android workout tracker and its update metadata. It contains no workout database, exercise history, personal notes, signing keys or credentials.

The app checks the permanent update feed:

```
https://github.com/daisy169903-stack/stride-updates/releases/latest/download/latest.json
```

Each feed points to a version-specific APK and includes its SHA-256, file size and version information. Stride verifies the download and signing certificate before opening Android's installation confirmation. Training continues to work offline.

Install the initial updater-enabled APK over your existing Stride installation; do not uninstall if you want to retain your local training data. Future releases are available through **Settings → Open app updates**.

The app is privately distributed, but these APK downloads are public. Android 8.0 or newer is required. This repository does not provide a hosted workout service or cloud sync.
