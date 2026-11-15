# Changelog

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
