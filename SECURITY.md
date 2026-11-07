# Security Policy

## Supported Versions

Security updates are provided for the latest stable release of macFUSE. Please
upgrade to the [latest release](https://github.com/macfuse/macfuse/releases/latest)
before checking whether a suspected vulnerability is still present, when possible.

| Version | Security updates |
| --- | --- |
| Latest stable release | Supported |
| Earlier releases | Not supported |
| Prerelease and development builds | Not supported |

Reports affecting older releases or development builds are still welcome,
especially if the issue may also affect the latest stable release.

## Reporting a Vulnerability

Please report suspected security vulnerabilities privately using
[GitHub private vulnerability reporting](https://github.com/macfuse/macfuse/security/advisories/new).
A GitHub account is required.

**Do not disclose vulnerability details in public issues, discussions, pull
requests, or mailing lists.** If you are unsure whether an issue has security
implications, please report it privately first.

This policy covers the components distributed with macFUSE, including the kernel
extension, FSKit backend, libraries, frameworks, and installation and mount tools.
For vulnerabilities in third-party file systems or applications that use macFUSE,
please contact their maintainers. If you are unsure which component is affected,
you can report the issue here for initial assessment.

Please include as much of the following information as possible:

- A description of the vulnerability, its potential impact, and any required
  access or privileges.
- The affected macFUSE version or source commit, macOS version and build, and
  hardware architecture (Apple Silicon or Intel).
- The affected component and backend (kernel or FSKit), if known, along with the
  file system application and any relevant mount options.
- Steps to reproduce the issue, ideally with a minimal proof of concept.
- Relevant logs, crash reports, or other supporting information, with passwords,
  credentials, personal data, and other sensitive information removed.
- Any suggested fix or mitigation, if available.

You do not need to have all of this information to submit a report.

## Response and Coordinated Disclosure

We aim to acknowledge reports within seven days. If you have not received a
response by then, please follow up through the same private report.

We will review the report, request additional information if needed, and explain
whether it is accepted as a security vulnerability. For accepted reports, we will
work with you to assess the impact, investigate a fix or mitigation, and coordinate
public disclosure. Resolution time depends on the severity and complexity of the
issue; a fixed release date cannot be guaranteed.

Please keep vulnerability details and exploit code private until a fix or
mitigation is available, or until we agree on a disclosure date. Let us know about
any disclosure deadline when you submit your report. We will credit your
contribution in a public advisory or release notes if you would like to be named.

## Other Issues

For bugs without security implications, use the
[issue tracker](https://github.com/macfuse/macfuse/issues). For installation and
usage guidance, see the [macFUSE wiki](https://github.com/macfuse/macfuse/wiki).
