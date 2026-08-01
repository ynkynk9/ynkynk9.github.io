# Qijing Zhang — Portfolio

A calm, editorial personal website for a product manager and UX designer with experience in digital media, data visualization and higher education.

## Structure

- `index.html` — Portfolio homepage with four project case-study dialogs
- `resume.html` — Web resume
- `contact.html` — Contact details
- `assets/css/` — shared styling
- `assets/js/` — navigation and accessible case-study dialogs
- `assets/images/` — replaceable SVG placeholders

The site intentionally has only three pages. Project details open in accessible dialogs on the portfolio page, so they do not create additional top-level pages.

## Publish to GitHub Pages

1. Copy all files in this folder to the root of the `ynkynk9.github.io` repository.
2. Commit and push to the `main` branch.
3. In **Settings → Pages**, select **Deploy from a branch**, then choose `main` and `/ (root)`.

No build step is required.

## Before publishing

- Replace `assets/images/portrait-placeholder.svg` with a professional portrait, keeping the same filename or updating the image path in `index.html`.
- Replace the four project placeholder SVGs with project screenshots when available.
- Add the LinkedIn profile URL wherever the current placeholder link appears.
- Add the final PDF resume and replace the Download PDF placeholder link in `resume.html`.
