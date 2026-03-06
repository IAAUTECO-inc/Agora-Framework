# Security Policy

## Supported Versions

The following versions of the Agora Framework currently receive security-relevant updates,
including corrections to compliance guidance, regulatory references, and toolchain recommendations.

| Version | Supported |
|---|---|
| 1.x.x (current stable) | ✅ Active |
| 0.9.x (beta) | ⚠️ Critical corrections only |
| < 0.9.0 | ❌ End of life |

---

## Scope

The Agora Framework is a **documentation and policy framework**, not a software application.
The security posture of this repository concerns:

- **Content integrity** — accuracy and trustworthiness of policy guidance, regulatory references,
  and compliance recommendations
- **Supply chain integrity** — provenance and auditability of contributions to this repository
- **Toolchain references** — security status of any tools, libraries, or external resources
  referenced or recommended within the framework documentation
- **Repository infrastructure** — GitHub Actions workflows, dependency files, and automation scripts

The following are **out of scope** for this security policy:

- Security vulnerabilities in third-party tools *referenced* by the framework
  (report those to the respective upstream maintainers)
- Implementation decisions made by organisations adopting the framework
  (those fall under the adopting organisation's own security governance)

---

## Reporting a Security Vulnerability

### Do Not Open a Public Issue

If you believe you have identified a security concern — including but not limited to:

- Materially incorrect compliance guidance that could lead an adopting organisation into
  legal or regulatory exposure
- A compromised or malicious dependency or toolchain reference
- A vulnerability in any automation or CI/CD component of this repository
- Evidence of repository supply chain compromise (e.g. malicious commit, tampered release artefact)

**do not open a public GitHub issue.** Public disclosure before assessment and remediation
may cause harm to organisations that have adopted the framework.

### Private Disclosure via GitHub Security Advisories

The preferred disclosure channel is GitHub's built-in **Private Security Advisory** mechanism:

1. Navigate to the repository's **Security** tab
2. Select **Advisories → Report a vulnerability**
3. Complete the advisory form with the information requested below

This channel is encrypted, visible only to repository maintainers, and supports coordinated
disclosure workflows natively.

### Disclosure by Email

If you are unable to use the GitHub advisory mechanism, you may report by email to:

**security@iaauteco.org**

Please encrypt sensitive reports using the maintainer's public PGP key, available at:  
`https://keys.openpgp.org` — search for `security@iaauteco.org`

---

## Information to Include in a Report

A complete report enables faster triage and remediation. Please provide:

| Field | Description |
|---|---|
| **Nature of concern** | Brief classification (content integrity / toolchain / infrastructure / other) |
| **Affected version(s)** | Which release(s) or branch(es) are affected |
| **Affected document(s)** | File path(s) and section(s) within the repository |
| **Description** | Clear explanation of the vulnerability or concern and its potential impact |
| **Reproduction** | Steps to reproduce or verify the issue |
| **Evidence** | Relevant excerpts, links, CVE identifiers, or references to authoritative sources |
| **Proposed remediation** | If known, your suggested correction |
| **Disclosure timeline** | Your intended public disclosure date, if any |

---

## Response Process and Timeline

IAAUTECO Inc. commits to the following response timeline:

| Milestone | Target |
|---|---|
| Acknowledgement of receipt | Within **72 hours** |
| Initial triage and severity assessment | Within **7 calendar days** |
| Remediation plan communicated to reporter | Within **14 calendar days** |
| Patch / correction published (critical severity) | Within **30 calendar days** |
| Patch / correction published (moderate severity) | Within **60 calendar days** |
| Public disclosure (coordinated with reporter) | Upon patch publication or agreed date |

If the assessment determines that the reported concern does not constitute a security
vulnerability within the scope of this policy, the reporter will be notified with a
clear explanation. The maintainers may, at their discretion, convert low-risk reports
into public issues for standard remediation.

---

## Severity Classification

Reports will be triaged according to the following severity framework:

| Severity | Criteria | Examples |
|---|---|---|
| **Critical** | Guidance that, if followed, would cause direct legal liability, regulatory non-compliance, or security breach in adopting organisations | Incorrect EUPL compatibility statement leading to licence violation; reference to a compromised tool |
| **High** | Materially incorrect regulatory or compliance guidance with significant potential impact | Outdated NIS2 article reference that misrepresents legal obligation |
| **Moderate** | Inaccurate guidance unlikely to cause immediate harm but requiring prompt correction | Incorrect SPDX identifier; outdated CHAOSS metric reference |
| **Low** | Minor inaccuracies, outdated links, deprecated references with no material impact | Broken hyperlink; superseded standard version reference |

---

## Coordinated Disclosure Policy

IAAUTECO Inc. supports **responsible coordinated disclosure**. We ask reporters to:

- Allow the maintainers a reasonable remediation period before public disclosure
- Coordinate the disclosure date with the maintainers
- Avoid sharing vulnerability details with third parties until public disclosure

In return, IAAUTECO Inc. commits to:

- Acknowledging the reporter's contribution in the remediation commit and release notes,
  unless the reporter requests anonymity
- Acting in good faith to address confirmed vulnerabilities promptly
- Notifying the reporter of all significant updates to the remediation status

---

## Security Best Practices for Framework Adopters

Organisations adopting the Agora Framework are advised to:

- Subscribe to repository **Watch → Custom → Releases** notifications to receive
  alerts when updated versions are published
- Review the `CHANGELOG.md` for each new release to identify security-relevant corrections
- Treat the framework as a living document: policy instruments derived from it should be
  reviewed annually, or upon any major release of the Agora Framework
- Apply the same supply chain security practices recommended within the framework
  to the framework repository itself — verify release tag signatures and SBOM metadata

---

## Attribution

This Security Policy is maintained by IAAUTECO Inc. and reviewed annually.  
It was last reviewed on: **June 2025**  
Next scheduled review: **June 2026**

---

*The Agora Framework is released under the European Union Public Licence v1.2 (EUPL-1.2).*  
*Security Policy — IAAUTECO Inc. — security@iaauteco.org*
