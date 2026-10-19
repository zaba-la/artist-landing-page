# Mara Solís — Artist Landing Page

Single-page site for an artist, built with **HTML and CSS only** (no JavaScript, no frameworks, no templates).

## Files

```
index.html          # content, semantic structure, Schema.org JSON-LD
styles.css          # all styles (Flexbox layout, BEM naming)
images/portrait.svg # hero illustration
images/favicon.svg
pagespeed-result.png  # add after running PageSpeed Insights
```

## Structure

`header > nav` → `main` (`#home` hero, `#about`, `#career`, `#shows`) → `footer`.
Each section is at least one viewport tall (`min-height: 100svh`).

## Checklist

- **Semantic HTML:** `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`, `address`, `time`, `dl`.
- **Accessibility:** skip link, `aria-label` on both navs and ticket buttons, `aria-labelledby` on sections, `alt` on the image, one `h1` then `h2`/`h3`, visible `:focus-visible` outline, `prefers-reduced-motion` support.
- **SEO:** title, meta description, canonical, Open Graph tags, and JSON-LD with `Person`/`MusicGroup`, `MusicAlbum` and `MusicEvent`.
- **Performance:** no JS, system fonts (no web-font download), tiny SVG images with fixed `width`/`height`.

## Before submitting

1. Public URL: https://zaba-la.github.io/artist-landing-page/
2. Publish (e.g. GitHub Pages: *Settings → Pages → Deploy from branch → main*).
3. Run the URL through https://pagespeed.web.dev/ and save the screenshot as `pagespeed-result.png`.
4. Optional checks: https://validator.w3.org/ and https://validator.schema.org/
