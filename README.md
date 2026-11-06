# QR Studio

A lightweight, mobile-friendly QR Code generator. No account, backend, or subscription required.

## Features

- Generate QR codes from text or URLs
- Customize foreground and background colors
- Choose output size and error correction level
- Download as PNG
- Responsive layout for mobile and desktop

## Run locally

Open `index.html` in a browser. The QR engine is loaded from CDNJS, so an internet connection is required.

## Deploy with GitHub Pages

1. Open **Settings > Pages** in this repository.
2. Select **Deploy from a branch**.
3. Choose `main` and `/ (root)`, then save.

After Pages is enabled and deployment finishes, the site should be available at:

https://mujib-syarif.github.io/QR-generator/

## Notes

This first version generates static QR codes. The content is embedded in the QR itself; changing it later requires generating and printing a new QR code. Dynamic redirects and scan analytics are intentionally left for a future version.
