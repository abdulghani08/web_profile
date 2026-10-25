# Decision Log

| ID | Decision | Status | Rationale / Notes |
|---|---|---|---|
| D-001 | Project is a professional portfolio for Muhammad Abdul Ghani | APPROVED | Project owner explicitly approved Project Understanding Lock v1.0 |
| D-002 | Primary identity is Software Developer | APPROVED | Approved baseline |
| D-003 | Primary focus is full-stack, backend, frontend, and mobile development | APPROVED | Technical-first emphasis |
| D-004 | IT systems, ERP/integration, operations, and project leadership are supporting differentiators | APPROVED | Preserve breadth without diluting primary identity |
| D-005 | Target audience includes recruiters, hiring managers, engineering leads, employers, and potential clients | APPROVED | Combined career, branding, and professional opportunity goal |
| D-006 | Bilingual Indonesian and English | APPROVED | English default is planned; routing mechanism remains pending |
| D-007 | Approximate content emphasis: 80% development / 20% leadership-management | APPROVED | Owner-approved positioning direction |
| D-008 | Eight-phase process with quality gates | APPROVED | No phase progression without audit |
| D-009 | Markdown documentation under `/docs` | APPROVED | Source of truth for planning and implementation |
| D-010 | Framework/stack | PENDING DECISION | Evaluate in Phase 3 after repository and deployment constraints audit |
| D-011 | Final routing/localization mechanism | PENDING DECISION | Depends on stack and SEO needs |
| D-012 | Hosting/domain/deployment | PENDING DECISION | Owner access and constraints not yet confirmed |
| D-013 | Contact form vs. direct contact links | PENDING DECISION | Prefer simplest secure approach meeting needs |
| D-014 | Analytics/third-party tracking | PENDING DECISION | No tracking by default without a documented need and approval |
| D-015 | Featured projects and public evidence | PENDING DECISION | Requires evidence and disclosure review |
| D-016 | Phase 1 gate outcome proposed as REWORK REQUIRED | SUPERSEDED | Historical proposal recorded in `27-phase-1-gate-review.md`; never accepted. Replaced as the current proposed outcome by D-019 after Owner decisions A1 (D-017) and B1 (D-018). Phase 1 was not closed by D-016. |
| D-017 | Transfer case-study evidence and publication-permission task to Phase 2 under change control (A1) | APPROVED | Owner-approved A1. The task is mandatory Phase 2 work under P2-T08/P2-T11 and must be completed or explicitly dispositioned before the Phase 2 gate. Evidence remains unverified; no unverified claims or assets may be published. |
| D-018 | Bilingual Indonesian-English remains approved; default language and language behavior deferred to Phase 2 (B1) | APPROVED | Owner-approved B1. Clarifies D-006. No default language is selected; P2-T09 must decide or explicitly defer it with impact. Indonesian copy/reviewer remains required. |
| D-019 | Phase 1 gate outcome: PASS WITH MINOR FIXES | ACCEPTED | Originally proposed in `27-phase-1-gate-review.md`; accepted by the Project Owner on 2026-10-25 after the Project Leader recommendation. Phase 1 is CLOSED. Acceptance does not close P1-F-02, P1-F-05, or the approved minor findings. Phase 2 authorization is recorded separately in D-026. |
| D-020 | Gate blocker scope — phase-relative interpretation (Option A) | APPROVED | Owner-approved clarification of `16`: a Critical/High finding blocks the phase or gate to which it is assigned; later-phase HIGH findings remain open in `29-blocker-register.md` and block their assigned gate; no finding may be reclassified, closed, or deferred merely to obtain a PASS; safety, security, confidentiality, and baseline violations are not bypassed. |
| D-021 | C-12 — create a document-status register in Phase 2 | APPROVED | Owner-approved disposition: create a document-status register or equivalent headers distinguishing draft, proposed, approved, superseded, and pending. Do not present D-019 as accepted. Remediation is Phase 2 P2-T01/T12; C-12 remains a minor gap until evidence is recorded. |
| D-022 | P1-F-04 — document-status remediation; keep finding open until remediated | APPROVED | Owner-approved disposition: apply the document-status remediation during Phase 2 P2-T01/T12. The finding remains open until the stated acceptance condition is met and evidence is recorded. |
| D-023 | P1-F-06 — verify contact details and professional links in Phase 2 | APPROVED | Owner-approved disposition: verify contact details and professional links during Phase 2 P2-T10. No placeholders, unverified links, or unnecessary personal information. Contact content is not ready until Owner verification; the finding remains open. |
| D-024 | P1-F-07 — defer hosting, domain, analytics, and privacy to later phases | APPROVED | Owner-approved deferral to Phase 3/8 as applicable. No analytics, tracking, contact form, or third-party service without demonstrated need, documented privacy implications, and Owner approval. D-012/D-014 remain pending; the finding remains open. |
| D-025 | P1-F-08 — root `README.txt` disposition; no deletion now | APPROVED | Owner-approved disposition path: deletion is NOT authorized. The Project Leader may assess whether to keep it as a pointer or propose retirement; if removal is recommended, request Owner approval before deleting. The finding remains open until the disposition is recorded. |
| D-026 | Phase 1 gate acceptance and Phase 2 planning authorization | APPROVED | Owner explicitly selected Option A — ACCEPT: PASS WITH MINOR FIXES on 2026-10-25. Phase 1 is CLOSED. Phase 2 — Requirements & Product Planning is AUTHORIZED TO START for planning and documentation only. P1-F-02 and P1-F-05 remain HIGH and open; all approved dispositions and conditions remain in force. Phase 2 gate acceptance is NOT granted. |

