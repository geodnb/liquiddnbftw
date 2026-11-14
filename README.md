# liquiddnbftw.com

The Liquiddnbftw website: one static page, plain HTML and CSS, no build step and no JavaScript. Built for GitHub Pages.

- `index.html`: the page and its styles (in a `<style>` block, so it renders without a second request).
- `assets/`: logo, icons, Open Graph image and the self-hosted Jost font (SIL Open Font License; licence in `assets/fonts/`).
- `_source/`: the Open Graph image's source. GitHub Pages skips folders starting with `_`, so it isn't published.
- `robots.txt`, `sitemap.xml`: for search engines.
- `CNAME`: the custom domain.

To preview locally, run `python -m http.server` in this folder and open http://localhost:8000.

The subscriber and video counts in the hero and the playlist counts are typed in by hand and need updating now and then.
