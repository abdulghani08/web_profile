# Blocker Register

**Status:** ACTIVE — Phase 1 remains OPEN; Phase 2 remains NOT STARTED.  
**Register owner:** Project Leader, with Project Owner approval for dispositions and removals.  
**Authority:** `16-phase-gate-and-audit-protocol.md`, `17-task-breakdown.md`, `25-decision-log.md`, `26-open-questions-and-evidence-gaps.md`, `27-phase-1-gate-review.md`, `28-phase-2-execution-plan.md`.  
**Date:** 2026-10-25

This register is the single visible record of unresolved Critical/High findings and findings deferred to a later phase or gate. It implements D-020 and does not close any finding, accept the Phase 1 gate, or authorize Phase 2.

## 1. Register rules

- A finding remains in this register until its acceptance condition is met and evidence is recorded, or the Project Owner approves an authorized disposition.
- An approved disposition is not the same as remediation. A finding with an approved disposition remains open unless its acceptance condition has been evidenced.
- A finding may not be removed, downgraded, reclassified, or deferred merely to obtain a PASS.
- Severity is not reduced by transfer or deferral.
- Any deferral must identify the responsible phase, owner, required evidence, acceptance condition, and deadline or gate.
- Critical safety, security, confidentiality, or baseline violations must not be bypassed by phase-relative interpretation.
- No unverified claim, metric, link, screenshot, client name, logo, or asset may be published.
- No next phase may begin until the Project Leader recommends a gate outcome and the Project Owner explicitly accepts it.

## 2. Open Critical/High blockers

| ID | Severity | Finding | Current status | Blocking scope | Responsible phase / owner | Required evidence and acceptance condition | Resolution gate / deadline | Publication impact |
|---|---|---|---|---|---|---|---|---|
| **P1-F-02** | HIGH | Case-study evidence and disclosure permissions remain unverified; transferred to Phase 2 by A1/D-017. | **OPEN** — not downgraded; Phase 2 content-readiness blocker. | Phase 2 gate and publication. Does not block Phase 1 under D-020. | Phase 2 / Project Owner with Project Leader. | P2-T08/P2-T11 content-readiness and permission register; every public claim and asset has an evidence and permission status; completion or an explicitly Owner-approved disposition before the Phase 2 gate. | Phase 2 gate P2-T13; AC-09 and AC-12 in `28`. | **Publication hold:** no unverified claim or asset may be published. Unsupported projects must be omitted, anonymized, or explicitly deferred. |
| **P1-F-05** | HIGH | No version control is established; no Git repository or executable was found. | **OPEN** — Phase 3 prerequisite. | Phase 3 gate. Does not block Phase 1 under D-020. | Phase 3 / Project Owner with Project Leader. | Canonical repository location, version control, and remote backup established and audited; `.gitignore` and change discipline in place before implementation. | Phase 3 gate; before implementation. No Git initialization is authorized in Phase 1 or Phase 2. | No direct publication impact; implementation must not proceed without version control. |

## 3. Deferred and residual findings

These findings are not current Phase 1 Critical/High blockers. They remain visible because they are deferred to a later phase or gate, or because an approved disposition is pending remediation.