**D-016 is retained for history.** It was a proposed gate outcome, never an accepted decision. D-019 replaced it as the proposed outcome after A1/D-017 and B1/D-018; D-019 was then accepted by the Project Owner on 2026-10-25. D-026 records the Phase 2 authorization.

**D-018 clarification:** D-006’s “English default is planned” note is historical. No default language is confirmed; B1/D-018 defers the default and language behavior to Phase 2.

**D-020–D-026 status note:** D-020–D-025 are Owner-approved policy and dispositions. D-026 records the Owner’s acceptance of the Phase 1 gate and authorization of Phase 2 planning only. Gate acceptance does not close the findings, and Phase 2 authorization is not implementation authorization.

## Change-control record A1 — evidence and publication-permission task transfer

**Decision ID:** D-017  
**Owner approval:** A1, explicitly approved by the Project Owner in the conversation.  
**Status:** APPROVED.

- **Previous decision or task classification:** `17-task-breakdown.md` assigned “Confirm case-study evidence and public disclosure permissions” to Phase 1, where it remained unchecked.
- **Problem and supporting evidence:** Project claims remain CV-derived and unverified. Accuracy, dates, metrics, links, screenshots, client identification, and publication permissions require confirmation. `06-project-evidence-inventory.md` and `26-open-questions-and-evidence-gaps.md` record these gaps.
- **Reason for change:** The Owner directed that the evidence and permission work may be transferred to Phase 2 while remaining mandatory. The transfer is intended to resolve the Phase 1 task-classification conflict without treating the evidence as verified.
- **Proposed replacement:** Transfer the task to Phase 2 workstream P2-T08 (content and case-study evidence readiness) and P2-T11 (privacy and publication permissions). Completion, or an explicitly Owner-approved disposition, is required before the Phase 2 gate closes. No unverified project or claim may be published.
- **Impact:** Phase 1 gate assessment changes because the open task is no longer a Phase 1 task; task tracking moves the work to Phase 2; Phase 2 content-readiness dependencies and acceptance criteria become mandatory; publication remains blocked until evidence and permission status are resolved. Scope is unchanged, no implementation cost is authorized, schedule impact is the moved Phase 2 work, quality risk is controlled by the Phase 2 gate, and the related documents (`17`, `25`, `26`, `27`, `28`) are updated.
- **Owner approval:** A1, explicitly approved by the Project Owner in the conversation.
- **Restrictions:** Unverified claims, metrics, links, screenshots, client names, logos, and assets remain unpublished. Unsupported projects must be omitted, anonymized where appropriate, or explicitly deferred until the Owner approves a supported alternative.

