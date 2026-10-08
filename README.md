# {{Project Name}}

## Overview
Brief description of the project, its purpose, and business value.

## Status
- {{Project Status}} i.e. Active / Paused / Complete

## Tech Stack
(If applicable, what products/technologies are used by the project)
- {{Project Language(s)}}: i.e. .NET / Node / Python
- {{Project Database(s)}}: i.e. SQL Server / mySQL
- Other: i.e. CloverDX / Docker

## Getting Started
This repository serves as the project's knowledge base and working archive.

**📖 [Browse the documentation wiki](docs/index.md)** - the recommended entry point into the project's domain, architecture, data model, integrations, ADRs, and meeting notes.

---

# Guiding Principles

This repository prioritizes documenting:

- Business concepts
- Business processes
- Data governance policies
- Stewardship processes
- Architectural decisions
- Integration patterns
- Operational knowledge

over implementation details alone.

The repository exists to preserve organizational knowledge and design rationale, not merely source code documentation.

---

# Repository Structure

## Wiki Root

```text
docs/
```

The document wiki lives under the `docs/` root folder.

## Vision

```text
docs/vision/
```

Project goals, roadmap, strategy, long-term direction, decisions in flight, and stakeholder information.

Recommended starting point for new team members.

---

## Domain

```text
docs/domain/
```

Core business concepts and terminology.

Examples:

- Customer
- Project
- Payment
- GL Account String

---

## Architecture

```text
docs/architecture/
```

System architecture and design documentation.

Examples:

- System Overview

---

## Data Model

```text
docs/data-model/
```

Documentation describing key entities, relationships, and governance rules.

---

## Integrations

```text
docs/integrations/
```

Documentation for source systems and consumers.

---

## Operations

```text
docs/operations/
```

Operational procedures and support documentation.

Examples:

- Monitoring
- Reconciliation
- Runbooks
- Data correction procedures

---

## ADRs

```text
docs/adrs/
```

Architecture Decision Records.

Each ADR should document:

- Context
- Decision
- Alternatives Considered
- Consequences

---

## Meeting Notes

```text
docs/meetings/
```

Meeting summaries, decisions, action items, and discussion outcomes.

Meeting notes should reference related ADRs and documentation when applicable.

---

## Glossary and Index

```text
docs/glossary.md
docs/index.md
```

`docs/index.md` is the recommended entry point into the wiki, linking out to every section above. `docs/glossary.md` defines domain terms consistently for reuse across all pages.

---

## Source Artifacts

```text
raw/
```

Original, unprocessed source material (presentations, spreadsheets, working documents) that has not yet been - or may only partially be - reflected in `docs/`. Content here should be reviewed and, where valuable, converted into the appropriate `docs/` page rather than treated as authoritative on its own.

---

## Templates

```text
templates/
```

Reusable page templates (e.g. `ADR.md`) for creating new documentation consistent with the standards below.

---

# Documentation Standards

## Naming

Use:

```text
kebab-case.md
```

Examples:

```text
project-scope.md
payment-data-reconciliation.md
source-system.md
```

## Linking

Prefer relative Markdown links between pages.

Cross-reference related concepts whenever possible.

## One Concept Per Page

Pages should have a clear purpose.

Expand an existing page before creating a duplicate concept page.

## Assumptions and Open Questions

When information is uncertain, explicitly document it using:

```markdown
> Assumption
```

or

```markdown
> Open Question
```

sections.

---

# New Team Members

Start with the [documentation wiki index](docs/index.md), which links to pages in recommended reading order

---

# AI-Assisted Documentation

This repository is designed to work well with GitHub Copilot and other AI-assisted documentation workflows.

AI-generated content should:

- Prefer business language over implementation detail
- Document decision rationale
- Identify assumptions
- Link related concepts
- Avoid creating duplicate pages
- Preserve architectural context

All generated content should be reviewed by project stakeholders before being considered authoritative.

---

# Repository

GitHub:

https://github.com/{{Organization}}/{{Repository}}

This repository is the long-term knowledge base for {{Project Name}}.
