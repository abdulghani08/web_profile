# Phase 2 — Requirements & Product Planning Execution Plan

**Project:** Muhammad Abdul Ghani Professional Portfolio Website  
**Phase:** Phase 2 — Requirements & Product Planning  
**Plan ID:** P2-PLAN-001  
**Status:** **PROPOSED / AWAITING FRESH PROJECT LEADER REVIEW AND OWNER AUTHORIZATION**  
**Prepared by:** Implementation Agent — DeepSeek V4.1 Flash Free via OpenCode CLI  
**Prepared for:** Project Leader review; Project Owner decisions  
**Date:** 2026-10-25  
**Baseline:** Project Understanding Lock v1.0, approved 2026-10-25  
**Phase definition:** `15-development-phases.md` Phase 2  
**Gate protocol:** `16-phase-gate-and-audit-protocol.md`  
**Prerequisite:** Phase 1 gate outcome in `27-phase-1-gate-review.md` (D-019 remains proposed PASS WITH MINOR FIXES) must be accepted by the Project Owner after a fresh Project Leader review. D-020–D-025 are approved policy/dispositions, not gate acceptance.  
**Task tracking:** `17-task-breakdown.md`

> **Plan status:** This is a planning document. It does not authorize implementation, framework setup, package installation, Git initialization, deployment, or content publication. D-020–D-025 are approved policy/dispositions, but they are not Phase 1 gate acceptance and do not authorize Phase 2 execution. Phase 2 remains **NOT STARTED** until the Phase 1 gate is accepted after a fresh Project Leader review and this plan is authorized.

---

## 1. Phase 2 Objective and Boundaries

### 1.1 Objective

Convert the approved Phase 1 baseline into a testable product specification that can be used by Phase 3 architecture and Phase 4 design without unresolved P0 ambiguity.

The Phase 2 objective, restated from `15-development-phases.md`, is to:

- Prioritize requirements.
- Finalize MVP and non-scope.
- Map user journeys.
- Choose success measures.
- Confirm content and page inventory.
- Define acceptance tests.
- Identify privacy, asset, and contact requirements.

### 1.2 In scope

| Area | Phase 2 responsibility |
|---|---|
| Requirements | Reconcile and finalize functional and nonfunctional requirements |
| MVP and scope | Define MVP, non-scope, priorities, and release constraints |
| Page and feature inventory | Confirm pages, purposes, navigation, and feature scope |
| User journeys | Map journeys for the approved audience and working personas, with expected outcomes |
| Acceptance | Define testable acceptance criteria and requirements traceability |
| Content readiness | Complete the A1/D-017 transferred evidence and publication-permission workstream; P1-F-02 remains HIGH; mandatory P2-T08/P2-T11; no publication until verified |
| Bilingual behavior | B1/D-018: bilingual Indonesian-English remains approved; define language behavior and decide default language in P2-T09; P1-F-03 remains open |
| Contact | Define contact pathway and professional-link requirements (D-023; P2-T10) |
| Privacy and permissions | Define privacy, consent, and publication-permission requirements (D-024; P2-T11) |
| Decisions | Resolve or explicitly defer open decisions and update the decision log, document-status register, and blocker register (D-021–D-025; P2-T12) |
| Gate | Prepare and audit the Phase 2 gate record; maintain `29-blocker-register.md` (D-020; P2-T13) |

### 1.3 Out of scope for Phase 2

Phase 2 does **not**:

- Select the final framework, stack, rendering strategy, hosting, domain, or deployment platform. Framework, stack, and rendering remain Phase 3 decisions; hosting, domain, and deployment remain Phase 3/8 decisions under D-024.
- Finalize architecture, folder structure, component boundaries, content-storage format, image-optimization strategy, or testing tools. These remain Phase 3 decisions.
- Produce final wireframes, visual design, design tokens, colors, fonts, logo, imagery, or breakpoints. These remain Phase 4 decisions.
- Write application code, create package manifests, install dependencies, scaffold a framework, initialize Git, create CI/CD, or deploy.
- Publish content, claim publication permission, or create project screenshots/media.
- Make legal determinations. Privacy and publication requirements may be documented, but legal advice is not provided.
- Start Phase 3 or any implementation phase.

### 1.4 Phase boundary rule

If a Phase 2 discussion becomes a technology, architecture, visual-design, implementation, hosting, domain, analytics, or privacy decision, it must be recorded as a Phase 3, Phase 4, or Phase 8 decision as appropriate rather than resolved inside Phase 2. Phase 2 may define the requirement or constraint that the later phase must satisfy.

---

## 2. Inputs Inherited from Phase 1

### 2.1 Approved baseline inputs

| Input | Source | Use in Phase 2 |
|---|---|---|
| Project Understanding Lock v1.0 | `01-project-understanding-lock.md`; D-001 | Authoritative baseline; do not change without Owner approval |
| Primary identity and focus | D-002, D-003, D-004; `01` §3 | Requirements and content scope |
| Target audience | D-005; `01` §4; `05-audience-and-personas.md` | User journeys and page priorities |
| Bilingual requirement | D-006; `01` §5; `03-positioning-and-brand-strategy.md` | Language behavior and content requirements |
| Default-language deferral | D-018; B1 | Bilingual remains; P2-T09 decides default language and behavior; no default selected |
| Evidence-task transfer | D-017; A1 | P2-T08/P2-T11 mandatory; evidence remains unverified; no publication |
| Content emphasis | D-007; `01` §5; `03` | Content hierarchy and page emphasis |
| Eight-phase process and gates | D-008; `01` §9; `15-development-phases.md`; `16-phase-gate-and-audit-protocol.md` | Phase 2 process and gate |
| Phase-relative gate policy | D-020; `16`; `29-blocker-register.md` | Gate scoping; later-phase blockers remain visible |
| Approved document-status dispositions | D-021/D-022 | Phase 2 status register and P1-F-04 remediation |
| Approved contact disposition | D-023 | Phase 2 contact/link verification |
| Approved hosting/domain/analytics/privacy deferral | D-024 | Phase 3/8 constraints; no unauthorized service |
| Approved root README disposition path | D-025 | P2-T01/T12; no deletion without Owner approval |
| Documentation source of truth | D-009 | Documentation updates and decision records |

### 2.2 Planning inputs that remain proposed or unverified

