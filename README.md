# kaavadata-site

The landing page at <https://kaavadata.fi/>: one static page, no build step. GitHub Pages publishes `main` from the
repository root (`CNAME` holds the domain, `.nojekyll` turns off Jekyll).

| file | what |
|---|---|
| `index.html` | the page, in Finnish; title, description and share-card tags in its head |
| `styles.css` | the Kaavadata brand v0.2 tokens (`--kd-*`, from kaava-decoder's `brand/kaavadata.css`) and the page's own layout |
| `assets/kaavadata-nakyma-*.webp` | the screenshot of the Kaavadata UI, 1200 and 2400 px wide |
| `assets/og.png` | the 1200 × 630 card shown when the link is shared |
| `assets/kaavadata-logo.svg`, `assets/apple-touch-icon.png` | the mark, also the favicon and the home-screen icon |

Preview locally:

```bash
python3 -m http.server 8000
```

then open <http://localhost:8000/>.
