<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://townlight.github.io/brand/svg/townlight-hall-lockup-tagline-reversed.svg">
    <img alt="Townlight — Municipal software cities can actually own." src="https://townlight.github.io/brand/svg/townlight-hall-lockup-tagline.svg" width="600">
  </picture>
</p>

[Prepared Windows 1.9.3.2 release links](https://github.com/townlight/townlight/releases/tag/townlight-windows-v1.9.3.2) · [Download signed MSI](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.9.3.2/Townlight-Windows-x64-1.9.3.2.msi) · [Checksums](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.9.3.2/SHA256SUMS-Windows-1.9.3.2.txt) · [Acceptance](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.9.3.2/ACCEPTANCE-Windows-1.9.3.2.md) · [Release notes](https://github.com/townlight/townlight/blob/main/docs/installer/windows-1.9.3.2-candidate.md) · [Previous signed MSI 1.9.3.1](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.9.3.1/Townlight-Windows-x64-1.9.3.1.msi) · [Public announcement](https://townlight.github.io/announcement.html)

Windows 1.9.3.2 is the current signed public beta, published 2026-11-24T05:50:39Z. The signed MSI passed direct-upgrade, lifecycle, and fresh exact-artifact acceptance checks. It is 1,866,072,064 bytes with SHA-256 `b00510e0649552b5efd9744513bf9fcaf59cbee5755fd864eb922a5151c96b77` ([signing/build run 45321294952](https://github.com/townlight/townlight/actions/runs/45321294952); [exact-artifact readback 45328280431](https://github.com/townlight/townlight/actions/runs/45328280431)). Candidate component evidence covers private Records attachment download and Station controls during session renewal.

Windows 1.9.3.2 is the current signed public beta, published 2026-11-24T05:50:39Z. The signed MSI passed direct-upgrade, lifecycle, and fresh exact-artifact acceptance checks. It is 1,866,072,064 bytes with SHA-256 `b00510e0649552b5efd9744513bf9fcaf59cbee5755fd864eb922a5151c96b77` ([signing/build run 45321294952](https://github.com/townlight/townlight/actions/runs/45321294952); [exact-artifact readback 45328280431](https://github.com/townlight/townlight/actions/runs/45328280431)). [Release notes](https://github.com/townlight/townlight/blob/main/docs/installer/windows-1.9.3.2-candidate.md) · [1.9.3.1 acceptance](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.9.3.1/ACCEPTANCE-Windows-1.9.3.1.md) · [Data](https://townlight.github.io/products/data/) · [Budget](https://townlight.github.io/products/budget/) · [Grants](https://townlight.github.io/products/grants/).

# Townlight

Townlight is local-first municipal software for clerks and city staff. Start with [Records](https://townlight.github.io/manuals/records.html#daily-workflow) or [Meetings](https://townlight.github.io/manuals/meetings.html#daily-workflow). Windows 1.9.2.1 adds revisioned council packets, shared Meetings and Records work across Windows environments, and approved portal delivery. [Acceptance and limits](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.9.2.1/ACCEPTANCE-Windows-1.9.2.1.md).

## Windows 1.9.2.1 previous release

The signed release adds revisioned staff and public council packets, shared Meetings and Records work between a city host and workstation, and unattended delivery of explicitly approved packets and recordings to a configured resident portal. Station records on the host. Acceptance used synthetic data on a physical Windows host and a clean Sandbox guest on the same machine; direct upgrades, a separate physical workstation, and a live city network or portal were not tested. [Windows release and source](https://github.com/townlight/townlight/releases/tag/townlight-windows-v1.9.2.1) · [Acceptance](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.9.2.1/ACCEPTANCE-Windows-1.9.2.1.md) · [Release guide](https://townlight.github.io/manuals/windows-1.9.2.1-candidate.html).

## Earlier evidence · Shared meeting imports · Windows 1.8.1.1

Windows 1.8.1.1 adds shared meeting imports for 31 source families, with 34 supported source/format pairs. Installed Windows Sandbox checks exercised preview, save and durable readback using public captures and fixtures, plus the documented Townlight handoffs. These checks do not establish automatic discovery on every live portal or a complete retest of every module.

[All 31 sources, formats and handoffs](https://townlight.github.io/manuals/meeting-imports.html) · [Installed acceptance](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.8.1.1/ACCEPTANCE-Windows-1.8.1.1.md).

Windows 1.9.1.1 was the previous release and included Townlight Runtime 0.3.3; its [release](https://github.com/townlight/townlight/releases/tag/townlight-windows-v1.9.1.1) and [acceptance](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.9.1.1/ACCEPTANCE-Windows-1.9.1.1.md) retain their original identities. Windows 1.9.2.1 includes Townlight Runtime 0.3.4. Exact repository pins and source archive hashes are listed in the [corresponding-source archive](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.9.2.1/Townlight-Windows-1.9.2.1-Corresponding-Source.zip).


Kept municipal products: Core, Records, Meetings, Code, Access, Notice, Zoning,
Planning, Permitting, Inspections, Station, Boards & Commissions, Contracts, and Procurement.

[Townlight website](https://townlight.github.io/) · [Suite manual](https://townlight.github.io/manuals/suite.html) ·
[Signed Windows x64 beta 1.9.3.1](https://github.com/townlight/townlight/releases/tag/townlight-windows-v1.9.3.1) ·
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
