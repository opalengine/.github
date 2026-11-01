# Contributing to Opal Engine

Thanks for helping. This applies to every Opal Engine repository that doesn't have its own
CONTRIBUTING file; where a repository has one, that one wins.

## How work flows

1. **Issues.** Bugs and feature requests start as issues, using the forms. Fill in the goal and
   the acceptance list: they become the work's definition of done.
2. **Triage.** The Opal software factory triages issues and grooms them into cards with a goal
   and a short list of checkable acceptance items. Maintainers decide what gets picked up.
3. **Delivery.** The factory delivers a picked-up card as a pull request. Automated agents author
   many of our pull requests. Every change, whoever wrote it, is held to the same checks and the
   same review before it merges.

You don't need to wait for the factory. Pull requests from people are welcome.

## Pull requests

- Fork the repository, branch from `main`, and open the pull request against `main`.
- Keep it small and focused: one change per pull request. Link the issue it closes.
- Run the project's own checks locally before you push. The repository's README says how.
- Add or update tests for any change in behaviour.
- Workflows on pull requests from forks need a maintainer's approval before they run, so CI may
  sit in "awaiting approval" for a while. That's expected.

## Sign off every commit (DCO)

Every commit needs a `Signed-off-by` line certifying the
[Developer Certificate of Origin](https://developercertificate.org/). Add it with:

```sh
git commit -s
```

The name and email must match the commit author. Pull requests with unsigned commits can't be
merged. To fix a branch: `git rebase --signoff main`, then force-push.

## Conduct and security

Everyone taking part follows the [Code of Conduct](CODE_OF_CONDUCT.md). Report security problems
privately as described in [SECURITY.md](SECURITY.md), never in a public issue.
