# Open Source Program Office Policy

## [ORGANISATION NAME] — Institutional Open Source Policy

**Document Reference:** [ORGANISATION-CODE]-OSPO-POL-001  
**Version:** [VERSION, e.g. 1.0]  
**Date of Adoption:** [DATE]  
**Date of Next Review:** [DATE + 2 YEARS]  
**Approved by:** [GOVERNING BODY OR EXECUTIVE TITLE]  
**Owner:** Open Source Program Office / [RESPONSIBLE UNIT]  
**Classification:** Public  

---

## 1. Purpose and Scope

### 1.1 Purpose

This Policy establishes the institutional framework governing [ORGANISATION NAME]'s engagement with open source software across all phases of the software lifecycle: consumption, contribution, publication, security management, and community engagement.

The objective of this Policy is to:

- Ensure legal compliance with the licence conditions applicable to all open source software used or published by [ORGANISATION NAME]
- Manage the security risks arising from open source dependencies
- Enable and structure the organisation's contributions to the open source ecosystem
- Align open source engagement with the organisation's strategic objectives, digital sovereignty commitments, and applicable regulatory obligations
- Provide clear guidance to all staff engaged in software-related activities

### 1.2 Scope

This Policy applies to:

- All staff, contractors, and consultants acting on behalf of [ORGANISATION NAME]
- All software consumed by [ORGANISATION NAME], including but not limited to open source libraries, frameworks, tools, operating system components, and services
- All software developed by or on behalf of [ORGANISATION NAME], whether for internal use or external publication
- All contributions to external open source projects made on behalf of or with the resources of [ORGANISATION NAME]

### 1.3 Exclusions

The following are excluded from the scope of this Policy: [LIST ANY SPECIFIC EXCLUSIONS, e.g. evaluation/prototype environments subject to separate policy, specific legacy systems with documented exemptions].

---

## 2. Definitions

For the purposes of this Policy, the following definitions apply:

| Term | Definition |
|---|---|
| **Open Source Software (OSS)** | Software distributed under a licence approved by the Open Source Initiative (OSI) or the Free Software Foundation (FSF) that grants the rights to use, study, modify, and distribute the software and its source code |
| **OSPO** | The Open Source Program Office of [ORGANISATION NAME], the institutional function responsible for implementing and enforcing this Policy |
| **Dependency** | Any open source component incorporated into a software system, whether directly or transitively |
| **SBOM** | Software Bill of Materials: a structured inventory of all software components and their associated metadata, including licence information and version identifiers |
| **Contribution** | Any submission to an external open source project, including source code, documentation, test cases, issue reports, translations, or design materials |
| **Publication** | The release of software developed by or for [ORGANISATION NAME] under an open source licence |
| **Copyleft** | A class of open source licences that require derivative works to be distributed under the same or a compatible licence |
| **Permissive licence** | An open source licence that permits incorporation into proprietary software without imposing copyleft obligations |
| **Inner Source** | The application of open source contribution and governance practices to internal software development, without public publication |

---

## 3. Institutional Mandate

### 3.1 Establishment of the OSPO

[ORGANISATION NAME] hereby establishes the Open Source Program Office (OSPO) as the institutional function responsible for open source governance.

### 3.2 OSPO Mission

The mission of the OSPO is to:

- Enable [ORGANISATION NAME] to realise the strategic benefits of open source software
- Ensure legal, security, and policy compliance in all open source activities
- Build institutional capacity for responsible and sustainable open source engagement
- Represent [ORGANISATION NAME] in the open source ecosystem

### 3.3 OSPO Authority

The OSPO is hereby authorised to:

- Develop, maintain, and enforce open source policies on behalf of [ORGANISATION NAME]
- Approve or reject requests for contribution to or publication of open source software
- Require units and projects to provide information necessary for compliance verification
- Engage on behalf of [ORGANISATION NAME] in open source community and governance forums
- Procure tooling and services necessary for the performance of its functions

### 3.4 OSPO Reporting

The OSPO reports to [TITLE OF RESPONSIBLE EXECUTIVE, e.g. Chief Information Officer / Director of Digital Services] and provides [QUARTERLY/ANNUAL] reports to [GOVERNING BODY].

---

## 4. Consumption Policy

### 4.1 Licence Classification

[ORGANISATION NAME] classifies open source licences into three categories:

**Category A — Approved for general use:**
Permissive licences that impose minimal obligations and are compatible with all internal and external uses.

