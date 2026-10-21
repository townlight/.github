<a id="getting-started-with-civicsuite"></a>

# Getting started with Townlight

Townlight is an open-source municipal operations suite designed to run locally on a city's own Windows hardware. The current city-core package is a public beta for evaluation—not a production system of record.

## Choose your path

### Municipal evaluator

1. Read the [plain-English status](https://github.com/townlight/townlight/blob/main/STATUS.md).
2. Review [hardware and operating requirements](https://github.com/townlight/townlight/blob/main/FAQ.md#what-does-a-civic-operator-need-to-run-the-city-core-beta).
3. Download the installer and evidence file from the [latest release](https://github.com/townlight/townlight/releases/tag/townlight-records-meetings-code-zoning-v1.4.0-beta.1).
4. Follow the [operator walkthrough](https://github.com/townlight/townlight/blob/main/docs/installer/operator-walkthrough.md) on a non-production Windows machine.
5. Share issues or questions in [Townlight Discussions](https://github.com/townlight/townlight/discussions).

Do not put live municipal records into the beta or treat its drafts as legal, accessibility, records, translation, or policy determinations.

### City IT or security reviewer

Start with the [architecture](https://github.com/townlight/townlight/blob/main/ARCHITECTURE.md), [provenance record](https://github.com/townlight/townlight/blob/main/PROVENANCE.md), [code-signing policy](https://github.com/townlight/townlight/blob/main/CODE_SIGNING_POLICY.md), and [security policy](https://github.com/townlight/townlight/blob/main/SECURITY.md). Verify the published MSI checksum before installation.

### Contributor

Read the [charter](https://github.com/townlight/townlight/blob/main/CHARTER.md), then use the [contribution routing guide](https://github.com/townlight/townlight/blob/main/CONTRIBUTING.md). Module code lives in its own repository; suite-wide governance, compatibility, installer work, and documentation live in the umbrella repository.

## Current operator path

The supported evaluation path is Townlight Windows Local: a single 64-bit Windows MSI with a Tauri/WebView2 desktop shell, portable PostgreSQL 17 with pgvector, bundled Python services, a local Ollama runtime, and optional local model setup that can be deferred during first run.

The current documentation recommends Windows 10 or 11, 32 GB RAM (16 GB workable minimum), WebView2, and at least 15 GB free disk. Confirm current requirements in the [FAQ](https://github.com/townlight/townlight/blob/main/FAQ.md) before downloading.

## Boundaries that matter

- Public beta: suitable for hands-on evaluation, not production or procurement.
- Windows Local is the current operator path; macOS and Linux lifecycle claims are not current.
- Records, Meetings, Code and opt-in Zoning are connected in the desktop beta; Core, Notice and Access support them. The broader catalog retains its separate maturity limits.
- AI outputs are drafts. Humans decide, review, and remain accountable.
- No documented live municipal deployment is claimed.
