# Aishee Jyoti Dhar — Portfolio

A single-page portfolio site for Aishee Jyoti Dhar, a civil engineering graduate from RUET focused on sustainable infrastructure, structural design, and water resource engineering.

## Design

- **Type:** IBM Plex Serif (headlines), IBM Plex Sans (body), IBM Plex Mono (labels/annotations)
- **Palette:** warm paper background, deep ink text, structural slate blue, brick-orange accent, moss green secondary
- **Motif:** a restrained nod to engineering drawings (line-art diagram, dimension marks, drafting-grid texture) without leaning on heavy blueprint clichés

## Stack

- HTML5, CSS3, vanilla JavaScript — no build step, deploys directly to GitHub Pages

## Structure

```text
index.html
css/styles.css
script.js
robots.txt
sitemap.xml
assets/
  favicon.svg
  favicon.png
  og-cover.svg
```

## Updating content

All copy lives directly in `index.html`, organized by section (`about`, `timeline`, `education`, `research`, `highlights`, `skills`, `certifications`, `leadership`, `contact`). Design tokens (colors, type, spacing) are CSS custom properties at the top of `css/styles.css`.
