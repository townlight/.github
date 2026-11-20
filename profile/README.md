<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://townlight.github.io/brand/svg/townlight-hall-lockup-tagline-reversed.svg">
    <img alt="Townlight — Municipal software cities can actually own." src="https://townlight.github.io/brand/svg/townlight-hall-lockup-tagline.svg" width="600">
  </picture>
</p>

[Download Windows beta 1.8.2.1](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.8.2.1/Townlight-Windows-x64-1.8.2.1.msi) · [Public announcement](https://townlight.github.io/announcement.html) · [Support and feedback](https://townlight.github.io/support.html)

Windows 1.8.2.1 has signed installed acceptance for fresh setup and an in-place upgrade from Windows 1.8.1.1. Before upgrading, back up city data and settings, close Townlight, run the signed MSI, and reopen it under the same Windows account with the existing `%LOCALAPPDATA%\CivicSuite` profile. Keep the prior installer and a restore path. Other upgrade paths are unverified. Station uses its separately configured service. The acceptance summary distinguishes new maintenance checks from reused workflow evidence.

# Townlight — Townlight Beta 1

## Shared meeting imports · Windows 1.8.1.1

Windows 1.8.1.1 adds shared meeting imports for 31 source families, with 34 supported source/format pairs. Installed Windows Sandbox checks exercised preview, save and durable readback using public captures and fixtures, plus the documented Townlight handoffs. These checks do not establish automatic discovery on every live portal or a complete retest of every module.

[All 31 sources, formats and handoffs](https://townlight.github.io/manuals/meeting-imports.html) · [Installed acceptance](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.8.1.1/ACCEPTANCE-Windows-1.8.1.1.md).

Windows 1.8.2.1 contains Townlight Runtime 0.3.2 and Meetings 1.0.6. Its current component sources and installed evidence are identified in the maintenance acceptance summary.


Kept municipal products: Core, Records, Meetings, Code, Access, Notice, Zoning,
Planning, Permitting, Inspections, Station, Boards & Commissions, Contracts, and Procurement.

[Townlight website](https://townlight.github.io/) · [Suite manual](https://townlight.github.io/manuals/suite.html) ·
[Signed Windows x64 beta 1.8.2.1](https://github.com/townlight/townlight/releases/tag/townlight-windows-v1.8.2.1) ·
[Versions, provenance and limits](https://townlight.github.io/versions.html)

| Product | Manual | Source |
|---|---|---|
| Core | [Manual](https://townlight.github.io/manuals/core.html) | [Repository](https://github.com/townlight/core) |
| Records | [Manual](https://townlight.github.io/manuals/records.html) | [Repository](https://github.com/townlight/sunshine) |
| Meetings | [Manual](https://townlight.github.io/manuals/meetings.html) | [Repository](https://github.com/townlight/meetings) |
| Code | [Manual](https://townlight.github.io/manuals/code.html) | [Repository](https://github.com/townlight/ordinances) |
| Access | [Manual](https://townlight.github.io/manuals/access.html) | [Repository](https://github.com/townlight/access) |
| Notice | [Manual](https://townlight.github.io/manuals/notice.html) | [Repository](https://github.com/townlight/notice) |
| Zoning | [Manual](https://townlight.github.io/manuals/zoning.html) | [Repository](https://github.com/townlight/zone) |
| Planning | [Manual](https://townlight.github.io/manuals/planning.html) | [Repository](https://github.com/townlight/plan) |
| Permitting | [Manual](https://townlight.github.io/manuals/permitting.html) | [Repository](https://github.com/townlight/permit) |
| Inspections | [Manual](https://townlight.github.io/manuals/inspections.html) | [Repository](https://github.com/townlight/inspect) |
| [Boards & Commissions](https://townlight.github.io/products/boards/) | [Guide](https://townlight.github.io/manuals/windows-staff-workflows.html#boards) | [Repository](https://github.com/townlight/boards) |
| [Contracts](https://townlight.github.io/products/contracts/) | [Guide](https://townlight.github.io/manuals/windows-staff-workflows.html#contracts) | [Repository](https://github.com/townlight/contracts) |
| [Procurement](https://townlight.github.io/products/procurement/) | [Guide](https://townlight.github.io/manuals/windows-staff-workflows.html#procurement) | [Repository](https://github.com/townlight/procure) |
| Station | [Manual](https://townlight.github.io/manuals/station.html) | [Repository](https://github.com/townlight/station) |


Windows 1.8.1.1 acceptance includes the configured Station worker processing a public Wistia MP4 and attaching its output to Records. Historical Station delivery evidence does not establish live broadcast, external upload or city deployment acceptance for this MSI.


## Separately deployed resident portal beta

[Portal release and downloads](https://github.com/townlight/townlight/releases/tag/townlight-beta-1-resident-portal) · [Portal guide](https://townlight.github.io/manuals/portal.html). Includes the approved city-facing website and the Meetings → Station → Records publication workflow. Deploy the portal and matching native bridge separately; the portal and bridge use their own release and deployment steps. Acceptance uses synthetic data; CivicCast remains separate.


[Open Hall brand package and usage guide](https://townlight.github.io/brand/).

## Parked prototypes

The following repositories are research or prototypes, are outside the released Windows suite, and are not presented as installable finished products: [311](https://github.com/townlight/311), [budget](https://github.com/townlight/budget), [comms](https://github.com/townlight/comms), [court](https://github.com/townlight/court), [data](https://github.com/townlight/data), [elections](https://github.com/townlight/elections), [grants](https://github.com/townlight/grants), [hr](https://github.com/townlight/hr), [legal](https://github.com/townlight/legal), [library](https://github.com/townlight/library), [parks](https://github.com/townlight/parks), [safety](https://github.com/townlight/safety), [utility](https://github.com/townlight/utility). Their source and history remain available.

[Organization maintenance and source identities](https://github.com/townlight/townlight/blob/main/docs/maintenance/ORGANIZATION-CLEANUP-2026-11.md).

## Windows 1.8.2.1 maintenance release

Windows 1.8.2.1 packages the staff authorization, explicit database configuration and component metadata corrections. Its exact signed installed checks cover setup, the 1.8.1.1 upgrade, saved staff records, procurement/Contracts handoffs, backup/restore and uninstall retention. Unchanged module and 31-source/34-format import evidence remains attributed to the earlier build that produced it; this is not a new exhaustive test of every module or live provider.

Windows 1.8.2.1 has signed installed acceptance for fresh setup and an in-place upgrade from Windows 1.8.1.1. Before upgrading, back up city data and settings, close Townlight, run the signed MSI, and reopen it under the same Windows account with the existing `%LOCALAPPDATA%\CivicSuite` profile. Keep the prior installer and a restore path. Other upgrade paths are unverified. Station uses its separately configured service. The acceptance summary distinguishes new maintenance checks from reused workflow evidence.

[Acceptance and limits](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.8.2.1/ACCEPTANCE-Windows-1.8.2.1.md).