| Input | Source | Status | Phase 2 treatment |
|---|---|---|---|
| Positioning headline and CTAs | `03-positioning-and-brand-strategy.md` | Proposed | Review; do not treat as approved |
| Sitemap and routing proposal | `08-information-architecture-and-sitemap.md` | Proposed | Confirm page inventory; routing remains Phase 3 |
| Page content/behavior requirements | `09-page-specifications.md` | Requirements draft; UI deferred to Phase 4 | Reconcile and approve content/behavior requirements |
| UX principles and journeys | `10-ux-strategy.md` | Working principles | Use as input; confirm journeys |
| UI direction | `11-ui-design-direction.md` | Direction stated; exact design pending | Do not finalize visual design |
| Stack candidates | `12-technology-decisions.md` | Candidates only | Do not select; record constraints for Phase 3 |
| Architecture principles | `13-architecture-principles.md` | Principles; decisions pending | Use as constraints; do not decide architecture |
| Content entities | `14-content-model-and-asset-policy.md` | Proposed | Use as input; final format is Phase 3 |
| SEO requirements | `18-seo-and-metadata.md` | Requirements; implementation pending | Define requirements; implementation Phase 3/5 |
| Accessibility/responsive requirements | `19-accessibility-and-responsive-requirements.md` | Baseline requirements | Define measurable acceptance criteria |
| Performance/security requirements | `20-performance-and-security.md` | Principles; thresholds proposed | Define requirements; final thresholds Phase 2/3 |
| Engineering standards | `21-engineering-standards.md` | Baseline standards | Use as constraints |
| Testing/acceptance requirements | `22-testing-and-acceptance.md` | Baseline requirements | Build acceptance matrix |
| Deployment/maintenance requirements | `23-deployment-and-maintenance.md` | Decisions pending | Record constraints; decide Phase 3/8 |
| Evidence inventory and gaps | `06-project-evidence-inventory.md`; `26-open-questions-and-evidence-gaps.md` | CV-derived / open | Content-readiness workstream |
| Phase 1 gate record | `27-phase-1-gate-review.md`; D-019 | Proposed PASS WITH MINOR FIXES; not accepted | Prerequisite to Phase 2 start; fresh Project Leader review and Owner acceptance required |
| Blocker register | `29-blocker-register.md`; D-020 | Active | Must remain current; later-phase findings remain visible |

### 2.3 Owner inputs still required

The Phase 2 plan depends on Owner-provided information listed in §9. These inputs are not assumed to exist.

---

## 3. Approved, Proposed, Unverified, and Owner-Input Classification

This classification must remain visible throughout Phase 2. A proposal is not an approval; a CV-derived claim is not a verified fact.

### 3.1 Already approved baseline decisions

| Decision | Status | Source |
|---|---|---|
| Project is a professional portfolio for Muhammad Abdul Ghani | APPROVED | D-001 |
| Primary identity is Software Developer | APPROVED | D-002 |
| Primary focus is full-stack, backend, frontend, and mobile development | APPROVED | D-003 |
| IT systems, ERP/integration, operations, and project leadership are supporting differentiators | APPROVED | D-004 |
| Target audience includes recruiters, hiring managers, engineering leads, employers, and potential clients | APPROVED | D-005 |
| Bilingual Indonesian and English | APPROVED | D-006 |
| Approximate content emphasis: 80% development / 20% leadership-management | APPROVED | D-007 |
| Eight-phase process with quality gates | APPROVED | D-008 |
| Markdown documentation under `/docs` | APPROVED | D-009 |
| Case-study evidence/permission task transferred to Phase 2 | APPROVED | D-017; A1 |
| Bilingual direction remains approved; default language deferred to Phase 2 | APPROVED | D-018; B1 |
| Gate blocker scope is phase-relative; later-phase blockers remain visible | APPROVED | D-020 |
| C-12 document-status register in Phase 2 | APPROVED | D-021 |
| P1-F-04 document-status remediation; finding remains open until remediated | APPROVED | D-022 |
| P1-F-06 contact and professional-link verification in Phase 2 | APPROVED | D-023 |
| P1-F-07 hosting/domain/analytics/privacy deferral to Phase 3/8 | APPROVED | D-024 |
| P1-F-08 root README disposition path; no deletion now | APPROVED | D-025 |

### 3.2 Proposed decisions awaiting approval

| Proposal | Current status | Source | Phase 2 treatment |
|---|---|---|---|
| Positioning headline wording and CTAs | Proposed | `03` | Review; Owner approval required before publication |
| Sitemap and route examples | Proposed | `08` | Confirm page inventory; routing Phase 3 |
| Page specifications | Content/behavior requirements; UI deferred | `09` | Reconcile and approve requirements |
| UI visual direction | Direction stated; exact design pending | `11` | Do not finalize; Phase 4 |
| Stack candidates | Not approved | `12` | Do not select; Phase 3 |
| Architecture principles | Principles; decisions pending | `13` | Use as constraints; Phase 3 |
| Content entities | Proposed | `14` | Use as input; final format Phase 3 |
| SEO implementation details | Pending | `18` | Requirements only; implementation Phase 3/5 |
| Performance thresholds | Proposed | `20` | Confirm or defer with method |
| Deployment/hosting/domain | Pending | `23`; D-024 | Phase 3/8 |
| Phase 1 gate outcome | Proposed PASS WITH MINOR FIXES; not accepted | `27`; D-019 | Fresh Project Leader review and Owner acceptance required; D-020–D-025 do not accept the gate |
| Phase 2 execution plan | Proposed | This document | Project Leader review and Owner authorization; Phase 2 not started |

### 3.3 Facts requiring verification

These must not be published until the Owner confirms them and the Project Leader records the evidence disposition.

| Fact area | Examples | Source | Verification needed |
|---|---|---|---|
| Roles and dates | MyCendekia role/dates; Odoo dates; PT Thinkdata dates | `06` | Owner confirmation; CV or other evidence |
| Metrics | 3,300+ registered users; 3,219 students + 87 supervisors; ~2,000 daily active users; 100+ Odoo users; seven-person team; 11 projects; 21 clients | `03`, `06` | Definitions, currency, permission, context |
| Personal contribution | Which features/modules the Owner personally built, maintained, or led | `06`, `26` | Owner-specific examples |
| Technologies | Stack by project/subsystem | `06`, `26` | Verified technology list |
| Project status | Production, prototype, academic, personal, internal, or unknown | `06`, `14`, `26` | Owner confirmation |
| Links and media | Public URLs, app listings, demos, screenshots, diagrams | `06`, `26` | Verification and permission |
| Client/employer names | Organization names, logos, client marks | `26` | Written publication permission or omission |
| Contact/profile links | Email, LinkedIn, GitHub, other professional profiles | `26`; D-023 | Phase 2 P2-T10 verification; no placeholders; Owner approval before publication |
| Indonesian content | Copy, terminology, reviewer | `26` | Native/natural review; not machine-only |
| Test/release environment | Browsers, devices, hosting, domain, analytics | `26`, `23`; D-024 | Owner confirmation; hosting/domain/analytics/privacy decisions deferred to Phase 3/8 |

