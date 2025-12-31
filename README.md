# Centris Photo Downloader (Google Colab)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/omessedaa/centris-photo-downloader/blob/main/centris-photo-downloader.ipynb)

Download high-quality photos from a Centris listing using **Google Colab + Playwright**.
The notebook captures listing images, removes duplicates (thumbs/icons), keeps only the best versions, and exports a clean ZIP.

---

## Screenshots (add yours here)

### Example output (ZIP + cleaned photos)
![Example output](assets/sample-photos.png)

### ZIP naming format
![ZIP naming](assets/demo-zip.png)

<!-- Optional -->
<!-- ### Consent popup handled automatically
![Consent popup](assets/consent-popup.png) -->

---

## Features
- Accepts a **listing number** or **full Centris URL**
- Handles the consent popup
- Captures images via Playwright network responses (fast + reliable)
- De-duplicates images using perceptual hashing (keeps the largest/best version)
- Keeps only “good” photos (size thresholds to avoid icons/thumbnails)
- Exports a ZIP named:
  - `listingNumber_address_downloadDateTime.zip`
  - If address can’t be detected: `listingNumber_address_not_found_downloadDateTime.zip`

---

## Q
