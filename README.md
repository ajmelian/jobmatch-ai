# JobMatch AI

**Evidence-driven job matching and CV optimization using Generative AI.**

JobMatch AI is an authored, structured **prompt-engineering methodology** for analysing technology job openings against a candidate's verified professional profile. It separates professional fit from estimated ATS-document fit, tracks evidence provenance, identifies uncertainty and controls factual accuracy when preparing a tailored CV.

**Author:** Aythami Melián Perdomo · [GitHub](https://github.com/ajmelian) · [LinkedIn](https://www.linkedin.com/in/aythami-melian/)

[Documentación en español](README.es.md) · [Usage guide](docs/USER_GUIDE.md) · [License](LICENSE.md)

## Why this project?

Generic CV-tailoring prompts can conflate missing documentation with missing skills, inflate ATS scores or fabricate credentials. JobMatch AI specifies a critical, reviewable workflow that prioritizes source evidence and responsible human oversight.

## Designed capabilities

- Six distinct **review perspectives** simulated within a single assistant; this is **not** a deployed multi-agent system.
- Structured classification of mandatory, preferred, implicit and disqualifying job requirements.
- Evidence register with provenance controls, uncertainty markers and factual vetoes.
- Weighted professional-fit assessment, a separately estimated document/ATS score and an eligibility assessment.
- Requirement-to-evidence traceability, risks, strengths and recruiter/engineering-manager reviews.
- Human-confirmed enrichment of the source résumé, with persistence verified only when files are actually saved.
- Separate consent before generating a tailored CV.
- Factual, editorial, document-extraction, visual-layout and hyperlink quality gates.

## Status

**Specification version: 1.2.0 (2026-10-28).** This repository documents a prompt-based workflow. It does **not** claim tested accuracy across LLM providers, integration with employer ATS products, autonomous multi-agent execution, validated hiring predictions or commercial deployment. Reproducible evaluation fixtures and model testing are planned.

The authoritative Spanish master prompt will be published under `prompts/`. Keep the original v1.2.0 unchanged when publishing; a candidate-neutral edition can follow as v1.3.0.

## Quick start

1. Open the master prompt from `prompts/` once it is available.
2. Supply the complete job advertisement or public URL, plus an up-to-date master CV in Markdown.
3. Provide verifiable evidence or clarifications as needed.
4. Review provisional findings before approving any changes to your CV.
5. Explicitly authorize adapted-CV generation; independently check all final claims.

See [Usage guide](docs/USER_GUIDE.md) for limitations and data-protection precautions.

## License

The original prompt and repository documentation are distributed under **CC BY-NC 4.0**. Attribution is required; the license does not authorize commercial use of licensed materials. [Full terms](LICENSE.md) · [Commercial licensing](COMMERCIAL-LICENSING.md).

Copyright © 2026 Aythami Melián Perdomo.
