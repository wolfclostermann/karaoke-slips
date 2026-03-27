# Karaoke Slip Generator

A self-contained single-page app for generating printable karaoke request slips.

**[Open Karaoke Slip Generator →](https://wolfclostermann.github.io/karaoke-slips/)**

---

## Features

- Configurable slip title with custom background/foreground colours
- Page size (A4, A5, US Letter, US Legal, B5) and orientation
- Configurable margins (top/bottom/left/right in mm)
- Slip count slider (1–30) with automatic best-fit grid layout
- Dashed cut lines between slips extending to page edge
- Typography controls: independent font selection for title, field labels, and hint text
- Fields: add, remove, reorder (drag), each with a label and hint text
- Back design: Blank / Logo+Text / Graph Grid / Lined
- Front/Back flip preview
- PDF export via jsPDF — correctly sized, no browser print dialog issues
- Persistence: all settings auto-saved to `localStorage`
- Save/Load settings as JSON

## Usage

Open the app, configure your slips using the sidebar, then click **🖨 Print / Save PDF** to download a correctly-sized PDF. Open the PDF in any viewer and print from there.

## Deployment

Single HTML file, no build step. GitHub Pages serves `index.html` from the `main` branch root.

## Development

To run locally, just open `index.html` in a browser. No dependencies to install.

To deploy your own copy:

1. Fork this repo
2. Enable GitHub Pages in Settings → Pages → Source: GitHub Actions
3. Push to `main` — the action will deploy automatically

## About

Built for pub karaoke nights. Part of the [SigFlow](https://github.com/wolfclostermann/sigflow) karaoke/streaming toolkit.
