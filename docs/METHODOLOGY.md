# JobMatch AI — Methodology / Metodología

**Applies to:** [master prompt v1.3.0](../prompts/JOBMATCH_MASTER_v1.3.0.md) · [original v1.2.0](../prompts/PROMPT_MAESTRO_JOB_MATCH_ANALYZER_v1.2.0.md)

## 1. Evidence and coverage

The source CV, verifiable candidate clarifications and documents actually examined take priority over model assumptions. Do not transfer facts between candidates or infer missing credentials.

| Evidence state | Reference coverage |
|---|---:|
| Acreditado / supported | 100% |
| Equivalente / equivalent | 75% |
| Parcial / partial | 40% |
| No acreditado / unverified | 0% |
| Incompatible / incompatible | 0% |

These are **specified heuristics** rather than externally calibrated measurements. Any justified exception must be explicit. Unverified does not necessarily mean the person lacks the skill.

## 2. Professional fit dimensions

| Dimension | Weight |
|---|---:|
| Mandatory technical knowledge | 30% |
| Experience and seniority | 20% |
| Architecture, methods and quality | 15% |
| Functional responsibilities | 15% |
| Complementary requirements | 10% |
| Languages and communication | 5% |
| Training and certifications | 5% |
| **Total** | **100%** |

Classify each vacancy requirement before assessing evidence. Interpret `A or B` as a genuine alternative unless the posting explicitly requires both. Explain any redistribution of non-applicable categories. Do not conceal missing non-negotiable criteria within a favorable average.

## 3. ATS-document compatibility is separate

```text
estimated_ats_document_fit =
    0.85 × semantic_fit + 0.15 × structural_readability
```

The semantic dimension is specified as requirements/terms (25%), evidence in context (25%), role/history clarity (20%), correct vacancy terminology (20%) and verifiable projects/references (10%). These internal weights do **not** reproduce a vendor's proprietary algorithm.

Formatting or keyword changes can improve an internal document estimate, **not** professional fit without new evidence. An inaccessible vacancy is insufficient for a definitive match score.

## 4. Provenance and quality gates

- **Claim gate:** no employer, certification, achievement, tool or tenure without defensible evidence.
- **Review gate:** highlight uncertainty, alternatives and exclusions; no false precision about actual hiring chances.
- **Authorization gate:** do not create a tailored CV without explicit permission.
- **Persistence gate:** claim saved or updated files only after successful write and inspection.
- **Deliverable gate:** verify factual content, extractable text, layout and links *if supported*; disclose missing checks.

## 5. Evaluation protocol (not yet executed)

To evaluate reliability: pin the exact prompt revision, model name/version, date, settings, input fixture and expected invariants; save actual outputs with sensitive content removed; have a reviewer mark pass/fail with evidence and repeat for stability. Record failures, disagreements and corrections. The four [fixtures](../examples/README.md) define **expected results** only; no measured pass rate exists.

**Important:** neither professional-fit nor ATS-document values are empirical hiring probabilities, employer ATS results, or independently validated predictions.
