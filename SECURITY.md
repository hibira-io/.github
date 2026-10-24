# Security Policy

We take the security of Hibira and its SDKs seriously, and we appreciate
reports from the security community.

## Reporting a vulnerability

**Please do not report security issues in public GitHub issues, discussions or
pull requests.**

Email **security@hibira.io** with:

- the affected product (the hosted service at hibira.io, or which SDK and version),
- a description of the issue and its impact,
- steps to reproduce or a proof of concept,
- your name or handle if you'd like to be credited.

You can also use GitHub's
[private vulnerability reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability)
on an SDK repository where it is enabled.

## What to expect

- We acknowledge your report within **3 business days**.
- We send an initial assessment within **10 business days**, and keep you
  updated until the issue is fixed.
- We coordinate the disclosure date with you and credit you in the release
  notes or advisory unless you'd rather stay anonymous.

## Scope

In scope: the hosted service on `hibira.io` and its subdomains (and the
legacy `hikibi.io` domain, which still serves existing apps), and the code
in the public repositories of the
[hibira-io](https://github.com/hibira-io) organization.

Out of scope: denial-of-service and load testing, social engineering,
physical attacks, spam, reports from automated scanners without a working
proof of concept, and issues in third-party services we use.

## Safe harbor

We won't take legal action against good-faith research that follows this
policy: test only against your own accounts and apps, don't access or change
other people's data, don't degrade the service, and give us reasonable time
to fix the issue before you disclose it.

## Supported versions

Security fixes go into the latest release of each SDK. Please upgrade to the
latest version before reporting an issue in an SDK.
