# Contributing to Spartan Labs Projects

Thank you for contributing. Individual repositories may add technology-specific requirements;
those rules supplement this organization-wide baseline.

## Before You Start

- Search existing issues and discussions before opening new work.
- Use the repository's issue templates and describe the problem, expected outcome, and relevant
  context.
- For work spanning multiple pull requests, use a tracking issue and link its sub-issues.
- Record dependencies with GitHub's dependency links rather than prose alone.

## Development Workflow

1. Create an issue for each unit of work.
2. Branch from the repository's default branch.
3. Keep the branch focused and short-lived.
4. Add or update tests and documentation appropriate to the change.
5. Open a pull request that explains the change, links its issue, and reports validation.
6. Address review feedback and ensure required checks pass before merging.

Use `Refs #N` for planning or documentation work. Only the implementation pull request should
use `Closes #N`.

## Commits and Pull Requests

Use [Conventional Commits](https://www.conventionalcommits.org/):

```text
<type>(<scope>): <subject>
```

Use `feat`, `fix`, `perf`, `refactor`, `docs`, `test`, `build`, `ci`, or `chore`. Breaking
changes use `!` in the subject and a `BREAKING CHANGE:` footer.

Keep pull requests narrowly scoped. Explain what changed and why, include the relevant issue,
and call out breaking changes, migrations, and follow-up work.

## Code, Tests, and Documentation

Follow the conventions established by the target repository. Preserve compatibility unless a
breaking change is intentional and documented. Update user-facing documentation whenever the
public behavior, API, build, or operational workflow changes.

## Security

Do not report vulnerabilities in public issues. Follow the repository's `SECURITY.md` policy or
contact <spartaksingh95@gmail.com>.
