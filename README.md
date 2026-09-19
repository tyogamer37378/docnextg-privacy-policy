# DocNextG — Official Public Privacy Policy

This repository hosts the official, public-facing Privacy Policy for **DocNextG** (`com.polyforge.magicpage`), published via GitHub Pages.

## Live Public URL
[https://tyogamer37378.github.io/docnextg-privacy-policy/](https://tyogamer37378.github.io/docnextg-privacy-policy/)

---

## Application Profile
* **Application Name**: DocNextG
* **Package / Application ID**: `com.polyforge.magicpage`
* **Target Version**: `0.1.0` (Version Code `1`)
* **Effective Date**: September 20, 2026
* **Support Contact**: [To be provided upon official release / Refer to Google Play listing]

---

## Privacy Architecture Summary
* **User Document Data (100% On-Device)**: Camera captures, gallery-imported photos, perspective-cropped documents, extracted OCR text, generated PDFs, and local backups remain strictly in application-private storage on the user's Android device (`context.filesDir`). Zero document bytes leave the device.
* **Operational SDK Telemetry (Disclosed)**: Bundled Google ML Kit client components transmit technical operational telemetry (API latency, error codes, device hardware model, Android OS version, and an installation UUID) to Google infrastructure (`play.googleapis.com`) to monitor SDK performance and reliability.
* **No Monetization or Tracking SDKs**: Zero advertising libraries (No AdMob, No `AD_ID`), zero analytics profiling (No Firebase Analytics), zero cloud user accounts, and zero billing SDKs (No Play Billing, No RevenueCat).

---

## Repository Structure
```
/
├── index.html                  # Public Privacy Policy webpage (responsive, accessible, standalone HTML/CSS)
├── README.md                   # Repository documentation
└── .github/
    └── workflows/
        └── pages.yml           # GitHub Actions workflow for automated Pages deployment
```

---

## Contact
For questions or privacy inquiries regarding DocNextG, please refer to the official developer contact information published on the Google Play Store listing.
