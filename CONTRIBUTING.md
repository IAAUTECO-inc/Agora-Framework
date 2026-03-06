# Contributing to the Agora Framework

Thank you for your interest in contributing to the Agora Framework. This document sets out the processes, standards, and expectations for all contributions. By participating, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

---

## Table of Contents

1. [Types of Contribution](#1-types-of-contribution)
2. [Before You Contribute](#2-before-you-contribute)
3. [Issue Tracking and Discussion](#3-issue-tracking-and-discussion)
4. [Contribution Workflow](#4-contribution-workflow)
5. [Documentation Standards](#5-documentation-standards)
6. [Policy Template Standards](#6-policy-template-standards)
7. [Commit Message Convention](#7-commit-message-convention)
8. [Review Process](#8-review-process)
9. [Licence and Copyright](#9-licence-and-copyright)
10. [Community Roles](#10-community-roles)

---

## 1. Types of Contribution

The Agora Framework welcomes contributions across multiple dimensions:

| Contribution Type | Description | Entry Point |
|---|---|---|
| **Documentation** | Improvements to white paper, templates, guides | Issues or direct PR |
| **Policy Templates** | New or revised OSPO policy instruments | Issue first (discuss scope) |
| **Translation** | Localisation of core documents | Issue first (language coordination) |
| **Regulatory Alignment** | Updates reflecting new EU/national legislation | Issue with reference to legislative text |
| **Tooling** | Scripts, automation, CI/CD improvements | Issue first (scope agreement) |
| **Research and Case Studies** | Real-world OSPO implementation evidence | Discussed via issue |
| **Corrections** | Factual errors, broken links, outdated references | Direct PR with clear explanation |

We do not accept contributions that:
- Introduce proprietary vendor dependencies without open-source alternatives
- Weaken licence compliance or governance standards
- Serve a commercial interest without explicit, declared benefit to the public-interest mission

---

## 2. Before You Contribute

### Check Existing Work

Before opening a new issue or pull request:

1. Search existing [issues](https://github.com/IAAUTECO-inc/Agora-Framework/issues) and [pull requests](https://github.com/IAAUTECO-inc/Agora-Framework/pulls) to avoid duplication.
2. Review the [Roadmap section of GOVERNANCE.md](GOVERNANCE.md#roadmap) to understand planned work.
3. Read the relevant section of the white paper or template you wish to modify.

### Declare Affiliations

If your contribution reflects or is motivated by the position of a specific organisation, institution, or regulatory body, please declare this in your issue or pull request. Transparency strengthens the legitimacy of the framework.

---

## 3. Issue Tracking and Discussion

### Opening an Issue

Use the appropriate issue label:

- `type:bug` — Factual error, broken reference, technical defect
- `type:enhancement` — Proposed improvement to existing content
- `type:new-content` — Proposal for new sections, templates, or documents
- `type:regulatory` — Updates required by legislative or normative changes
- `type:translation` — Localisation requests or submissions
- `type:question` — Questions about the framework's application or intent

### Issue Quality Standards

An issue should contain:

- **Title**: Clear, specific, and descriptive
- **Context**: Why this change is needed (institutional, technical, or policy rationale)
- **Proposed approach**: What you intend to do (even if not yet certain)
- **References**: Links to standards, legislation, or prior art supporting the proposal

---

## 4. Contribution Workflow

### Step 1: Fork and Branch

```bash
# Fork the repository on GitHub, then:
git clone https://github.com/YOUR-USERNAME/Agora-Framework.git
cd Agora-Framework
git remote add upstream https://github.com/IAAUTECO-inc/Agora-Framework.git
git fetch upstream
git checkout -b feature/your-descriptive-branch-name upstream/main
```

**Branch naming convention:**

| Prefix | Use |
|---|---|
| `feature/` | New content or capability |
| `fix/` | Correction of an error |
| `docs/` | Documentation-only changes |
| `policy/` | Policy template additions or revisions |
| `i18n/` | Translation and localisation |
| `chore/` | Maintenance, tooling, dependency updates |

### Step 2: Make Your Changes

Follow the [Documentation Standards](#5-documentation-standards) and [Policy Template Standards](#6-policy-template-standards) below.

### Step 3: Commit

Write clear, conventional commit messages (see [Section 7](#7-commit-message-convention)).

### Step 4: Synchronise

Before submitting, synchronise with upstream:

```bash
git fetch upstream
git rebase upstream/main
```

Resolve conflicts carefully, preserving the intent of both your changes and the upstream content.

### Step 5: Open a Pull Request

Use the [Pull Request Template](.github/PULL_REQUEST_TEMPLATE.md). Ensure all checklist items are addressed.

---

## 5. Documentation Standards

### Language

- All core documents must be written in **institutional English**.
- Language must be clear, precise, and accessible to both technical and non-technical audiences.
- Avoid jargon without explanation. When technical or legal terminology is necessary, provide a brief definition on first use.

### Markdown

- Use [CommonMark](https://commonmark.org/) Markdown.
- Use ATX-style headings (`# H1`, `## H2`, etc.).
- Use fenced code blocks with language identifiers.
- Tables must have a header row and use `|---|` separators.
- Line length is not enforced, but readability is: prefer one sentence per line for prose that benefits from diff clarity.

### Structure

- Each major document should begin with a purpose statement and scope definition.
- Documents longer than 10 sections should include a table of contents.
- All documents must include a version or date indicator in the document header.

---

## 6. Policy Template Standards

Policy templates are the primary operational artefacts of the Agora Framework. They must meet a higher standard of precision.

- **Normative Language**: Use RFC 2119 keywords (`MUST`, `SHOULD`, `MAY`) consistently and correctly.
- **Placeholders**: Mark all organisation-specific fields as `[ORGANISATION NAME]`, `[DATE]`, etc.
- **Regulatory References**: Cite specific articles, recitals, or sections of referenced legislation — not merely document titles.
- **Applicability Statement**: Each template must specify the organisational types for which it is appropriate.
- **Changelog within Template**: Templates must include a version history table at the end.

---

## 7. Commit Message Convention

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification.

**Format:**
```
<type>(<scope>): <short imperative description>

[optional body: what and why, not how]

[optional footer: references, breaking changes]
```

**Types:**

| Type | Use |
|---|---|
| `feat` | New content, template, or framework section |
| `fix` | Correction of factual, legal, or structural errors |
| `docs` | Documentation changes not affecting policy content |
| `style` | Formatting, whitespace, markdown corrections |
| `refactor` | Restructuring without content change |
| `chore` | Tooling, CI, metadata |
| `i18n` | Translation additions or corrections |

**Examples:**

```
feat(policy): add SBOM management policy template

Adds a new policy template covering SBOM generation, maintenance,
and disclosure obligations aligned with NIS2 Article 13 and the
EU Cyber Resilience Act requirements.

Closes #42
```

```
fix(whitepaper): correct OpenChain ISO reference to ISO/IEC 5230:2020

The previous reference cited ISO 5230 without the IEC co-publication
designation, which could cause ambiguity in formal contexts.
```

---

## 8. Review Process

All pull requests require:

- **At least one approving review** from a Maintainer or Core Contributor
- **CI checks passing** (link checking, REUSE compliance, YAML validation)
- **No unresolved review comments**

Review criteria:

1. **Accuracy**: Factual, legal, and technical content is correct and up to date.
2. **Consistency**: Contribution is consistent with the framework's style and standards.
3. **Scope**: The change is within the declared scope of the issue or PR.
4. **Licence**: All contributed content is compatible with EUPL-1.2 and REUSE-compliant.

Maintainers aim to provide an initial review response within **10 business days**.

---

## 9. Licence and Copyright

By submitting a contribution to the Agora Framework, you agree that:

1. Your contribution is licensed under the **European Union Public Licence v1.2 (EUPL-1.2)**, or a licence compatible therewith.
2. You have the right to make this contribution (i.e., it is your original work or you have the necessary permissions).
3. You agree to the **Developer Certificate of Origin (DCO)**. Sign off your commits:

```bash
git commit -s -m "feat(governance): add OSPO mandate definition template"
```

This appends `Signed-off-by: Your Name <your.email@example.org>` to the commit message, certifying your agreement with the [DCO](https://developercertificate.org/).

4. If your contribution incorporates third-party content, you must identify it, confirm it is under a compatible licence, and add the appropriate REUSE copyright and licence header.

---

## 10. Community Roles

| Role | Description |
|---|---|
| **Contributor** | Anyone who opens an issue or submits a pull request |
| **Reviewer** | Contributors with demonstrated expertise invited to review PRs |
| **Core Contributor** | Regular, substantive contributors with merge recommendation rights |
| **Maintainer** | Responsible for final review, merge authority, and release management |
| **Steward** | IAAUTECO Inc. — ultimate governance and direction authority |

Role transitions are governed by the [Governance document](GOVERNANCE.md).

---

*For questions not answered here, please open a `type:question` issue or contact the maintainers at governance@iaauteco.org.*
