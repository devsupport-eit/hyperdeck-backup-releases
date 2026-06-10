# HyperDeck Backup — Downloads

Official releases of **HyperDeck Backup** by Entertainment IT — automated backup of Blackmagic HyperDeck recordings with fan-out to Google Drive, SFTP, and USB drives.

**[⬇ Download the latest release](https://github.com/devsupport-eit/hyperdeck-backup-releases/releases/latest)**

## Choose your platform

| Platform | File | Notes |
|----------|------|-------|
| **macOS** (Apple Silicon) | `HyperDeck-Backup-{version}-mac-arm64.dmg` | Signed with Developer ID. Open the DMG and drag to Applications. |
| **Windows** | `HyperDeck-Backup-{version}-windows.zip` | Unzip and run `HyperDeck Backup.exe`. If SmartScreen appears, click "More info" → "Run anyway". |
| **TrueNAS / Docker** | `ghcr.io/devsupport-eit/hyperdeck-backup:{version}` | Public container image — no download needed here. See the install guide PDF attached to each release. |

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
