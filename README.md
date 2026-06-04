<p align="center">
  <img src="https://github.com/engrpanda/Scanora_QR_Barcode/blob/main/Asset/scanora_logo.png?raw=true" alt="Scanora Logo" width="140"/>
</p>

<h1 align="center">Scanora — QR & Barcode Scanner · Maker</h1>

<p align="center">
  <b>Scan it. Make it. Share it.</b><br/>
  A fully offline, privacy-first QR code and barcode scanner + generator for Android.
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
  <img src="https://img.shields.io/badge/Android-5.0%2B-3DDC84?logo=android&logoColor=white" alt="Android 5.0+"/>
  <img src="https://img.shields.io/badge/Kotlin-2.0-7F52FF?logo=kotlin&logoColor=white" alt="Kotlin 2.0"/>
  <img src="https://img.shields.io/badge/Offline-100%25-1E88E5" alt="100% Offline"/>
  <img src="https://img.shields.io/badge/License-MIT-blue" alt="MIT License"/>
  <a href="./PRIVACY_POLICY.md">
    <img src="https://img.shields.io/badge/Privacy-No%20Data%20Collected-43A047" alt="Privacy Policy"/>
  </a>
</p>

---

## ⚠️ Beta Release (v1.0 · Prerelease)

Scanora is currently in **active beta**. Core scanning and generation features are stable and ready to use. UI/UX polish, performance improvements, and additional barcode formats are actively being developed.

