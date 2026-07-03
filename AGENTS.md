# AGENTS.md — frontender-is-unprofitable

Single-file HTML presentation built with [Shower](https://github.com/shower/shower). Slides, styles, and markup live in `index.html`; images are in `pictures/`.

## Commands

- `npm install` — install `@shower/core` and `@shower/ribbon`.
- `npm run serve` — dev server on `http://localhost:8080/`. Run this to preview.
- `npm run pdf` — export the deck to a PDF.
- `npm run archive` — package the deck into an archive.
- `npm run bundle` — prepare a bundled build (writes to `bundled/`).
- `npm run publish` — publish to GitHub Pages.

There are no tests, lint, typecheck, or CI workflows in this repo. `package.json` is marked `private`.

## Architecture

- Entry point: `index.html`.
- Runtime: `node_modules/@shower/core/dist/index.js` (loaded with `defer`).
- Theme: `node_modules/@shower/ribbon/styles/index.css`, plus inline overrides in `index.html`.
- Slides: `<section class="slide">` elements. Add `.clear` for a blank background.
- Assets: keep all images in `pictures/` and reference them with relative paths. No bundler processes them.
- Google Tag Manager snippet is hard-coded.

## Conventions

- `.editorconfig`: 2 spaces, LF, UTF-8, `max_line_length = 100`.
- The `<link rel="stylesheet" href="node_modules/@shower/ribbon/styles/index.css">` line has a `<!-- prettier-ignore -->` marker — preserve it.
- Custom styles are embedded directly in `index.html`; no separate CSS file.

## Git ignores

`node_modules/`, `bundled/`, `*.pdf`, `.DS_Store`.
