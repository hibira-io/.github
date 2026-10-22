# Contributing to Hikibi SDKs

Thanks for helping improve the Hikibi 響 client SDKs. This guide applies to
every public repository in the [hikibi-io](https://github.com/hikibi-io)
organization unless the repository has its own `CONTRIBUTING.md`.

Issues and pull requests here are about the SDKs. For problems with your account, billing or the hosted
service, see [SUPPORT.md](SUPPORT.md).

## Reporting bugs

1. Search the existing issues first.
2. Open a new issue with the **Bug report** form and include the SDK version,
   platform and OS version, what you expected and what happened.
3. Add the smallest code sample or project that reproduces it, and logs with
   timestamps if you have them.

**Never post secrets.** Remove app secrets, API keys, auth tokens, device
tokens and user data from code, logs and screenshots before you post them.

Security issues must not be reported in public issues. Follow
[SECURITY.md](SECURITY.md) instead.

## Suggesting features

Open an issue with the **Feature request** form. Describe the problem you
want to solve before the solution you have in mind. For larger changes,
please wait for a maintainer to agree on the approach before you write code.

## Pull requests

1. Fork the repository and branch from the default branch.
2. Keep each pull request to one change, with a clear description and a link
   to the issue it fixes.
3. Add or update tests for the behaviour you change, and make sure the
   existing tests and linters pass.
4. Update the README or docs when you change public API or behaviour.
5. Keep public APIs compatible where possible. If a change breaks them, say so
   in the pull request.

Maintainers review pull requests as time allows. We may ask for changes, or
decline a change that doesn't fit the SDK's direction; we'll explain why.

## Licensing

The SDKs are released under the license in each repository (MIT for the push
SDKs, which are forks of the Pusher Beams client SDKs). By submitting a pull
request you agree that your contribution is licensed under that repository's
license. Keep existing copyright and license notices intact.

## Code of conduct

Everyone taking part is expected to follow our
[Code of Conduct](CODE_OF_CONDUCT.md).