> 👉 Found a bug or have a suggestion? [Open an issue](https://github.com/engrpanda/Scanora_QR_Barcode/issues) — your feedback directly shapes the roadmap.

---

## 📖 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [Installation](#-installation)
- [Tech Stack](#-tech-stack)
- [Permissions](#-permissions)
- [Privacy](#-privacy)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🔎 About

**Scanora** is a clean, fast, and fully offline Android app that lets you scan any QR code or barcode using your camera or from an image in your gallery — and generate professional-grade barcodes and QR codes right on your device.

No internet connection is ever required. No accounts. No ads. No data collection. Everything runs entirely on-device, making Scanora one of the most private barcode tools available on Android.

Whether you're a retail shop owner printing price labels, a developer testing barcodes, or just someone who needs to scan a code quickly — Scanora is built for you.

---

## ✨ Features

### 📷 Scanner
- **Live camera scanning** — Instantly detects QR codes and all major 1D/2D barcode formats in real time
- **Gallery import** — Scan a code from any saved image in your photo library
- **Batch mode** — Continuously scan multiple codes without stopping between each one
- **Pinch-to-zoom** — Natural gesture zoom plus a seekbar control for precision
- **Flashlight / torch toggle** — With optional auto-flash in low-light environments
- **Beep & vibrate feedback** — Configurable haptic and audio confirmation on every successful scan
- **Format detection** — Automatically identifies and labels the type of code scanned

---

### 🏷️ Barcode Generator (Details / Price Tag Mode)

A full-featured retail label builder designed for real-world use. Fill in your product details and generate a print-ready barcode label in seconds.

**Supported fields — each fully customizable:**

| Field | Options |
|---|---|
| Store / Shop Name | Text size, bold, color, fill background, X/Y position, angle, hide/show |
| Product Code / SKU | Text size, bold, color, fill background, X/Y position, angle, hide/show |
| Price | Text size, bold, color, fill background, X/Y position, angle, hide/show |
| Unit (e.g. pc, kg) | Optional unit appended to price |
| Date | Text size, bold, color, fill background, X/Y position, angle, hide/show |
| Barcode Bars | Width %, height, X/Y position |
| Barcode Number | Text size, X/Y position, hide/show |
| Additional Fields | Add unlimited custom fields, each with full styling |

**Canvas / Sticker Size:**
- Set exact sticker dimensions in **inches** at **300 DPI** (print-ready)
- Default: **1.25" × 1.0"** — standard retail price label size
- Quick presets: 1×0.75", 1.25×1", 2×1", 3×1.5"
- Custom sliders for width and height (0.25" – 20")
- All font sizes and element proportions **auto-scale** when you change canvas size

**Barcode Formats supported:**
`Code 128` · `Code 39` · `Code 93` · `EAN-13` · `EAN-8` · `UPC-A` · `UPC-E` · `ITF` · `Codabar` · `PDF417` · `Aztec` · `Data Matrix`

---

### 🔷 QR Code Generator

Generate QR codes for any content type with full visual customization.

**Supported content types:**
- Plain text
- URL / Website
- Email
- Phone number
- SMS
- vCard Contact
- Wi-Fi credentials
- Geo location
- Calendar event

**Customization options:**
- Custom foreground and background colors
- Output image size
- Error correction level (L / M / Q / H)
- Embedded logo or icon overlay
- Custom label text below the QR code

---

### 📋 Scan Result Screen

Every scan opens a rich result screen with smart contextual actions based on what was scanned:

- **URL** → Open in browser
- **Phone number** → Tap to call
- **SMS** → Open message composer
- **Contact (vCard)** → Add to contacts
- **Wi-Fi** → Connect directly
- **Geo location** → Open in maps
- **Calendar event** → Add to calendar
- **Any content** → Copy to clipboard · Share

Format identification card shows the detected barcode type, category, and a human-readable description.

---

### 🗂️ History

- Full local history of every scan and generated code
- Filter view: **Scanned** / **Generated** / **All**
- Full-text search across all history entries
- Configurable history limit: 25 · 50 · 100 · 250 · Unlimited
- Swipe-to-delete individual entries with **Undo**
- Bulk-delete all history

---

### ⚙️ Settings

| Setting | Options |
|---|---|
| Theme | Light / Dark / Follow system |
| Scan beep | On / Off |
| Vibration | On / Off |
| Auto-flash | On / Off |
| Batch scan default | On / Off |
| History limit | 25 / 50 / 100 / 250 / Unlimited |

---

## 📸 Screenshots

> _Screenshots coming soon. Add yours to `/screenshots` and open a PR!_

---

## 📲 Installation

### Download APK (Recommended for Beta)

1. Go to [Releases](https://github.com/engrpanda/Scanora_QR_Barcode/releases/latest)
2. Download the latest `.apk` file
3. On your Android device, allow **Install from unknown sources** if prompted
4. Open the downloaded APK and tap Install

### Build from Source

```bash
# Clone the repository
git clone https://github.com/engrpanda/Scanora_QR_Barcode.git
cd Scanora_QR_Barcode

# Open in Android Studio (Hedgehog or newer recommended)
# Sync Gradle, then build:
./gradlew assembleDebug
```

**Requirements:**
- Android Studio Hedgehog (2023.1.1) or newer
- JDK 17+
- Android SDK 34
- Kotlin 2.0

---

## 🛠️ Tech Stack

| Layer | Library / Technology |
|---|---|
| Language | Kotlin 2.0 |
| UI Framework | Material Design 3 · ViewBinding · Navigation Component |
| Camera | CameraX (Jetpack) |
| Barcode Scanning | ML Kit Barcode Scanning (bundled — fully offline) |
| QR / Barcode Generation | ZXing Core |
| Local Database | Room (SQLite) |
| Preferences | AndroidX Preference |
| Architecture | MVVM · ViewModel · LiveData · Repository pattern |
| Min SDK | API 21 (Android 5.0 Lollipop) |
| Target SDK | API 34 (Android 14) |

---

## 🔐 Permissions

Scanora requests only the permissions it genuinely needs:

| Permission | Why it's needed |
|---|---|
| `CAMERA` | Live camera scanning |
| `VIBRATE` | Haptic feedback on successful scan |
| `FLASHLIGHT` | Torch control while scanning |
| `READ_MEDIA_IMAGES` (API 33+) | Import an image from gallery to scan |
| `READ_EXTERNAL_STORAGE` (API ≤ 32) | Import an image from gallery to scan |
| `WRITE_EXTERNAL_STORAGE` (API ≤ 28) | Save generated barcodes/QR codes to gallery |

**No `INTERNET` permission is declared or used. All processing is 100% on-device.**

---

## 🔒 Privacy

Scanora was designed with privacy as a core principle, not an afterthought.

- ✅ **No internet connection** — ever. Not even for analytics.
- ✅ **No accounts required** — use it anonymously, forever.
- ✅ **No ads** — no ad SDKs, no tracking libraries.
- ✅ **No data collection** — scan history and preferences are stored only on your device.
- ✅ **No cloud sync** — your data never leaves your phone.
- ✅ **Open source** — inspect every line of code yourself.

See [PRIVACY_POLICY.md](./PRIVACY_POLICY.md) for the full policy.

---

## 🗺️ Roadmap

Planned improvements and upcoming features:

- [ ] Google Play Store release
- [ ] Batch barcode export (PDF / ZIP)
- [ ] Custom label templates (save & reuse)
- [ ] Print directly to Bluetooth/Wi-Fi label printers
- [ ] History export (CSV / JSON)
- [ ] Widget / home screen shortcut for quick scan
- [ ] Theme color customization
- [ ] Multiple language support (i18n)
- [ ] Tablet / large screen layout optimization
- [ ] Scan from URL / clipboard

---

## 🧪 Beta Testing Notes

If you're helping test Scanora, please try:

- Scanning QR codes in different lighting conditions
- Scanning 1D barcodes (EAN-13, Code 128, UPC-A) from products
- Gallery image scanning from screenshots and photos
- Generating a price tag label with all fields filled in
- Changing canvas size and verifying auto-scaling
- History search and deletion
- Theme switching (light/dark)

**Report issues at:** https://github.com/engrpanda/Scanora_QR_Barcode/issues

Please include: Android version, device model, steps to reproduce, and a screenshot if possible.

---

## 🤝 Contributing

Contributions are welcome and appreciated!

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m 'Add: your feature description'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a Pull Request with a clear description of what you changed and why

For major changes, please [open an issue](https://github.com/engrpanda/Scanora_QR_Barcode/issues) first to discuss the approach.

---

## 📄 License

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
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

---

<p align="center">Made with ❤️ by <a href="https://github.com/engrpanda">engrpanda</a></p>