*Examples*: MIT, Apache 2.0, BSD 2-Clause, BSD 3-Clause, ISC, EUPL-1.2 (in consumption contexts)

**Category B — Conditionally approved:**
Licences that may be used subject to specific conditions or OSPO review, including weak copyleft licences.

*Examples*: LGPL-2.1, LGPL-3.0, MPL-2.0, CDDL

**Category C — Restricted:**
Strong copyleft licences that impose significant distribution obligations. Use requires OSPO review and approval. Distribution of Category C-licensed components in external-facing software products is prohibited without explicit OSPO authorisation.

*Examples*: GPL-2.0, GPL-3.0, AGPL-3.0

**Category D — Prohibited:**
Licences that are incompatible with [ORGANISATION NAME]'s legal or operational requirements.

*Examples*: Non-commercial licences, proprietary "open source" licences, licences with jurisdiction-restriction clauses incompatible with applicable law

### 4.2 Dependency Management Obligations

All software projects within scope MUST:

4.2.1 Maintain an accurate, current SBOM for all open source dependencies, generated using OSPO-approved tooling.

4.2.2 Register the SBOM with the OSPO in accordance with the procedures set out in [OSPO PROCEDURES DOCUMENT].

4.2.3 Update the SBOM upon any change to the dependency set (addition, removal, or version change).

4.2.4 Ensure that no Component classified as Category C or D is incorporated into a software product distributed externally without prior written authorisation from the OSPO.

### 4.3 Security Due Diligence

Prior to incorporating a new open source dependency, the responsible team MUST conduct a security assessment that includes:

4.3.1 Review of known vulnerabilities in current and recent versions using authoritative databases (CVE, OSV, or equivalent).

4.3.2 Assessment of community health indicators including maintenance activity, issue responsiveness, and release cadence.

4.3.3 Verification of the integrity of downloaded components (checksum verification, where signing is not available).

---

## 5. Contribution Policy

### 5.1 General Principles

[ORGANISATION NAME] recognises that contribution to open source projects is a legitimate and strategically valuable activity that supports the sustainability of the open source ecosystem on which the organisation depends. Contribution is encouraged subject to the conditions of this section.

### 5.2 Authorisation for Contribution

5.2.1 Contributions to open source projects that have been designated as **strategic projects** by the OSPO MAY be made without individual prior authorisation, subject to the standing conditions in Section 5.3.

5.2.2 Contributions to projects not designated as strategic SHOULD be authorised by the OSPO prior to submission. The OSPO MUST respond to authorisation requests within [10] business days.

5.2.3 Contributions involving the disclosure of code that was developed under contract or that may contain third-party intellectual property MUST be authorised by the OSPO and, where required, by [LEGAL FUNCTION].

### 5.3 Standing Conditions for Contribution

All contributions made on behalf of [ORGANISATION NAME] MUST:

5.3.1 Be made under the licence designated by the receiving project, which MUST be a licence on the OSI-approved licence list or an equivalent open source licence.

5.3.2 Not include materials whose intellectual property is owned by a third party without the express written permission of that party.

5.3.3 Not disclose confidential, security-sensitive, or personal data.

5.3.4 Be recorded in the OSPO contribution register within [5] business days of submission.

5.3.5 Be attributed to [ORGANISATION NAME] where the project's contributor requirements and the nature of the contribution make attribution appropriate.

---

## 6. Publication Policy

### 6.1 Publication Criteria

Software developed by or for [ORGANISATION NAME] MAY be published as open source where the following criteria are met:

6.1.1 The software has potential utility for other organisations or the public beyond its original internal purpose.

6.1.2 Publication is not restricted by third-party contractual obligations, national security classifications, or data protection obligations.

6.1.3 The publishing unit commits to maintaining the published software for a minimum period of [24] months, or provides for an explicit sunset process.

6.1.4 The software meets the quality, documentation, and security standards set out in the OSPO Publication Guidelines.

### 6.2 Licence Selection for Publication

When publishing software as open source, [ORGANISATION NAME] SHOULD use the **European Union Public Licence v1.2 (EUPL-1.2)** as the default licence, reflecting the organisation's European public mandate and the EUPL's compatibility with the GPL licence family.

Deviation from the default licence requires OSPO authorisation and documented justification.

### 6.3 Publication Requirements

All published open source software MUST:

6.3.1 Include REUSE-compliant copyright and licence headers in all source files.

