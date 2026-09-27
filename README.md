# CRC Vision — Lesion Detection & Cancer Grading

React 18 + Tailwind CSS single-page app with light/dark mode. No build step.

- **Lesion Detection** — endoscopy frame → boxed findings, frame assessment and finding type (14 Kvasir-Capsule classes).
- **Cancer Grading** — H&E histology patch → estimated G1 / G2 / G3 with gland and nuclear-density overlay.

Runs 100% in the browser; images are never uploaded.

> **Not a medical device.** Estimates come from image-analysis rules (colour, shading, outline, texture, stain separation), not a trained or validated model. Never use for diagnosis.

## Run locally
Open `index.html` (needs internet for the React/Tailwind CDN scripts), or `python -m http.server 8000`.

## Deploy on GitHub Pages
1. Push these files to a public repo's `main` branch.
2. Settings → Pages → Deploy from a branch → `main` / `(root)`.
3. Live at `https://<user>.github.io/<repo>/` after ~1 minute.
