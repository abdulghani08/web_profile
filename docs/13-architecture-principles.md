# Architecture Principles

## Principles

- Prefer the simplest architecture that satisfies approved requirements.
- Keep content, presentation, and reusable UI concerns separated.
- Avoid a backend unless a verified requirement needs one.
- Keep secrets out of source control; public portfolio content must not contain sensitive data.
- Use explicit language variants and consistent content fields.
- Use semantic HTML and progressive enhancement where practical.
- Minimize dependency count and client-side JavaScript.
- Make the production build deterministic and repeatable.
- Keep environment-specific configuration documented and validated.
- Treat project case studies as public content requiring disclosure review.

## Pending architecture decisions

- Framework/rendering model
- Route and localization structure
- Component boundaries
- Content storage (typed local data, Markdown/MDX, or another approach)
- Image/media optimization strategy
- Contact delivery mechanism
- Hosting, domain, redirects, and environment configuration
- Testing approach and automation level

## Proposed logical areas (not a committed folder tree)

- App/routes and page composition
- Reusable UI components
- Content and localization
- Styles/design tokens
- Static assets
- Tests and validation
- Project documentation

## Repository-first rule

The implementation agent must inspect the existing repository, package manager, framework, git status, current files, and build/test commands before recommending a structure. Do not overwrite or restructure existing work without explaining impact and obtaining approval where material.