| ID | Severity | Finding | Current status | Blocking scope | Responsible phase / owner | Required evidence and acceptance condition | Resolution gate / deadline |
|---|---|---|---|---|---|---|---|
| **P1-F-01** | HIGH | Phase 1 gate outcome was not previously recorded. | **RESOLVED (procedural)** — gate record created; fresh Project Leader recommendation and Owner acceptance pending. | Phase 1 gate decision; not a content blocker. | Project Leader and Project Owner. | Updated gate record; fresh Project Leader recommendation; explicit Owner gate acceptance. | Phase 1 gate decision. |
| **P1-F-03** | MEDIUM | Default language and language behavior are not selected. | **DEFERRED** — B1/D-018; no default selected. | Phase 2 gate and Phase 3 routing. | Phase 2 / Project Owner with Project Leader. | P2-T09 decision or explicit deferral with impact; Indonesian copy and reviewer identified; AC-10. | Phase 2 gate P2-T13. |
| **P1-F-04** | MEDIUM | Document-level approval status is ambiguous. | **OPEN** — Owner-approved disposition D-022; Phase 2 remediation. | Phase 2 documentation quality; not a Phase 1 blocker. | Phase 2 / Project Leader. | Document-status register or equivalent headers distinguishing draft, proposed, approved, superseded, and pending; evidence of review; finding remains open until remediated. | Phase 2 P2-T01/P2-T12; Phase 2 gate P2-T13; AC-17 in `28`. |
| **P1-F-06** | MEDIUM | Contact method and professional links are unverified. | **OPEN** — Owner-approved disposition D-023; Phase 2 verification. | Phase 2 gate and contact content. | Phase 2 / Project Owner with Project Leader. | P2-T10 verified contact method and professional links; no placeholders, unverified links, or unnecessary personal information; contact content not ready until Owner verification; AC-11. | Phase 2 gate P2-T13. |
| **P1-F-07** | MEDIUM | Hosting, domain, analytics, and privacy decisions remain pending. | **DEFERRED** — Owner-approved D-024; Phase 3/8. | Phase 3 and Phase 8; not a Phase 1 or Phase 2 content blocker. | Phase 3/8 / Project Owner with Project Leader. | Recorded constraints and decisions; no analytics, tracking, contact form, or third-party service without demonstrated need, documented privacy implications, and Owner approval; D-012/D-014 remain pending. | Phase 3 gate for constraints; Phase 8 release gate for deployment configuration. |
| **P1-F-08** | LOW | Root `README.txt` is an extra, undocumented entry point. | **OPEN** — Owner-approved disposition path D-025; no deletion authorized. | Documentation entry-point clarity; not a Phase 1 blocker. | Phase 2 / Project Leader; Owner approval before deletion. | Project Leader assesses whether to keep as a pointer or propose retirement; if removal is recommended, Owner approval is recorded before deletion; docs index remains authoritative. | Phase 2 P2-T01/P2-T12; no deletion without Owner approval. |
| **C-12** | Criterion gap (minor) | Documents must reflect approved decisions and explicitly mark unknowns; document-level status labels are inconsistent. | **OPEN** — Owner-approved disposition D-021; Phase 2 remediation. | Phase 2 documentation quality; not a Phase 1 blocker. | Phase 2 / Project Leader. | Document-status register or equivalent headers created and reviewed; C-12 evidence recorded; finding remains open until the register/headers exist. | Phase 2 P2-T01/P2-T12; Phase 2 gate P2-T13; AC-17 in `28`. |

## 4. Gate status

| Gate | Status | Current blocker scope |
|---|---|---|
| Phase 1 | **OPEN / AWAITING FRESH PROJECT LEADER REVIEW AND OWNER ACCEPTANCE** | D-019 remains a proposed PASS WITH MINOR FIXES. Under D-020, P1-F-02 and P1-F-05 are not Phase 1 blockers; P1-F-01 is procedural and resolved by the gate record, with fresh Project Leader recommendation and Owner acceptance pending. The gate still requires a fresh Project Leader review and explicit Owner acceptance. |
| Phase 2 | **NOT STARTED** | P1-F-02 is a Phase 2 content-readiness and publication blocker. P1-F-03, P1-F-04, P1-F-06, and C-12 are Phase 2 conditions; P1-F-04/C-12 are tracked by AC-17. P1-F-08 is a Phase 2 documentation disposition, not a gate blocker. P1-F-05 and P1-F-07 are later-phase matters. |
| Phase 3 | **NOT STARTED** | P1-F-05 is a Phase 3 prerequisite. P1-F-07 constraints must be resolved for Phase 3/8 as applicable. |

## 5. Change control

Additions, removals, severity changes, phase reassignments, or disposition changes require the Project Leader’s review and, where a baseline or approved decision is affected, Project Owner approval under `16-phase-gate-and-audit-protocol.md`. The decision must be recorded in `25-decision-log.md`.

**No finding is closed by this register’s creation. No Phase 1 gate outcome is accepted. No Phase 2 work is authorized.**
