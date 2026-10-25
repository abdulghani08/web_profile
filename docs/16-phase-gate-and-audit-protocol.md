# Phase Gate and Audit Protocol

**Current clarification:** D-020 (Owner-approved) defines phase-relative blocker scope. See “Gate blocker scope, deferral, and blocker register” below.

## Gate outcomes

- **PASS:** acceptance criteria are met with adequate evidence.
- **PASS WITH MINOR FIXES:** no unresolved critical/high blockers applicable to the current gate; limited issues and their dispositions are explicitly recorded and Owner-approved.
- **REWORK REQUIRED:** meaningful criteria are unmet; return to the current phase.
- **FAIL:** baseline or safety/quality requirements are materially violated; stop and re-plan.

## Audit format

Every audit must use:

**FINDING → SEVERITY → ANALYSIS → ACTION**

For phase closeout, use:

**PHASE RESULT → AUDIT → ISSUES → DECISION → NEXT PHASE**

## Evidence requirements

- Cite files, routes, test outputs, screenshots, command results, or reproducible steps where available.
- Separate verified findings from assumptions.
- Never report a test as passed if it was not run.
- If a browser, device, hosting account, or external service is unavailable, report the limitation.
- Record the date and environment for test results.

## Severity

- **Critical:** data/security exposure, site unusable, release/build blocked, or major misleading content.
- **High:** major feature or route broken, serious accessibility/responsive defect, significant SEO/content failure.
- **Medium:** notable but non-blocking issue affecting a user journey or quality.
- **Low:** minor visual inconsistency or polish issue.

## Gate rule

No next phase may begin until the Project Leader recommends a gate outcome and the Project Owner explicitly accepts it. No silent phase advancement.

## Gate blocker scope, deferral, and blocker register

Gate blockers are evaluated against the acceptance criteria and release-readiness obligations of the phase currently under review. A finding is a gate blocker only when it is unresolved and either:

- arises from the current phase’s acceptance criteria or release-readiness obligations; or
- is explicitly assigned to the current gate by the approved phase plan, an Owner-approved decision, or the blocker register.

A HIGH finding that is a mandatory prerequisite for a later phase must remain open and block that later phase as specified. It does not automatically block an earlier phase if it is demonstrably outside the earlier phase’s acceptance criteria and the approved protocol permits deferral.

A finding cannot be reclassified, closed, or deferred merely to obtain a PASS. Deferral does not reduce severity. Any deferral must identify:

1. the responsible phase;
2. the owner;
3. the required evidence;
4. the acceptance condition; and
5. the deadline or gate at which it must be resolved.

Critical safety, security, confidentiality, or baseline violations must not be bypassed by phase-relative interpretation. If a finding implicates those requirements, it must be escalated and resolved under the applicable stricter requirement.

Every unresolved Critical/High finding, and every finding deferred to a later gate, must remain visible in `29-blocker-register.md` until evidence proves remediation or an authorized Owner-approved disposition applies. A finding may be removed from the register only when its evidence and acceptance condition are recorded.

`PASS WITH MINOR FIXES` requires no unresolved critical/high blockers applicable to the current gate and requires the minor findings and their dispositions to be explicitly recorded and Owner-approved. Findings that block a later phase must remain visible in the blocker register until resolved.

This clarification is implemented under D-020. It does not close any finding, accept any gate, or authorize any phase transition.

## Change control

When a baseline decision must change, present:
1. Previous decision
2. Problem or evidence
3. Reason for change
4. Proposed replacement
5. Scope, cost, quality, schedule, and documentation impact

Obtain owner approval before changing a fundamental baseline decision.
