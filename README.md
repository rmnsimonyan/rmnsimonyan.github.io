# rmnsimonyan.github.io

Personal website of **Arman A. Simonyan** — a minimalist digital CV.

**Live site:** https://rmnsimonyan.github.io/

## About this repository

The site is a single, self-contained `index.html` with inlined CSS and a few lines of vanilla JS.
The only external dependency is Google Fonts (Inter, Source Serif 4). It follows the system
light/dark setting and prints cleanly (media and link sections are hidden in print).
YouTube videos are shown as thumbnails and only load the player when clicked.

There is no build step: edit `index.html` and push to `master`, and GitHub Pages serves it directly.

## Page structure

A sticky section index sits on the left (a scrollable top bar on phones):

Profile · Scientific career · Education · Skills · Grants and awards · Publications ·
Teaching and outreach · Media · Press · Links

## Contents

| File | Purpose |
|------|---------|
| `index.html` | The entire website (markup, styles, scripts). |
| `CV_Arman_Simonyan.docx` | Downloadable CV, linked from the header. |
| `CV_Arman_Simonyan.pdf` | Previous CV (no longer linked from the page). |
| `photo.jpg` | Profile photo shown in the header and in link previews. |
| `ddsa_arman_simonyan_2023.mp4` | Danish Data Science Academy feature video, shown in the Media section. |
| `favicon.ico` | Site icon. |
