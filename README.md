# Apporo Assistant

An English-first Android assistant for your spaces, your work and everyday tasks. Optional Traditional Chinese is included.

[Download the latest release](https://github.com/WOOWTECH/apporo-assistant-releases/releases/latest) · [Apporo](https://www.apporo.ai/) · [Application source](https://github.com/WOOWTECH/woowtech_mika_smart_app/tree/main)

## Install

Android 11 or later is required. Most recent Android phones should use the `-arm64.apk` attachment; the other APK is universal. Open the downloaded APK and permit installation from that browser/file manager if Android requests it.

The bundled sandbox/computation runtime requires arm64. Other architectures have startup-only validation; a universal APK does not mean every feature is available on every ABI.

This is a Beta direct-APK distribution. Model/service credentials and Android permissions must be configured before corresponding tasks are available. Approval and payment handoff boundaries remain in place.

The first public release uses an independent Apporo release certificate. Internal test-signed Apporo APKs cannot be updated in place by this certificate: preserve anything you need before removing a test installation, then install the public APK. Removing an app deletes its local data. Future public releases will use this same release certificate.

## Source and verification

This repository hosts release metadata and binaries. GitHub's automatic Source code archives for this repository contain that metadata, not the application source. Each release links the exact application source commit and attaches the corresponding GPL/LGPL component source bundle, public signing certificate, SHA256SUMS and provenance. Application code is based on Mika under Apache-2.0; bundled components retain their own licenses.

Apporo and WOOWTECH use different Android package IDs, signing identities and release channels. Releases here are for `com.apporo.assistant` only.

See each release's notes for validation scope and remaining limitations.
