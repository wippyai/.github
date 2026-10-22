# Contributing to Wippy

Contributions to Wippy repositories include code, documentation, tests, and
reproducible issue reports. This guide applies to every repository in the
wippyai organization that has no CONTRIBUTING.md of its own; a repository's own
guide takes precedence.

## Before you start

Check existing issues before opening a new one. Use an issue to discuss
substantial behavior or API changes before implementing them. Report
vulnerabilities privately through the affected repository's
**Security → Report a vulnerability** form, never in a public issue.

## Developer Certificate of Origin

Wippy open source repositories accept contributions under the
[Developer Certificate of Origin 1.1](https://github.com/wippyai/.github/blob/main/DCO.md)
and the license of the repository you contribute to. No contributor license
agreement is required.

Certify the DCO by adding a `Signed-off-by` trailer to every commit, using your
real name and an email address you control:

```sh
git commit -s -m "fix: handle an empty result"
```

This appends:

```text
Signed-off-by: Jane Developer <jane@example.com>
```

The DCO check fails a pull request when any commit lacks a sign-off. To sign off
commits already on your branch, run `git rebase --signoff <base>` and
force-push the branch.

## Development

Fork the repository and create a focused branch for your change. Read the
repository README first; its Makefile and CI workflows define the supported
commands and tool versions. Keep credentials and local runtime state out of Git,
and preserve existing license headers and third-party notices.

Add tests for behavior changes and run the repository's build, lint, and test
targets before opening a pull request. CI must pass before merge.

## Pull requests

1. Keep commits focused. Use a short imperative subject with a prefix such as
   `docs: clarify setup`, `fix: handle empty records`, or `feat: add a module`.
2. Describe the problem, the resulting behavior, linked issues, and the commands
   you ran with their results, including checks you could not run.
3. Address maintainer feedback and keep the branch current with its target.
   Maintainers approve and merge.

## Help

For licensing or contribution questions, email
[licensing@wippy.ai](mailto:licensing@wippy.ai).
