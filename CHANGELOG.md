# Changelog

## 0.1.8 — 2026-11-25

- Removed irrelevant legacy FiveM preset notices from successful GPU and NVIDIA profile completion.
- The old machine-specific entries remain excluded. Actionable warnings and errors stay visible; driver installation and profile settings are unchanged.

## 0.1.7 — 2026-11-25

- Fixed a `Microsoft.PowerShell.Utility` module error that could stop the adaptive NVIDIA profile step near 90% in Auto GPU.
- Profile file checks now work in the packaged toolbox host without depending on that PowerShell module. Existing settings, snapshots, verification and rollback behavior are retained.
- If the driver installation already completed before this error, update the toolbox and run **Apply NVIDIA Profile** in GPU Studio; reinstalling the driver is unnecessary.

## 0.1.6 — 2026-11-24

- NVIDIA profile preparation now uses the installed driver's current game profiles and applies the toolbox's existing supported custom settings.
- Retained explicit custom profiles, settings and added game associations, with toolbox values taking precedence on conflicts. Refreshing driver defaults can restore previously deleted vendor profiles or associations. Unsupported or unmatched entries are reported.
- Added a before-change snapshot and export of the resulting profiles using the actual installed driver version.
- Updated NVIDIA profile descriptions and confirmation text in all supported interface languages.

## 0.1.5 — 2026-11-24

- Added automatic discovery of compatible NVIDIA WHQL Game Ready drivers, including 621.40. Future compatible releases can appear without a toolbox update.
- New driver entries use the existing NVCleanstall debloat, component selection and clean-install workflow.
- Retained existing compatible driver choices and a saved catalog when NVIDIA's live lookup is unavailable.
- Driver selection and installation remain explicit actions. Driver downloads are checked before the existing installation workflow continues.
- Fixed a progress-counter overflow that could stop preparation of large driver packages.

## 0.1.4 — 2026-11-14

- Added the optional nothoov Matte Chalk cursor pack in Personal Settings.
- Added separate Apply and Restore controls for the cursor pack.
- Retained the existing startup presentation and update confirmation.

## 0.1.3 — 2026-11-14

- Added a monochrome sci-fi startup sequence with a segmented loading bar, animated rings and an nH logo reveal over a subtle galaxy backdrop.
- Improved startup text contrast and readability.
- Removed unnecessary access notices from the interface.

## 0.1.2 — 2026-11-14

- Startup now asks whether to install a newer release instead of only showing a notice after the splash.
- The update confirmation appears above the splash screen. Declining keeps the current version open; no update downloads without approval.
- Added a startup integration check that exercises the packaged app, its gateway and the live GitHub feed together.
- Retained title-bar dragging, the administrator launch fix, package verification and update recovery.

## 0.1.1 — 2026-11-14

### Fixed

- Drag the toolbox using the logo, title or empty header space. Dragging a maximized window restores it so it can be moved.
- Navigation, update and window-control buttons remain clickable without starting a drag.
- Corrected the launcher handoff across administrator approval, which could reject a valid downloaded copy with an Ownership Protection message.

### Retained

- Package signatures, file-integrity checks and protected launch validation.
- GitHub update checks, confirmation before installing an update and recovery of the previous executable if installation fails.
- The white nH logo and existing startup presentation.

## 0.1 — 2026-11-14

- Initial nothoovs-toolbox release with Overview, Windows Repair, GPU Studio, COD Config, Debloat, ISLC Setup, PC Health and Cleanup.
- Added GitHub release updates and Discord support links.
