# Security Policy

This policy covers every repository in the [steerspec-hub](https://github.com/steerspec-hub)
organization unless that repository ships a `SECURITY.md` of its own.

## Supported versions

Only the latest release of each realm receives fixes. A realm is pinned by tag, so a fix ships as a
new release; older releases are not changed.

## Reporting a vulnerability

**Do not open a public issue, discussion, or pull request for a security problem.**

Report it privately through GitHub: on the affected repository, go to **Security → Report a
vulnerability**, or use the `/security/advisories/new` path directly. That form is private to you
and the maintainers, and it is the only channel we monitor for security reports.

Include the affected repository and release, the impact, and the smallest set of steps that
reproduces the problem.

## What happens next

- We aim to acknowledge a report within five working days.
- If it is confirmed, we work the fix on a private fork and keep you updated through the advisory
  thread.
- Disclosure is coordinated: we publish a GitHub Security Advisory alongside the release that
  contains the fix, and credit the reporter unless they ask us not to.
- If we conclude a report is not a vulnerability, we explain why in the same thread rather than
  closing it silently.

## Scope

**In scope** — anything that lets a consumer of a realm be misled or compromised: a published realm
whose content does not match the standard's release it claims to come from, a generator or CI
workflow that untrusted pull request content can influence, a token or secret disclosed in logs or
outputs, or a supply-chain issue in what these repositories publish.

**Out of scope** — the content of a standard itself. A requirement you believe is wrong belongs
with the standard's authors (for OWASP ASVS, [OWASP/ASVS](https://github.com/OWASP/ASVS)). Problems
in the SteerSpec tooling belong with [SteerSpec](https://github.com/SteerSpec/.github/blob/main/SECURITY.md).