## Decision record B1 — bilingual direction and default language

**Decision ID:** D-018  
**Owner approval:** B1, explicitly approved by the Project Owner in the conversation.  
**Status:** APPROVED.

- Bilingual Indonesian-English remains approved under D-006.
- Default language and related language behavior are deferred to Phase 2, task P2-T09.
- No default language is selected by this decision. The earlier “English default is planned” note in D-006 is not confirmed as a decision.
- Indonesian copy provision/review and bilingual content readiness remain Phase 2 requirements.
- This is not a Phase 1 blocker. The Phase 2 gate condition is AC-10 in `28-phase-2-execution-plan.md`.

## Decision record D-020 — gate blocker scope (Option A)

**Decision ID:** D-020  
**Status:** APPROVED  
**Owner approval:** Explicitly approved by the Project Owner in the conversation.

**DECISION:** Adopt the phase-relative interpretation of `16-phase-gate-and-audit-protocol.md`’s “no critical/high blockers” requirement. A Critical/High finding blocks the phase or gate to which it is assigned by the protocol, the approved phase plan, or an explicit Owner-approved disposition. It does not automatically block an earlier phase when it is demonstrably outside that phase’s acceptance criteria and the approved protocol permits deferral.

**Previous wording and ambiguity:** `16` previously said: “PASS WITH MINOR FIXES: no critical/high blockers; limited issues are explicitly listed with owner-approved disposition.” It did not define “blocker” or state whether the prohibition was phase-relative or global. The Phase 1 audit found that the phase-relative reading in `27` was not an explicit protocol rule and that P1-F-02 (HIGH, Phase 2 evidence) and P1-F-05 (HIGH, Phase 3 version control) could be read as blocking Phase 1.

**Issue exposed by the Phase 1 audit:** A literal global reading would require Phase 2 evidence work and Phase 3 version-control work before Phase 1 could close, while the approved phase plan prevents Phase 2 or Phase 3 from starting until Phase 1 passes. That would create circular dependencies and would nullify A1/D-017’s approved transfer.

**REASON:** Phase-relative blocking is necessary to avoid unrelated future-phase prerequisites blocking an earlier phase. It preserves the phase-gate structure, gives effect to A1/D-017, and keeps later-phase HIGH findings enforceable at their assigned gates.

**Approved replacement / clarification:** `16` now states that gate blockers are evaluated against the current phase’s acceptance criteria and release-readiness obligations; a later-phase HIGH finding remains open and blocks its assigned phase; any deferral identifies the responsible phase, owner, required evidence, acceptance condition, and deadline or gate; Critical safety, security, confidentiality, or baseline violations are not bypassed; no finding may be reclassified, closed, or deferred merely to obtain a PASS; and all unresolved Critical/High and deferred findings remain visible in `29-blocker-register.md` until evidence or an authorized disposition applies.

**IMPACT:** Applies to all future phase gates. P1-F-02 remains HIGH and blocks the Phase 2 gate and publication. P1-F-05 remains HIGH and blocks the Phase 3 gate. P1-F-01 remains a procedural HIGH resolved by the gate record, with fresh Project Leader recommendation and Owner acceptance pending. The Phase 1 gate remains proposed and is not accepted by this decision. Phase 2 remains not started. The clarification does not reduce severity or permit unverified publication.

**Owner approval:** Explicit.  
**Restrictions:** No reclassification, closure, or deferral merely to obtain a PASS. No weakening of Critical safety, security, confidentiality, or baseline requirements. No publication of unverified claims or assets. No Phase 2 execution or gate acceptance by this decision.

## Approved minor-finding dispositions D-021–D-025

