# Agora: A Reference Framework for Open Source Program Offices in Public and Mission-Driven Institutions

**Document Type:** White Paper  
**Version:** 1.0.0  
**Date:** June 2025  
**Status:** Published  
**Licence:** European Union Public Licence v1.2 (EUPL-1.2)  
**Publisher:** IAAUTECO Inc.  
**Contact:** governance@iaauteco.org  
**Repository:** https://github.com/IAAUTECO-inc/Agora-Framework

---

## Table of Contents

1. [Executive Summary](#1-executive-summary)
2. [Introduction: The Open Source Imperative](#2-introduction-the-open-source-imperative)
3. [The OSPO: Concept, History, and Institutional Relevance](#3-the-ospo-concept-history-and-institutional-relevance)
4. [The Agora Framework: Rationale and Design Philosophy](#4-the-agora-framework-rationale-and-design-philosophy)
5. [Pillar I: Institutional Mandate](#5-pillar-i-institutional-mandate)
6. [Pillar II: Policy Architecture](#6-pillar-ii-policy-architecture)
7. [Pillar III: Compliance and Licence Stewardship](#7-pillar-iii-compliance-and-licence-stewardship)
8. [Pillar IV: Contribution Governance](#8-pillar-iv-contribution-governance)
9. [Pillar V: Community and Ecosystem Engagement](#9-pillar-v-community-and-ecosystem-engagement)
10. [Pillar VI: Metrics and Accountability](#10-pillar-vi-metrics-and-accountability)
11. [Alignment with the European Regulatory Landscape](#11-alignment-with-the-european-regulatory-landscape)
12. [Implementation Guidance](#12-implementation-guidance)
13. [Conclusion](#13-conclusion)
14. [References and Further Reading](#14-references-and-further-reading)

---

## 1. Executive Summary

Public administrations, research organisations, and mission-driven enterprises across Europe are increasingly dependent on open source software. This dependency, while strategically advantageous, introduces governance obligations that most institutions are ill-equipped to manage systematically. The consequences are legal exposure through licence non-compliance, security vulnerabilities in untracked dependencies, missed opportunities for upstream contribution, and the erosion of institutional knowledge concerning the organisation's own software assets.

The **Agora Framework** addresses these challenges by providing a comprehensive, standards-aligned reference architecture for establishing and operating an **Open Source Program Office (OSPO)**. Drawing on the metaphor of the ancient Greek *agora* — the civic space in which public deliberation, commerce, and governance converged — the framework positions the OSPO not as a bureaucratic control function but as an enabling institution: the central forum through which an organisation's relationship with the open source ecosystem is strategically managed, ethically governed, and publicly accountable.

This white paper presents the six structural pillars of the Agora Framework — Institutional Mandate, Policy Architecture, Compliance and Licence Stewardship, Contribution Governance, Community and Ecosystem Engagement, and Metrics and Accountability — alongside guidance on European regulatory alignment and a phased implementation pathway.

The Agora Framework is released under the EUPL-1.2 licence and is designed for institutional adoption, adaptation, and contribution.

---

## 2. Introduction: The Open Source Imperative

### 2.1 The Pervasiveness of Open Source

Open source software is no longer a peripheral phenomenon in institutional computing. It constitutes the foundational layer of virtually all modern digital infrastructure: operating systems, networking stacks, container orchestration platforms, data processing pipelines, artificial intelligence frameworks, and web services. Surveys consistently indicate that more than 95% of commercial software products incorporate open source components. In the public sector, this proportion is equally significant, with European institutions operating critical services on Linux-based infrastructure, deploying applications built on open source frameworks, and increasingly publishing their own software as open source.

This pervasiveness is both an asset and a responsibility. Open source software offers verifiable auditability, vendor independence, collaborative development at ecosystem scale, and alignment with the European values of transparency and digital sovereignty. It is also software that comes with obligations: licence conditions that govern its use, modification, and distribution; security implications that require active supply chain management; and community relationships that demand institutional engagement if the benefits of the ecosystem are to be sustainably maintained.

### 2.2 The Governance Gap

Despite the strategic centrality of open source software, the governance structures within most institutions remain rudimentary. Software is procured or adopted without systematic licence evaluation. Contributions are made — or not made — without policy guidance. Security vulnerabilities in open source dependencies are discovered reactively. The institutional knowledge of which open source components are deployed, and under what terms, is fragmented across teams and individuals.

This governance gap is not merely an operational inconvenience. It represents a growing legal, security, and strategic risk:

**Legal risk**: Licence non-compliance can expose an organisation to intellectual property claims, reputational damage, and, in the context of software distributed to third parties, significant commercial liability.

**Security risk**: The NIS2 Directive and the EU Cyber Resilience Act impose supply chain security obligations that cannot be met without systematic visibility into software dependencies — the exact visibility that an OSPO is designed to provide.

**Strategic risk**: Institutions that consume open source without contributing to it are progressively excluded from upstream governance, rendering them dependent on the decisions of external communities over which they have no influence.

**Sovereign risk**: European public institutions that outsource their open source governance to US-headquartered platforms or proprietary toolchains undermine the very digital sovereignty that open source is intended to advance.

### 2.3 The Emerging Mandate

Recognition of this governance gap is driving institutional action. The European Commission's Open Source Strategy 2020–2023 explicitly mandated the creation of OSPOs within Commission services. The Interoperable Europe Act establishes interoperability and openness as foundational principles of European public digital infrastructure. National digital ministries from France to Germany to the Netherlands are implementing open source policies that require institutional governance structures commensurate with the strategic importance of open source.

The Agora Framework responds to this mandate with a practical, standards-aligned, and immediately deployable governance architecture.

---

## 3. The OSPO: Concept, History, and Institutional Relevance

### 3.1 Origins of the OSPO

The Open Source Program Office emerged in the technology industry during the early 2000s, as enterprises sought to manage the legal, strategic, and community dimensions of their growing open source engagement. Google established one of the first known OSPOs circa 2004. Subsequently, companies including Red Hat, IBM, Microsoft, and Intel formalised similar structures.

The TODO Group — an open community of practitioners at major technology companies — played a key role in standardising OSPO practices, developing guidance documents, case studies, and the open governance model upon which much current practice is based.

### 3.2 The OSPO in Public and Institutional Contexts

The public sector and research institution application of the OSPO concept is more recent, but is accelerating rapidly. The European Commission's OSPO, established in 2020, was among the first institutional OSPOs in a public administration. It has been followed by OSPOs at several European national agencies, research councils, and intergovernmental bodies.

Public-sector OSPOs differ from their private-sector antecedents in several important respects:

- They operate under public procurement law, which introduces specific obligations and constraints on software acquisition and publication.
- They must balance transparency and auditability obligations inherent in public accountability with the operational security requirements of critical infrastructure.
- Their licence compliance obligations are shaped not merely by commercial risk but by the legal personality of public bodies and the specific conditions of public-sector licences.
- Their contribution to open source is simultaneously a policy act — a form of public investment — and must therefore be governed with the rigour appropriate to public expenditure.

### 3.3 OSPO Functions: An Overview

A fully operational OSPO performs functions across five domains:

**Legal and Compliance**: Maintaining an inventory of open source components, evaluating licence compatibility, managing the contribution process to ensure that intellectual property obligations are met.

**Policy and Strategy**: Developing and maintaining the institution's open source policy framework, advising on open source implications of procurement decisions, and aligning open source strategy with institutional digital strategy.

**Engineering Support**: Providing technical guidance on open source tooling, security practices, SBOM generation, and dependency management.

**Community and Ecosystem**: Managing the institution's relationships with upstream communities, coordinating participation in standards bodies and industry working groups, and representing the institution in open source governance forums.

**Education and Evangelism**: Building institutional awareness and capacity for open source engagement, training staff, and communicating the value of open source governance to institutional leadership.

---

## 4. The Agora Framework: Rationale and Design Philosophy

### 4.1 Name and Metaphor

The *agora* (ἀγορά) was the central public space of the ancient Greek *polis* — simultaneously a marketplace, a civic forum, a place of justice, and an arena for democratic deliberation. It was not merely a location but an institution: the organised expression of a community's commitment to conduct its collective affairs publicly, transparently, and accountably.

The choice of this name for an OSPO reference framework is deliberate. An effective OSPO is not a control function imposed on an organisation's software practices. It is an enabling institution — a structured space in which the organisation's relationship with the open source ecosystem is conducted with the same qualities that made the ancient agora the foundation of democratic governance: openness, deliberation, accountability, and the primacy of the public interest.

### 4.2 Design Principles

The Agora Framework is designed according to the following principles:

**Interoperability-first**: All components of the framework are designed to interoperate with existing institutional processes — procurement, security, legal, and IT governance — rather than existing in isolation.

**Standards alignment**: The framework does not reinvent the wheel. Where authoritative standards exist — OpenChain ISO/IEC 5230, REUSE, CHAOSS, publiccode.yml — the framework aligns to and extends them, rather than creating competing instruments.

**Proportionality**: The framework is modular. Institutions at different levels of open source maturity can adopt specific pillars while deferring others, following a phased implementation pathway that respects organisational capacity constraints.

**Openness by design**: The framework itself is open source, governed by the EUPL-1.2, and developed in public. The governance instruments that guide the production of the framework are the same instruments it recommends for institutional adoption.

**European sovereignty**: The framework is explicitly oriented toward the European institutional context — its regulatory alignment, its licence recommendations, its governance philosophy — while remaining practically applicable in any jurisdiction that values open, auditable, and accountable digital infrastructure.

### 4.3 Framework Architecture

The Agora Framework is structured around six pillars, each representing a distinct domain of OSPO responsibility. The pillars are designed to be mutually reinforcing: effective licence compliance depends on clear policy; effective contribution governance depends on community engagement; effective metrics depend on all other pillars being operational.

---

## 5. Pillar I: Institutional Mandate

### 5.1 The Necessity of Formal Mandate

An OSPO without institutional authority is an advisory function without leverage. The history of OSPO implementations demonstrates consistently that programme offices that lack formal mandate — expressed through policy instrument, executive decision, or legislative act — are unable to enforce compliance, establish policy, or allocate resources commensurate with the scope of the governance challenge.

Pillar I of the Agora Framework concerns the establishment of this formal mandate: the institutional, legal, and organisational authority that positions the OSPO as a legitimate governance function rather than an informal community of practice.

### 5.2 Components of an Institutional Mandate

An effective institutional mandate for an OSPO comprises the following components:

**Founding Instrument**: A policy decision, executive order, or governance resolution that formally establishes the OSPO, defines its mission, and grants it authority to develop and enforce policy within its domain.

**Scope Definition**: Explicit definition of the software categories, organisational units, and activities subject to OSPO governance. This includes consumed open source software, internally developed software published as open source, contributions to external projects, and procurement decisions with open source implications.

**Resource Allocation**: Dedicated staffing, budget, and tooling. An OSPO that operates on the margins of existing teams' capacity cannot perform its functions effectively.

**Reporting Line**: The OSPO's position within the institutional hierarchy. For maximum effectiveness, the OSPO should report to a senior executive with authority over both legal/compliance and engineering/IT functions.

**Accountability Mechanism**: A defined mechanism by which the OSPO reports on its activities, metrics, and policy decisions to institutional leadership and, where applicable, to external stakeholders.

### 5.3 The Mandate Template

The Agora Framework provides a formal [OSPO Policy Template](../templates/ospo-policy-template.md) that can be adapted to serve as the founding instrument for an institutional OSPO. The template is designed to be adopted by formal decision of the relevant governing body and to provide a complete, self-contained policy instrument.

---

## 6. Pillar II: Policy Architecture

### 6.1 Overview

Policy is the mechanism through which the institutional mandate is operationalised. An OSPO's policy architecture defines the rules, principles, and procedures that govern every dimension of the organisation's open source engagement.

The Agora Framework identifies six policy domains, each requiring a dedicated policy instrument or policy section:

### 6.2 Policy Domain 1: Consumption Policy

The Consumption Policy governs the use of open source software within the organisation. It addresses:

- **Licence categorisation**: Classifying open source licences into approved, conditionally approved, and prohibited categories based on their compatibility with the organisation's legal context and distribution practices.
- **Dependency management**: Requirements for maintaining a current, complete inventory of open source dependencies (Software Bill of Materials).
- **Security due diligence**: Obligations to assess the security posture of open source components before adoption, including review of known vulnerability databases (CVE, OSV) and community health indicators.
- **Procurement integration**: Requirements for open source licence and security assessment to be incorporated into software procurement processes.

### 6.3 Policy Domain 2: Contribution Policy

The Contribution Policy governs the organisation's contributions to external open source projects. It addresses:

- **Authority and approval**: Who may contribute on behalf of the organisation and under what circumstances.
- **IP assignment and licence**: Under what licence contributions are made and how intellectual property ownership is managed.
- **Disclosure obligations**: What must be disclosed to the OSPO prior to contribution.
- **Strategic contribution**: How the organisation identifies strategic upstream projects in which contribution is actively encouraged.

### 6.4 Policy Domain 3: Publication Policy

The Publication Policy governs the release of internally developed software as open source. It addresses:

- **Publication criteria**: Conditions under which internal software may or should be published as open source.
- **Licence selection**: Guidance on selecting an appropriate open source licence for published software, with specific consideration of EUPL-1.2 for public administrations.
- **Quality standards**: Minimum standards of documentation, security, and maintainability that software must meet before publication.
- **Community obligations**: Institutional commitments to maintaining published software over time.

### 6.5 Policy Domain 4: Security Policy

The Security Policy addresses the specific security obligations arising from open source use. It addresses:

- **SBOM generation and maintenance**: Requirements for generating and maintaining Software Bills of Materials aligned with SPDX or CycloneDX standards.
- **Vulnerability management**: Processes for monitoring, triaging, and remediating security vulnerabilities in open source dependencies.
- **Supply chain integrity**: Measures to verify the integrity and provenance of open source components, including signing requirements.
- **NIS2 and CRA alignment**: Specific provisions to meet the supply chain security obligations imposed by the NIS2 Directive and the EU Cyber Resilience Act.

### 6.6 Policy Domain 5: Inner Source Policy

The Inner Source Policy governs the application of open source principles to internal software development. It addresses:

- **Inner source programme scope**: Which internal repositories are governed by inner source principles.
- **Cross-unit contribution**: Rules enabling staff from one organisational unit to contribute to codebases maintained by another.
- **Review and quality standards**: Equivalent standards to those applied in external open source contributions.

### 6.7 Policy Domain 6: AI and Model Governance (Emerging)

As organisations increasingly deploy AI systems built on open source models and frameworks, a dedicated policy domain is required. It addresses:

- **Open source AI model licensing**: Compliance with the specific and often complex licence conditions attached to open source AI models.
- **Training data provenance**: Obligations concerning the provenance and licence compliance of training datasets.
- **Model publication**: Standards for the publication of internally trained models as open source.

---

## 7. Pillar III: Compliance and Licence Stewardship

### 7.1 The OpenChain Standard

The Agora Framework aligns its compliance pillar with **OpenChain ISO/IEC 5230:2020**, the international standard for open source licence compliance programmes. OpenChain defines the minimum requirements for a quality open source compliance programme and provides a self-certification pathway that institutions can use to demonstrate compliance to partners and regulators.

### 7.2 Core Compliance Processes

An OpenChain-aligned compliance programme within the Agora Framework comprises the following processes:

**Component Identification**: The systematic identification of all open source components in every software system, using automated tooling (licence scanners, dependency graph analysis) supplemented by manual review.

**Licence Analysis**: Evaluation of each identified licence to determine its conditions, categorise it within the organisation's licence classification system, and identify any compatibility constraints.

**Obligation Fulfilment**: Implementation of processes to fulfil the specific obligations of each licence: provision of licence notices, attribution statements, source code availability, and other conditions.

**SBOM Management**: Generation, maintenance, and — where required — disclosure of Software Bills of Materials. The Agora Framework recommends alignment with the SPDX standard (ISO/IEC 5962) for SBOM format.

**Compliance Verification**: Periodic audits of compliance processes and their outcomes, including verification of SBOM accuracy and completeness.

### 7.3 REUSE Compliance

For software published by the organisation, the Agora Framework recommends compliance with the **REUSE Specification** developed by the Free Software Foundation Europe. REUSE provides a simple, machine-readable method for declaring copyright and licence information at the per-file level, making licence compliance auditable by automated tools.

---

## 8. Pillar IV: Contribution Governance

### 8.1 The Strategic Importance of Contribution

Contribution to upstream open source projects is not a peripheral activity — it is the primary mechanism through which an organisation sustains the open source components on which it depends. Organisations that consume without contributing are free riders on the labour of others. More practically, they have no influence over the roadmap of projects that may be critical to their operations.

Contribution governance — the set of policies, processes, and accountabilities that structure how the organisation contributes to external open source projects — is therefore a strategic function of the OSPO.

### 8.2 Contribution Models

The Agora Framework distinguishes three contribution models:

**Inbound contributions**: Open source software consumed by the organisation and incorporated into internal systems. Governance concerns: licence compliance, security due diligence, dependency tracking.

**Outbound contributions**: Code, documentation, testing, or other contributions made by organisational staff to external open source projects. Governance concerns: IP ownership, licence alignment, approval workflow, strategic alignment.

**Inner source**: Application of open source contribution practices to internal software development, enabling cross-organisational collaboration without public publication. Governance concerns: review standards, contribution rules, intellectual property between units.

### 8.3 Contribution Workflow

A standardised contribution workflow governed by the OSPO should include the following stages:

1. **Identification**: The contributing individual identifies the project and nature of contribution.
2. **Pre-contribution review**: OSPO review of IP ownership, licence compatibility, and strategic alignment.
3. **Authorisation**: Formal authorisation (which may be pre-authorised for approved projects or categories).
4. **Contribution**: The contribution is made, following the project's own contribution guidelines.
5. **Recording**: The contribution is recorded in the organisation's contribution register.
6. **Review**: Periodic review of contribution portfolio to assess strategic value and alignment.

---

## 9. Pillar V: Community and Ecosystem Engagement

### 9.1 Ecosystem Participation as Governance

Open source ecosystems are not markets — they are communities. The norms, decisions, and trajectories of these communities are shaped by the participation of their members. An organisation that does not participate in the governance of the open source projects it depends upon is not merely a passive consumer; it is an absentee stakeholder in decisions that directly affect its operational continuity.

The OSPO is the institution's primary interface with the open source ecosystem. Its community engagement function encompasses:

**Upstream governance participation**: Representation of the organisation in the governance bodies of strategic open source projects — technical committees, steering groups, advisory boards.

**Standards body engagement**: Participation in standards development organisations whose work shapes the normative landscape of open source: OASIS, ISO/IEC JTC1, W3C, IETF, and European standards bodies.

**Consortium and working group membership**: Active participation in organisations such as the TODO Group, OSPO Alliance, Linux Foundation, Eclipse Foundation, and Open Source Initiative.

**Ecosystem health investment**: Funding, tooling, infrastructure support, and event sponsorship that sustains the health of the ecosystems in which the organisation has strategic interest.

### 9.2 Community Communication

The OSPO must also manage the organisation's public communication as an open source actor: publishing contribution statistics, communicating open source policy, and representing the organisation's open source posture to external audiences including partners, regulators, and civil society.

---

## 10. Pillar VI: Metrics and Accountability

### 10.1 CHAOSS Alignment

The Agora Framework aligns its metrics pillar with the **CHAOSS** (Community Health Analytics in Open Source Software) project, which provides a comprehensive catalogue of open source community health metrics. CHAOSS metrics are designed to be measurable, actionable, and comparable across projects and organisations.

### 10.2 OSPO Metrics Categories

The Agora Framework organises OSPO metrics across four categories:

**Consumption Metrics**
- Number of open source dependencies tracked
- Percentage of dependencies with up-to-date SBOM entries
- Time-to-remediation for high-severity vulnerabilities in open source dependencies
- Licence compliance rate (percentage of components with verified licence compliance)

**Contribution Metrics**
- Volume of outbound contributions (commits, pull requests, issues, documentation)
- Number of upstream projects to which the organisation contributes
- Acceptance rate of submitted contributions
- Number of staff with active upstream contributions

**Community Metrics**
- Number of open source projects maintained or co-maintained by the organisation
- Community health scores for maintained projects (CHAOSS indicators)
- Participation in open source governance bodies
- Number of open source events hosted or sponsored

**Governance Metrics**
- Policy coverage rate (percentage of OSPO policy domains with active, reviewed policy instruments)
- OSPO maturity level (aligned with a defined maturity model)
- Staff training completion rate (open source licence and compliance training)
- Time-to-decision for contribution authorisation requests

### 10.3 Reporting and Accountability

OSPO metrics should be reported at defined intervals (quarterly operational metrics; annual strategic metrics) to institutional leadership and, where applicable, published in an annual Open Source Programme Report. This report serves as the primary instrument of public accountability for the organisation's open source stewardship.

---

## 11. Alignment with the European Regulatory Landscape

The Agora Framework is designed with explicit awareness of the European regulatory landscape in which most of its target institutions operate. The following table summarises key alignments:

| Instrument | Relevance | Agora Coverage |
|---|---|---|
| **EU Open Source Strategy 2020–2023** | Mandates OSPO establishment in Commission services; sets "open source by default" aspiration | Pillars I, II |
| **Interoperable Europe Act** | Establishes interoperability and openness as mandated principles for public digital infrastructure | Pillars I, II, VI |
| **NIS2 Directive** | Supply chain security obligations for essential and important entities | Pillar III, II §6.4 |
| **EU Cyber Resilience Act** | Software security requirements for products with digital elements | Pillar III, II §6.4 |
| **European Interoperability Framework (EIF)** | Interoperability principles across technical, semantic, organisational, and legal layers | Pillars II, V |
| **GDPR / Data Governance Act** | Data handling obligations relevant to open source projects involving personal data | Pillar II §6.4 |
| **Public Procurement Directive (2014/24/EU)** | Requirements affecting open source procurement and publication decisions | Pillars I, II §6.3 |
| **OpenChain ISO/IEC 5230:2020** | International standard for open source licence compliance programmes | Pillar III |
| **SPDX ISO/IEC 5962:2021** | Standard for Software Bill of Materials format | Pillar III |
| **REUSE Specification** | Per-file copyright and licence metadata | Pillar III |
| **publiccode.yml** | Machine-readable public software metadata | Pillar I, II §6.3 |

---

## 12. Implementation Guidance

### 12.1 Maturity-Based Phasing

The Agora Framework acknowledges that organisations begin OSPO implementation from different starting points. A phased approach, calibrated to the organisation's current open source maturity, is recommended:

**Phase 0 — Assessment (Months 1–2)**
- Inventory existing open source consumption, contribution, and publication practices
- Assess current governance gaps against the six Agora pillars
- Identify champions and stakeholders
- Establish the business case for OSPO establishment

**Phase 1 — Foundation (Months 3–6)**
- Establish the institutional mandate (Pillar I)
- Draft and adopt the consumption policy (Pillar II, Domain 1)
- Deploy basic SBOM tooling (Pillar III)
- Appoint initial OSPO staff

**Phase 2 — Consolidation (Months 7–18)**
- Complete the policy architecture (Pillar II, all domains)
- Implement OpenChain-aligned compliance processes (Pillar III)
- Establish the contribution governance workflow (Pillar IV)
- Deploy baseline CHAOSS metrics (Pillar VI)

**Phase 3 — Maturity (Month 18+)**
- Activate community and ecosystem engagement (Pillar V)
- Establish inner source programme (Pillar IV)
- Publish annual Open Source Programme Report (Pillar VI)
- Pursue OpenChain self-certification or third-party assessment

### 12.2 Toolchain Recommendations

The Agora Framework does not mandate specific tools, but recommends consideration of the following open source toolchain components:

- **SBOM generation**: `syft`, `cdxgen`, or SPDX tools
- **Licence scanning**: `licensee`, `scancode-toolkit`, or `FOSSA` (community edition)
- **Dependency tracking**: `Dependency-Track`, `GUAC`
- **REUSE compliance**: `reuse` CLI tool (FSFE)
- **Community health metrics**: GrimoireLab (CHAOSS)
- **Git forge**: Forgejo, GitLab CE, or GitHub (with awareness of sovereignty implications)

---

## 13. Conclusion

The establishment of a well-governed Open Source Program Office is no longer a voluntary enhancement to institutional digital strategy — it is an operational necessity and, for an increasing number of European public bodies, a regulatory obligation. The governance gap between the strategic centrality of open source software and the institutional maturity to manage it cannot be closed by informal means.

The Agora Framework provides the architecture to close this gap: a six-pillar model that covers the full scope of OSPO responsibility, aligned with European standards and regulatory requirements, and available in immediately adaptable form for institutional deployment.

Like the ancient agora, an effective OSPO is not simply an administrative function. It is a civic institution — the organised expression of an organisation's commitment to conduct its engagement with the open source commons with the transparency, accountability, and respect for the public interest that the commons demands.

The Agora Framework is an open source project. We invite institutions, practitioners, and communities to engage with it, adapt it, and contribute to its continued development.

---

## 14. References and Further Reading

**Standards and Specifications**
- OpenChain ISO/IEC 5230:2020 — https://www.openchainproject.org/
- SPDX ISO/IEC 5962:2021 — https://spdx.dev/
- REUSE Specification — https://reuse.software/
- CHAOSS Metrics — https://chaoss.community/
- publiccode.yml Standard — https://yml.publiccode.tools/

**European Policy and Legislation**
- European Commission Open Source Strategy 2020–2023 — https://ec.europa.eu/info/departments/informatics/open-source-software-strategy_en
- Interoperable Europe Act (EU) 2024/903
- NIS2 Directive 2022/2555
- EU Cyber Resilience Act (pending)
- European Interoperability Framework — https://joinup.ec.europa.eu/collection/nifo-national-interoperability-framework-observatory/european-interoperability-framework-detail

**OSPO Community Resources**
- TODO Group — https://todogroup.org/
- OSPO Alliance — https://ospo.zone/
- Linux Foundation OSPO Guide — https://github.com/todogroup/ospodefinition.org
- Eclipse Foundation OSPO Resources — https://www.eclipse.org/

**Licences**
- European Union Public Licence v1.2 — https://joinup.ec.europa.eu/collection/eupl/eupl-text-eupl-12
- SPDX Licence List — https://spdx.org/licenses/

---

*This document is part of the Agora Framework, published by IAAUTECO Inc. under the European Union Public Licence v1.2.*