### 3.4 Questions requiring Owner input

| ID | Question | Why it matters | Phase 2 task |
|---|---|---|---|
| OQ-01 | What default language and language behavior will Phase 2 decide or explicitly defer? | B1/D-018 defers the decision; language switch, routing, SEO, content workflow | P2-T09 |
| OQ-02 | Who will draft and review Indonesian copy? | Bilingual parity and quality | P2-T09 |
| OQ-03 | Which projects should be featured, and what evidence/permissions exist? | Content credibility and case-study scope; A1/D-017 transferred this work to Phase 2 | P2-T08, P2-T11 |
| OQ-04 | May the Owner publish the named metrics, client names, logos, and screenshots? | Confidentiality and truthfulness; no publication without evidence and permission | P2-T08, P2-T11 |
| OQ-05 | What contact method should be public? | Contact page and privacy requirements; D-023 verification | P2-T10 |
| OQ-06 | Which professional links are current and approved? | Contact/profile requirements; D-023 verification | P2-T10 |
| OQ-07 | Is a downloadable CV wanted? | Page/content scope | P2-T03 |
| OQ-08 | Should location be shown, and at what granularity? | Profile content and privacy | P2-T03, P2-T11 |
| OQ-09 | Are there brand assets, preferred colors, fonts, or imagery? | Phase 4 input; content planning | P2-T03 |
| OQ-10 | Is analytics required, and what privacy/consent rules apply? | Privacy and Phase 3/8 decisions; D-024 defers service decisions | P2-T11 |
| OQ-11 | Is a contact form necessary, or are direct links sufficient? | Contact and security requirements; no form implementation without Owner approval | P2-T10 |
| OQ-12 | Who maintains content and dependencies? | Maintainability and release planning | P2-T12 |
| OQ-13 | What browsers/devices are available for testing? | Acceptance and QA planning | P2-T07 |
| OQ-14 | Is a domain already owned, and what hosting access exists? | Phase 3/8 constraints; D-024 deferral | P2-T12 (record/defer to Phase 3/8) |

---

## 4. Workstreams and Logical Sequence

### 4.1 Workstream overview

| Workstream | Purpose | Tasks |
|---|---|---|
| WS-1 — Requirements baseline and scope | Reconcile inputs, define MVP, confirm page/feature scope | P2-T01, P2-T02, P2-T03 |
| WS-2 — Specification and acceptance | Finalize FR/NFR, journeys, acceptance, and traceability | P2-T04, P2-T05, P2-T06, P2-T07 |
| WS-3 — Content, evidence, language, contact, privacy readiness | Complete the A1/D-017 evidence workstream; establish bilingual, contact, and permission requirements | P2-T08, P2-T09, P2-T10, P2-T11 |
| WS-4 — Decisions and gate | Consolidate decisions, update logs, audit, and obtain Owner approval | P2-T12, P2-T13 |

### 4.2 Sequence

```text
Phase 1 gate accepted
        │
        ▼
P2-T01 Requirements review and reconciliation
        │
        ▼
P2-T02 MVP definition and prioritization
        │
        ▼
P2-T03 Page and feature scope
        │
        ├───────────────┬───────────────┐
        ▼               ▼               ▼
P2-T04 Functional   P2-T05 Nonfunctional   P2-T06 User journeys
requirements        requirements           and outcomes
        └───────────────┴───────────────┘
                        │
                        ▼
P2-T07 Acceptance criteria and traceability
                        │
        ┌───────────────┼───────────────┬───────────────┐
        ▼               ▼               ▼               ▼
P2-T08 Content/     P2-T09 Bilingual   P2-T10 Contact   P2-T11 Privacy/
evidence readiness  language behavior  requirements     publication permissions
        └───────────────┴───────────────┴───────────────┘
                        │
                        ▼
P2-T12 Open decisions and decision-log updates
                        │
                        ▼
P2-T13 Phase 2 final audit and Owner approval
```

### 4.3 Status vocabulary

| Status | Meaning |
|---|---|
| Not started | No work has begun |
| In progress | Work is underway |
| Blocked | Work cannot proceed without a dependency or decision |
| Complete | Output exists and has been reviewed against its acceptance criteria |
| Deferred | Explicitly postponed with Owner approval and a recorded destination phase |

All Phase 2 tasks are currently **Not started**. No task is marked complete by this plan. D-020–D-025 are approved policy and dispositions; they do not start Phase 2 or authorize execution.

---

## 5. Phase 2 Work Breakdown

### P2-T01 — Requirements review and reconciliation

- **Task ID:** P2-T01
- **Objective:** Reconcile the Phase 1 documents, identify conflicts, duplicates, ambiguities, and missing requirements, classify every requirement as approved, proposed, deferred, or requiring Owner input, and establish the document-status register required by C-12/P1-F-04.
- **Inputs:** `01`, `02`, `03`, `04`, `05`, `06`, `07`, `08`, `09`, `10`, `11`, `12`, `13`, `14`, `18`–`23`, `25`, `26`, `27`, `29`.
- **Expected output:** Requirements reconciliation memo or an updated `04-scope-and-requirements.md` with status notes and an issue log; document-status register or equivalent headers; root `README.txt` disposition note.
- **Acceptance criteria:** Every requirement in `04` has a status; every conflict or duplicate is logged with a disposition; no approved baseline decision is silently changed; unresolved items are assigned to a Phase 2 task or a later phase; every planning document has an explicit status or documented exception; C-12/P1-F-04 evidence is recorded (AC-17); D-019 is not represented as accepted; root `README.txt` disposition is recorded without deletion.
- **Dependencies:** Phase 1 gate acceptance (CA-01); D-021/D-022/D-025; Project Leader review.
- **Status:** Not started.

### P2-T02 — MVP definition and prioritization

