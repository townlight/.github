# Documentation deployment

The organization site at https://townlight.github.io/ is served from `townlight/townlight.github.io`, main branch, root. It contains all 17 component landing pages and the 18-manual reference kit (Suite plus 17 component manuals), including 12 current manual PDF/Word pairs. The suite documentation entry at https://townlight.github.io/townlight/ is served from `townlight/townlight`, main, `/docs`, and links the same coordinated edition.

This `.github` repository supplies the GitHub organization profile and does not deploy a Pages site. Preview changed static files headlessly, verify links and keyboard/mobile behavior, then use the repository's PR/check/merge process. Only merge download-link updates once the exact linked release is available.
