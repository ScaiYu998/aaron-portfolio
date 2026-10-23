# Aaron Portfolio

A bilingual, responsive, front-end-only portfolio site. It uses plain HTML, CSS and JavaScript; the animated topographic field is drawn locally on a canvas, so there are no image or runtime API dependencies. Display, body and mono fonts (Syne, Manrope, JetBrains Mono) are self-hosted in `fonts/`, so the site renders the same without access to Google Fonts.

## Run locally

Open `index.html` in a browser, or run a static server from this directory:

```sh
python3 -m http.server 4173
```

Then open `http://localhost:4173`.

## Personalize before publishing

- Update the sample contact address in `index.html` (`hello@aaron.dev`).
- Replace the generic service copy with your actual strengths and project examples.
- Update the page description and title in `index.html` when your positioning is final.

The site defaults to English. The EN / 中 control switches language and remembers the choice locally.
