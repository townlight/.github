<a id="civicsuite-organization-profile-and-public-front-door"></a>

# Townlight organization profile and public front door

This repository owns Townlight's GitHub organization profile and concise public documentation. The organization front door at <https://townlight.github.io/> lives in the [`townlight/townlight.github.io`](https://github.com/townlight/townlight.github.io) repository. Detailed product documentation and the current Windows Local release remain authoritative in the [`townlight/townlight`](https://github.com/townlight/townlight) umbrella repository.

## Public surfaces

- [`profile/README.md`](profile/README.md) — the profile displayed on the Townlight organization page.
- [`docs/getting-started.md`](docs/getting-started.md) — visitor and evaluator routing.
- [`docs/architecture.md`](docs/architecture.md) — concise suite architecture overview.
- [`docs/project-status.md`](docs/project-status.md) — public maturity language and source-of-truth links.

The organization front door is <https://townlight.github.io/>. The detailed product site is <https://townlight.github.io/townlight/>. Neither replaces the umbrella repository's product documentation.

## Deployment

Nothing in this repository is published through GitHub Pages. The former `site/` directory and its Pages workflow were retired on October 23, 2026 in favor of the root site; see [`docs/deployment.md`](docs/deployment.md).

## Content authority

Public status, versions, release evidence, checksums, requirements, and module maturity must be sourced from the umbrella repository. Do not duplicate fast-changing details here unless they are accompanied by a verification date and an authoritative link.

## License

Documentation and site content are licensed under [CC BY 4.0](LICENSE-DOCS). Code: AGPL-3.0-only, with the TownLight Public Institution Exception for qualifying deployments. See [LICENSE](LICENSE) and [LICENSE-EXCEPTION.md](LICENSE-EXCEPTION.md).
