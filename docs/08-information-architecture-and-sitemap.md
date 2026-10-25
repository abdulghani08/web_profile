# Information Architecture and Sitemap

## Proposed sitemap

- `/` — Home (English default proposed)
- `/en/about/` or equivalent — About
- `/en/experience/` — Experience
- `/en/projects/` — Projects index
- `/en/projects/<slug>/` — Individual project/case study
- `/en/skills/` — Skills and technology
- `/en/contact/` — Contact
- Indonesian equivalents, such as `/id/...`, subject to stack and routing decision
- Custom not-found page
- Privacy notice only if collection/analytics/contact functionality creates a real need

**Routing is a proposal, not an approved implementation detail.** Phase 3 must select a routing/localization approach and document redirects/canonical/hreflang behavior if relevant.

## Primary navigation

Home, About, Experience, Projects, Skills, Contact; language switcher. Navigation labels may be simplified for mobile.

## Hierarchy rules

- Projects must be reachable from the landing page.
- Featured projects link to their detail pages.
- Contact is reachable without hunting through the page.
- Avoid deep navigation; important content should be within a few clear steps.
- Do not add pages without a content purpose and sufficient evidence.

## Not-found behavior

Provide a helpful 404 page with a route back to Home and Projects. Verify that unknown paths do not silently render misleading content.
