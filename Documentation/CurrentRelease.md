# Roam Control 0.9.4

Build 74, released 26 September 2026.

Roam Control 0.9.4 is the current public release for testing an iPhone's reported location from a clean Apple Maps interface.

## Before installing

- Requires iOS 27 or newer.
- Requires Developer Mode and LocalDevVPN.
- This is an unsigned IPA. SideStore signs it with the user's own Apple account.
- Intended only for development, quality assurance and responsible testing on a device the user owns and controls.

Read the [installation guide](Installation.md), [privacy explanation](Privacy.md) and [responsible-use policy](ResponsibleUse.md) before using it.

## Download

Download `RoamControl-0.9.4-build74.ipa` from the [Roam Control 0.9.4 release](https://github.com/seanhowarthdev/Roam-Control/releases/tag/v0.9.4).

SHA-256:

`b55bf4bf6a509dd02731a6e4e97253724857a72cc31085571bd6eda1e5d0ad20`

## Highlights

- Added Backup & Restore for favourites, history and supported app preferences.
- Added Mainland China coordinate compatibility for searched and selected locations.
- Added Automatic, Off and Force Correction location compatibility modes.
- Improved walking-route and active-session behaviour.
- Improved Stop & Restore guidance and session recovery messaging.
- Improved update checking so prerelease builds are not offered as stable updates.
- Updated Connection Health guidance for compatible Personal VPNs.
- Added preparation for the one-time app migration planned for Roam Control 0.9.5.

## Backup & Restore

Backup & Restore is available from Settings.

Backups include favourites, history, appearance, map style and location compatibility preferences.

Pairing records, analytics consent, analytics identity, active-session recovery data and diagnostics are deliberately not included.

Roam Control 0.9.5 will use a new app identifier. Users upgrading from 0.9.4 should create a fresh backup before moving to 0.9.5 and will need to pair the iPhone again afterward.

## Distribution constraints

SideStore and free Apple accounts are subject to Apple's app-count and seven-day refresh limits. Pairing and location sessions require a physical iPhone.

Please report ordinary bugs with the issue template and security problems through a private GitHub security advisory.
