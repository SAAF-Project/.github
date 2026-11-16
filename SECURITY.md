# Security policy

This is the vulnerability disclosure policy of Stichting SAAF for every repository in the SAAF-Project organisation that has no `SECURITY.md` of its own. We follow coordinated vulnerability disclosure: you report a weakness to us privately, we fix it, and we publish it together.

## Reporting a weakness

Please do not open a public issue for a security problem.

- Preferred: use GitHub private vulnerability reporting on the repository concerned (Security tab, "Report a vulnerability").
- Or mail info@saafproject.com.

Tell us what you found, where it is (repository, file, endpoint or commit), how to reproduce it and what impact you expect.

## What we ask of you

- Report as soon as you can, and only to us, until it is fixed or 90 days have passed.
- Do no more than is needed to show the weakness. Do not read, change or delete data that is not yours.
- Work on a local copy, with synthetic data. No attacks on live systems, no denial of service, no social engineering.
- Do not use keys you find. Report them, and do not put live keys, secret values or personal data in the report.

## What you can expect from us

| Step | When |
|---|---|
| We confirm that we received your report | within 2 days |
| A first assessment | within 10 days |
| An update on progress | every 14 days until it is closed |
| Public disclosure, together with you | once it is fixed, and after 90 days at the latest |

- We treat your report in confidence and do not share your personal details without your consent.
- We name you as the finder in the fix or the advisory, if you want that.
- If you follow this policy, we will not take legal action against you for your report.
- There is no financial reward.

## Scope

In scope: the code and configuration in the repositories of the SAAF-Project organisation, on their default branch (for example `main` or `master`).

Out of scope: third-party services an agent calls, findings that need real audit evidence or personal data to reproduce, and anything that requires an attack on a live system.

## Owner

Stichting SAAF, info@saafproject.com. The owner named in a repository's `CODEOWNERS` handles reports for that repository. This policy is reviewed every quarter.
