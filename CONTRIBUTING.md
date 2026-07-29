# Contributing to Open-source Club (alpha)

Thanks for wanting to contribute! This guide covers everything you need to go from "browsing the repo" to "merged pull request." If anything here is unclear, ask in [Discussions → Q&A](https://github.com/orgs/open-source-club-alpha/discussions/categories/q-a) — unclear docs are a bug too, and we'd rather fix them.

By participating, you agree to follow our [Code of Conduct](./CODE_OF_CONDUCT.md).

## Ways to contribute

You don't need to write code to contribute:
- 💡 Propose an idea in [Discussions → Ideas](https://github.com/orgs/open-source-club-alpha/discussions/categories/ideas)
- 🐛 Report a bug via an Issue
- 📖 Improve documentation
- 🎨 Design, UX feedback, testing
- 💻 Pick up an open issue and submit a PR

## Finding something to work on

- New here? Look for issues labeled [`good first issue`](https://github.com/search?q=org%3Aopen-source-club-alpha+label%3A%22good+first+issue%22&type=issues) — scoped and beginner-friendly.
- Want more of a challenge? Try [`help wanted`](https://github.com/search?q=org%3Aopen-source-club-alpha+label%3A%22help+wanted%22&type=issues).
- **Claim an issue before starting**: comment "I'd like to work on this" and wait for a maintainer to assign it to you. This avoids two people duplicating work.
- If an issue is assigned but has gone quiet for over a week, feel free to comment and ask if it's still being worked on.

## Development setup

```bash
# 1. Fork the repository, then clone your fork
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

# 2. Add the upstream remote
git remote add upstream https://github.com/[org-name]/<repo-name>.git

# 3. Install dependencies
[install command — e.g. npm install / pip install -r requirements.txt]

# 4. Run the project locally
[run command]

# 5. Run tests
[test command]
```

## Branching and commits

- Create a branch off `main` for your work — don't commit directly to `main`:
  ```bash
  git checkout -b feature/short-description
  # or fix/short-description, docs/short-description
  ```
- Write commit messages using [Conventional Commits](https://www.conventionalcommits.org/):
  ```
  feat: add dark mode toggle
  fix: correct off-by-one error in pagination
  docs: update setup instructions
  ```
- Keep commits focused — one logical change per commit is easier to review than one giant commit.

## Submitting a pull request

1. Push your branch to your fork and open a PR against `main`.
2. Fill out the PR template completely — link the issue it closes (`Closes #123`).
3. Make sure CI checks pass before requesting review.
4. A maintainer will review within [X days] — expect comments and requested changes; this is normal, not a rejection.
5. Once approved, a maintainer will merge it. Please don't merge your own PR unless explicitly told to.

## Code style

- [Linter/formatter used, e.g. "Run `npm run lint` before committing"]
- [Any naming conventions, folder structure rules]
- Add or update tests for any behavior change.
- Update documentation/README if your change affects usage.

## Questions?

Ask in [Discussions](https://github.com/orgs/open-source-club-alpha/discussions) or reach out to a maintainer directly. Don't hesitate — every contributor was new once.
