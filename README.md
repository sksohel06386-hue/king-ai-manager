# KING AI Dropshipping Manager V1

A free, Android-friendly, local-first PWA starter for managing a small Indian reseller/dropshipping workflow.

## Included
- Product catalogue
- Profit calculator (product, shipping, COD, RTO/returns and other costs)
- Supplier tracker and verification checklist
- Customer order/status tracker
- Offline AI-helper templates for supplier enquiries, listings and validation
- JSON backup and restore
- Installable PWA shell and offline cache

## Important limitations
- The AI Helper is an offline template assistant, not a connected AI model.
- No supplier discovery/verification, live market research, website checkout, payment collection, WhatsApp sending, supplier messaging or order placement is automated.
- All records are stored in this browser's local storage. Export backups regularly.
- This is a single-device prototype, not a secure multi-user production store. Do not store sensitive personal, payment or identity data.

## Run on Android
1. Extract the ZIP.
2. Publish the files to a static HTTPS host such as GitHub Pages (free tier), keeping all files in the same folder.
3. Open the published HTTPS link in Chrome.
4. Chrome menu -> Add to Home screen / Install app.

Service workers and PWA installation require HTTPS or localhost. Opening index.html directly still allows the core local app, but offline PWA installation will not work.

## GitHub Pages
Upload `index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg` and this README to the repository root. In repository Settings -> Pages, choose Deploy from a branch, `main`, `/ (root)`, and save. Wait for the deployment status, then open the Pages URL.
