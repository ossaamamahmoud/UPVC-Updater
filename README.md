# UPVC Updater

Lightweight auto-update service for the **UPVC Ordering System**.

## Overview

UPVC Updater is a standalone companion utility that manages seamless over-the-air updates for the UPVC Ordering System desktop application. It checks for new releases, downloads update packages, and applies them silently — ensuring end-users always run the latest and most secure version.

## How It Works

1. **Version Check** — On app startup, the main UPVC application queries the update endpoint for the latest available version.
2. **Download** — If a newer version is detected, the update package is downloaded in the background with a progress indicator.
3. **Apply & Restart** — The updater extracts and replaces application files, then restarts the main application automatically.

## Features

- 🔄 **Automatic update detection** on application launch
- 📥 **Background download** with real-time progress bar
- ⚠️ **Critical update enforcement** — mandatory security patches cannot be skipped
- 🛡️ **Integrity verification** before applying updates
- 🌍 **Bilingual UI** — Arabic & English update notifications
- 📦 **Self-contained** — no external dependencies required

## Integration

The updater is designed to work exclusively. It reads release metadata from the configured update server and manages the full update lifecycle.

## Tech Stack

- **Platform:** .NET 8 / WPF
- **Target:** Windows 10+ (x64)
- **Deployment:** Single-file self-contained executable

## License

Proprietary — © 2026 Osama Studios. All rights reserved.
