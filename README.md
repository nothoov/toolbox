# nothoovs-toolbox

A Windows desktop toolbox for system information, maintenance, repair and configuration. Version **0.1.6** builds NVIDIA profile settings from the installed driver's current game profiles and the toolbox's existing custom settings.

[Download the latest release](https://github.com/nothoov/toolbox/releases/latest) · [Changelog](CHANGELOG.md) · [Discord support](https://www.discord.gg/89YeTh3zgB)

## What's inside

| Page | Features |
| --- | --- |
| **Overview** | CPU, GPU, memory, motherboard, BIOS and Windows details; shortcuts to personal settings, services, registry controls and VALORANT compatibility checks. Personal Settings includes Apply and Restore controls for the optional nothoov Matte Chalk cursor pack. |
| **Windows Repair** | DISM and SFC, separately or together, with live progress and saved session logs. |
| **GPU Studio** | Automatic discovery of compatible NVIDIA WHQL Game Ready drivers, driver debloating, clean-install workflow and profile settings that use the installed driver's current game profiles. |
| **COD Config** | Install and restore supported Call of Duty configurations, with backups of original settings. |
| **Debloat** | Review installed apps and choose which supported apps to remove. |
| **ISLC Setup** | Configure Intelligent Standby List Cleaner for detected memory, manage startup and control its running state. |
| **PC Health** | Hardware monitoring and on-demand Windows health and reliability reports. |
| **Cleanup** | Scan supported cleanup locations, review estimated space and select what to clean. |

## Getting started

1. Download **`nothoovs-toolbox.exe`** from the [latest release](https://github.com/nothoov/toolbox/releases/latest).
2. Save it in a folder you can keep and open it on Windows. Approve the administrator prompt for system tools.
3. Choose a page and review the action before applying changes. Keep the app open while an operation is running.

To use the included cursor pack, open **Overview → Personal Settings → nothoov Matte Chalk cursors** and choose **Install & apply**. **Restore previous** returns to your saved cursor scheme.

GPU Studio checks NVIDIA for Game Ready releases matched to your detected GPU and Windows version, so newly released compatible drivers can appear without a toolbox update. New entries use the same driver debloat and clean-install steps as the existing choices. You still choose the driver and confirm the operation; discovery does not install anything. If the live lookup is unavailable, the toolbox can use recent saved NVIDIA entries alongside NVCleanstall's compatible driver list. A download still requires internet access unless the package is already cached.

The NVIDIA profile step uses game profiles supplied by your installed driver and applies the toolbox's supported custom settings. Explicit custom profiles, settings and added game associations are retained; toolbox values take precedence when both specify the same setting. Refreshing driver defaults can restore vendor profiles or associations you previously deleted. Unsupported or unmatched entries are reported. A snapshot is saved before changes, and the resulting profile export reflects the actual installed driver version. New game profiles come from NVIDIA's driver; the toolbox keeps its existing tuning values.

The standalone executable is the file to share. GPU Studio's NVIDIA controls require compatible NVIDIA hardware; other features depend on the software and hardware installed on the PC. Internet access is needed for update checks and tools that download components.

## Updates

The app checks this repository's releases at startup. When a newer version is available, it asks whether to download and install it now. Choose **Yes** to update, or **No** to keep using the current version and update later with **Check for updates**. Downloads and installation start only after your confirmation. Downloads are verified before installation, and the previous executable is retained for recovery. You can also download releases manually from GitHub.

## Support

Join [Discord](https://www.discord.gg/89YeTh3zgB) for help or feedback. When reporting a problem, include the app version, Windows version, affected page and exact error message. Include a relevant log if available, after removing personal information.

This repository hosts product information and executable releases. Development source is maintained privately.
