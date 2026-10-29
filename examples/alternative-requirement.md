# Synthetic fixture 01 — Alternative requirement

**Status:** specification of expected behavior, **not executed**. All data is fictional.

## Job advertisement

> Backend engineer. Mandatory: professional experience using **PHP or Go**. SQL knowledge is desirable. Remote work available.

## Candidate evidence

> Fictional candidate with two years implementing PHP REST APIs and SQL queries. No evidence supplied about Go.

## Evaluation task

Apply the [v1.3.0 master prompt](../prompts/JOBMATCH_MASTER_v1.3.0.md). Provide the requirement matrix and explain eligibility and internal professional/document fit without asserting real ATS performance.

## Expected invariants

- `PHP or Go` is a **disjunction**: documented PHP experience can satisfy the mandatory alternative.
- Do **not** claim Go is a mandatory missing skill.
- Do not invent additional tenure, employers, languages or certifications.
- SQL is supported as desirable, not promoted to a separate mandatory criterion.
- Report unknown information as unknown; score methodology must be explainable.

## Record of execution

**Not executed.** No model version, transcript, trial count or pass/fail result is available.

[Fixture index](README.md) · [Methodology](../docs/METHODOLOGY.md).
