# Security Policy

## Authenticity

Official Focus Palm Android releases use:

- Package: `com.mateusgomes.focusapp`
- Certificate SHA-256: `66ef952ba112112325e03a5964f9b3102810cd22f3db50bdce796831cc943dab`

Do not install an APK whose package or certificate differs from these values.

## Update integrity

The Focus Palm updater verifies:

1. the update manifest structure;
2. HTTPS download origin;
3. APK SHA-256;
4. Android package identity;
5. increasing `versionCode`;
6. signing certificate identity.

The Android system always asks the user to confirm installation. Focus Palm does not silently install updates.

## Reporting a problem

Do not publish credentials, tokens, private data, or signing material in a public issue. Use the contact channel listed on the official Focus Site for sensitive reports.
