# Changelog

Public-facing changes to Roam Control are recorded here.

Detailed internal engineering notes are maintained privately.

## 0.9.4 - Build 74

Released 26 September 2026.

### New

- Added Backup & Restore for favourites, history and supported app preferences.
- Added Mainland China coordinate compatibility for searched and selected locations.
- Added Automatic, Off and Force Correction location compatibility modes.
- Added advance guidance for the one-time app migration planned for Roam Control 0.9.5.

### Improved

- Improved location correction handling without changing manually entered coordinates.
- Improved walking-route and active-session behaviour.
- Refined Stop & Restore messaging and recovery behaviour.
- Improved stable-release update checking so prereleases are ignored.
- Updated Connection Health guidance for compatible Personal VPNs and Device VPN conflicts.
- Restored an immutable packaged build timestamp so SideStore re-signing does not change the displayed build time.

### Backup & migration

- Backups include favourites, history, appearance, map style and location compatibility preferences.
- Pairing records, analytics consent and identity, active-session recovery state and diagnostics are deliberately excluded.
- Roam Control 0.9.4 can remind users to create a fresh backup before moving to 0.9.5.

## 0.9.3 - Build 63

### New

- Added manual route drawing for locations where Apple walking directions are unavailable.
- Added support for planning routes from an active simulated location.
- Added support for intermediate waypoints while keeping an existing selected destination fixed as the route endpoint.
- Added Manual Diagnostics in Connection Health, allowing users to submit a privacy-conscious troubleshooting snapshot and receive a short support code.
- Added automatic and manual release update checking.

### Pairing and recovery

- Added a pairing-expiry notification so users are alerted when the six-digit pairing flow has taken too long and needs to be restarted.
- Improved guidance when pairing expires or does not complete successfully.
- Added clearer recovery actions when pairing or reconnecting fails.
- Improved pairing status and failure information in Connection Health.

### Location, timezone and session behaviour

- Improved timezone handling during location simulation.
- Improved timezone restoration when simulation ends and the device returns to its real location.
- Improved Stop & Restore messaging so it is clearer when Roam Control has stopped simulation and iOS is reacquiring the real location.
- Replaced older user-facing “spoofing” terminology with clearer “location simulation” wording.
- Refined restoration and background-session status messaging.
- Clarified guidance for continuing an active location session over mobile data.

### Route planning and map behaviour

- Improved route planning while a simulated-location session is already active.
- Refined route preview, manual route drawing and map framing.
- Improved map recenter behaviour so it follows the relevant real or simulated location for the current session.
- Refined floating map-control placement across route-planning, route-preview and manual-drawing states.

### Known issue

- A region-specific location-selection issue can still cause searched or selected locations to appear several hundred metres away from the intended position in some configurations. Investigation is ongoing.

### Diagnostics and updates

- Expanded Connection Health with clearer pairing, session, scheduler and location-write information.
- Improved troubleshooting information for failed location writes and ended device sessions.
- Improved update notifications so dismissing one build does not prevent a newer release from being surfaced later.
- Refined the “New version available” experience and manual update checking.

### General

- Refined wording and recovery guidance across pairing, Connection Health, route planning and session restoration.

## 0.9.2 - Build 61

Promoted to the main public release on 16 September 2026.

### Improved

- Improved pairing reliability on SideStore-resigned installations.
- Improved fixed and walking-session stability.
- Improved interrupted-session recovery.
- Improved connection guidance and diagnostics.
- Continued privacy-preserving optional usage statistics.

## 0.9.1 - Build 47

Released 10 September 2026.

### Improved

- Clearer Stop & Restore behaviour.
- Improved interrupted-session recovery.
- Improved background-session reliability.
- Richer place-search results.
- Reorderable favourites.

### Added

- Copy Diagnostics.
- GitHub bug and feature-request links.
- Manual update checking.
- Privacy-preserving failure telemetry.

## 0.9.0 Beta 1 - Build 29

Released 4 September 2026.

First public beta.

### Added

- Fixed reported locations.
- Map and coordinate selection.
- Walking-route simulation.
- Favourites and history.
- On-device pairing.
- Guided LocalDevVPN setup.
- Interrupted-session recovery.
- Explicit real-location restoration.
- Accessibility and appearance options.
- Optional anonymous usage statistics.
