# Contributing

Thank you for considering a contribution. This document describes the preferred workflow and guidelines to make contributions easy to review and accept.

## Code of conduct
Be respectful and inclusive. Report violations by opening an issue or contacting the maintainers.

## How to contribute
1. Fork the repository.
2. Create a branch from main (or the default branch):
    - git checkout -b my-feature
3. Make small, focused commits. Rebase/squash as appropriate before the final push.
4. Push to your fork and open a pull request against the repository's default branch.

## Branching & commit messages
- Use descriptive branch names: feature/..., fix/..., docs/...
- Commit message format:
  - Short summary (<= 50 chars)
  - Optional blank line
  - Detailed description (wrap at 72 chars)
- Keep commits atomic and focused.

## Pull request checklist
- [ ] Is the change minimal and focused?
- [ ] Does it include tests for new behavior?
- [ ] Does it pass CI and linters?
- [ ] Is documentation updated as needed?
- [ ] Provide a clear description and link to any related issue.

## Issues
- Search existing issues before filing.
- Include steps to reproduce, expected vs actual behavior, environment, and minimal reproducible example when possible.

## Tests & CI
- Add or update tests for new features and bug fixes.
- Run the full test suite locally before opening a PR.
- Ensure CI status is green before merge.

## Style & quality
- Follow the repository's style (PEP 8 for Python). Use linters/formatters defined in the repo (e.g., black, flake8).
- Keep API and UX changes documented and justified.

## Dependencies & security
- Avoid unnecessary dependency bumps. Provide rationale for upgrades.
- Do not commit secrets (API keys, credentials). Use environment variables or secrets manager.

## Review process
- PRs will be reviewed; maintainers may request changes.
- Address review comments promptly and keep the conversation focused.

## License & copyright
- By contributing you agree to the repository's license terms. Ensure you have the right to submit the code.

## Contact
For questions, open an issue or contact the maintainers via the repo's preferred channel.

Thank you for contributing.
