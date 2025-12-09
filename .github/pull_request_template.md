## PR Title

<!-- Put an 'x' in the box if true -->

- [ ] The PR title follows the [conventional commits](https://github.com/Lifeforce-Digital/.github/blob/development/.github/CONTRIBUTING.md) format. e.g.

```
feat(account): add profile picture upload button and functionality
^      ^        ^
|      |        |__ Subject
|      |_______ Scope (optional) e.g. the feature/domain/section affected
|__________ Type
```
`Type` can be one of `build`, `chore`, `ci`, `docs`, `feat`, `fix`, `perf`, `refactor`, `release`, `revert`, `test`

> Use **lowercase** for `Type` and `Scope` values.
>
> First char of `Subject` value must be **lowercase)).
> 
> If it's a BREAKING CHANGE add a `!` after the type/scope e.g. `feat(sms)!: replace twilio with telnyx for SMS`

Below are examples of well-formatted commits:

```txt
build(deps): update xyz dependency/library
feat(call-log): add call duration to log
fix(auth): handle password validation error
docs: fix link to website page
test(user): add test for update phone number
ci(actions): edit xyz workflow to do abc
```

## Types of changes

<!--- What types of changes does your code introduce? Put an `x` in all the boxes that apply: -->

- [ ] Bug `fix` (non-breaking change which fixes an issue)
- [ ] New `feat` (non-breaking change which adds functionality)
- [ ] Breaking change (`fix(scope)!` or `feat(scope)!` that would cause existing functionality to change)
- [ ] Does NOT change the functionality of code e.g. `docs`, `build`, `refactor`

## Checklist:

<!--- Go over all the following points, and put an `x` in all the boxes that apply. See the README for information on testing. -->
<!--- If you're unsure about any of these, don't hesitate to ask. We're here to help! -->

- [ ] My change requires a change to the documentation.
- [ ] I have updated the documentation accordingly.
- [ ] I have added tests to cover my changes.
- [ ] All new and existing tests passed.
