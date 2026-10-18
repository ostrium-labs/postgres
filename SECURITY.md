# Security Policy

This repository is Loams Postgres' fork of PostgreSQL. It is maintained as part of Loams Postgres
(`ostrium-labs/loams-postgres`) and follows
[Loams' security policy](https://github.com/ostrium-labs/loams/security/policy).

## Reporting a vulnerability

**Please do not report security vulnerabilities in public issues, pull
requests or discussions.**

Report them privately through GitHub's private vulnerability reporting:
open this repository's **Security** tab and choose **Report a vulnerability**
([direct link](https://github.com/ostrium-labs/postgres/security/advisories/new)).
Only you and the maintainers can see the report.

If you cannot use GitHub, email **security@ostriumlabs.org**.

We acknowledge a report within **3 business days**, keep you updated while we
investigate, agree on a disclosure timeline with you, and credit you in the
advisory unless you ask us not to.

## What to report where

- **A vulnerability in PostgreSQL itself:** report it to the PostgreSQL
  Security Team, as https://www.postgresql.org/support/security/ says
  (security@postgresql.org). We take PostgreSQL's security releases into the
  `loams/REL_<N>_STABLE` branches.
- **A vulnerability in a change this fork makes to PostgreSQL** (Neon's
  patches on the `REL_<N>_STABLE_neon` history, or ours on `loams/*`):
  report it to us as above. Neon does not maintain these branches for us.

The branches we maintain are `loams/*`. `REL_<N>_STABLE_neon` is frozen
history and gets no fixes.
