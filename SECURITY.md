# Security policy

## Reporting a vulnerability

Please **do not** open a public issue for a security problem.

Email **security@juntolabs.dev** with:

- the affected repository and version or commit,
- what the problem is and how to reproduce it,
- what an attacker could do with it, if you know.

We'll acknowledge your report within 3 business days and keep you updated until it's resolved. We're happy to credit you in the release notes unless you'd rather stay anonymous.

## Scope

Junto runs AI agents and holds credentials on their behalf, so we especially want to hear about:

- an agent getting write access or credentials it shouldn't have,
- a way around review or approval rules, including self-approval,
- an agent reading knowledge outside its granted scope,
- hidden instructions in outside text reaching an agent unfiltered,
- evidence or audit records that can be forged or altered.

## Supported versions

Junto is in early development. Only the latest commit on `main` of each repository is supported.
