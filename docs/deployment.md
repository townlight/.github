# Landing-page deployment

The Townlight organization front door is served at <https://townlight.github.io/> from the [`townlight/townlight.github.io`](https://github.com/townlight/townlight.github.io) repository, a single dependency-free `index.html` on `main`.

This `.github` repository no longer publishes a site. Its earlier `site/` directory, contract tests and `Deploy organization landing page` workflow were removed on October 23, 2026, and GitHub Pages was disabled here, so the organization has one front door.

## Change the front door

1. Edit `index.html` in `townlight/townlight.github.io`.
2. Confirm every product claim against the umbrella repository's `STATUS.md`.
3. Preview with `python -m http.server 4173` from that repository.
4. Push to `main`. GitHub Pages redeploys the root automatically.
