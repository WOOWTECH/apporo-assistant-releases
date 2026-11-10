# Apporo Assistant

An English-first Android assistant for your spaces, your work and everyday tasks. Optional Traditional Chinese is included.

[Download the latest release](https://github.com/WOOWTECH/apporo-assistant-releases/releases/latest) · [Apporo](https://www.apporo.ai/) · [Application source](https://github.com/WOOWTECH/woowtech_mika_smart_app/tree/main)

## Browser opening is temporarily suspended

On November 10, 2026, Chrome displayed a dangerous-site warning for the newly published opening page. Google's public Safe Browsing report identifies `woowtech.github.io` as unsafe for deceptive content; the report's displayed information was last updated October 29, 2026. This does not identify the triggering page or establish that the Apporo page is a false positive.

The public page now contains only a suspension notice. App-opening actions, download links and JavaScript have been removed from the published directory. Do not bypass the browser warning. If Apporo Assistant is already installed, open it from the phone's home screen or app list.

The original opening template is retained in `templates/`, outside the GitHub Pages source directory, for review. It must not be republished until the affected site issues are resolved and the opening flow is verified again. GitHub Pages serves only `main:/docs`.

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
