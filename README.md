# HisabSetu — Official Public Releases

Official public distribution repository for **HisabSetu** (Smart Chit, Loan & Collection Management).

This repository is public and is used strictly for distributing compiled application Android APKs, update manifests, and SHA-256 checksums to employee and client devices.

> **Security Guarantee**: This repository contains ONLY compiled APKs, update metadata, and public release notes. The source repository remains private. No database files, credentials, tokens, or financial records are ever hosted here.

---

## 📥 Current Release: Version 1.0.3

- **Version**: `1.0.3` (Build 4)
- **Release Date**: 2026-11-04
- **Platforms**: Android 7.0+ (API 24+)

### Download Links
- **Android APK**: [`HisabSetu-v1.0.3.apk`](https://github.com/MICHITI/hisabsetu_releases/releases/download/v1.0.3/HisabSetu-v1.0.3.apk)
- **Online Manifest**: [`update_manifest.json`](https://raw.githubusercontent.com/MICHITI/hisabsetu_releases/main/update_manifest.json)
- **Subdirectory Manifest**: [`releases/update_manifest.json`](https://raw.githubusercontent.com/MICHITI/hisabsetu_releases/main/releases/update_manifest.json)

---

### Verification (PowerShell)
You can verify the downloaded APK anytime using PowerShell:
```powershell
(Get-FileHash 'HisabSetu-v1.0.3.apk' -Algorithm SHA256).Hash.ToLower()
# Expected: 4771688d113bf6cb6f397dbce755cd148709b031284395a8d458f9d71e77816a
```

---

### Release Notes (v1.0.3)
- Configured official public update distribution channel (hisabsetu_releases).
- Corrected Settings screen error display with compact, auto-dismissing notifications.
- Enhanced update-check concurrency controls and error handling.
- Preserved offline SQLite ledger integrity and one-click database backup.
