# Cubas Cuts Trees

Single-page static website for **Cubas Cuts Trees** (Alex Cubas, 919-333-5653): tree cutting & removal, trimming, cleanup, and storm work.

Plain HTML/CSS with no build step and no dependencies.

```
index.html        page markup
styles.css        all styles
assets/           images (hero crop, Open Graph link-preview image, favicon)
```

To view it locally, open `index.html` in a browser.

## Publishing with GitHub Pages

1. Push this repository to GitHub (`main` branch).
2. On GitHub, go to **Settings > Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose branch **`main`** and folder **`/ (root)`**, then click **Save**.
5. After a minute or two, the site is live at `https://thaylin.github.io/CubasCutsTrees/`.

The Open Graph tags in `index.html` (`og:url` and `og:image`) use that GitHub Pages URL so link previews show the business card. If you move the site to a custom domain, update those two URLs to match.
