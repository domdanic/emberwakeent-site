# Emberwake Entertainment Website

A lightweight static website for Emberwake Entertainment.

## Pages

- `/` — company overview and current projects
- `/null-reverie/` — early-stage Null Reverie project page
- `/404.html` — custom not-found page

## Local preview

Because this site uses plain HTML and CSS, it can be previewed with any simple local web server. From the repository root:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deployment

The site is designed for GitHub Pages. During development, pages include:

```html
<meta name="robots" content="noindex, nofollow">
```

Remove that tag when the site is ready to be indexed publicly.

The custom domain can be connected after GitHub Pages is enabled. A `CNAME` file should be added only when the domain is ready to point at this repository.

## Current external link

The domdanic project card points to `https://domdanic.com`. That destination may remain unavailable until the domdanic site is published.