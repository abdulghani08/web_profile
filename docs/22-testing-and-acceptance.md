# Testing and Acceptance

## Test layers

1. **Build/static checks:** production build, type checking, linting, dependency checks as supported.
2. **Functional:** navigation, language switch, project routes, contact/profile links, 404 behavior.
3. **Responsive:** representative mobile, tablet, laptop, and desktop viewports.
4. **Accessibility:** keyboard-only review, focus visibility, semantic structure, contrast, alt text, reduced motion.
5. **SEO/content:** page metadata, canonical/localized behavior, sitemap/robots where applicable, no accidental noindex, factual claim review.
6. **Performance:** production measurement and asset/payload review.
7. **Security/privacy:** secret scan, public data review, dependency findings, form/tracking review.
8. **Cross-browser:** current mainstream browsers available for testing; document any untested environment.
9. **Production smoke tests:** repeat critical journey checks on the deployed site.

## Acceptance evidence

For every requirement, record:
- Requirement ID
- Test/check performed
- Environment or viewport
- Result (pass/fail/not tested)
- Evidence or reproduction steps
- Defect severity and follow-up

## Release acceptance

Release candidate is accepted only when:
- All P0 requirements pass.
- No unresolved critical/high blocker remains.
- Both languages have reviewed core content.
- All important links/routes work.
- Production build passes.
- Accessibility, responsive, SEO, performance, and security reviews are recorded.
- Owner accepts any remaining minor issues.
