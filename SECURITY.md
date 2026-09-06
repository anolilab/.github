# Security Policy

This policy applies to every anolilab repository that does not ship its own `SECURITY.md`.

## Reporting a vulnerability

**Email `security@anolilab.de`** with as much detail as you can share. PGP / encrypted mail is welcome — request a key in your first message if you'd like to use one.

Alternatively, open a private security advisory on the affected repository (Security → Advisories → Report a vulnerability). **Do not** open a public issue or discussion for security problems.

Useful things to include:

-   A clear description of the vulnerability and the affected repository, package and version.
-   Reproduction steps — a minimal repro, proof-of-concept script, or command invocation is ideal.
-   Impact assessment as you see it (data exposure, RCE, privilege escalation, auth bypass, DoS, …).
-   The commit SHA or released version you tested against.
-   Your name or handle if you'd like public credit once the issue is fixed.

## What to expect from us

-   **Acknowledgement within 72 hours** of receipt.
-   A coordinated disclosure timeline negotiated with you. Default target: a fix published within 30 days of confirmation for high-severity issues; longer is fine if the bug is low-severity or hard to reproduce.
-   Credit in the release notes, unless you prefer to stay anonymous.
-   No legal action against good-faith research that follows this policy.

## Supported versions

Security fixes are published for the **latest released major version** of each package. Older majors are not patched — upgrade to the current major to receive fixes.

## Scope

In scope: code in anolilab repositories and the packages published from them, including their build and release pipelines.

Out of scope: vulnerabilities in upstream dependencies (report them to that dependency's maintainers — if one materially affects our software, we handle the coordinated upgrade), and findings that require a compromised local machine or physical access.
