## Commit Messages

We must adhere as closely as possible to the [conventional commits specification](https://www.conventionalcommits.org/en/v1.0.0/).
The following convention encourages commit best-practices and facilitates commit-powered features like changelog generation.

The following commit prefixes are supported:

- `build:`, a change that affects the build system or external dependencies
- `chore:`, project housekeeping
- `ci:`, a change that affects CI
- `docs:`, a documentation update
- `feat:`, a new feature
- `fix:`, a bugfix
- `perf:`, project performance
- `refactor:`, refactor of the code without change in functionality
- `release:`, release of a new version
- `revert:`, revert a previous change
- `test:`, a test update

Below are examples of well-formatted commits:

```txt
build(deps): update xyz dependency/library
feat(call-log): add call duration to log
fix(auth): handle password validation error
docs: fix link to website page
test(user): add test for update phone number
ci(actions): edit xyz workflow to do abc
```

## Creating Pull Requests

Use a "conventional commits" formatted title for the PR, as this title will be used as the default commit message on the squashed commit after merging.

See the [Commit Messages](#commit-messages) about conventional commit format.

We are using [action-semantic-pull-request](https://github.com/amannn/action-semantic-pull-request) to lint the titles of pull requests. If the 'Lint Pull Request Titles' workflow fails, please correct the title.