- **Task ID:** P2-T02
- **Objective:** Define the MVP, non-scope, P0/P1/P2 priorities, success measures, and release constraints.
- **Inputs:** `02`, `04`, `15`, `16`, `22`, `26`, `27`.
- **Expected output:** MVP/non-scope statement, prioritized backlog, and approved success measures.
- **Acceptance criteria:** The Owner approves the MVP and non-scope; every P0 requirement has a rationale and is testable; no unapproved scope is treated as committed; success measures are documented and measurable where practical.
- **Dependencies:** P2-T01; Owner decisions on MVP and scope.
- **Status:** Not started.

### P2-T03 — Page and feature scope

- **Task ID:** P2-T03
- **Objective:** Confirm the page and feature inventory, page purposes, navigation, 404 behavior, and conditional privacy-notice requirement.
- **Inputs:** `04`, `05`, `08`, `09`, `10`, `18`, `26`.
- **Expected output:** Approved page/feature inventory; sitemap draft status; page-level scope notes; list of pages deferred or excluded.
- **Acceptance criteria:** Every page has a purpose, audience, required content, and evidence requirement; no orphan pages; primary navigation, contact route, language switch, and 404 behavior are covered; sitemap is marked draft or approved; conditional pages are explicitly conditional.
- **Dependencies:** P2-T02; Owner input on contact and privacy.
- **Status:** Not started.

### P2-T04 — Functional requirements

- **Task ID:** P2-T04
- **Objective:** Finalize functional requirements FR-01–FR-08 and any additional approved functional requirements, including behavior, inputs, outputs, and edge cases.
- **Inputs:** `04`, `08`, `09`, `10`, `18`, `19`, `22`.
- **Expected output:** Functional requirements specification with unique IDs, descriptions, priorities, and testable acceptance statements.
- **Acceptance criteria:** Each functional requirement has an ID, description, priority, acceptance criterion, and traceability to a page or journey; navigation, language switch, project routes, contact links, 404 behavior, and metadata are covered; unavailable evidence is handled as omission or pending, never fabrication.
- **Dependencies:** P2-T02, P2-T03.
- **Status:** Not started.

### P2-T05 — Nonfunctional requirements

- **Task ID:** P2-T05
- **Objective:** Finalize nonfunctional requirements for responsive behavior, accessibility, SEO, performance, security, privacy, maintainability, and release quality.
- **Inputs:** `04`, `18`, `19`, `20`, `21`, `22`, `23`.
- **Expected output:** Nonfunctional requirements specification with measurable criteria, measurement methods, and explicit deferrals where Phase 3 values are required.
- **Acceptance criteria:** Each nonfunctional requirement has a measurable criterion or a documented deferral; WCAG 2.2 AA-informed intent is recorded without claiming conformance; performance thresholds are set or assigned to Phase 3 with a measurement method; security/privacy rules are explicit; no requirement depends on an unapproved technology.
- **Dependencies:** P2-T01, P2-T02, P2-T03.
- **Status:** Not started.

### P2-T06 — User journeys and expected outcomes

- **Task ID:** P2-T06
- **Objective:** Map the journeys for Personas A–D, including entry points, steps, expected outcomes, language-switch behavior, and failure/edge cases.
- **Inputs:** `05`, `08`, `09`, `10`, `04`.
- **Expected output:** Journey maps and outcome statements, with traceability to pages and requirements.
- **Acceptance criteria:** Each persona has at least one primary journey; each journey has a success outcome and required pages/CTAs; the language switch preserves page context where a translation exists; no journey depends on unverified content; edge cases and failure paths are documented.
- **Dependencies:** P2-T03, P2-T04.
- **Status:** Not started.

### P2-T07 — Acceptance criteria and requirements traceability

- **Task ID:** P2-T07
- **Objective:** Create the acceptance matrix and traceability links among requirements, pages, journeys, and verification methods.
- **Inputs:** P2-T04, P2-T05, P2-T06; `22-testing-and-acceptance.md`; `16-phase-gate-and-audit-protocol.md`.
- **Expected output:** Acceptance matrix and requirements traceability matrix; testability review; list of untestable or ambiguous requirements.
- **Acceptance criteria:** Every P0 requirement has at least one objective acceptance criterion and a verification method; every journey maps to requirements; every page maps to requirements; no orphan requirements; testability gaps are logged with a disposition; evidence format follows `22`.
- **Dependencies:** P2-T04, P2-T05, P2-T06.
- **Status:** Not started.

### P2-T08 — Content and case-study evidence readiness (A1/D-017 transferred task)

- **Task ID:** P2-T08
- **Objective:** Complete the evidence and publication-permission work transferred from Phase 1 by A1/D-017. Assess evidence for candidate projects, select featured projects or defer them, define content gaps, and establish publication-permission requirements. This work is mandatory before the Phase 2 gate.
- **Inputs:** `03`, `06`, `07`, `09`, `14`, `25` (D-017), `26`, `27`, `29`.
- **Expected output:** Content readiness register with required fields: project/claim; role; dates; personal contribution; technologies; project status; outcome; metrics and definitions; public links; screenshots/assets; client/employer identification; permission status; evidence source; and disposition (publish/anonymize/omit/defer). Also a featured-project shortlist, case-study content plan, permission checklist, and updated `29-blocker-register.md` status for P1-F-02.
- **Acceptance criteria:** Every candidate or featured project and every public claim has an evidence status and a permission status; no unverified metric or claim is treated as publishable; no publication occurs without Owner approval; unsupported projects or claims are omitted, anonymized where appropriate, or explicitly deferred until the Owner approves a supported alternative; the transferred task is complete or explicitly dispositioned by the Owner before the Phase 2 gate; evidence remains unverified until confirmed; no confidential or personal data is included; the blocker register records the evidence status and gate condition.
- **Dependencies:** P2-T02, P2-T03; A1/D-017; D-020; Owner evidence and permissions.
- **Status:** Not started — Owner input required; transferred from Phase 1, not complete.
- **Gate dependency:** P2-T13 cannot pass without this task’s completion or an explicitly Owner-approved disposition. Content publication is blocked until then.

### P2-T09 — Bilingual content and language behavior (B1/D-018)

