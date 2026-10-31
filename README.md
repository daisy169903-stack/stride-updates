# Stride Android updates

Download signed Stride APKs from [Releases](https://github.com/daisy169903-stack/stride-updates/releases/latest).

This repository distributes the personal Android workout tracker and its update metadata. It contains no workout database, exercise history, personal notes, signing keys or credentials.

The app checks the permanent update feed:

```
https://github.com/daisy169903-stack/stride-updates/releases/latest/download/latest.json
```

Each feed points to a version-specific APK and includes its SHA-256, file size and version information. Stride verifies the download and signing certificate before opening Android's installation confirmation. Training continues to work offline.

Existing updater-enabled installations can download new releases through **Profile → Open app updates** (**Settings** in version 1.1). Do not uninstall if you want to retain your local training data. Android asks you to confirm installation.

Version 1.2 introduces a charcoal/cyan interface, GPS run/walk recording, distance/time/pace cards and a saved-route library. GPS recording and route traces work offline. Street-map tiles require internet when not cached. Location is requested only when you start recording; no workout database or GPS track is uploaded. Exported JSON backups include precise route coordinates, so keep them private.

The app is privately distributed, but these APK downloads are public. Android 8.0 or newer is required. This repository does not provide a hosted workout service or cloud sync.

