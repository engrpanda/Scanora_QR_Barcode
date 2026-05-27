# Privacy Policy — Scanora

**Last updated:** May 27, 2026

---

## Overview

Scanora ("the App") is a QR code and barcode scanner and generator for Android. This Privacy Policy explains what data the App handles, how it is stored, and your rights as a user.

**Short version:** Scanora does not collect, transmit, or share any personal data. Everything stays on your device.

---

## 1. Information We Collect

**Scanora collects no personal information.**

The App does not:
- Send any data to a server or the internet
- Use analytics, crash reporting, or telemetry services
- Contain advertisements
- Use third-party SDKs that collect user data

The App does not have the `INTERNET` permission declared in its manifest, which means it is technically incapable of transmitting any data off your device.

---

## 2. Data Stored Locally on Your Device

The App stores the following data **locally on your device only**:

| Data | Where stored | Purpose |
|---|---|---|
| Scan history (scanned content, format, timestamp, type) | Room SQLite database | Show your past scans and generated codes |
| App settings (theme, beep, vibrate, flash, batch mode, history limit) | SharedPreferences | Remember your preferences between sessions |
| Generated QR/barcode images (if you choose to save) | Device gallery (`Pictures/Scanora/`) | Keep a copy of codes you created |

This data never leaves your device and is not accessible to the developer or any third party.

---

## 3. Permissions Explained

The App requests the following Android permissions. Each is used only for the purpose stated and for no other reason.

**CAMERA**
Required to use the live camera viewfinder for scanning QR codes and barcodes. The camera feed is processed entirely on-device by ML Kit's offline model. No images or video are recorded, stored, or transmitted.

**VIBRATE**
Used to provide haptic feedback when a code is successfully scanned. No data is involved.

**FLASHLIGHT**
Used to toggle the device torch while scanning in dark environments. No data is involved.

**READ_MEDIA_IMAGES** (Android 13 and above) / **READ_EXTERNAL_STORAGE** (Android 12 and below)
Used only when you tap "Gallery" in the scanner to pick an image from your photo library and scan a code from it. The image is processed on-device and immediately discarded after scanning. It is not stored or transmitted.

**WRITE_EXTERNAL_STORAGE** (Android 9 and below only)
Used only when you choose to save a generated QR code or barcode image to your gallery. On Android 10 and above, saving uses the MediaStore API and this permission is not needed or requested.

---

## 4. Camera and Images

The App uses the device camera exclusively for real-time barcode and QR code detection. Processing is performed locally using Google ML Kit's bundled (offline) barcode scanning model. No camera frames, images, or video are saved, uploaded, or shared by the App.

When you use "scan from gallery," the selected image is decoded locally and the result (the text content of the code) is shown on screen. The image itself is not retained by the App.

---

## 5. Children's Privacy

Scanora is a general-purpose utility app. It does not knowingly collect any data from anyone, including children under the age of 13. Because no data is collected at all, the App is safe for use by all age groups.

---

## 6. Data Retention and Deletion

Your scan history is stored on your device until you delete it. You can clear all history at any time from **Settings → Clear History**. Uninstalling the App removes all locally stored data.

---

## 7. Third-Party Libraries

Scanora uses the following open-source libraries. None of these libraries collect user data in this App's configuration:

- **Google ML Kit Barcode Scanning** — used in bundled (offline) mode; no data is sent to Google.
- **ZXing (Zebra Crossing)** — used for QR code and barcode image generation; fully local.
- **CameraX (Jetpack)** — Android camera abstraction; no data collection.
- **Room (AndroidX)** — local SQLite database library; no network access.

---

## 8. Changes to This Policy

If this policy is updated, the new version will be published at this URL with an updated "Last updated" date. Because the App collects no data, material changes are unlikely, but any update that affects your rights will be clearly noted.

---

## 9. Contact

If you have questions about this Privacy Policy, you can reach the developer via GitHub:

**GitHub:** [https://github.com/engrpanda/Scanora_QR_Barcode](https://github.com/engrpanda/Scanora_QR_Barcode)

---

_This privacy policy applies to the Scanora Android application published on the Google Play Store by engrpanda._
