# JobMatch AI v1.3.0 — Release Notes / Notas de versión

**Status:** proposed candidate-neutral specification in [Draft PR #1](https://github.com/ajmelian/jobmatch-ai/pull/1), **not merged into `main`**.

## Changes / Cambios

- A parametrized session contract for CV, vacancy, response language, region, preferences and optional evidence.
- Rules to avoid transferring candidate facts between independent sessions.
- Clarification that six review perspectives are simulated by a single model, not separately executing agents.
- Explicit prohibition on protected-attribute scoring and automated hiring decisions.
- Architecture, methodology, security and operational documentation.
- Four synthetic scenarios with expected observable invariants.
- Bilingual README and usage example.
- CC BY-NC 4.0 license references and separate commercial licensing information.

## Compatibility and boundaries

The v1.2.0 master prompt remains published unchanged as a historical baseline. The v1.3.0 file is a derivative *draft*, not a validated replacement. Prompt-based safeguards do not guarantee compliance, real ATS scores, PDF quality or file persistence.

## Acceptance checklist

- [x] Preserve the v1.2.0 original.
- [x] Publish a candidate-neutral v1.3.0 draft on a review branch.
- [x] Explain architecture, scoring boundaries and responsible use.
- [x] Provide reproducible *input fixtures and expectations*.
- [x] Update English and Spanish README documents and usage guide.
- [ ] Review the entire v1.3.0 prompt for remaining personal assumptions and inconsistent statements.
- [ ] Execute fixture tests across specified model versions, save outputs and record independent reviews.
- [ ] Verify all document links and perform editorial / licensing review.
- [ ] Merge and tag only after the intended review criteria are met.

**No benchmark results or measured hiring outcomes are claimed.**
