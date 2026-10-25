# Eight Development Phases

Each phase requires an explicit quality-gate result before the next phase begins.

## Phase 1 — Discovery & Professional Positioning

**Goal:** Establish a truthful professional story and approved project baseline.  
**Inputs:** CV, owner answers, project context.  
**Tasks:** Analyze experience and evidence; map competencies; define audiences; refine positioning; inventory candidate projects; identify disclosure/evidence gaps; approve Project Understanding Lock.  
**Outputs:** Approved baseline, positioning, audience definitions, evidence inventory, open-question list.  
**Acceptance:** Owner approves positioning, audience, language, content emphasis, and eight-phase plan; no unresolved contradiction in core identity.  
**Dependency:** None.  
**Definition of Done:** Documents reflect approved decisions and explicitly mark unknowns.

**Current status:** Baseline approved. Additional project evidence gathering remains an ongoing content task.

## Phase 2 — Requirements & Product Planning

**Goal:** Convert the baseline into a testable product specification.  
**Inputs:** Phase 1 baseline and evidence inventory.  
**Tasks:** Prioritize requirements; finalize MVP/non-scope; map user journeys; choose success measures; confirm content/page inventory; define acceptance tests; identify privacy, asset, and contact requirements.  
**Outputs:** Approved requirements, scope, sitemap draft, page specifications, prioritized backlog, acceptance matrix.  
**Acceptance:** Each P0 requirement is testable; owner approves MVP and unresolved product choices are logged.  
**Definition of Done:** No ambiguous P0 requirement blocks architecture/design.

## Phase 3 — Technical Architecture & Engineering Foundation

**Goal:** Choose a suitable, maintainable implementation approach.  
**Inputs:** Approved Phase 2 requirements and repository access.  
**Tasks:** Audit repository and hosting constraints; evaluate stack candidates; decide routing/localization, content model, rendering, styling, testing, deployment, security and dependency policy; define architecture and folder structure.  
**Outputs:** Approved architecture decision records, engineering foundation, setup/verification plan.  
**Acceptance:** Choices are justified against criteria; no unsupported infrastructure; baseline build/test path is defined.  
**Definition of Done:** Owner approves material stack/hosting decisions and the architecture is documented.

## Phase 4 — UX, UI & Content Design

**Goal:** Translate requirements into usable page flows and visual system.  
**Inputs:** Approved scope and architecture constraints.  
**Tasks:** Sitemap refinement; wireframes; content hierarchy; responsive behavior; design tokens/components; language switching; interaction states; accessibility and reduced-motion decisions; content plan for case studies.  
**Outputs:** Approved wireframes/design direction, design system specification, content drafts and asset checklist.  
**Acceptance:** Main journeys are covered; both languages and key viewport states are accounted for; owner approves design direction.  
**Definition of Done:** Implementation can proceed without unresolved major design questions.

## Phase 5 — Core Implementation

**Goal:** Build the agreed functional site skeleton and primary content routes.  
**Inputs:** Approved architecture and design.  
**Tasks:** Repository setup per decision; shared layout/navigation; localization; core pages; project index/details; content model; contact links; metadata foundations; baseline tests.  
**Outputs:** Working implementation, source changes, test/build evidence.  
**Acceptance:** P0 pages/routes work; bilingual navigation works as specified; content is evidence-based; build passes.  
**Definition of Done:** Core functionality is complete and audited; no critical issue remains.

## Phase 6 — Refinement & Content Integration

**Goal:** Improve visual quality, content completeness, and production behavior.  
**Inputs:** Phase 5 implementation and owner-approved assets/content.  
**Tasks:** Refine responsive layouts; integrate verified media; polish copy in both languages; add metadata/social previews; improve loading/performance; motion and interaction refinement; verify external links.  
**Outputs:** Refined implementation, completed content, updated verification evidence.  
**Acceptance:** No known major visual/content inconsistency; media rights checked; important links and language parity verified.  
**Definition of Done:** Candidate release is ready for comprehensive QA.

## Phase 7 — QA & Release Readiness

**Goal:** Independently verify the site against acceptance criteria.  
**Inputs:** Release candidate and test matrix.  
**Tasks:** Functional, responsive, accessibility, SEO, performance, security/dependency, link, language, content, build, and browser checks; triage defects.  
**Outputs:** QA report, defect list, remediation evidence, release recommendation.  
**Acceptance:** No unresolved critical/high release blockers; agreed checks pass; residual issues are documented and accepted by owner.  
**Definition of Done:** Gate explicitly passes or returns for rework.

## Phase 8 — Deployment, Verification & Maintenance

**Goal:** Release safely and verify the real production deployment.  
**Inputs:** Approved release candidate, domain/hosting access, release checklist.  
**Tasks:** Configure hosting/domain/HTTPS and environment as needed; deploy; smoke-test production routes, language switching, links, metadata, and assets; document rollback and maintenance; confirm indexing setup if applicable.  
**Outputs:** Production site, deployment record, smoke-test report, maintenance notes.  
**Acceptance:** Production behaves as expected; HTTPS and routes work; no critical production defect; owner accepts release.  
**Definition of Done:** Deployment and verification are complete, and maintenance responsibilities are documented.
