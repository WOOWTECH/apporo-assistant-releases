# Apporo Assistant

An English-first Android assistant for your spaces, your work and everyday tasks. Optional Traditional Chinese is included.

[Open the installed app](https://woowtech.github.io/apporo-assistant-releases/) · [Download the latest release](https://github.com/WOOWTECH/apporo-assistant-releases/releases/latest) · [Apporo](https://www.apporo.ai/) · [Application source](https://github.com/WOOWTECH/woowtech_mika_smart_app/tree/main)

## Open the installed app

Use https://woowtech.github.io/apporo-assistant-releases/ on an Android phone, then tap **Open Apporo Assistant**. Apporo .7 or later is required. The page uses a user-initiated Android Intent, with a package-pinned target and a same-page fallback. It does not send tasks or redirect automatically. In LINE or another embedded browser, choose **Open in browser** and tap the button in Chrome.

The page is hosted by GitHub Pages from `main:/docs`. The app URI is not an HTTPS website and should not be entered as a domain in the browser address bar.

## Install

Android 11 or later is required. Most recent Android phones should use the `-arm64.apk` attachment; the other APK is universal. Open the downloaded APK and permit installation from that browser/file manager if Android requests it.

The bundled sandbox/computation runtime requires arm64. Other architectures have startup-only validation; a universal APK does not mean every feature is available on every ABI.

This is a Beta direct-APK distribution. Model/service credentials and Android permissions must be configured before corresponding tasks are available. Approval and payment handoff boundaries remain in place.

Public Apporo releases use the same dedicated Apporo release certificate. Public apporo.3 can be updated to apporo.4 without uninstalling or clearing app data. Internal test-signed Apporo APKs cannot be updated in place by this certificate: preserve anything you need before removing a test installation, then install the public APK. Removing an app deletes its local data. The package remains `com.apporo.assistant`; check each release’s version code and certificate before updating.

Google Play Protect blocked the previous public APK on a POCO Android 15 phone. The current update does not claim to resolve that verdict. If installation is blocked, keep your installed app and data; do not disable protection to force an update.

## Source and verification

This repository hosts release metadata and binaries. GitHub's automatic Source code archives for this repository contain that metadata, not the application source. Each release links the exact application source commit and attaches the corresponding GPL/LGPL component source bundle, public signing certificate, SHA256SUMS and provenance. Application code is based on Mika under Apache-2.0; bundled components retain their own licenses.

Apporo and WOOWTECH use different Android package IDs, signing identities and release channels. Releases here are for `com.apporo.assistant` only.

See each release's notes for validation scope and remaining limitations.
