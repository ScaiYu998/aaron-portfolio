# Aaron Portfolio

A bilingual, responsive, front-end-only portfolio site. It uses plain HTML, CSS and JavaScript; the animated topographic field is drawn locally on a canvas, so there are no image or runtime API dependencies. Display, body and mono fonts (Syne, Manrope, JetBrains Mono) are self-hosted in `fonts/`, so the site renders the same without access to Google Fonts.

## Run locally

Open `index.html` in a browser, or run a static server from this directory:

```sh
python3 -m http.server 4173
```

Then open `http://localhost:4173`.

## Personalization

- Contact email: `scaiyu998@gmail.com`. If it changes, update both the `mailto:` links in `index.html` and the copy-email handler in `app.js`.
- Replace the generic service copy with your actual strengths and project examples.
- Update the page description and title in `index.html` when your positioning is final.

The site defaults to English. The EN / 中 control switches language and remembers the choice locally.

## Deployment

- Production: https://www.scaiyu998.com/
- The root domain https://scaiyu998.com/ redirects to the production domain.
- Vercel fallback: https://aaron-portfolio-sigma.vercel.app/
- Repository: https://github.com/ScaiYu998/aaron-portfolio

Vercel deploys the `main` branch automatically. This is a static site: use the **Other** framework preset, repository root `./`, and no build command. To publish an update, commit the site changes and push to `main`.
