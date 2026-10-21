# ATO Copilot Prompt Library

## Purpose

This repository provides a central location for:

- Business use cases for Microsoft Copilot
- Prompt candidates and engineered prompts
- Prompt patterns and reusable templates
- Testing evidence and evaluation results
- Governance artefacts and standards
- Prompt engineering guidance
- Version history and continuous improvement records

## Vision

Establish an ATO-wide repository to capture, develop, test, govern and share high-value Copilot use cases and prompts that improve productivity, consistency and quality across business areas.

## Business Areas

- Private Wealth
- Public Groups
- Individuals
- Small Business
- Frontline
- Resource Management
- Objections and Reviews
- People and Culture
- Enterprise Strategy and Design

## Prompt Lifecycle

```text
Proposed
    ↓
Design
    ↓
Prompt Engineering
    ↓
Testing & Refinement
    ↓
Approved
    ↓
Published
    ↓
Review & Optimisation
```

## Governance

All prompts are subject to:

- Business owner endorsement
- Human review requirements
- Testing and validation
- Quality assessment
- Version control
- Ongoing review and maintenance

---

# Current Use Cases

# Private Wealth

## Available Use Cases

| ID | Use Case | Description |
|------|------|------|
| [PW-UC4-001](docs/business-lines/private-wealth/PW-UC4-001-case-orientation.md) | Case Orientation Assistant | Generate a structured taxpayer and group profile from multiple information sources. |
| [PW-UC4-002](docs/business-lines/private-wealth/PW-UC4-002-rfi-assessment.md) | RFI Response Completeness Assessment | Assess completeness of taxpayer responses against RFI requirements. |
| [PW-UC4-003](docs/business-lines/private-wealth/PW-UC4-003-chronology-generator.md) | Case Chronology Generator | Produce a timeline of events, transactions and supporting evidence. |

## Future Business Areas

- Public Groups
- Individuals
- Small Business
- Frontline
- Resource Management
- Objections and Reviews
- People and Culture
- Enterprise Strategy and Design
---

# Prompt Catalogue

# Prompt Catalogue

| ID | Use Case | Business Area | Status |
|------|------|------|------|
| business-lines/private-wealth/PW-UC4-001-case-orientation.md | Case Orientation Assistant | Private Wealth | Proposed |
| business-lines/private-wealth/PW-UC4-002-rfi-assessment.md | RFI Response Completeness Assessment | Private Wealth | Proposed |
| business-lines/private-wealth/PW-UC4-003-chronology-generator.md | Case Chronology Generator | Private Wealth | Proposed |

## Repository Structure

```text
business-lines/
├── private-wealth/
├── public-groups/
├── individuals/
├── small-business/
└── frontline/

governance/
├── authoring-standards.md
├── testing-framework.md
└── quality-rubric.md

templates/
├── use-case-template.md
└── prompt-template.md

prompt-patterns/

test-evidence/

metrics/
```

## Success Measures

Prompts will be evaluated against:

- Productivity improvement
- Quality of output
- Consistency and repeatability
- Traceability and explainability
- Risk management
- User adoption
- Reusability across business areas

## Guiding Principle

A prompt is not considered a production asset until it has been:

1. Designed against a clear business problem.
2. Tested against defined scenarios.
3. Assessed for quality and risk.
4. Endorsed by the relevant business owner.
5. Published with documented limitations and governance requirements.
