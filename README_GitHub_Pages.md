# GitHub Pages / PWA upload package

This folder contains the web/PWA version of the preoperative facial nerve adhesion probability calculator.

Upload the contents of this folder to the root of a GitHub repository, then enable GitHub Pages from the repository's `main` branch and `/root` folder.

Files:

- `index.html`: calculator page.
- `manifest.webmanifest`: PWA metadata for mobile/desktop installation.
- `sw.js`: service worker for HTTPS/localhost offline caching.
- `icons/`: app icons.
- `.nojekyll`: keeps GitHub Pages from applying Jekyll processing.

Notes:

- The calculator remains a research-use internal model; displayed bands are not externally validated clinical action thresholds.
- No patient-level source data are included in this package.
- PWA offline caching works on HTTPS, including GitHub Pages, and on localhost. It will not run as a service worker from a direct `file://` URL.
