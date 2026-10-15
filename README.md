# Sofija Dimitrijevic — research website

A dependency-free academic website prepared for GitHub Pages. All styles, scripts, and images are local; there are no analytics, trackers, or remote font dependencies.

## Publish

For the root personal site, use the repository `sofijadimitrijevic1/sofijadimitrijevic1.github.io` (publish from the GitHub account named `sofijadimitrijevic1`). Upload the contents of this directory to the root of that repository on `main`. In **Settings → Pages**, select **GitHub Actions**. The included Pages workflow deploys each push to `main`. The expected address after a successful deployment is `https://sofijadimitrijevic1.github.io/`.

Alternatively, select **Deploy from a branch**, branch `main`, folder `/ (root)`; these static files also work without Actions.

## Preview

Run `python3 -m http.server 8000` from this directory and visit `http://localhost:8000`.

## Update

Edit `index.html` for the research-focused main page and `cv.html` for the complete printable CV. Keep `Sofija_Dimitrijevic_CV.tex` in sync with the original CV. The original CSCSU manuscript is explicitly unarchived; the expanded AAIRC paper links to arXiv. CSS is in `style.css`. JavaScript is optional and adds active navigation and printing.

The design takes inspiration from https://academicpages.github.io/; implementation and wording are original. Portrait supplied by Sofija Dimitrijevic. No third-party template code is copied.