- **Task ID:** P2-T09
- **Objective:** Implement B1/D-018: bilingual Indonesian-English remains approved; decide the default language and language behavior in Phase 2; plan Indonesian copy and review.
- **Inputs:** `01`, `03`, `07`, `08`, `18`, `25` (D-018), `26`, `29`.
- **Expected output:** Language behavior requirements; bilingual content plan; default-language decision record; Indonesian review plan.
- **Acceptance criteria:** The bilingual requirement remains approved; the default language and language behavior are decided in Phase 2 or explicitly deferred with impact; no default is selected without an Owner decision; every page has a language-variant requirement; the language switch preserves context where a translation exists; fallback, redirect, canonical, and hreflang requirements are documented for Phase 3; Indonesian copy and reviewer are identified.
- **Dependencies:** P2-T03; B1/D-018; Owner input on default language and Indonesian copy.
- **Status:** Not started.

### P2-T10 — Contact and professional-link requirements

- **Task ID:** P2-T10
- **Objective:** Define the contact pathway, decide direct links versus a contact form (or defer with criteria), and verify professional profile links under D-023.
- **Inputs:** `04` FR-05; `09`; `12`; `13`; `20`; `26`; D-023; `29`.
- **Expected output:** Contact requirements; verified professional-link inventory; contact-form decision record if applicable; updated `29-blocker-register.md` status for P1-F-06.
- **Acceptance criteria:** At least one verified contact method is identified; all professional links are verified or omitted; contact content is not marked ready until Owner verification; if a form is proposed, delivery, privacy, spam handling, security, and error handling requirements are documented; no placeholder links or exposed personal data; the blocker register records the verification status.
- **Dependencies:** P2-T03; Owner input on contact method and links; D-023.
- **Status:** Not started.

### P2-T11 — Privacy and publication permissions

- **Task ID:** P2-T11
- **Objective:** Define privacy, consent, and publication-permission requirements for project names, client names/logos, screenshots, metrics, testimonials, and any collection or analytics. D-024 defers hosting/domain/analytics/privacy service decisions to Phase 3/8; this task still defines the requirements those decisions must satisfy.
- **Inputs:** `01`, `06`, `14`, `20`, `25` (D-017, D-024), `26`, `29`.
- **Expected output:** Privacy requirements; publication-permission register; redaction checklist; conditional privacy-notice decision; updated `29-blocker-register.md` permission status for P1-F-02.
- **Acceptance criteria:** Every public claim or asset has a permission status; the privacy-notice requirement is decided or explicitly deferred; no sensitive data is approved for publication; no client/employer claim is made without permission; no publication occurs until P2-T08/P2-T11 are complete and the Owner approves the supported content; unsupported claims are omitted, anonymized, or deferred until a supported alternative is approved; analytics/consent requirements are recorded if applicable; no third-party service is selected without documented need, privacy implications, and Owner approval.
- **Dependencies:** P2-T08; A1/D-017; Owner input; privacy/legal constraints.
- **Status:** Not started.
- **Gate dependency:** P2-T13 cannot pass without the permission register and evidence disposition.

### P2-T12 — Open decisions and decision-log updates

- **Task ID:** P2-T12
- **Objective:** Consolidate D-010–D-025 and new Phase 2 decisions, classify them as resolved, deferred, or rejected, and update the decision log, document-status register, blocker register, and open-question list.
- **Inputs:** `25`, `26`, `29`, P2-T01–P2-T11.
- **Expected output:** Updated `25-decision-log.md`; document-status register; updated `29-blocker-register.md`; open-question disposition register; change-control notes for any baseline-affecting proposal.
- **Acceptance criteria:** Every Phase 2 decision has an ID, status, rationale, Owner approval where required, and impact; no pending decision is silently treated as approved; deferred decisions have a destination phase, owner, evidence, acceptance condition, and gate; `25`, `26`, and `29` are consistent; the document-status register is reviewed and C-12/P1-F-04 evidence is recorded (AC-17).
- **Dependencies:** P2-T01–P2-T11; Project Leader review.
- **Status:** Not started.

### P2-T13 — Phase 2 final audit and Owner approval

- **Task ID:** P2-T13
- **Objective:** Audit all Phase 2 deliverables against the Phase 2 gate criteria, produce the gate record, recommend an outcome, and obtain Owner acceptance.
- **Inputs:** All Phase 2 outputs; `16`; `22`; `27`; `29`.
- **Expected output:** Phase 2 gate review record using `PHASE RESULT → AUDIT → ISSUES → DECISION → NEXT PHASE`; audit findings; updated blocker register; Owner acceptance.
- **Acceptance criteria:** All Phase 2 gate criteria are met or explicitly dispositioned; the A1/D-017 evidence and permission workstream status is reviewed; no unverified public claim is approved; no unresolved critical/high blocker applicable to the Phase 2 gate remains; later-phase findings remain visible in `29-blocker-register.md`; the Project Leader recommends an outcome; the Owner accepts it; Phase 2 is marked closed only after acceptance; no implementation artifact is created.
- **Dependencies:** P2-T12; A1/D-017 evidence/permission review; D-020; Project Leader review.
- **Status:** Not started.

---

## 6. Deliverables by Workstream

| Workstream | Deliverables | Review owner |
|---|---|---|
| WS-1 — Requirements baseline and scope | Requirements reconciliation memo; MVP/non-scope statement; prioritized backlog; page/feature inventory; sitemap draft status; document-status register | Project Leader; Project Owner |
| WS-2 — Specification and acceptance | Functional requirements specification; nonfunctional requirements specification; journey maps; acceptance matrix; traceability matrix | Project Leader; Project Owner |
| WS-3 — Content, evidence, language, contact, privacy readiness | Content readiness register; evidence/permission gate status; featured-project shortlist; bilingual content plan; language behavior requirements; contact requirements; verified link inventory; privacy requirements; publication-permission register | Project Leader; Project Owner |
| WS-4 — Decisions and gate | Updated decision log; document-status register review; open-question disposition register; Phase 2 gate review record; Owner acceptance | Project Leader; Project Owner |

Deliverables are planning artifacts. They do not authorize Phase 3, Phase 4, implementation, or publication.

---

## 7. Dependencies and Decision Points

### 7.1 Decision points

