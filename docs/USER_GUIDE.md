# JobMatch AI — Usage guide / Guía de uso

## Inputs / Entradas

- A complete job advertisement (preferably its full text, or an accessible public URL).
- A current master CV in structured Markdown.
- Optional factual clarifications and technical artifacts that can actually be examined.

Do **not** supply credentials, sensitive identifiers, confidential employer documents or other material you lack permission to process.

## Workflow / Flujo

1. Read the full offer and master CV.
2. Extract and classify requirements, distinguishing explicit conditions from inferred ones.
3. Map each requirement to a source and to an evidence status.
4. Calculate separate, documented estimates for professional fit and ATS-document compatibility.
5. Detect material uncertainties and ask targeted questions; do not treat silence as confirmation.
6. Incorporate confirmed facts into the source CV only when the file can actually be saved and verified.
7. Present the critical analysis and request **separate permission** to generate an adapted CV.
8. For generated files, inspect extracted text, layout, links and factual claims before declaring them ready.

## Limitations / Limitaciones

The scores are **internal heuristic assessments**, not real employer ATS scores or probabilities of being hired. The six roles are analytical perspectives simulated in one model, not independently running agents. The instruction set does not guarantee model compliance, factual correctness, actual file persistence or ATS compatibility. The operator must verify every external claim and final document.

Los porcentajes son estimaciones internas, no predicciones de contratación. El prompt no garantiza que un modelo cumpla las instrucciones ni que tenga herramientas para navegar, guardar o validar archivos. Toda salida requiere comprobación humana.

## Privacy / Privacidad

Test with synthetic CVs and fictional job advertisements in public issues and examples. Protect personal data and respect your chosen LLM provider's retention and processing policies.
