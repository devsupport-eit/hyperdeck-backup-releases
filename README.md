# HyperDeck Backup — Downloads

Official releases of **HyperDeck Backup** by Entertainment IT — automated backup of Blackmagic HyperDeck recordings with fan-out to Google Drive, SFTP, and USB drives.

## Direct downloads (always the latest version)

- **macOS (Apple Silicon):** [HyperDeck-Backup-mac-arm64.dmg](https://github.com/devsupport-eit/hyperdeck-backup-releases/releases/latest/download/HyperDeck-Backup-mac-arm64.dmg)
- **Windows:** [HyperDeck-Backup-windows.zip](https://github.com/devsupport-eit/hyperdeck-backup-releases/releases/latest/download/HyperDeck-Backup-windows.zip)

Or browse all versions: **[Releases](https://github.com/devsupport-eit/hyperdeck-backup-releases/releases)**

## Choose your platform

| Platform | File | Notes |
|----------|------|-------|
| **macOS** (Apple Silicon) | `HyperDeck-Backup-mac-arm64.dmg` | Signed with Developer ID. Open the DMG and drag to Applications. |
| **Windows** | `HyperDeck-Backup-windows.zip` | Unzip and run `HyperDeck Backup.exe`. If SmartScreen appears, click "More info" → "Run anyway". |
| **TrueNAS / Docker** | `ghcr.io/devsupport-eit/hyperdeck-backup:{version}` | Public container image — no download needed here. See the [install instructions](https://www.entertainmentit.co/truenas-hyperdeck-install-instructions). |

## TrueNAS quick reference

```bash
docker pull ghcr.io/devsupport-eit/hyperdeck-backup:latest
docker pull ghcr.io/devsupport-eit/hyperdeck-manager:latest
```

## Release notes

Each release includes the full changelog for that version. In-app: **Settings → What's New**.

## Support

- Email: devsupport@entertainmentit.co
- Security concerns: [Report a security concern](mailto:devsupport@entertainmentit.co?subject=Security%20Concern%20Report&body=Please%20describe%20your%20concern%20below%3A%0A%0A)

---

© Entertainment IT, INC. This repository contains compiled releases only; source code is maintained privately.