The Project Owner explicitly approved the following dispositions. They are **not** Phase 1 gate acceptance and do not authorize Phase 2 execution. Each finding remains in `29-blocker-register.md` until its acceptance condition is evidenced or an authorized disposition applies.

| ID | DECISION | REASON | IMPACT | Acceptance condition | Restrictions |
|---|---|---|---|---|---|
| **D-021** | Approve C-12 disposition: create a document-status register or equivalent headers in Phase 2. | The documentation index and several documents mix approved baseline content with proposals, creating a risk that a proposal is mistaken for an approval. | Phase 2 P2-T01/T12 must distinguish draft, proposed, approved, superseded, and pending documents and decisions. C-12 remains a minor documentation gap until the register/headers exist and are reviewed. | Register/headers exist and are reviewed; AC-17 evidence recorded; the Phase 2 gate record records C-12 as remediated or explicitly dispositioned. | Do not present D-019 or any other proposed gate outcome as accepted. Do not treat proposed content as approved. |
| **D-022** | Approve P1-F-04 disposition: apply the document-status remediation during Phase 2 and keep the finding open until remediated. | Document-level approval status is ambiguous across `03`, `08`, `09`, `11`–`14`, `18`, and `23`. | Phase 2 P2-T01/T12; the finding remains open and must be evidenced before closure. No product or technical change is authorized by this disposition. | Document-status register/headers created and reviewed; AC-17 evidence recorded; finding explicitly closed or carried forward with an Owner-approved disposition. | Do not approve the underlying proposed content. Do not close the finding merely because the disposition is approved. |
| **D-023** | Approve P1-F-06 disposition: verify contact details and professional links during Phase 2. | No verified public contact method or professional profile URL is recorded; FR-05 and the contact page require verified links. | Phase 2 P2-T10 must verify or omit links; no placeholders, unverified links, or unnecessary personal information. Contact content cannot be marked ready until Owner verification; the finding remains open. | Verified contact method and professional links recorded, or explicit Owner-approved deferral with fallback; AC-11 evidence. | Do not publish placeholders, unverified links, or unnecessary personal information. Do not treat this disposition as verification. |
| **D-024** | Approve P1-F-07 disposition: defer hosting, domain, analytics, and privacy decisions to the appropriate later phases. | These are Phase 3/8 dependencies, not Phase 1 identity requirements. Premature decisions would create unsupported infrastructure and privacy risk. | Phase 3/8 decisions; record constraints; no analytics, tracking, contact form, or third-party service without demonstrated need, documented privacy implications, and Owner approval. D-012/D-014 remain pending; the finding remains open. | Constraints and decisions recorded in the appropriate phase; privacy implications documented; Owner approval recorded before any service is added. | Do not select a hosting provider, domain, analytics service, contact form, or third-party service in this task. Do not weaken privacy or security requirements. |
| **D-025** | Approve P1-F-08 disposition path: determine the root `README.txt` disposition; no deletion is authorized now. | The root file is an extra entry point that could drift from `docs/README.md`, but deletion requires an explicit decision. | Project Leader assesses whether to keep it as a pointer or propose retirement; if removal is recommended, Owner approval is required before deletion. The finding remains open until the disposition is recorded. | Disposition recorded in Phase 2 P2-T01/T12; if retained, docs index remains authoritative; if removal is approved, evidence of Owner approval is recorded. | **Do not delete `README.txt` in this task.** Do not change the docs index in a way that hides the file’s status. |

**Status note:** D-021–D-025 are APPROVED dispositions, but C-12, P1-F-04, P1-F-06, P1-F-07, and P1-F-08 are not automatically closed. P1-F-02 and P1-F-05 remain HIGH and open. P1-F-03 remains deferred under B1/D-018. P1-F-01 remains a procedural HIGH resolved by the gate record, with fresh Project Leader recommendation and Owner gate acceptance pending.

## Change procedure

Any change to an approved decision requires the change-control sequence in `16-phase-gate-and-audit-protocol.md`. Update this log and related documents only after approval.
