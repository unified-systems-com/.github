# Security Policy

This is the default security policy for repositories in the
`unified-systems-com` organization — TAP core and the TAP plugins we maintain.
A repository with its own `SECURITY.md`, such as
[TAP core](https://github.com/unified-systems-com/tap/blob/main/SECURITY.md),
extends this policy with repo-specific scope; the reporting process below is
the same everywhere.

## Reporting a vulnerability

Report vulnerabilities privately through GitHub's private vulnerability
reporting on the **affected repository** — the "Report a vulnerability" button
under that repository's **Security** tab. If you are unsure which repository
is affected, report against
[unified-systems-com/tap](https://github.com/unified-systems-com/tap/security/advisories/new).

**Please do not open a public issue for a suspected vulnerability.**

## What to expect

- Acknowledgment within 7 days.
- Initial assessment within 14 days.
- We follow coordinated disclosure: we ask for a reasonable window (90 days is
  a fine default) before public disclosure. When a fix ships we publish a
  GitHub security advisory, credit the reporter (unless you prefer anonymity),
  and request a CVE where warranted.

Repositories outside this organization — including third-party TAP plugins —
are out of scope; report those to their maintainers.

There is no bug bounty program at this time.
