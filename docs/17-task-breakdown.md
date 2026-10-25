# Phase-Level Task Breakdown

This is a planning backlog, not permission to implement immediately. Exact tasks should be refined at the start of each phase.

## Phase 1 — Discovery
- [x] Review CV and identify candidate positioning.
- [x] Define target audiences and technical-first emphasis.
- [x] Establish bilingual direction and eight phases.
- [x] Obtain owner approval of Project Understanding Lock v1.0.
- [x] Transfer case-study evidence and public disclosure permissions to Phase 2 under Owner-approved change control A1 (D-017).
- [ ] Review and accept the Phase 1 gate outcome proposed in `27-phase-1-gate-review.md` (fresh Project Leader recommendation, then Owner decision; Phase 1 remains open).

Note: The transfer action is complete, but the evidence task itself is not complete. It remains mandatory Phase 2 work (P2-T08/P2-T11) and the evidence remains unverified. No unverified claims or assets may be published. B1/D-018 defers default language and language behavior to Phase 2. D-020 adopts the phase-relative gate interpretation; D-021–D-025 approve the minor-finding dispositions. These decisions are not Phase 1 gate acceptance and do not start Phase 2.

## Phase 2 — Requirements
Detailed plan: `28-phase-2-execution-plan.md`. All Phase 2 tasks remain not started pending Phase 1 gate acceptance.

- [ ] Confirm case-study evidence and public disclosure permissions (P1-F-02; transferred from Phase 1 by A1/D-017; mandatory P2-T08/P2-T11; evidence remains unverified; update `29-blocker-register.md`).
- [ ] Decide or explicitly defer default language and language behavior (P1-F-03; B1/D-018; P2-T09; no default selected).
- [ ] Confirm MVP and content/page inventory.
- [ ] Prioritize and approve functional/non-functional requirements.
- [ ] Confirm success measures and release constraints.
- [ ] Verify contact details and professional links; no placeholders or unverified links (P1-F-06; D-023; P2-T10; update `29-blocker-register.md`).
- [ ] Create document-status register/headers and distinguish draft, proposed, approved, superseded, and pending (C-12/P1-F-04; D-021/D-022; P2-T01/T12; AC-17).
- [ ] Determine root `README.txt` disposition; no deletion without Owner approval (P1-F-08; D-025; P2-T01/T12).
- [ ] Create acceptance matrix and prioritized backlog.

Note: Hosting, domain, analytics, and privacy decisions are deferred under D-024 to Phase 3/8. No analytics, tracking, contact form, or third-party service may be added without demonstrated need, documented privacy implications, and Owner approval.

## Phase 3 — Architecture
Current repository state: no Git repository or Git executable was found. Establishing version control is a Phase 3 prerequisite and P1-F-05 blocks the Phase 3 gate under D-020 (see `27-phase-1-gate-review.md`, CA-07, and `29-blocker-register.md`).

- [ ] Inspect actual repository and git state.
- [ ] Establish canonical repository, version control, remote backup, and `.gitignore` before implementation (P1-F-05; Phase 3 gate).
- [ ] Verify deployment/domain constraints and owner maintenance preference.
- [ ] Record hosting/domain/analytics/privacy constraints; no third-party service without demonstrated need, documented privacy implications, and Owner approval (P1-F-07; D-024; Phase 3/8).
- [ ] Evaluate stack candidates against documented criteria.
- [ ] Decide localization, rendering, content, styling, test, and deployment approaches.
- [ ] Document architecture, folder structure, dependency/security policy.
- [ ] Owner approves material technical decisions.

## Phase 4 — Design
- [ ] Confirm sitemap and user journeys.
- [ ] Draft wireframes for core pages.
- [ ] Establish visual system and responsive rules.
- [ ] Define navigation, language switch, and interactive states.
- [ ] Prepare content drafts and approved asset inventory.
- [ ] Owner approves design direction.

## Phase 5 — Core implementation
- [ ] Implement approved repository foundation.
- [ ] Build layout, navigation, localization, and core routes.
- [ ] Build project list and detail pattern.
- [ ] Integrate approved profile, experience, and skills content.
- [ ] Add baseline metadata and contact links.
- [ ] Run build and tests; report evidence.

## Phase 6 — Refinement
- [ ] Integrate approved screenshots/media.
- [ ] Refine responsive and interaction behavior.
- [ ] Review both languages.
- [ ] Complete page metadata and social sharing.
- [ ] Reduce unnecessary payloads and dependencies.
- [ ] Verify all external/internal links.

## Phase 7 — QA
- [ ] Run functional and route checks.
- [ ] Test responsive viewports and keyboard navigation.
- [ ] Review contrast, semantics, image alternatives, reduced motion.
- [ ] Review SEO, performance, security, dependencies, and content claims.
- [ ] Triage and fix blockers; produce QA report.
- [ ] Owner accepts release readiness.

## Phase 8 — Release
- [ ] Confirm domain, hosting, DNS, HTTPS, analytics/privacy, and required credentials via secure channel (P1-F-07; D-024; no unauthorized third-party service).
- [ ] Deploy approved release.
- [ ] Run production smoke tests.
- [ ] Verify redirects, language routing, metadata, and assets.
- [ ] Document rollback, maintenance, and content-update workflow.
- [ ] Owner accepts production release.
