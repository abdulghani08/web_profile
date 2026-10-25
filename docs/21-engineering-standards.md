# Engineering Standards

Final conventions must be aligned to the approved stack in Phase 3. These baseline standards apply regardless of framework.

## General

- Follow existing repository conventions after auditing them.
- Prefer clear, small, composable components over unnecessary abstraction.
- Use descriptive names and consistent formatting.
- Avoid duplicated content and inconsistent bilingual facts.
- Keep presentation separate from content where practical.
- Avoid adding dependencies for trivial functionality.
- Do not disable lint, type, security, or build checks just to make a task pass.
- Do not introduce dead code, placeholder links, fake data, or console errors into release builds.
- Do not overwrite user work without inspecting git status and explaining material changes.

## Type safety and errors

If the approved stack supports TypeScript, use strict type checking where practical. Handle loading, empty, and error states for actual asynchronous features. Do not create asynchronous complexity when the site does not need it.

## Git and change discipline

- Inspect branch and working-tree state before changes.
- Make focused changes aligned to one task.
- Do not discard uncommitted changes.
- Summarize files changed, rationale, tests run, test results, and known limitations.
- Do not claim tests/builds passed without executing them.

## Comments and documentation

Comment why a non-obvious decision exists, not what a clear line already says. Update documentation when an approved decision or implementation behavior changes.
