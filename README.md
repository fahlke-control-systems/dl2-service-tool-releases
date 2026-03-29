# DL2 Service Tool

Professional diagnostic and analysis software for Fahlke DL2 actuator control systems.

## Download

Go to the **[Releases](https://github.com/fahlke-control-systems/dl2-service-tool-releases/releases)** page and download the archive for your operating system:

| Platform | File |
|----------|------|
| Windows (64-bit) | `DL2-ServiceTool-vX.X.X-win-x64.zip` |
| Windows (ARM64) | `DL2-ServiceTool-vX.X.X-win-arm64.zip` |
| Linux (64-bit) | `DL2-ServiceTool-vX.X.X-linux-x64.tar.gz` |
| Linux (ARM64) | `DL2-ServiceTool-vX.X.X-linux-arm64.tar.gz` |
| macOS (Intel) | `DL2-ServiceTool-vX.X.X-osx-x64.tar.gz` |
| macOS (Apple Silicon) | `DL2-ServiceTool-vX.X.X-osx-arm64.tar.gz` |

## Installation

No installation required. Extract the archive and run the executable directly.

- **Windows**: Unzip and double-click `DL2-Decryptor.exe`
- **Linux**: Extract and run `./DL2-Decryptor`
- **macOS**: Extract and run `./DL2-Decryptor`

Settings are saved next to the executable in `config.json` and persist across updates.

## Features

- Open encrypted Prot.TXT log files from any DL2 firmware version
- Automatic firmware profile detection across 136+ supported versions
- Timeline scatter chart and heatmap visualization with zoom and pan
- Live grid sync — log table filters to show only events visible in the current chart view
- Filter by category, year, user, or free-text search
- Export to CSV for analysis in Excel or other tools
- Encrypted debug reports for Fahlke support
- Dark and light themes
- Available in English, German, Spanish, Chinese, and Thai

## Updating

The application checks for updates automatically on startup. When a new version is available, a notification banner appears with a direct download link.

You can also check manually via **Help > Check for Updates**.

To update: download the new archive, extract it, and replace the old executable. Your settings are preserved.

## System Requirements

| Platform | Requirement |
|----------|-------------|
| Windows x64 | Windows 10 or later |
| Windows ARM64 | Windows 11 ARM |
| Linux x64 | glibc 2.17+ (Ubuntu 18.04+, RHEL 7+) |
| Linux ARM64 | glibc 2.17+ (Raspberry Pi 4+, AWS Graviton) |
| macOS Intel | macOS 10.15 or later |
| macOS Apple Silicon | macOS 12 or later |

No additional software or runtime installation required.

## Support

Fahlke Control Systems KG
Rudolf-Diesel-Str. 3, 27356 Rotenburg, Germany

- **Email**: csg@fahlke.de
- **Phone**: +49 (0) 4261-9143-0
- **24h Service**: +49 (0) 4261-9143-100
- **Web**: https://www.fahlke.de

---

*Copyright 2024-2026 Fahlke Control Systems KG. All rights reserved.*
