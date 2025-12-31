[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/omessedaa/centris-photo-downloader/blob/main/centris-photo-downloader.ipynb)

# Centris Photo Downloader (Google Colab)

A Google Colab + Playwright notebook that captures listing images, removes duplicates, keeps only the best versions, and exports a clean ZIP.

## Features
- Listing number or full URL input
- Handles consent popup
- Captures images via Playwright network responses
- De-duplicates images (keeps largest version)
- Keeps only “good” photos (size thresholds)
- ZIP named: `listingNumber_address_downloadDateTime.zip`
- Address fallback: `address_not_found`

## Disclaimer
For personal/educational use. Please respect Centris’ terms of use. Not affiliated with Centris.

## License
MIT
