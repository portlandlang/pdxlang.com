# Changelog

## Unreleased

- **Redirect site** — `index.html` and `404.html` send every path on pdxlang.com to https://portlandlang.com/ with a meta refresh, a canonical link, and `noindex`, served by GitHub Pages from `main` with no build step. Replaces DNSimple's URL-forwarding records, which could redirect only over plain HTTP.
