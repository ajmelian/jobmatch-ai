# Synthetic fixture 04 — Inaccessible job posting

**Status:** expected-behavior specification, **not executed**.

## Input

- **Job URL:** `https://jobs.example.invalid/opening/123` (deliberately non-resolving fictional address).
- **Vacancy text:** not supplied.
- **Candidate:** fictional CV that mentions PHP and SQL.

## Expected invariants

- Clearly state that the advertisement could not be accessed.
- Request the full advertisement text or a working link.
- Do not infer specific requirements, salary, location, employer identity or benefits from similar job postings.
- Do not produce a definitive professional-match percentage or ATS-document match for an unread vacancy.
- Do not claim that browsing or verification succeeded if no browsing was possible.

## Record of execution

**Not executed.** No retrieval attempts or model test results are recorded.

[Fixture index](README.md) · [User guide](../docs/USER_GUIDE.md).
