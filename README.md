# 📱 Linkpad — Official Releases

Welcome to the official public distribution repository for **Linkpad**.

Convert your Android smartphone or modern mobile browser into an ultra-low-latency trackpad, remote keyboard with **full Arabic and Unicode typing support**, instant **URL sharing to your PC's default browser**, and **direct file transfer to your PC's Downloads folder**.

---

## ⬇️ Downloads

| Package | Platform | Latest Release | Download Link |
|---|---|---|---|
| **Android APK** | Android 7.0+ (API 24+) | **v1.5.1 (Build 14)** (Build 13) | [Download Linkpad-release.apk](https://github.com/Omar-allahham/linkpad-releases/releases/latest/download/Linkpad-release.apk) |
| **Windows Installer** | Windows 10 & 11 (64-bit) | **v1.5.1 (Build 14)** | [Download RemoteTouchpad-Setup.exe](https://github.com/Omar-allahham/linkpad-releases/releases/latest/download/RemoteTouchpad-Setup.exe) |

---

## 🔐 Security & Signature Verification

All release APKs in this repository are cryptographically signed with our verified release key.

- **Package Name**: `com.allahham.linkpad`
- **Developer / Issuer**: `CN=Remote Touchpad, O=OpenSource, C=US`
- **Certificate SHA-256 Fingerprint**:
  ```text
  2F:62:84:7F:B2:36:06:3E:26:49:17:61:C5:A0:A2:49:3F:2C:85:D3:06:00:73:4D:B5:27:FF:29:26:3F:42:1D
  ```
- **Signature Schemes**: APK Signature Scheme v2 and v3 (Android SDK `apksigner` verified).

To verify the APK signature integrity on your machine:
```bash
apksigner verify --verbose Linkpad-release.apk
```

---

## ✨ Features
- **Phone as Trackpad**: 1-finger smooth mouse motion, left click, 2-finger right click, 2-finger scroll, long-press drag.
- **Remote Keyboard**: Android soft keyboard integration (Gboard, SwiftKey, etc.) with flawless Arabic (`العربية`) and Unicode support.
- **Instant URL Sharing**: Share URLs from any Android app directly to open in the PC's default browser.
- **Fast File Transfer**: Share photos, videos, and documents directly to the PC's `Downloads` directory.
- **Roku TV Remote**: Independent Wi-Fi remote control for Roku TVs with automatic PC power sync.
- **Single Port Simplicity**: Runs on port `8765` for WebSockets, REST APIs, and instant PWA web client.
