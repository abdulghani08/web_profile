# Project Understanding Lock v1.0

**Status: APPROVED by the project owner**  
**Baseline date:** 2026-10-25  
**Change policy:** Fundamental changes require an explicit proposal and owner approval.

## 1. What is being built?

A professional personal portfolio website for Muhammad Abdul Ghani. It will communicate software development capabilities, present selected work and career evidence, and make it easy for recruiters, employers, and potential clients to evaluate and contact him.

## 2. Why build it?

- Support software-development job applications and professional opportunities.
- Establish a credible, coherent professional identity.
- Present selected projects with enough context to understand the problem, contribution, implementation, and outcome.
- Support relevant freelance, consulting, and collaboration opportunities without diluting the primary developer positioning.

## 3. Professional identity and positioning

**Primary identity:** Software Developer.

**Primary focus:** Full-stack, backend, frontend, and mobile application development.

**Supporting differentiators:** IT systems operations, ERP implementation/integration, databases and APIs, application maintenance, troubleshooting, and technical project leadership.

The website must not imply an unsupported seniority level, proficiency, ownership, performance result, or business outcome.

## 4. Target audiences

Recruiters, hiring managers, engineering leads, software companies, startups, non-technology companies with software teams, international/remote employers, and potential clients or collaborators.

## 5. Goals and language

- Combine career opportunities, personal branding, and relevant client/collaboration opportunities.
- Bilingual Indonesian and English.
- Planned default language: English. Final URL/localization mechanics remain a technical/design decision.
- Technical-first content emphasis: approximately 80% software development and 20% leadership/management.

## 6. Character and design direction

Modern, professional, engineering-oriented, clearly structured, responsive, accessible, and visually distinctive without gimmicks. Avoid generic templates, excessive animation, unsupported visual claims, and decorative elements that obstruct content.

## 7. Content principles

- Use CV-supported facts as the starting point.
- Distinguish personal contribution from team contribution.
- Distinguish verified outcomes from estimates and unverified claims.
- Do not publish confidential code, personal data of platform users, private client information, credentials, or sensitive architecture.
- Do not invent testimonials, metrics, project links, screenshots, technologies, or results.
- Where evidence is missing, mark it as a content gap until the owner confirms it.

## 8. Scope

A bilingual portfolio with a home page, professional profile, experience, selected projects and case studies, skills/technologies, and contact pathway; supporting SEO, accessibility, responsive behavior, testing, deployment, and maintenance documentation.

See `04-scope-and-requirements.md` for detailed scope and non-scope.

## 9. Eight development phases

1. Discovery & Professional Positioning
2. Requirements & Product Planning
3. Technical Architecture & Engineering Foundation
4. UX, UI & Content Design
5. Core Implementation
6. Refinement & Content Integration
7. QA & Release Readiness
8. Deployment, Verification & Maintenance

Phase progression is controlled by explicit quality gates. See `15-development-phases.md` and `16-phase-gate-and-audit-protocol.md`.

## 10. Roles

- **Project Owner — Muhammad Abdul Ghani:** supplies evidence and assets, makes product decisions, approves baseline changes, and accepts phase results.
- **Project Leader — ChatGPT:** maintains scope, requirements, architecture/UX direction, documentation, consistency, audits, quality gates, and decision proposals.
- **Implementation Agent — DeepSeek V4.1 Flash Free via OpenCode CLI:** performs implementation only against approved requirements and phase-specific tasks; audits repository state before acting; reports evidence and limitations.

## 11. Success definition

The project is successful when the site presents a credible and evidence-based developer profile; makes selected projects understandable; works across target screen sizes; meets agreed accessibility, SEO, performance, and security checks; has maintainable code; has no unresolved critical release blockers; and is deployed and verified with maintenance instructions.

## 12. Technical decisions not locked

Framework, rendering strategy, content storage, animation library, hosting provider, domain, analytics, contact form mechanism, and final folder structure are **PENDING DECISION**. Decide during Phases 2–3 based on evidence and constraints.
