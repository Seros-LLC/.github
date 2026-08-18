# Contributing to Seros projects

Thanks for taking the time. This file applies to every repository in the
[Seros-LLC](https://github.com/Seros-LLC) organisation unless a repository overrides it.

## Before you write code

- **Open an issue first** for anything larger than a typo. Describe the problem, not only
  the fix you have in mind. We would rather agree on the problem than argue about a patch.
- **Check the scope.** Seros is a small team building a focused product. A change that adds
  a dependency, a service, or a configuration surface needs a reason that survives a year.

## Working agreement

| Rule | Why |
|---|---|
| One logical change per pull request | Reviewable, revertible |
| Tests with behaviour changes | We only trust what runs |
| No secrets, keys, tokens, customer data, or real personal data in commits, fixtures, or screenshots | Non-negotiable |
| Conventional commit subjects (`feat:`, `fix:`, `docs:`, `chore:`, `refactor:`, `test:`) | Readable history and changelogs |
| Keep the public surface documented | Undocumented behaviour becomes accidental API |

## Pull requests

1. Fork or branch: `feat/short-description`.
2. Make the change, add or update tests, run the repository's checks locally.
3. Fill in the pull request template: what changed, why, how it was verified, risk.
4. Expect review comments. They are about the code.

CI must be green before merge. A green run is not proof a deploy job ran — check the
per-job conclusions if the pull request touches deployment.

## Reporting bugs and requesting features

Use the issue templates. A bug report without reproduction steps and expected-versus-actual
behaviour will usually be closed with a request for those things.

## Security issues

Do not open an issue. See [SECURITY.md](SECURITY.md) and email security@seros.dev.

## Licence and ownership of contributions

Unless a repository states otherwise, contributions are made under that repository's
licence, and you confirm you have the right to contribute the work. Contributions to
private Seros repositories by contractors or employees are governed by the signed
agreement with Seros, LLC, not by this file.

## Conduct

Everything here is subject to the [Code of Conduct](CODE_OF_CONDUCT.md).