| ID | Decision point | Decision owner | When | Impact if unresolved |
|---|---|---|---|---|
| DP-01 | Accept the Phase 1 gate outcome (D-019 remains proposed PASS WITH MINOR FIXES) after fresh Project Leader review | Project Owner | Before Phase 2 start | Phase 2 cannot start; D-020–D-025 are not gate acceptance |
| DP-02 | Approve MVP and non-scope | Project Owner | P2-T02 | Requirements and page scope cannot be finalized |
| DP-03 | Complete A1/D-017 evidence workstream; confirm featured projects, evidence, and permissions | Project Owner | P2-T08/P2-T11 | Content readiness and case-study scope blocked; Phase 2 gate cannot pass |
| DP-04 | Decide or explicitly defer default language; confirm Indonesian copy/reviewer under B1/D-018 | Project Owner | P2-T09 | Language behavior and Phase 3 routing blocked; no default selected |
| DP-05 | Confirm contact method and professional links under D-023 | Project Owner | P2-T10 | Contact requirements blocked |
| DP-06 | Confirm privacy/analytics/publication constraints under D-024 | Project Owner | P2-T11 | Privacy and permission requirements blocked |
| DP-07 | Approve Phase 2 gate outcome | Project Owner | P2-T13 | Phase 3 cannot start |
| DP-08 | Select stack, routing, and architecture; choose hosting/domain under D-024 | Phase 3/8 process | Phase 3/8 | Not a Phase 2 decision; must not be decided early |

### 7.2 Dependency rules

- P2-T01 depends on Phase 1 gate acceptance.
- P2-T02 depends on P2-T01.
- P2-T03 depends on P2-T02.
- P2-T04, P2-T05, and P2-T06 may run in parallel after P2-T03.
- P2-T07 depends on P2-T04, P2-T05, and P2-T06.
- P2-T08, P2-T09, P2-T10, and P2-T11 may run in parallel after P2-T02/P2-T03, subject to Owner input.
- P2-T08/P2-T11 are mandatory under A1/D-017; P2-T13 cannot pass without their completion or an explicitly Owner-approved disposition.
- P2-T09 must decide the default language under B1/D-018; no default is selected in Phase 1.
- D-020 requires `29-blocker-register.md` to remain current at every gate; later-phase findings do not block Phase 2 unless assigned to the Phase 2 gate.
- P2-T12 depends on P2-T01–P2-T11.
- P2-T13 depends on P2-T12, D-020, and the A1/D-017 evidence/permission review.
- Phase 3 depends on the Phase 2 gate being accepted; P1-F-05 remains a Phase 3 gate blocker.

### 7.3 Phase 2 vs Phase 3/8 decision boundary

| Topic | Phase 2 responsibility | Phase 3/8 responsibility |
|---|---|---|
| Language | B1/D-018: decide default language; define bilingual behavior and content requirements | Choose routing/localization implementation; canonical/hreflang mechanics |
| Contact | Decide direct links vs form; define requirements | Choose delivery mechanism, security implementation, and hosting configuration |
| Content | Complete A1/D-017 evidence readiness; define content model requirements | Choose content storage format and implementation |
| Performance | Set requirements or defer with method | Choose measurement tooling and architecture that supports thresholds |
| SEO | Define metadata/SEO requirements | Choose rendering/metadata implementation |
| Testing | Define acceptance criteria and testability | Choose testing tools and automation approach |
| Hosting/domain | Record constraints | Choose hosting, domain, DNS, CI/CD, and deployment approach; Phase 8 executes release configuration |

---

## 8. Phase 2 Acceptance Criteria

These criteria are designed to be objectively checkable at the Phase 2 gate.

| ID | Acceptance criterion | Evidence required |
|---|---|---|
| AC-01 | Phase 1 gate outcome is accepted by the Owner | Signed/recorded acceptance in `27` or an amended gate record |
| AC-02 | Requirements reconciliation is complete | Reconciliation memo or updated `04` with status for every requirement |
| AC-03 | MVP and non-scope are approved | Owner-approved MVP/non-scope statement |
| AC-04 | Page and feature inventory is approved | Inventory with page purpose, audience, content, and evidence requirements |
| AC-05 | Functional requirements are complete and testable | FR specification with IDs, priorities, and acceptance statements |
| AC-06 | Nonfunctional requirements are complete and measurable or explicitly deferred | NFR specification with thresholds/methods or Phase 3 deferrals |
| AC-07 | User journeys for Personas A–D are complete | Journey maps with outcomes and page/requirement traceability |
| AC-08 | Acceptance matrix and traceability are complete | Matrix covering every P0 requirement and every journey |
| AC-09 | A1/D-017 evidence task is complete or has an explicitly Owner-approved disposition; featured projects are evidence-ready or explicitly deferred (P1-F-02) | Content readiness register with evidence and permission status; gate review evidence; updated `29` status |
| AC-10 | B1/D-018 is recorded; default language and bilingual behavior are decided in Phase 2 or explicitly deferred with impact (P1-F-03) | Decision record; language behavior requirements; Indonesian review plan |
| AC-11 | Contact method and professional links are verified or explicitly deferred with fallback under D-023 | Verified link inventory or Owner-approved deferral; updated `29` status |
| AC-12 | Privacy and publication permissions are documented; no unverified claim is approved; D-024 service decisions remain deferred | Privacy requirements; permission register; redaction checklist; publication hold |
| AC-13 | All Phase 2 decisions are resolved or explicitly deferred | Updated `25`, `26`, and `29`; decision impact notes |
| AC-14 | Phase 2 gate record is complete and accepted | Gate record using `PHASE RESULT → AUDIT → ISSUES → DECISION → NEXT PHASE`; Project Leader recommendation; Owner acceptance |
| AC-15 | No implementation artifact exists | Repository inspection confirms no code, manifest, dependency, framework, or deployment configuration added by Phase 2 |
| AC-16 | No unresolved critical/high blocker applicable to the Phase 2 gate remains; later-phase findings remain visible in `29`; residual minor issues have Owner-approved disposition | Gate audit evidence and issue disposition; A1 evidence risk explicitly reviewed; blocker register current |
| AC-17 | Document-status register or equivalent headers exist and are reviewed; C-12/P1-F-04 evidence is recorded | Register/headers; review evidence; updated `29` status |

A criterion is not satisfied merely because a document exists. It must be reviewed against the stated evidence requirement.

---

## 9. Evidence and Information Required from the Project Owner

The Owner should provide or confirm the following through an appropriate channel. Private evidence, credentials, client data, and unpublished materials must not be committed to the public repository. A1/D-017 transferred the evidence and permission work to Phase 2; OI-01–OI-07 are mandatory for P2-T08/P2-T11, not optional inputs.

