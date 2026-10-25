# Scope and Requirements

## In scope

- Bilingual Indonesian and English experience.
- Home/landing page with positioning and clear calls to action.
- About/profile page or section.
- Professional experience.
- Selected project index and individual project/case-study pages or equivalent detail views.
- Skills/technology overview grounded in actual experience.
- Contact pathway and verified professional profile links.
- Responsive layout, accessibility, SEO metadata, social sharing metadata, performance checks, testing, deployment, and maintenance notes.
- Content model that supports both languages without duplicating inconsistent facts.

## Out of scope unless separately approved

- User accounts, authentication, or visitor dashboards.
- Database-backed CMS.
- Complex backend services.
- Public code or architecture disclosures for confidential/client systems.
- Blog/news system at launch unless a validated content-maintenance need exists.
- Paid integrations or analytics that require accounts/consent before owner approval.
- Claims or testimonials that cannot be verified.
- Automated CV parsing or AI chat widget on the portfolio.
- Any claim that the site guarantees hiring or client conversion.

## Functional requirements

- FR-01: Visitors can identify the owner and primary professional positioning from the landing page.
- FR-02: Visitors can browse experience and selected projects.
- FR-03: Each featured project identifies the problem/context, owner contribution, technology actually used, and outcome/evidence where available.
- FR-04: Visitors can switch between Indonesian and English.
- FR-05: Contact links and external profile links work and are verified.
- FR-06: Navigation and language choice remain usable on mobile and desktop.
- FR-07: The site exposes appropriate page titles, descriptions, canonical/localized metadata where supported, and social preview metadata.
- FR-08: Unavailable project evidence is omitted or clearly treated as pending, never fabricated.

## Non-functional requirements

- NFR-01: Responsive across common mobile, tablet, and desktop viewports.
- NFR-02: Keyboard-accessible navigation and visible focus.
- NFR-03: Semantic HTML, meaningful headings, image alternatives, and adequate contrast.
- NFR-04: Minimize unnecessary JavaScript, dependencies, and motion.
- NFR-05: No secrets or private data committed to the repository.
- NFR-06: Production build and defined tests pass before release.
- NFR-07: Maintainable components, content, and documentation.
- NFR-08: Search-engine crawlability and useful metadata.
- NFR-09: No unresolved critical or high-severity release blockers.

## Priority

- **P0:** accurate positioning, core pages, bilingual content, project evidence, navigation, contact, responsive behavior, build/release safety.
- **P1:** refined case studies, social preview polish, subtle motion, optional analytics after approval.
- **P2:** blog, CMS, elaborate animation, extra integrations; only if validated and approved.

## Acceptance principle

Requirements are not considered satisfied merely because an element exists. They must be tested against a written criterion and supported by a reproducible observation or artifact.
