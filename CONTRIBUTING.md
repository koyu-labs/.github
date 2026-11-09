# Contributing to Koyu Labs repos

Internal rules, the same in every repo. The full version is `docs/guides/repo-conventions.md` in `koyu-labs/koyu-labs`.

- **Issues:** one `area:` label and at least one `project:` label. `needs:danilo` when it waits on Danilo,
  `agent-ok` when Claude or Copilot can take it without a decision.
- **Lab work:** a parent issue in `koyu-labs/koyu-labs`; this repo's tasks are its sub-issues. Lab milestones keep
  the same name in every repo.
- **Pull requests:** close issues with `Fixes #n` (or `Fixes koyu-labs/<repo>#n`). Nothing is merged or published
  without Danilo.
- **Setup work** closes only with its guide in `koyu-labs/docs/guides/` written or updated.
- **Secrets** are named, never written: not in issues, PRs, docs or code.
