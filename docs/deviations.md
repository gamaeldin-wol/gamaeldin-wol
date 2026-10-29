# Deviations from the engineering standard

Governed by a private engineering standard. Profile: `artifact-repo`, version v1.2.

This repository is a public page governed by a standard that is not published. The
waivers are recorded here so the reasons stay readable; the rule identifiers are
left out on purpose.

| Area | Scope | Why | Approved | Expires | Revisit if |
| --- | --- | --- | --- | --- | --- |
| Declaration lives here | `README.md` | This README is a public, recruiter-facing profile page, not software documentation. A standards section would put process noise on the one page a hiring manager reads, and the page cannot link to an unpublished standard. The declaration lives in this file instead | 2026-10-29 | permanent, while the page is public-facing | The profile becomes a project README, or the standard is published |
| Page shape | `README.md` | The four-section documentation template (what, how to run, how to verify, what it does not do) describes software. A profile page answers who, what, and how to reach the person | 2026-10-29 | permanent, while the page is a profile | The repository gains code |

## Not applicable

The code-facing rules of the standard do not apply, and this is recorded rather than
left to a reader to guess: the repository has no executable code, no service
surface, no schema or migrations, no external calls, no test tier, and no container.
What remains is the failure-mode table in `docs/failure-modes.md`.

## Rules

- A waiver without an expiry must justify why it is permanent.
- Expiry is a date, not "later". An expired waiver is a defect.
- Waivers are reviewed with the standard, quarterly.
