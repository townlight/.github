<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://townlight.github.io/brand/svg/townlight-hall-lockup-tagline-reversed.svg">
    <img alt="Townlight — Municipal software cities can actually own." src="https://townlight.github.io/brand/svg/townlight-hall-lockup-tagline.svg" width="600">
  </picture>
</p>

[Download Windows beta 1.8.0.1](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.8.0.1/Townlight-Windows-x64-1.8.0.1.msi) · [Public announcement](https://townlight.github.io/announcement.html) · [Support and feedback](https://townlight.github.io/support.html)

New installations use a fresh profile. Upgrade from the previous public Windows 1.7.2.1 retains saved settings and data; older upgrade paths are unverified.

# Townlight — Townlight Beta 1

Kept municipal products: Core, Records, Meetings, Code, Access, Notice, Zoning,
Planning, Permitting, Inspections, Station, Boards & Commissions, Contracts, and Procurement.

[Townlight website](https://townlight.github.io/) · [Suite manual](https://townlight.github.io/manuals/suite.html) ·
[Signed Windows x64 beta 1.8.0.1](https://github.com/townlight/townlight/releases/tag/townlight-windows-v1.8.0.1) ·
[Versions, provenance and limits](https://townlight.github.io/versions.html)

Windows 1.8.0.1 adds Boards & Commissions, Contracts, and Procurement to the full Windows profile. The signed Windows Sandbox checks cover a fresh installation, the three staff workflows, role boundaries, record persistence, and upgrade from 1.7.2.1 with retained city data and settings. Station continues to use its separately configured local service. The release includes the MSI, matching source, checksums
and an [acceptance summary](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.8.0.1/ACCEPTANCE-Windows-1.8.0.1.md).
Earlier releases retain their original identities and acceptance evidence. City-specific policies, staff and equipment still
require commissioning. Station uses a pinned CivicCast media implementation;
standalone CivicCast remains a separate product. Current owned code and manuals
are AGPL-3.0-only, with retained historical grants and vendor notices.

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


The earlier Windows acceptance covers the paired-loopback Meetings → Station → Records handoff using a synthetic recorded file. Historical Station delivery evidence does not establish live broadcast, external upload or city deployment acceptance for this MSI.


## Separately deployed resident portal beta

[Portal release and downloads](https://github.com/townlight/townlight/releases/tag/townlight-beta-1-resident-portal) · [Portal guide](https://townlight.github.io/manuals/portal.html). Includes the approved city-facing website and the Meetings → Station → Records publication workflow. Deploy the portal and matching native bridge separately; the portal and bridge use their own release and deployment steps. Acceptance uses synthetic data; CivicCast remains separate.


[Open Hall brand package and usage guide](https://townlight.github.io/brand/).
