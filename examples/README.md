# Synthetic evaluation examples

All fixtures must be invented, anonymous and free from personal information. They illustrate expected decisions but do **not** demonstrate measured LLM reliability.

| Scenario | Expected invariant |
|---|---|
| `alternative-requirement.md` | “PHP or Go” requires one of the alternatives, not both |
| `unsupported-credential.md` | An invented professional credential is blocked |
| `editorial-only-improvement.md` | Styling may change ATS-document fit, not real professional fit |
| `inaccessible-offer.md` | Missing offer text triggers a request, not invented requirements |

Recommended report for each model evaluation: exact model and date, instructions, fixture, observed output, manual scoring, errors and retry count.
