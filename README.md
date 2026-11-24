<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://townlight.github.io/brand/svg/townlight-hall-lockup-tagline-reversed.svg">
    <img alt="Townlight — Municipal software cities can actually own." src="https://townlight.github.io/brand/svg/townlight-hall-lockup-tagline.svg" width="600">
  </picture>
</p>

**Windows 1.9.3.2 public beta** · [Download signed MSI](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.9.3.2/Townlight-Windows-x64-1.9.3.2.msi) · [Checksums](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.9.3.2/SHA256SUMS-Windows-1.9.3.2.txt) · [Acceptance](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.9.3.2/ACCEPTANCE-Windows-1.9.3.2.md) · [Release tag](https://github.com/townlight/townlight/releases/tag/townlight-windows-v1.9.3.2) · [Release notes](https://github.com/townlight/townlight/blob/main/docs/installer/windows-1.9.3.2-candidate.md) · [Suite manual](https://townlight.github.io/manuals/suite.html) · [Support](https://townlight.github.io/support.html) · [Announcement](https://townlight.github.io/announcement.html) · [Technical reference](https://townlight.github.io/reference/index.html) · [Windows staff guide](https://townlight.github.io/manuals/windows-staff-workflows.html)

Windows 1.9.3.2 is the current signed public beta, published 2026-11-24T05:50:39Z. The public release tag is `townlight-windows-v1.9.3.2` in `townlight/townlight`. It is available to download and evaluate. The signed MSI is 1,866,072,064 bytes with SHA-256 `b00510e0649552b5efd9744513bf9fcaf59cbee5755fd864eb922a5151c96b77`. The signed MSI passed direct-upgrade, lifecycle, and fresh exact-artifact acceptance checks. Acceptance records scope and limits; component evidence covers private Records attachment download and Station controls during session renewal, but it does not imply that every workflow was retested. [Acceptance and limits](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.9.3.2/ACCEPTANCE-Windows-1.9.3.2.md).

## Install and upgrade

Fresh install: download and run the signed MSI, then complete first-run setup. Tested direct upgrade: from 1.9.3.1; back up city data and settings, close Townlight, run the MSI, and reopen with the same Windows account and Townlight profile. Preserve `%LOCALAPPDATA%\CivicSuite` for compatibility. Station is bundled and provisioned during first-run; a physical camera requires a signed-in Windows session.

## Suite

Current suite has 17 components: Core (platform) and 16 functional modules. Data, Budget, and Grants are shipped modules in this suite.

| Product | Manual | Source |
|---|---|---|
| Core (platform) | [Manual](https://townlight.github.io/manuals/core.html) | [Repository](https://github.com/townlight/core) |
| Records | [Manual](https://townlight.github.io/manuals/records.html) | [Repository](https://github.com/townlight/sunshine) |
| Meetings | [Manual](https://townlight.github.io/manuals/meetings.html) | [Repository](https://github.com/townlight/meetings) |
| Code | [Manual](https://townlight.github.io/manuals/code.html) | [Repository](https://github.com/townlight/ordinances) |
| Access | [Manual](https://townlight.github.io/manuals/access.html) | [Repository](https://github.com/townlight/access) |
| Notice | [Manual](https://townlight.github.io/manuals/notice.html) | [Repository](https://github.com/townlight/notice) |
| Zoning | [Manual](https://townlight.github.io/manuals/zoning.html) | [Repository](https://github.com/townlight/zone) |
| Planning | [Manual](https://townlight.github.io/manuals/planning.html) | [Repository](https://github.com/townlight/plan) |
| Permitting | [Manual](https://townlight.github.io/manuals/permitting.html) | [Repository](https://github.com/townlight/permit) |
| Inspections | [Manual](https://townlight.github.io/manuals/inspections.html) | [Repository](https://github.com/townlight/inspect) |
| Station | [Manual](https://townlight.github.io/manuals/station.html) | [Repository](https://github.com/townlight/station) |
| Boards & Commissions | [Manual](https://townlight.github.io/manuals/boards.html) | [Repository](https://github.com/townlight/boards) |
| Contracts | [Manual](https://townlight.github.io/manuals/contracts.html) | [Repository](https://github.com/townlight/contracts) |
| Procurement | [Manual](https://townlight.github.io/manuals/procurement.html) | [Repository](https://github.com/townlight/procure) |
| Data | [Manual](https://townlight.github.io/manuals/data.html) | [Repository](https://github.com/townlight/data) |
| Budget | [Manual](https://townlight.github.io/manuals/budget.html) | [Repository](https://github.com/townlight/budget) |
| Grants | [Manual](https://townlight.github.io/manuals/grants.html) | [Repository](https://github.com/townlight/grants) |

CivicCast remains a separate product.

## Historical release evidence

Historical attribution only; these links are not current operating guidance.

- Windows 1.9.3.1: [release](https://github.com/townlight/townlight/releases/tag/townlight-windows-v1.9.3.1) · [acceptance](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.9.3.1/ACCEPTANCE-Windows-1.9.3.1.md).
- Windows 1.9.2.1: [release](https://github.com/townlight/townlight/releases/tag/townlight-windows-v1.9.2.1) · [acceptance](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.9.2.1/ACCEPTANCE-Windows-1.9.2.1.md) · [historical release guide](https://townlight.github.io/manuals/windows-1.9.2.1-candidate.html).
- Windows 1.8.1.1: [acceptance](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.8.1.1/ACCEPTANCE-Windows-1.8.1.1.md) · [historical meeting-import reference](https://townlight.github.io/manuals/meeting-imports.html).

## Parked prototypes

The parked repositories are [311](https://github.com/townlight/311), [comms](https://github.com/townlight/comms), [court](https://github.com/townlight/court), [elections](https://github.com/townlight/elections), [hr](https://github.com/townlight/hr), [legal](https://github.com/townlight/legal), [library](https://github.com/townlight/library), [parks](https://github.com/townlight/parks), [safety](https://github.com/townlight/safety), and [utility](https://github.com/townlight/utility). These are outside the installed suite; their source remains available.

[Open Hall brand package and usage guide](https://townlight.github.io/brand/) · [Townlight website](https://townlight.github.io/)

License: AGPL-3.0-only.