# EplayerX

[简体中文](README.md) | English

The public hub for EplayerX feedback and macOS downloads.

## Download for macOS

Current version: [**1.2.2**](https://github.com/liixing/eplayerx/releases/tag/v1.2.2-macos). Requires **macOS 12.0 or later**.

| Mac processor | Download |
| --- | --- |
| Apple Silicon (M-series) | [Download for Apple Silicon](https://github.com/liixing/eplayerx/releases/download/v1.2.2-macos/EplayerX-1.2.2-50-macOS-Apple-Silicon.zip) |
| Intel | [Download for Intel](https://github.com/liixing/eplayerx/releases/download/v1.2.2-macos/EplayerX-1.2.2-50-macOS-Intel.zip) |

Choose ** → About This Mac** in the top-left corner of your screen and check the Chip or Processor field to select the right download.

Download and extract the `.zip`, drag EplayerX into Applications, then launch it from Applications. The app is code-signed and has passed Apple’s notarization. [Releases](https://github.com/liixing/eplayerx/releases) includes the changelog and SHA-256 checksums.

### SHA-256 checksums

[Download checksum file](https://github.com/liixing/eplayerx/releases/download/v1.2.2-macos/SHA256SUMS.txt)

| Mac processor | SHA-256 |
| --- | --- |
| Apple Silicon | `4fd7b9f95ea5c0af05e39e454fc7a792ab43f9ae6c5d53fa5bf21c79a82cd865` |
| Intel | `45821ed66fc20bcbc20958275a7a58d1de98dfa8528fcd9a2e43fe48301d6d65` |

## Switching from the App Store version

If you purchased or subscribed through the Mac App Store, you can try the following steps on **the same Mac** to retain your membership:

1. Install EplayerX from the Mac App Store. Use the Apple Account you purchased with, select Restore Purchases in the app, and confirm that your membership is active.
2. Quit EplayerX completely. Keep its existing app data; do not remove it with a cleanup tool.
3. Download the standalone version for your processor above, extract it, and drag EplayerX into Applications to replace the existing app.
4. Open the standalone version and check your membership status.

This process may retain your existing local membership state. **It is not guaranteed and does not cover a new Mac or an installation after clearing app data.** If your membership does not appear, return to the App Store version to confirm your purchase and [report the issue](https://github.com/liixing/eplayerx/issues/new?template=bug_report_en.md). Please do not repurchase just to troubleshoot.

## Report a bug or request a feature

- [Report a bug](https://github.com/liixing/eplayerx/issues/new?template=bug_report_en.md)
- [Request a feature](https://github.com/liixing/eplayerx/issues/new?template=feature_request_en.md)
- [Browse existing feedback](https://github.com/liixing/eplayerx/issues)

Please search existing issues before opening a new one. Bug reports should include the app version, OS version, device information, and steps to reproduce. For playback issues, media format and codec details are also helpful.

Issues and attachments are public. Do not share passwords, access tokens, playback URLs containing authentication parameters, or other private information. Redact logs and screenshots before uploading them.

## Updates

Starting with **1.2.2**, the standalone app checks for updates automatically. When an update is available, a teal download button appears on the right side of the sidebar Pro card. Click it, or select **Check for Updates…** in the app menu, to read the release notes and download the update. Choose **Install and Relaunch** when you are ready to restart. Background reminders do not interrupt playback. You can opt into automatic installation in Sparkle’s update window.

**Version 1.2.1 has no built-in updater: download and install 1.2.2 manually once to enable future in-app updates.**

New versions and bilingual changelogs are also published on [Releases](https://github.com/liixing/eplayerx/releases). To receive release notifications, select **Watch → Custom → Releases** at the top of this repository.

This repository is for app distribution and user feedback. It does not contain the app's source code.