6.3.2 Include a `publiccode.yml` file providing machine-readable metadata compliant with the publiccode.yml standard.

6.3.3 Include a `README`, `CONTRIBUTING`, and `CODE_OF_CONDUCT` document meeting the standards set out in the OSPO Publication Guidelines.

6.3.4 Be registered in the OSPO software publication register.

---

## 7. Security Policy

### 7.1 Supply Chain Security

7.1.1 [ORGANISATION NAME] MUST maintain an up-to-date SBOM for all software systems in scope, in a format compliant with SPDX ISO/IEC 5962 or CycloneDX.

7.1.2 Vulnerability monitoring for open source dependencies classified as Critical or High severity MUST be performed on a continuous basis using OSPO-approved tooling.

7.1.3 High-severity vulnerabilities in open source dependencies of production systems MUST be triaged within [72 hours] and remediated within [30 days] unless a documented risk acceptance is obtained from [APPROPRIATE AUTHORITY].

7.1.4 Critical-severity vulnerabilities MUST be triaged within [24 hours] and remediated within [14 days] unless a documented risk acceptance is obtained.

### 7.2 NIS2 and CRA Alignment

This section shall be read in conjunction with [ORGANISATION NAME]'s broader cybersecurity policy. The OSPO is responsible for ensuring that open source governance practices meet the supply chain security requirements of the NIS2 Directive (where applicable to [ORGANISATION NAME]) and the EU Cyber Resilience Act.

---

## 8. Compliance, Monitoring, and Enforcement

### 8.1 Compliance Responsibilities

8.1.1 Unit managers are responsible for ensuring that their teams comply with this Policy.

8.1.2 The OSPO is responsible for monitoring compliance, providing guidance, and escalating material non-compliance to [APPROPRIATE AUTHORITY].

8.1.3 All staff are individually responsible for complying with the provisions of this Policy in their personal activities.

### 8.2 Compliance Monitoring

The OSPO SHALL conduct periodic compliance assessments, including:

- Annual review of SBOM completeness and accuracy across in-scope projects
- Annual review of contribution register
- Periodic licence scan of published software repositories
- Annual policy review (Section 9)

### 8.3 Non-Compliance

Material non-compliance with this Policy shall be escalated to [APPROPRIATE AUTHORITY] and may result in:

- Suspension of the non-compliant project's open source activities pending remediation
- Formal notification to the project team and their management
- In cases of serious or repeated non-compliance, referral to disciplinary procedures in accordance with [ORGANISATION NAME]'s [HR POLICY]

---

## 9. Policy Review

This Policy SHALL be reviewed annually by the OSPO and updated as necessary to reflect:

- Changes in applicable legislation or regulatory requirements
- Changes in the organisation's open source strategy
- Significant changes in the open source landscape (new licence types, community practices, standards)
- Findings from compliance monitoring and incident reports

Material revisions require approval by [GOVERNING BODY OR EXECUTIVE].

---

## 10. Related Documents

| Document | Reference |
|---|---|
| OSPO Procedures Document | [REFERENCE] |
| OSPO Publication Guidelines | [REFERENCE] |
| SBOM Management Procedures | [REFERENCE] |
| Information Security Policy | [REFERENCE] |
| Procurement Policy | [REFERENCE] |
| HR Policy | [REFERENCE] |

---

## Appendix A: Regulatory Reference Table

| Instrument | Provisions Relevant to this Policy |
|---|---|
| EU Open Source Strategy 2020–2023 | Strategic framework for open source in Commission services |
| Interoperable Europe Act (EU) 2024/903 | Interoperability and openness requirements for public digital infrastructure |
| NIS2 Directive 2022/2555 | Supply chain security obligations for essential and important entities |
| EU Cyber Resilience Act | Software security requirements for products with digital elements |
| GDPR (EU) 2016/679 | Personal data protection obligations applicable to open source projects |
| OpenChain ISO/IEC 5230:2020 | Open source licence compliance programme standard |
| SPDX ISO/IEC 5962:2021 | SBOM standard |

---

## Document History

| Version | Date | Author | Summary of Changes |
|---|---|---|---|
| 1.0 | [DATE] | [AUTHOR] | Initial adoption |
| | | | |

---

*This template is part of the Agora Framework, published by IAAUTECO Inc. under the European Union Public Licence v1.2 (EUPL-1.2). Organisations are encouraged to adapt this template freely, subject to the terms of the EUPL-1.2.*
