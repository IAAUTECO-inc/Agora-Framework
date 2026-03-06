# Governance

## The Agora Framework — Governance Model

**Version:** 1.0.0  
**Effective Date:** 2025-06-01  
**Maintained by:** IAAUTECO Inc.

---

## 1. Purpose and Principles

This document describes the governance model of the **Agora Framework** — a public, institutionally-oriented open source project under the stewardship of IAAUTECO Inc.

The governance of the Agora Framework is founded on the following principles:

**Transparency**: All decisions, discussions, and rationales are documented publicly in this repository.

**Meritocracy**: Influence in the project is earned through substantive, sustained contribution, not through institutional position or commercial standing.

**Subsidiarity**: Decisions are made at the lowest appropriate level. Technical decisions are made by practitioners. Strategic decisions are made by Maintainers. Constitutional decisions require community consultation.

**Public Interest Primacy**: The framework serves the public interest in open, sovereign, and auditable digital infrastructure. No governance decision may prioritise private or commercial interests over this mission.

**Accountability**: All role-holders are accountable to the community and to the governance model described herein.

---

## 2. Project Roles and Responsibilities

### 2.1 Steward

**Holder:** IAAUTECO Inc.

The Steward holds ultimate fiduciary and strategic responsibility for the project. The Steward's responsibilities include:

- Maintaining the project repository and infrastructure
- Ensuring the project remains aligned with its public-interest mission
- Exercising final authority in cases of unresolved governance disputes
- Managing legal instruments including the project licence and contributor agreements
- Approving changes to this Governance document

The Steward commits to exercising authority sparingly and transparently, in accordance with the principles above. The Steward publishes a rationale for any decision made in override of community consensus.

### 2.2 Maintainers

Maintainers are individuals with a demonstrated, sustained commitment to the Agora Framework. They hold merge authority and final editorial responsibility.

**Current Maintainers:** Listed in `MAINTAINERS.md` (to be created upon appointment of additional maintainers).

**Responsibilities:**
- Review and merge pull requests
- Manage the issue backlog and project roadmap
- Release new versions following the process in Section 5
- Enforce the Code of Conduct
- Communicate project decisions to the community
- Represent the project in external forums and working groups

**Quorum:** Decisions requiring Maintainer consensus require agreement from a majority of active Maintainers (at least two, where more than two Maintainers are appointed).

### 2.3 Core Contributors

Core Contributors are individuals who make regular, high-quality contributions and participate in project discussions. They hold advisory rights in governance discussions but not merge authority.

**Recognition criteria:**
- Minimum of five accepted, substantive pull requests over a 6-month period, OR
- Demonstrated domain expertise of direct relevance to the framework, with at least three accepted contributions

**Responsibilities:**
- Review pull requests and provide substantive technical or editorial feedback
- Participate in roadmap discussions
- Advocate for community interests in Maintainer deliberations

**Appointment:** Proposed by any Maintainer. Confirmed by Maintainer consensus. Recorded in `MAINTAINERS.md`.

### 2.4 Reviewers

Reviewers are contributors with specific domain expertise (legal, regulatory, technical, or policy) invited to review particular pull requests or sections. They do not hold ongoing governance responsibilities.

### 2.5 Contributors

Anyone who opens an issue, submits a pull request, participates in discussions, or otherwise engages with the project is a Contributor. Contributors are subject to the Code of Conduct and the Contributing guidelines.

---

## 3. Decision-Making Processes

### 3.1 Operational Decisions

**Definition:** Day-to-day decisions concerning individual pull requests, issue prioritisation, minor documentation updates, and process improvements.

**Process:** Decided by the Maintainer performing review, following the standards in `CONTRIBUTING.md`. No formal vote required.

### 3.2 Significant Decisions

**Definition:** Changes to framework scope, introduction of new major sections, regulatory alignment updates, toolchain changes, and decisions affecting the project roadmap.

