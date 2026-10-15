# ScanClip Android test build

[**Download APK — 1.0.0 (1)**](https://github.com/axisj/ScanClip/releases/download/android-v1.0.0-test.1/ScanClip-Android-1.0.0-test.apk) · [Release notes](https://github.com/axisj/ScanClip/releases/tag/android-v1.0.0-test.1) · [한국어](README.md)

Recognize Korean and English text live from books and documents, then copy and collect the passages you need on your device.

## Install

1. Open the APK link on a phone running **Android 8.0 or later**. The download is approximately 63MB.
2. Open `ScanClip-Android-1.0.0-test.apk`.
3. If prompted, allow **Install unknown apps** for the browser or file manager used to open the APK, then install it.
4. Launch ScanClip and grant camera access.

This is a test build distributed before Google Play publication. Physical-camera quality has not been verified. It uses a development signing key. A future production build with a different signing key may require reinstallation: copy or share any collection you need to keep before switching builds.

## Features and privacy

- Offline Korean/English live OCR, adjustable region, text highlights, and full-preview recognition.
- Start/pause, copy after a successful save, and duplicate confirmation.
- Add, edit, delete, reorder, copy all, share, and restore your collection after relaunch.
- Korean/English interface and in-app privacy information.

Camera frames and photographs are not saved or sent to a developer server. The OCR model is bundled and the app has no internet permission. The collection stays on the device; automatic backup and device transfer are disabled. **Uninstalling the app deletes the collection.**

## Verification

All 11 core tests and 16 device tests passed on an Android 14 emulator. Korean/English OCR was tested with fixture images. Focus, movement, sustained recognition speed, heat, and battery use still require physical-device testing.

## File integrity and support

SHA-256: `206aedbcffa5567581224ecacf36173e3794989526a2cea31e4d0c2d0a33111b`

[Checksums](SHA256SUMS.txt) · [Build metadata](build.json) · [Report an issue](https://github.com/axisj/ScanClip/issues)

Include your phone model, Android version, app version, and reproduction steps. Issues are public: do not include private documents or personal information.

This folder contains installation instructions and build metadata. APK binaries are hosted in GitHub Releases. App source code and private signing keys are not included.
