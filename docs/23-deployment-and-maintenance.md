# Deployment and Maintenance

## Deployment decisions still pending

Domain, hosting provider, DNS control, CI/CD approach, environment variables, analytics, monitoring, and rollback mechanism have not yet been approved.

## Release checklist

- Owner approves release candidate and outstanding issues.
- Repository state and build are reproducible.
- No secrets or private data are committed.
- Required environment variables are documented without publishing values.
- Domain/DNS and HTTPS configuration are verified.
- Production build and relevant tests pass.
- Metadata, language routing, links, and assets are correct.
- 404 behavior and redirects are checked.
- Production smoke tests are completed.
- Rollback or recovery steps are known.
- Owner has access to the hosting/domain accounts.

## Post-deployment verification

Test the live site on desktop and mobile, verify all key routes and language variants, check the contact route, inspect metadata and social previews, and record the deployment date and commit/version.

## Maintenance

- Keep dependencies updated using a reviewed process.
- Recheck links and project facts periodically.
- Update portfolio content only when dates, roles, technologies, and outcomes are verified.
- Re-run build, accessibility, performance, and security checks after material changes.
- Maintain domain/hosting renewal and account access.
- Store recovery information securely, not in public repository files.
