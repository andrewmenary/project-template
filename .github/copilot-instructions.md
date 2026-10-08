# {{Project Name}} Documentation Repository

This repository contains the documentation for {{Project Name}}.

This documentation repository serves as a living knowledge base for information related to the project, especially from an Information Technology perspective. It documents decisions and integrations and provides guidance for developers and IT staff working on the project.

---

## How to Assist
- Generate structured documentation
- Suggest improvements
- Identify missing edge cases
- Help debug and analyze issues

---

## Repository Structure

(Incomplete, maintain as the project evolves)

docs/

  adrs/

  architecture/

  data-model/

  domain/

  integrations/

  migration/

  operations/


---

## Naming

Use kebab-case filenames.

Examples:

- golden-record.md
- duplicate-detection.md
- source-system.md

One concept per page.

Do not create a new page if an existing page should be expanded.

Avoid:

- misc.md
- notes.md
- stuff.md

---

## Documentation Philosophy

Document business concepts before technical implementation.

Prioritize:

1. Why a capability exists
2. Business rules
3. Domain concepts
4. Data ownership
5. System interactions
6. Technical implementation details

Assume the audience consists of:

- Enterprise Architects
- Solution Architects
- System Implementors
- Software Developers
- Product Owners
- Data Stewards

Do not assume readers are familiar with the current implementation.

---

## Writing Style

Use concise professional language.

Prefer:

- Markdown
- Headings
- Lists
- Mermaid diagrams
- Examples

Avoid:

- Marketing language
- Unsubstantiated assumptions
- Excessive implementation detail

Explicitly call out uncertainty using:

> Assumption

or

> Open Question

sections.

---

## Documentation Structure

Prefer organizing documentation into:

- Domain
- Architecture
- Data Model
- Migrations
- Data Mappings
- Integrations
- Processes
- Services
- Decisions (ADR)
- Operations

When creating documentation, suggest appropriate placement.

---

## Domain Terminology

Use the following terminology consistently.

(Fill out as they are defined in the project)

---

## Architecture Guidance

Favor documentation that explains:

- Bounded contexts
- System boundaries
- Integration patterns
- Event flows
- Ownership boundaries
- Trust boundaries

Include context diagrams when helpful.

When describing services:

- Purpose
- Responsibilities
- Dependencies
- Published Events
- Consumed Events
- APIs
- Failure Modes

---

## Architecture Decision Records

When identifying major design decisions, create ADR drafts, follow the `templates\ADR.md` ADR template.

Each ADR should contain:

- Context
- Decision
- Consequences
- Alternatives Considered

Mark inferred decisions as draft proposals.

---

## Repository Wiki Behavior

When generating documentation:

- Create cross-links between related concepts
- Avoid duplicate definitions
- Update existing pages before creating new ones
- Prefer evolving documentation over recreating it

Suggest new wiki pages when new concepts emerge.

---

## Important Principle

The most valuable documentation is not API documentation.

Prioritize documenting:

- Business meaning
- Data ownership
- Stewardship processes
- Architectural decisions
- Operational concerns

over endpoint descriptions and implementation details.

---

## Page Types

### Domain Page

Defines a business concept.

Required sections:

- Definition
- Business Purpose
- Related Concepts
- Examples

### Architecture Page

Required sections:

- Purpose
- Responsibilities
- Dependencies
- Data Flow

### Integration Page

Required sections:

- Producer
- Consumer
- Events
- Contracts
- Error Handling

### ADR

Required sections:

- Context
- Decision
- Consequences
- Alternatives
