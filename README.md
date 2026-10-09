# shelfscribe-site

One-page static site for ShelfScribe, a service that turns messy supplier info into clean, consistent, ready-to-import product listings for independent home and gift shops. The custom domain in `CNAME` is `getshelfscribe.com`.

## Edit the site

The site is plain HTML and CSS at the repo root. There is no build step.

| File | What to change |
| --- | --- |
| `index.html` | Page copy, sections, and links |
| `styles.css` | Layout and visual design |
| `favicon.svg` | Browser icon |
| `og-image.png` | Social preview image |
| `CNAME` | Custom domain |

The pilot buttons are `mailto:` links. When a Square checkout URL is ready, search `index.html` for `SQUARE CHECKOUT` and replace those `href`s.

Pushing to `main` runs `.github/workflows/pages.yml`, which publishes the repo root to GitHub Pages. To preview locally, open `index.html` in a browser or serve the repo root with any static file server.
