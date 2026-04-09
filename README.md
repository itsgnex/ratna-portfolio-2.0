# Ratna Koushik Portfolio

Personal portfolio site for Ratna Koushik Appasani.

This is a static single-page portfolio built with vanilla HTML, CSS, and JavaScript. The site keeps a black neon terminal aesthetic and uses a custom ASCII animation that transitions from a face render into a Porsche 911 as the user scrolls.

## Overview

- custom canvas-based ASCII hero animation
- face to Porsche 911 scroll transition
- recruiter-focused portfolio content and project highlights
- sections for About, Education, Skills, Experience, Achievements, GitHub work, Interests, and Contact
- resume download built into the page
- responsive layout with no framework or build step

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript
- Canvas API
- Google Fonts (`Inter` and `Space Mono`)

## Run Locally

Open `index.html` directly in a browser, or serve the folder locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`

## Project Structure

- `index.html` - complete site markup, styling, and animation logic
- `face.png` - source image for the ASCII face render
- `car.png` - source image for the Porsche transition
- `Ratna_Resume.pdf` - downloadable resume used by the site
- `face_1.png` - alternate image asset
- `face_2.png` - alternate image asset

## Current Site Highlights

- hero overlay with portfolio links and resume access
- ASCII quote that fades in with the Porsche phase
- education and experience sections aligned to current resume details
- recent achievements section linked to LinkedIn posts
- expanded GitHub projects section with portfolio and experimental work
- beyond-code section covering Porsche design, hiking, homelabs, and a DIY NAS

## Editing Notes

- most content updates can be made directly in the HTML sections near the middle of `index.html`
- animation behavior lives in the script block at the bottom of `index.html`
- the hero animation depends on existing IDs and selectors, so those should be preserved when editing
- this project can be deployed to any static host such as GitHub Pages, Netlify, or Vercel

## License

This repository is for personal portfolio use.
