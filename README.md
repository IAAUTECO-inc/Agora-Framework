# Agora Framework

> *From the Ancient Greek ἀγορά — the central public space of civic life, deliberation, and democratic governance.*

**Agora** is an institutional reference framework for establishing, structuring, and operating an **Open Source Program Office (OSPO)** within public administrations, European institutions, research organisations, and mission-driven enterprises.

[![License: EUPL-1.2](https://img.shields.io/badge/License-EUPL_1.2-blue.svg)](https://opensource.org/licenses/EUPL-1.2)
[![Standard: publiccode.yml](https://img.shields.io/badge/Standard-publiccode.yml-brightgreen)](https://yml.publiccode.tools/)
[![Status: Active](https://img.shields.io/badge/Status-Active-success)]()
[![Version: 1.0.0](https://img.shields.io/badge/Version-1.0.0-informational)]()

---

## Overview

The **Agora Framework** provides a structured, auditable, and interoperable methodology for organisations seeking to formalise their engagement with open source software — from initial policy definition through to contribution governance, compliance management, and ecosystem participation.

It is designed in alignment with:

- The **European Interoperability Framework (EIF)**
- The **EU Open Source Strategy 2020–2023** and its successor
- The **REUSE Specification** for licence compliance
- The **OpenChain ISO/IEC 5230** standard for open source licence compliance programmes
- **CHAOSS** metrics for community health and sustainability

---

## Why Agora?

In the ancient Greek city-state, the **Agora** was the heart of public life: a space where citizens gathered to deliberate, trade, legislate, and innovate collectively. It was simultaneously a marketplace of ideas and a seat of governance.

An **Open Source Program Office** plays an analogous role within a modern organisation: it is the institutional forum through which open source strategy is debated, policies are enacted, contributions are coordinated, and the health of the commons is sustained.

---

## Scope and Applicability

The Agora Framework is applicable to:

| Sector | Use Case |
|---|---|
| Public Administration | Digital sovereignty, procurement policy, open standards compliance |
| European Institutions | Interoperability mandates, shared infrastructure, regulatory alignment |
| Research Organisations | Open Science, reproducibility, scholarly communication |
| Critical Infrastructure | Security governance, supply chain transparency, licence compliance |
| Mission-driven Enterprises | ESG alignment, community stewardship, ecosystem contribution |

---

## Repository Structure

```
agora-framework/
├── README.md                          # This document
├── CHANGELOG.md                       # Release history and versioning
├── CODE_OF_CONDUCT.md                 # Community standards
├── CONTRIBUTING.md                    # Contribution guidelines
├── GOVERNANCE.md                      # Project governance model
├── publiccode.yml                     # Machine-readable public software metadata
├── LICENSE                            # European Union Public Licence 1.2
│
├── .github/
│   └── PULL_REQUEST_TEMPLATE.md       # Standard pull request template
│
├── docs/
│   ├── whitepaper/
│   │   ├── agora-whitepaper.md        # White paper (Markdown)
│   │   ├── agora-whitepaper.docx      # White paper (Word/OOXML)
│   │   └── agora-whitepaper.odt       # White paper (ODF — LibreOffice)
│   │
│   └── templates/
│       ├── ospo-policy-template.md    # OSPO Policy Template (Markdown)
│       ├── ospo-policy-template.docx  # OSPO Policy Template (Word/OOXML)
│       └── ospo-policy-template.odt   # OSPO Policy Template (ODF — LibreOffice)
│
└── articles/
    ├── linkedin-article-1.md          # LinkedIn: Introducing Agora
    └── linkedin-article-2.md          # LinkedIn: OSPO as Institutional Infrastructure
```

---

## Quick Start

### For Policy Makers and Institutional Leaders

1. Read the [White Paper](docs/whitepaper/agora-whitepaper.md) to understand the strategic rationale for an OSPO.
2. Adapt the [OSPO Policy Template](docs/templates/ospo-policy-template.md) to your organisational context.
3. Review the [Governance Model](GOVERNANCE.md) to understand how the Agora Framework itself is governed.

### For Practitioners and Technical Leads

1. Fork this repository or use it as a template for your organisation's OSPO documentation.
2. Review [CONTRIBUTING.md](CONTRIBUTING.md) before submitting improvements.
3. All contributions must comply with the [Code of Conduct](CODE_OF_CONDUCT.md).

### For Developers and Integrators

```bash
# Clone the repository
git clone https://github.com/IAAUTECO-inc/Agora-Framework.git
cd Agora-Framework

# The framework is documentation-first; no build step is required.
# Markdown sources may be compiled to PDF using pandoc:
pandoc docs/whitepaper/agora-whitepaper.md -o agora-whitepaper.pdf
```

---

## Core Pillars of the Framework

### I. Institutional Mandate
Establishing the legal, strategic, and organisational authority of the OSPO within its host institution.

### II. Policy Architecture
Designing the policy instruments that govern open source consumption, contribution, and publication.

### III. Compliance and Licence Stewardship
Implementing processes for licence identification, compatibility assessment, and SBOM (Software Bill of Materials) management.

### IV. Contribution Governance
Structuring the rules, workflows, and accountabilities for upstream and downstream contribution.

### V. Community and Ecosystem Engagement
Building the institutional relationships and participation models that sustain open source ecosystems.

### VI. Metrics and Accountability
Measuring the impact, health, and sustainability of the organisation's open source programme.

---

## Alignment with European Standards

| Standard / Framework | Agora Coverage |
|---|---|
| EU Open Source Strategy | Strategic mandate, contribution policy |
| European Interoperability Framework | Interoperability layers, shared components |
| NIS2 Directive | Supply chain security, SBOM, vulnerability management |
| GDPR / Data Governance Act | Data handling in open source projects |
| OpenChain ISO/IEC 5230 | Licence compliance programme |
| REUSE Specification | Per-file copyright and licence metadata |
| publiccode.yml | Machine-readable software metadata for public administrations |

---

## Licence

This project is licensed under the **European Union Public Licence v1.2 (EUPL-1.2)**.

The EUPL-1.2 is compatible with the GPL family of licences and is specifically designed for European public software. It ensures that derivative works remain open and auditable.

See [LICENSE](LICENSE) for the full licence text.

---

## Maintainers

The Agora Framework is developed and maintained by **IAAUTECO Inc.** in partnership with the open source community.

- **Primary Maintainer:** IAAUTECO Inc.  | Sovereign Infrastructure
- **Repository:** https://github.com/IAAUTECO-inc/Agora-Framework
- **Contact:** contact@iaauteco.ovh

---

## Contributing

We welcome contributions from practitioners, policy experts, legal professionals, and community members. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening an issue or pull request.

---

## Acknowledgements

The Agora Framework draws on the collective work of the global OSPO community, including contributions from the **TODO Group**, the **Linux Foundation**, the **Eclipse Foundation**, **OSPO Alliance**, and the **European Commission's DIGIT** directorate.

---

*"The strength of open source is the community around it."*  
— Linus Torvalds
