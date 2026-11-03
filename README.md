# HisabSetu — Official Public Releases

Official public distribution repository for **HisabSetu** (Smart Chit, Loan & Collection Management).

This repository is public and is used strictly for distributing compiled application Android APKs, update manifests, and SHA-256 checksums to employee and client devices.

> **Security Guarantee**: This repository contains ONLY compiled APKs, update metadata, and public release notes. The source repository remains private. No database files, credentials, tokens, or financial records are ever hosted here.

---

## 📥 Current Release: Version 1.0.1

- **Version**: `1.0.1` (Build 2)
- **Release Date**: 2026-11-04
- **Platforms**: Android 7.0+ (API 24+)

### Download Links
- **Android APK**: [`HisabSetu-v1.0.1.apk`](https://github.com/MICHITI/hisabsetu_releases/releases/download/v1.0.1/HisabSetu-v1.0.1.apk)
- **Online Manifest**: [`update_manifest.json`](https://raw.githubusercontent.com/MICHITI/hisabsetu_releases/main/update_manifest.json)
- **Subdirectory Manifest**: [`releases/update_manifest.json`](https://raw.githubusercontent.com/MICHITI/hisabsetu_releases/main/releases/update_manifest.json)

---

### Verification (PowerShell)
You can verify the downloaded APK anytime using PowerShell:
```powershell
(Get-FileHash 'HisabSetu-v1.0.1.apk' -Algorithm SHA256).Hash.ToLower()
# Expected: def6e24b92ffd79f70709c7fdf3d91fe9f481cdbb213eab2bb1770499858ffb0
```

---

### Release Notes (v1.0.1)
- Integrated secure in-app APK Auto Update System V1.
- Enhanced Settings / About screen with manual "Check Now" update controls.
- Automated background update detection with 15-minute cooldown throttling.
- Strict HTTPS download verification with SHA-256 integrity checks.
- Configured dedicated production release signing keystore (`hisabsetu_release.jks`).
- Upgraded Android Gradle Plugin & NDK build configuration for reliable packaging.
