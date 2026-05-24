# PKGBUILDs

Arch Linux PKGBUILDs that I maintain.

## <img src="https://cdn.simpleicons.org/archlinux/1793D1" width="24" height="24" style="vertical-align:bottom"> [AUR Packages](packages/aur/)
*Maintained and synchronized with the Arch User Repository.*

| Package | Source | AUR | Build |
| :--- | :---: | :---: | :---: |
| linux-arctis-<br>manager | [![Source](https://img.shields.io/github/v/release/elegos/Linux-Arctis-Manager?label=&style=flat-square&color=444)](https://github.com/elegos/Linux-Arctis-Manager/releases) | [![AUR](https://img.shields.io/aur/version/linux-arctis-manager?label=&style=flat-square&color=1793D1)](https://aur.archlinux.org/packages/linux-arctis-manager) | [![Status](https://img.shields.io/github/actions/workflow/status/ifeign/PKGBUILDs/test.yml?branch=main&label=&style=flat-square)](https://github.com/ifeign/PKGBUILDs/actions/workflows/test.yml) |
| linux-arctis-<br>manager-git | [![Rolling](https://img.shields.io/badge/rolling-444?style=flat-square)](https://github.com/elegos/Linux-Arctis-Manager/commits/master) | [![AUR](https://img.shields.io/aur/version/linux-arctis-manager-git?label=&style=flat-square&color=1793D1)](https://aur.archlinux.org/packages/linux-arctis-manager-git) | [![Status](https://img.shields.io/github/actions/workflow/status/ifeign/PKGBUILDs/test.yml?branch=main&label=&style=flat-square)](https://github.com/ifeign/PKGBUILDs/actions/workflows/test.yml) |

## 📦 [Personal Packages](packages/personal/)
*Custom configurations and builds for local environments.*

| Package | Source | Build |
| :--- | :---: | :---: |
| — | — | — |

## Repository Structure

```text
.
├── .github/workflows/   # CI/CD pipeline logic
├── packages/
│   ├── aur/             # Production PKGBUILDs synced to AUR
│   └── personal/        # Experimental or local-only builds
├── nvchecker.toml       # Upstream version tracking config
├── old_versions.json    # Version state (auto-generated)
└── README.md
