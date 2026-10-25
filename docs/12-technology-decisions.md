# Technology Decisions

**Status:** No implementation stack is locked. This file records evaluation criteria and required decisions.

## Decision criteria

- Fit for a primarily content-led portfolio
- Bilingual routing and metadata
- SEO and rendering needs
- Build/deployment simplicity
- Accessibility and responsive implementation
- Maintainability by the owner
- Ecosystem stability and security
- Performance and JavaScript payload
- Compatibility with existing repository and hosting constraints
- Agent/tooling reliability

## Candidates to evaluate

- Next.js + TypeScript
- React + Vite + TypeScript
- Astro, potentially with interactive components only where needed

These are candidates, not a final shortlist ranking or decision. The actual repository, deployment target, and content needs must be inspected first.

## Required decisions in Phase 3

- Framework and version policy
- Language routing/localization approach
- Rendering strategy and metadata support
- Styling/design-system approach
- Content source/model
- Whether any backend is genuinely required
- Contact method and spam/privacy strategy
- Testing tools
- Build and deployment platform
- Analytics/consent decision, if any
- Dependency management and lockfile policy

## Decision record format

For each decision record:
- ID and date
- Status (proposed/approved/rejected/superseded)
- Context and constraints
- Options considered
- Decision and rationale
- Consequences and trade-offs
- Validation required
- Owner approval

## Guardrail

Do not add a database, CMS, backend, analytics, animation library, or UI library without a concrete requirement and a documented reason.
