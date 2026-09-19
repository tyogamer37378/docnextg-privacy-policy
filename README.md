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
* **Support Email**: [support@polyforge.app](mailto:support@polyforge.app)

---

## Privacy Architecture Summary
* **User Document Data (100% On-Device)**: Camera captures, gallery-imported photos, perspective-cropped documents, extracted OCR text, generated PDFs, and local backups remain strictly in application-private storage on the user's Android device (`context.filesDir`). Zero document bytes leave the device.
* **Operational SDK Telemetry (Disclosed)**: Bundled Google ML Kit client components transmit technical operational telemetry (API latency, error codes, device hardware model, Android OS version, and an installation UUID) to Google infrastructure (`play.googleapis.com`) to monitor SDK performance and reliability.
* **Planned Monetization Boundary (Conditional Disclosures)**: In releases where monetization features are enabled, Google Mobile Ads (AdMob) processes advertising identifiers and interaction telemetry for free users, and Google Play Billing verifies anonymous subscription tokens for Pro users. **Neither AdMob nor Google Play Billing receives document images, OCR text, PDFs, or scanned files.**

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
For questions or privacy inquiries regarding DocNextG:  
**Email**: [support@polyforge.app](mailto:support@polyforge.app)