| ID | Information / evidence | Needed for | Blocking level |
|---|---|---|---|
| OI-01 | CV or confirmation of CV-derived roles, dates, and responsibilities | P2-T01, P2-T08 | Required for content readiness |
| OI-02 | Personal contribution for each candidate project | P2-T08 | Required for case-study selection |
| OI-03 | Verified technologies by project/subsystem | P2-T08 | Required for project content |
| OI-04 | Project status: production, prototype, academic, personal, internal, or unknown | P2-T08 | Required for project content |
| OI-05 | Metrics definitions, currency, context, and permission to publish | P2-T08, P2-T11 | Required before any metric publication |
| OI-06 | Public URLs, app listings, demo access, screenshots, diagrams | P2-T08, P2-T11 | Required or project deferred |
| OI-07 | Permission for client/employer names, logos, and marks | P2-T11 | Required or omitted/anonymized |
| OI-08 | Default language decision under B1/D-018 | P2-T09 | Required for Phase 2 gate; no default selected |
| OI-09 | Indonesian copy and reviewer/translator | P2-T09 | Required for Phase 2 gate |
| OI-10 | Contact method and professional profile URLs | P2-T10 | Required for Phase 2 gate; verify under D-023 |
| OI-11 | Contact form requirement or preference | P2-T10 | Required for contact decision; no form implementation without Owner approval |
| OI-12 | Downloadable CV decision | P2-T03 | Required for page scope |
| OI-13 | Location display preference | P2-T03, P2-T11 | Required for profile content |
| OI-14 | Brand assets, preferred colors, fonts, imagery | P2-T03; Phase 4 | Required for Phase 4 planning |
| OI-15 | Analytics/consent requirements | P2-T11; Phase 3/8 | Required for privacy requirements; D-024 defers service decisions |
| OI-16 | Domain ownership and hosting access constraints | Phase 3/8 | Required for Phase 3/8; D-024 deferral |
| OI-17 | Maintainer for content and dependencies | P2-T12; Phase 8 | Required for maintenance planning |
| OI-18 | Browsers/devices available for testing | P2-T07; Phase 7 | Required for test planning |

If an input is unavailable, the Owner may explicitly defer it. A deferral must include the impact, destination phase, and whether it blocks Phase 2 gate closure.

---

## 10. Risks, Unresolved Questions, and Mitigations

| Risk / question | Severity | Analysis | Mitigation |
|---|---|---|---|
| Case-study evidence unavailable | HIGH | The strongest project story may lack verifiable details or permission | A1/D-017 transferred the work to P2-T08/P2-T11; mandatory before Phase 2 gate; feature fewer, stronger projects; omit unverified claims; defer projects; do not fabricate |
| Publication permission denied | HIGH | Client/employer names, logos, screenshots, or metrics may not be publishable | A1/D-017 and P2-T11; anonymize or omit; use generic descriptions; record permission status; no publication without approval |
| Transferred evidence work not completed | HIGH | A1/D-017 moves the work to Phase 2, but the Phase 2 gate could be attempted without evidence if not enforced | P2-T08/P2-T11 mandatory; AC-09/AC-12; no publication; P2-T13 cannot pass |
| Default language unresolved | MEDIUM | Blocks language behavior, routing requirements, and bilingual parity | P1-F-03; B1/D-018 defers the decision to P2-T09; record in `25`; do not choose on Owner’s behalf |
| Indonesian copy/reviewer unavailable | MEDIUM | Bilingual P0 content may be delayed or low quality | Identify reviewer early; budget for professional review; no machine-only publication |
| Contact links unverified | MEDIUM | Contact page cannot be implemented truthfully | D-023; verify or defer; no placeholder links; use a verified direct method if available |
| Scope creep | MEDIUM | Phase 2 could absorb Phase 3/4 decisions or optional features | Use MVP/non-scope guardrails; log change requests; defer to later phases |
| Phase 2/3 boundary confusion | MEDIUM | Stack, routing, hosting, and content-format decisions could be made prematurely | Use §7.3 boundary table; record Phase 3 items without deciding them |
| Owner availability | MEDIUM | Decisions may block multiple tasks | Schedule checkpoints; allow async decisions; maintain a decision queue |
| Gate-policy ambiguity | HIGH | A later-phase HIGH finding could be read as blocking an earlier gate, or a current-phase blocker could be incorrectly deferred | D-020 phase-relative rule; `29-blocker-register.md`; Project Leader review at every gate |
| Document status drift | MEDIUM | Proposals may be mistaken for approvals | D-021/D-022 status register; decision log; explicit labels in Phase 2 outputs |
| Blocker-register drift | HIGH | A High finding could lose visibility or be treated as closed without evidence | D-020 register maintenance; gate review; Owner-approved removals only |
| Privacy/analytics ambiguity | MEDIUM | Tracking or form collection could create consent obligations | D-024 deferral; no tracking by default; document requirements; obtain Owner approval; seek qualified advice if needed |
| Performance thresholds not set | LOW/MEDIUM | Cannot verify performance at release | Set thresholds or defer to Phase 3 with measurement method; measure in Phase 7 |
| Accessibility conformance claim | LOW/MEDIUM | Automated checks do not prove conformance | Record WCAG 2.2 AA-informed intent; test before claiming; document limitations |
| Metrics overprecision | MEDIUM | Approximate figures could be presented as exact results | Preserve context; label estimates; omit if unverified |
| Bilingual inconsistency | MEDIUM | English and Indonesian facts may diverge | One source of truth; independent review; cross-check dates/names/metrics |
| No version control | HIGH | Changes cannot be tracked or rolled back; P1-F-05 blocks the Phase 3 gate under D-020 | Phase 3 prerequisite; establish Git and remote backup before implementation |
| Root README/status ambiguity | LOW | Two entry points and inconsistent status labels | D-025 disposition path; decide in P2-T01/T12; no deletion without Owner approval; keep docs index authoritative |

### 10.1 Unresolved questions carried into Phase 2

The Phase 2 plan must resolve or explicitly defer the questions in `26-open-questions-and-evidence-gaps.md` that are needed for the active phase. The following are the main Phase 2 questions:

- Which projects are featured, and what evidence/permissions exist? (A1/D-017; P2-T08/P2-T11)
- Are the CV-derived metrics current, correctly defined, and publishable? (A1/D-017; P2-T08/P2-T11)
- What default language and language behavior will Phase 2 decide or explicitly defer, and who reviews Indonesian copy? (B1/D-018; P2-T09)
- What contact method and professional links are approved or verifiable under D-023?
- Is a contact form necessary?
- Are client/employer names, logos, screenshots, or demos publishable?
- Is a downloadable CV wanted?
- Should location be displayed?
- Are analytics or other collection features required? (D-024 defers service decisions to Phase 3/8.)
- Who maintains content and dependencies?
- What browsers/devices are available for testing?

