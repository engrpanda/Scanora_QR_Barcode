# Scanora — QR & Barcode Scanner · Maker

<p align="center">
  <img src="https://github.com/engrpanda/Scanora_QR_Barcode/blob/main/Asset/scanora_logo.png?raw=true" alt="Scanora Logo" width="120"/>
</p>

<p align="center">
  <b>Scan it. Make it. Share it.</b><br/>
  A fully offline QR code and barcode scanner + generator for Android.
</p>


<p align="center">
  <a href="https://github.com/engrpanda/Scanora_QR_Barcode/releases/latest">
    <img src="https://img.shields.io/badge/⬇️%20Download-Scanora%20App-4CAF50?style=for-the-badge&logo=android&logoColor=white" alt="Download Scanora"/>
  </a>
</p>





<p align="center">
  <a href="https://github.com/engrpanda/Scanora_QR_Barcode/releases/latest">
<img src="https://img.shields.io/github/v/release/engrpanda/Scanora_QR_Barcode?include_prereleases&label=version&color=4CAF50" alt="Version"/>
  </a>
  <img src="https://img.shields.io/badge/Android-5.0%2B-3DDC84?logo=android&logoColor=white" alt="Android"/>
  <img src="https://img.shields.io/badge/Kotlin-2.0-7F52FF?logo=kotlin&logoColor=white" alt="Kotlin"/>
  <img src="https://img.shields.io/badge/Offline-100%25-1E88E5" alt="Offline"/>
  <a href="./PRIVACY_POLICY.md">
    <img src="https://img.shields.io/badge/Privacy-No%20Data%20Collected-43A047" alt="Privacy"/>
  </a>
</p>






---

## ⚠️ Beta Release (v1.0 - Prerelease)

Scanora is currently in **beta testing phase**.

This version is:
- 🧪 Actively being tested
- 🐛 May contain bugs or unfinished features
- 🚀 Receiving frequent updates

### What to expect in beta:
- Core scanning and generating features are stable
- Some UI/UX improvements are still in progress
- Performance optimizations will continue
- New barcode formats and features may be added or changed

---

## 🧪 Testing Notes

If you're testing Scanora:
- Try scanning different QR / barcode types
- Test gallery image scanning
- Test flashlight + zoom features
- Check history saving and deletion
- Report any crashes or incorrect scans

👉 Your feedback helps improve stability before stable release.

---

## 💡 Suggestions / Feature Requests

We welcome suggestions such as:
- New barcode formats
- UI improvements
- Faster scanning performance ideas
- Export / backup history feature
- Theme customization options
- Widgets or shortcuts

Feel free to open an issue or discussion:
👉 https://github.com/engrpanda/Scanora_QR_Barcode/issues

---







---

## Features

### Scanner
- **Live camera scanning** — QR codes and all major barcode formats
- **Gallery import** — scan a code from any image in your photo library
- **Batch mode** — keep scanning continuously without pausing
- **Pinch-to-zoom** and seekbar zoom control
- **Flashlight toggle** with optional auto-flash in dark environments
- **Beep & vibrate** feedback on successful scan

### Generator
- **QR Code maker** — supports Text, URL, Email, Phone, SMS, vCard Contact, Wi-Fi, Geo location, and Calendar events
- **Barcode maker** — supports Code 128, Code 39, EAN-13, EAN-8, UPC-A, UPC-E, ITF, Codabar, PDF417, Aztec, Data Matrix, and more
- **QR customization** — custom foreground/background colors, output size, error correction level, embedded logo/icon, and label text
- **Save to gallery** or **share** generated images directly

### Result Screen
- Contextual action buttons based on content type (Open URL, Call, Send SMS, Add Contact, Connect Wi-Fi, Open Map, Add to Calendar)
- Copy to clipboard, share raw content
- Format identification card with category and description

### History
- Full scan and generate history stored locally
- Filter by Scanned / Generated
- Search by content
- Configurable history limit (25 – Unlimited)
- Swipe-to-delete with undo

### Settings
- Light / Dark / System theme
- Beep and vibrate toggle
- Auto-flash toggle
- Batch scan default
- History limit

---

## Screenshots

> _Add your screenshots here — suggest placing them in a `/screenshots` folder._

---

## Tech Stack

| Layer | Library |
|---|---|
| Language | Kotlin 2.0 |
| UI | Material Design 3 · ViewBinding · Navigation Component |
| Camera | CameraX (Jetpack) |
| Barcode Scanning | ML Kit Barcode Scanning (bundled — fully offline) |
| QR/Barcode Generation | ZXing (core) |
| Local Storage | Room (SQLite) |
| Preferences | AndroidX Preference |
| Min SDK | API 21 (Android 5.0 Lollipop) |
| Target SDK | API 34 (Android 14) |

---

## Permissions

| Permission | Why it's needed |
|---|---|
| `CAMERA` | Live camera scanning |
| `VIBRATE` | Haptic feedback on scan |
| `FLASHLIGHT` | Torch control while scanning |
| `READ_MEDIA_IMAGES` (API 33+) | Import an image from gallery to scan |
| `READ_EXTERNAL_STORAGE` (API ≤ 32) | Import an image from gallery to scan |
| `WRITE_EXTERNAL_STORAGE` (API ≤ 28) | Save generated codes to gallery |

**No internet permission is used. All processing is 100% on-device.**


## Privacy

Scanora collects **no personal data**. All scan history and preferences are stored locally on your device and never transmitted anywhere. See [PRIVACY_POLICY.md](PRIVACY_POLICY.md) for full details.

---

## License

```
MIT License

Copyright (c) 2026 engrpanda

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

<p align="center">Made with ❤️ by <a href="https://github.com/engrpanda">engrpanda</a></p>
