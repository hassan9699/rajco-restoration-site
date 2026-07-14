# Rajco Restoration Corp — Website

Static marketing site for Rajco Restoration Corp, built as a Jekyll site (no build step needed to run locally — GitHub Pages builds it automatically on push) and hosted on GitHub Pages at the custom domain `rajcorestoration.com`.

## Structure

- `_layouts/default.html` — shared page shell
- `_includes/` — header (nav), footer, brand-mark (logo + wordmark), head (meta/CSS)
- `assets/css/style.css` — single stylesheet, brand tokens + all page styles
- `violations/` — one page per violation category (DOT sidewalk, Local Law 11/FISP, DOB ECB/OATH, HPD)
- `services/` — one page per general service (waterproofing, brickwork, painting, concrete, construction)

## Local preview

Requires Ruby + Jekyll (`gem install bundler jekyll`), then:

```
jekyll serve
```

Not required to deploy — GitHub Pages builds and serves the site automatically on every push to `main`.
