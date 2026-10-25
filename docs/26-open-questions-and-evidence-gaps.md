# Open Questions and Evidence Gaps

This list intentionally preserves uncertainty rather than inventing answers.

## Decision status

- **A1 / D-017:** Case-study evidence and publication-permission confirmation is transferred to the Phase 2 mandatory workstream P2-T08/P2-T11. The evidence remains unverified. No unverified claims or assets may be published.
- **B1 / D-018:** Bilingual Indonesian-English remains approved. Default language and language behavior are deferred to Phase 2, task P2-T09. No default language is selected.
- **D-020:** Gate blocker scope is phase-relative. Later-phase HIGH findings remain open and block their assigned gate; they do not automatically block an earlier phase. `29-blocker-register.md` is the visible register.
- **D-021 / D-022:** C-12 and P1-F-04 document-status remediation is approved for Phase 2 P2-T01/T12. The findings remain open until the register/headers exist and are reviewed.
- **D-023:** P1-F-06 contact and professional-link verification is approved for Phase 2 P2-T10. The finding remains open until verified or explicitly deferred with a fallback.
- **D-024:** P1-F-07 hosting, domain, analytics, and privacy decisions are deferred to Phase 3/8 under the stated constraints. The finding remains open.
- **D-025:** P1-F-08 root `README.txt` disposition path is approved; deletion is not authorized. The finding remains open until the disposition is recorded.
- **Gate status:** Phase 1 remains OPEN; D-019 is still a proposed PASS WITH MINOR FIXES. Fresh Project Leader review and explicit Owner gate acceptance are required. Phase 2 remains NOT STARTED.

## Gate and documentation dispositions

| ID | Approved disposition | Destination / acceptance condition | Current status |
|---|---|---|---|
| C-12 | Create a document-status register or equivalent headers. | Phase 2 P2-T01/T12; register reviewed; evidence recorded; AC-17. | Open; D-021 approved; remediation pending. |
| P1-F-04 | Apply the document-status remediation; keep the finding open until remediated. | Phase 2 P2-T01/T12; status labels verified; evidence recorded; AC-17. | Open; D-022 approved; remediation pending. |
| P1-F-06 | Verify contact details and professional links; no placeholders. | Phase 2 P2-T10; Owner verification or explicit deferral with fallback; AC-11. | Open; D-023 approved; verification pending. |
| P1-F-07 | Defer hosting/domain/analytics/privacy to Phase 3/8; no unauthorized service. | Phase 3/8 constraints and decisions; documented privacy implications; Owner approval. | Deferred; D-024 approved; decisions pending. |
| P1-F-08 | Determine root `README.txt` disposition; no deletion now. | Phase 2 P2-T01/T12; Project Leader assessment; Owner approval before deletion. | Open; D-025 approved; disposition pending. |

These dispositions are not gate acceptance and do not close the findings.

## Project evidence

These questions remain open. Transfer to Phase 2 does not resolve them; they are Phase 2 content-readiness inputs under P1-F-02 and P2-T08/P2-T11.

- Which MyCendekia features did the owner personally design/build/maintain?
- Which technologies and versions were used for each MyCendekia subsystem?
- Are public web/app links current and approved for portfolio use?
- Are screenshots, diagrams, or demo access available and safe to publish?
- Are the registered-user and daily-active-user figures current, and may they be published?
- What exact Odoo customization/integration work can be described publicly?
- Which other projects are complete, deployed, prototypes, academic, or internal?
- Which projects have source/demo links and permission for public display?
- Can any client/organization names or logos be published?

## Profile and content

- Which professional links should appear, and are their URLs correct? **Owner-approved for Phase 2 verification under D-023/P2-T10; still unverified.**
- What contact method should be public? **Owner-approved for Phase 2 verification under D-023/P2-T10; no placeholders.**
- What default language and language behavior will Phase 2 decide or explicitly defer under B1/D-018? Indonesian copy and a reviewer still need to be identified.
- Does the owner want a downloadable CV on the site?
- Are there any brand assets, preferred colors, fonts, or imagery?
- Should location be shown only as city/region or omitted?

## Technical and release constraints

- Is there an existing repository? What framework, package manager, and current git state does it have? **Current audit: no Git repository; P1-F-05 is a Phase 3 gate blocker under D-020.**
- Is a domain already owned? **Deferred to Phase 3/8 under D-024.**
- What hosting platform and account access are available? **Deferred to Phase 3/8 under D-024.**
- Who will maintain content and dependencies?
- Is a contact form necessary, or are direct email/profile links sufficient? **No form implementation without documented need, privacy implications, and Owner approval; D-024.**
- Is analytics required? If so, what privacy/consent requirements apply? **Deferred to Phase 3/8 under D-024; no analytics without demonstrated need and Owner approval.**
- What browsers/devices are available for release testing?

## Decision rule

Resolve only the questions needed for the active phase. Record owner answers and decisions. Do not block early planning on optional details, but do not invent facts for public content or make irreversible technical decisions without evidence. An approved disposition is not evidence of remediation; open findings remain visible in `29-blocker-register.md` until their acceptance conditions are met. These decisions do not accept the Phase 1 gate or authorize Phase 2 execution.
