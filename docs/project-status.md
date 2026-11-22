# Townlight Windows beta status

The current public MSI is **Windows 1.9.1.1**. The [release](https://github.com/townlight/townlight/releases/tag/townlight-windows-v1.9.1.1) includes the signed MSI, corresponding source, checksums and acceptance. Its signed artifact passed a physical C920 camera and microphone preview check. See the [acceptance summary](https://github.com/townlight/townlight/releases/download/townlight-windows-v1.9.1.1/ACCEPTANCE-Windows-1.9.1.1.md) for results by build.

The signed **Windows 1.9.2.1 candidate** passed an installed Meetings → Station → Records workflow across a Windows host and a separate Windows Sandbox client. Checks exercised council packet approvals, a verified Station original handed off to Records, and unattended delivery, correction and withdrawal through a test resident portal. Cold recovery was tested on the original Windows host and account using a fresh profile. [Candidate source and checks](https://github.com/townlight/townlight/pull/339) · [Operator walkthrough](https://github.com/townlight/townlight/blob/main/docs/installer/operator-walkthrough.md).

The [suite manual](https://townlight.github.io/manuals/suite.html) covers the coordinated products and supporting modules. Standalone CivicCast retains its own installation and data. Historical releases retain their original evidence.
