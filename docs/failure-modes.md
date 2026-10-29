# Failure modes

A profile page has one job: every claim on it must still be true when a recruiter reads it.

| Symptom | Detection | Mitigation |
| --- | --- | --- |
| A badge or link is broken | Click it, or run a link check before publishing | Fix or remove it. A dead badge reads as neglect |
| A claim no longer matches the resume | Compare the two documents by hand | Update both; the README and `identity/resume` must not disagree on dates, titles, or skills |
| A private detail appears on the page | Read the diff before committing | Remove it. No phone number, address, private note, or roadmap material |
| The page renders badly on GitHub | Open the rendered preview, not the source | Fix the Markdown; tables and badges are the fragile parts |
| A project link points at a private repository | Open the link while signed out | Replace it with a public project or remove it |

## Escalation

If a claim cannot be verified, remove it rather than soften it.
