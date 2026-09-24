# Focus Palm Releases

Official distribution repository for **Focus — Palm** on Android.

> Your focus, in your hands.

This repository contains only public release artifacts and update metadata:

- signed Android APKs;
- stable update manifest;
- SHA-256 checksums;
- release notes in Portuguese and English;
- installation and verification instructions.

The Focus source code is maintained separately. Development, internal, beta, and unreleased builds are never published here.

## Official Android identity

- Package: `com.mateusgomes.focusapp`
- Signing certificate SHA-256: `66ef952ba112112325e03a5964f9b3102810cd22f3db50bdce796831cc943dab`
- Distribution channel: `stable`

A release is considered available only after its APK has been uploaded and the stable manifest has been updated. The manifest is always published last.

## Installation

See [Android installation instructions](docs/android-installation.md).

## Security

Every APK is distributed over HTTPS and accompanied by a SHA-256 checksum. Focus Palm validates the downloaded file, package identity, version, and signing certificate before opening the Android installer.

See [Security policy](SECURITY.md).

## Links

- [Releases](../../releases)
- [Focus Site](https://focus-website-seven.vercel.app/)

No Focus 6.0 artifact or metadata is published before its official release.