**Process:**
1. A proposal is documented as a GitHub Issue with the label `governance:proposal`.
2. A minimum **14-day comment period** allows community input.
3. The proposal is discussed at the next scheduled Maintainer review cycle.
4. Maintainer consensus is required for approval.
5. The decision and its rationale are documented in the issue before closure.

### 3.3 Constitutional Decisions

**Definition:** Changes to this Governance document, the Code of Conduct, the project licence, the project name or mission, or Maintainer appointments and removals.

**Process:**
1. Proposed as a pull request with the label `governance:constitutional`.
2. Minimum **30-day community consultation period**.
3. All Core Contributors and current Maintainers are individually notified.
4. Supermajority (two-thirds) of active Maintainers must approve.
5. The Steward holds right of veto, which must be exercised in writing with stated rationale within the consultation period.

### 3.4 Conflict Resolution

Where a pull request or proposal generates irreconcilable disagreement:

1. **Level 1 — Facilitated discussion**: The submitting party and a Maintainer engage in structured discussion on the issue thread. Goal: identify common ground or a compromise.
2. **Level 2 — Maintainer panel**: All active Maintainers are convened. A decision is reached by majority vote, with rationale recorded.
3. **Level 3 — Steward arbitration**: If Maintainers cannot reach consensus, the Steward makes a final determination, which is documented in full.

---

## 4. Community Forums

| Forum | Purpose | Access |
|---|---|---|
| GitHub Issues | Proposals, bug reports, questions | Public |
| GitHub Discussions | Community deliberation and RFC processes | Public |
| Pull Requests | Code and documentation review | Public |
| Maintainer Review (async) | Coordination of releases and significant decisions | Maintainers |
| governance@iaauteco.org | Formal governance correspondence | Email |

Community meetings may be convened as needed, with at least **14 days' advance notice**, published as a GitHub Discussion. Meetings are recorded and minutes published within 7 days.

---

## 5. Versioning and Release Process

The Agora Framework uses **Semantic Versioning 2.0.0**:

- **MAJOR** (`X.0.0`): Breaking changes to the framework structure, scope, or fundamental policy templates
- **MINOR** (`1.X.0`): New templates, major new sections, significant enhancements
- **PATCH** (`1.0.X`): Corrections, clarifications, regulatory updates, formatting fixes

### Release Steps

1. Maintainer opens a `release/vX.Y.Z` branch from `main`.
2. `CHANGELOG.md` is updated to move items from `[Unreleased]` to the new version section.
3. `publiccode.yml` `softwareVersion` and `releaseDate` fields are updated.
4. Pull request from release branch to `main` is opened with label `type:release`.
5. At least one additional Maintainer reviews and approves.
6. Pull request is merged and a signed Git tag `vX.Y.Z` is created.
7. A GitHub Release is published with the `CHANGELOG.md` section as release notes.

---

## 6. Roadmap

The following capabilities are planned for future releases. Priorities are reviewed at each minor release cycle.

| Item | Target Version | Status |
|---|---|---|
| Multilingual templates (FR, DE, ES) | v1.1.0 | Planned |
| OSPO Maturity Model assessment toolkit | v1.1.0 | In discussion |
| SBOM policy and workflow template | v1.2.0 | Planned |
| CI/CD pipeline for REUSE compliance | v1.1.0 | Planned |
| Case study collection | v1.2.0 | Seeking contributions |
| Integration guides (GitHub Enterprise, GitLab) | v1.2.0 | Planned |
| OpenChain ISO/IEC 5230 self-certification checklist | v1.3.0 | Planned |

---

## 7. Amendments to This Document

Amendments to this Governance document follow the Constitutional Decision process (Section 3.3). The amendment history is tracked via Git commit history. Each amendment is documented in `CHANGELOG.md`.

---

*"Governance is not control — it is the shared framework within which freedom becomes productive."*

---

**Agora Framework Governance** — maintained by IAAUTECO Inc. under the European Union Public Licence v1.2.
