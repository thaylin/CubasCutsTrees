# Cubas Cuts Trees

Single-page static website for **Cubas Cuts Trees** (Alex Cubas, 919-333-5653): tree cutting & removal, trimming, cleanup, and storm work in Smithfield, NC and within 50 miles.

Plain HTML/CSS with no build step and no dependencies.

```
index.html        page markup
styles.css        all styles
robots.txt        crawler rules + sitemap location
sitemap.xml       sitemap for search engines
assets/           images (hero crop, Open Graph link-preview image, favicon)
```

To view it locally, open `index.html` in a browser.

## Publishing with GitHub Pages

1. Push this repository to GitHub (`main` branch).
2. On GitHub, go to **Settings > Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose branch **`main`** and folder **`/ (root)`**, then click **Save**.
5. After a minute or two, the site is live at `https://thaylin.github.io/CubasCutsTrees/`.

## Site URL and SEO

The site's full URL (`https://thaylin.github.io/CubasCutsTrees/`) is hard-coded in a few places: the canonical link, Open Graph tags, and JSON-LD structured data in `index.html`, plus `robots.txt` and `sitemap.xml`. If you move to a custom domain, search for that URL and replace it everywhere.

Crawlers only read `robots.txt` at the root of a domain, so it has no effect on a `github.io/CubasCutsTrees/` project site; it starts working if you use a custom domain. Until then, submit `sitemap.xml` directly in Google Search Console.

After publishing:

- Verify the site in [Google Search Console](https://search.google.com/search-console) and submit the sitemap.
- Check the structured data with Google's [Rich Results Test](https://search.google.com/test/rich-results).
- Link the site from the business's Google Business Profile.