Questions that belong to Phase 3/8 (stack, hosting, domain, routing implementation, analytics implementation) must be recorded as constraints, not decided in Phase 2.

---

## 11. Review Checkpoints with the Project Leader

| Checkpoint | Timing | Inputs | Outputs / decision |
|---|---|---|---|
| CP-01 — Phase 2 kickoff | After Phase 1 gate acceptance | `27`, this plan, `25`, `26`, `29` | Confirm scope, task sequence, owners, decision queue, blocker register, and checkpoints |
| CP-02 — Requirements reconciliation review | After P2-T01 | Reconciliation memo/updated `04`; issue log | Approve issue dispositions; confirm no baseline drift |
| CP-03 — MVP and scope review | After P2-T02/P2-T03 | MVP/non-scope; page/feature inventory | Approve MVP and page scope; identify deferred items |
| CP-04 — Specification review | After P2-T04–P2-T07 | FR/NFR; journeys; acceptance/traceability matrix | Confirm requirements are testable and traceable |
| CP-05 — Content, evidence, language, contact, privacy review | After P2-T08–P2-T11 | A1/D-017 evidence/permission status; language plan under B1/D-018; contact requirements; privacy/permission register | Confirm evidence disposition and Owner decisions |
| CP-06 — Pre-gate audit | After P2-T12 | All Phase 2 outputs; decision log; open-question register; blocker register; A1/D-017 evidence status; B1/D-018 language decision | Verify AC-01–AC-17; identify blockers; prepare gate record |
| CP-07 — Phase 2 gate review | After P2-T13 | Phase 2 gate record; audit evidence | Project Leader recommends outcome; Owner accepts or requires rework |

Checkpoints are review points, not automatic approvals. The Project Leader may return work for rework. The Project Owner makes the final phase acceptance decision.

---

## 12. Final Phase 2 Gate Requirements

### 12.1 Gate outcome definitions

From `16-phase-gate-and-audit-protocol.md`:

- **PASS:** acceptance criteria are met with adequate evidence.
- **PASS WITH MINOR FIXES:** no unresolved critical/high blockers applicable to the current gate; limited issues and their dispositions are explicitly recorded and Owner-approved.
- **REWORK REQUIRED:** meaningful criteria are unmet; return to the current phase.
- **FAIL:** baseline or safety/quality requirements are materially violated; stop and re-plan.

### 12.2 Gate conditions

Phase 2 may be recommended for PASS or PASS WITH MINOR FIXES only when:

1. AC-01–AC-17 are met; any residual minor issues have an explicit Owner-approved disposition.
2. Every P0 requirement is testable and traceable to a page, journey, and verification method.
3. MVP and non-scope are approved.
4. Page/feature inventory and content requirements are approved.
5. Functional and nonfunctional requirements are approved.
6. User journeys for Personas A–D are complete.
7. Acceptance matrix and traceability are complete.
8. The A1/D-017 evidence task is complete or explicitly dispositioned by the Owner; featured projects are evidence-ready or explicitly deferred; no unverified public claim is approved.
9. B1/D-018 is recorded; P1-F-03 default language and bilingual behavior are decided or explicitly deferred with impact; Indonesian copy/reviewer plan is approved.
10. Contact method and professional links are verified or explicitly deferred with a fallback under D-023.
11. Privacy and publication permissions are documented; D-024 service decisions remain deferred; no publication occurs before P2-T08/P2-T11 are complete and the Owner approves supported content.
12. D-010–D-025 and new Phase 2 decisions are resolved or explicitly deferred with Owner approval.
13. `25-decision-log.md`, `26-open-questions-and-evidence-gaps.md`, and `29-blocker-register.md` reflect the current state.
14. No unresolved critical/high blocker applicable to the Phase 2 gate remains; findings assigned to later phases remain visible in `29-blocker-register.md`.
15. No implementation artifact was created.
16. The Phase 2 gate record is complete, includes the Project Leader’s recommendation, and is accepted by the Project Owner.

### 12.3 Gate record format

The Phase 2 gate record must use:

**PHASE RESULT → AUDIT → ISSUES → DECISION → NEXT PHASE**

It must cite evidence, separate verified findings from assumptions, state limitations, and record the Project Leader’s recommendation and the Owner’s decision. Phase 3 must not begin until the Phase 2 gate is accepted.

### 12.4 No automatic progression

This plan does not guarantee a PASS. A failed or incomplete Phase 2 returns to REWORK REQUIRED. Phase 3 is not authorized by this plan.

---

## 13. Explicitly Excluded Activities

The following are outside Phase 2 and must not be performed under this plan:

- Writing application source code.
- Creating or modifying `package.json`, lockfiles, or any package manifest.
- Installing packages or dependencies.
- Running framework scaffolding or initialization commands.
- Initializing Git or changing repository configuration.
- Creating CI/CD, hosting, domain, DNS, or deployment configuration.
- Selecting the final framework, stack, rendering strategy, hosting, domain, or architecture.
- Creating final wireframes, visual designs, design tokens, colors, fonts, logo, imagery, or breakpoints.
- Publishing content, screenshots, project links, testimonials, metrics, client names, or logos.
- Claiming publication permission that has not been granted.
- Implementing analytics, tracking, contact forms, or third-party services.
- Starting Phase 3, Phase 4, Phase 5, or any implementation work.
- Changing the approved Project Understanding Lock v1.0 without change control and Owner approval.

---

## 14. Plan Status and Next Action

**Current status:** PROPOSED. Phase 1 gate outcome remains proposed PASS WITH MINOR FIXES (D-019); A1/D-017, B1/D-018, D-020, and D-021–D-025 are recorded. D-020–D-025 are approved policy/dispositions, not gate acceptance. Phase 2 has not started. All Phase 2 tasks are Not started.

**Next action:** Fresh Project Leader review of this plan and the updated Phase 1 gate record, followed by the Project Owner’s Phase 1 gate decision in `27-phase-1-gate-review.md`. If the gate is accepted and this plan is authorized, Phase 2 begins with P2-T01; P2-T08/P2-T11 are mandatory before the Phase 2 gate. No implementation or publication is authorized.

---

**End of proposed Phase 2 execution plan.**
