# Performance and Security Requirements

## Performance principles

- Prefer static/pre-rendered content where appropriate for the approved architecture.
- Minimize client-side JavaScript and third-party scripts.
- Optimize images and fonts; avoid shipping oversized assets.
- Use lazy loading for non-critical media where appropriate.
- Avoid layout shifts and blocking effects.
- Measure a production build, not only a development server.
- Establish final numeric thresholds in Phase 2/3 based on the deployment environment and measurement method.

## Suggested release targets

Use Core Web Vitals as the measurement framework where field data is available: LCP ≤ 2.5 s, INP ≤ 200 ms, CLS ≤ 0.1 at the 75th percentile. For a new site without field data, use lab measurements as directional evidence and state that they are not equivalent to field performance. These are proposed targets, not yet owner-approved contractual thresholds.

## Security

- No secrets, API keys, passwords, tokens, or private environment files in version control.
- No sensitive personal data in screenshots or project content.
- Keep dependencies limited and maintained; inspect vulnerability reports before release.
- Validate and safely handle any user input if a form is approved.
- Protect contact delivery from spam without exposing secrets in client-side code.
- Use HTTPS in production.
- Do not add third-party analytics, embeds, or tracking without a documented need and owner approval.
- Do not expose internal system diagrams, private APIs, production logs, or client data.

## Release blockers

Any confirmed secret exposure, private-data leak, critical dependency vulnerability, insecure contact handling, or production configuration error blocks release until resolved or explicitly assessed through a documented exception approved by the owner.
