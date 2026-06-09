# Minet Zambia Annual Pension Conference

This repository hosts a single-page landing site for the Minet Zambia Annual Pension Conference. It provides a simple, responsive download page that delivers the official conference program PDF to attendees.

## Event
- **Title:** Minet Zambia Annual Pension Conference
- **Venue:** Radisson Blu, Livingstone
- **Date:** 11th June 2026 to 12th June 2026

## Contents
- `index.html` — responsive landing page with a prominent download button and auto-download behavior for QR visitors.

## How it works
- The download button links to the program PDF hosted in the repository's GitHub Releases.
- When visitors open the page (for example by scanning a QR code), the page attempts to auto-trigger the download of the release asset `2026.Minet.Zambia.Program.pdf`.

## Deploying / Hosting
- The page is static and can be hosted on GitHub Pages, any static hosting provider, or served directly from the repository root.
- To use GitHub Pages, publish the `main` branch or the `/docs` folder via the repository settings.

## Release asset
- Add the PDF file to a GitHub Release using the exact filename: `2026.Minet.Zambia.Program.pdf`.
- The page uses the URL: `https://github.com/minet-zambia-insurance-brokers/Minet-Zambia-2026-Program-/releases/latest/download/2026.Minet.Zambia.Program.pdf`

## QR code
- Point the QR code to the repository's `index.html` (or GitHub Pages URL). When scanned, the page will open and automatically start the download.

## Local testing
1. Place `index.html` and the PDF file in the same folder (for local test using a direct PDF file).
2. Open `index.html` in your browser to verify layout and download behavior.

## Pushing to GitHub
```powershell
git init
git add .
git commit -m "Add landing page and README"
git branch -M main
git remote add origin https://github.com/minet-zambia-insurance-brokers/Minet-Zambia-2026-Program-.git
git push -u origin main
```

If you don't have permission to push, either fork the repository, push to your fork, and open a PR, or ask the repository owner to add your account as a collaborator.

## Notes
- Ensure the release asset filename matches the URL in `index.html`.
- If automatic download is blocked by a browser, the user can click the "Download Program PDF" button to start it manually.

---
Generated on 2026-06-09.
