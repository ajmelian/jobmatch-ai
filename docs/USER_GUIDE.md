# JobMatch AI — User Guide / Manual de uso

[English README](../README.md) · [README en español](../README.es.md)

## 1. Choose a version / Elige una versión

- [v1.2.0 — Original](../prompts/PROMPT_MAESTRO_JOB_MATCH_ANALYZER_v1.2.0.md): historic Spanish baseline, preserved.
- [v1.3.0 — Candidate-neutral draft](../prompts/JOBMATCH_MASTER_v1.3.0.md): public parametrized instructions, **under review** in [PR #1](https://github.com/ajmelian/jobmatch-ai/pull/1).

Both are instructions for an LLM, **not** stand-alone executable software.

## 2. Prepare inputs / Prepara las entradas

For v1.3.0 provide:

| Field | Meaning | Required |
|---|---|---|
| `{{CV_MAESTRO}}` | Up-to-date CV text or accessible file / CV maestro | Yes |
| `{{OFERTA}}` | Full job description or accessible URL / oferta | Yes |
| `{{IDIOMA_SALIDA}}` | Response language / idioma | Optional |
| `{{REGION}}` | Market / country, if known / región | Optional |
| `{{PREFERENCIAS}}` | Confirmed work preferences / preferencias | Optional |
| `{{EVIDENCIAS_ADICIONALES}}` | Verifiable clarifications / evidencias | Optional |

Supply the actual CV and job advertisement as session data. Placeholder labels are not evidence. If browsing is unavailable, **paste the offer text**. Never infer requirements from a broken URL.

## 3. Minimal fictional example / Ejemplo ficticio

```text
Usa JobMatch AI v1.3.0.
IDIOMA_SALIDA: Español
REGION: España
OFERTA: "Backend: PHP o Go obligatorio; SQL deseable; remoto."
CV_MAESTRO: "Perfil ficticio con dos años desarrollando API REST en PHP y SQL."
Primero presenta el análisis; no generes el CV adaptado sin mi aprobación.
```

## 4. Follow the review / Revisa el análisis

1. Check requirement extraction and whether alternatives (`A or B`) were interpreted correctly.
2. Inspect the evidence register, uncertain claims and stated exclusions.
3. Treat professional fit and ATS-document fit as **independent heuristic estimates**.
4. Answer clarification questions only with verifiable facts.
5. Decide separately whether to authorize CV adaptation.
6. Verify the generated document and every factual claim yourself.

## 5. Tool capabilities / Limitaciones técnicas

URL retrieval, editable-file writes, CV export, PDF rendering, text extraction and link validation depend on the assistant's environment. If unavailable, the model must say so. Do not interpret a verbal claim of persistence or file validation as proof.

## 6. Privacy, evaluation and licensing

Avoid exposing real CVs in public code or issue threads. Read [security guidance](SECURITY.md), [methodology](METHODOLOGY.md) and [synthetic examples](../examples/README.md). The examples describe expected behavior, not verified benchmark performance.

Original project prompts and documentation are **CC BY-NC 4.0**; commercial uses not covered by the license require separate permission. See [license](../LICENSE.md) and [commercial terms](../COMMERCIAL-LICENSING.md).
