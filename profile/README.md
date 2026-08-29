# ADARA AI LAB

**Teaching AI to understand Africa in its languages, its logic, and its lived reality.**

We build data, models, evaluation, and developer infrastructure so AI systems work for African languages, speech, and context — not as an afterthought.

Website: [adaraai.vercel.app](https://adaraai.vercel.app) · Marketing site: [`adaraui`](https://github.com/AI-Factory-AI/adaraui)

## What we are building

| Layer | Repositories |
| --- | --- |
| Public site | `adaraui` |
| Platform (apps + services) | `adara-platform` |
| Models | `adara-ai` |
| Intelligence | `adara-speech` · `adara-language` · `adara-context` |
| Evaluation | `adara-evals` |
| Developers | `adara-sdk` · `adara-docs` |
| Research & data specs | `adara-research` · `adara-datasets` |
| Products | `adara-voice` (flagship) · `adara-trader` · `adara-agri` · `adara-education` |
| Cloud | `adara-infrastructure` |

Most of this is **foundation**, not production AI. Status lives in each README.

## Research areas

- African language understanding, translation, morphology, dialects
- Speech (ASR/TTS), accents, code-switching
- Cultural and commercial context
- Evaluation and safety for African settings
- Consent-first data governance

## Open source vs proprietary

Public by default: evaluation tooling, SDK, docs, speech/language interfaces, research scaffolding.

Private: platform, model training ops, infrastructure, flagship products, strategic context engine internals.

Datasets are **never** dumped into Git. Cards, schemas, and licenses live in `adara-datasets`.

## Developer ecosystem

```
DATA → AI → INTELLIGENCE → PLATFORM API → SDK → PRODUCTS
```

Products call the ADARA API. They do not query other teams' databases.

## Data ethics

Publicly accessible is not the same as free to use. Collection requires consent, attribution, licensing, and a path to community benefit. See `adara-platform/docs/data-governance/`.

## How to contribute

1. Read this profile and `adara-platform/ADARA-ARCHITECTURE.md`
2. Open an issue with the right `type:` / `area:` labels
3. Follow Conventional Commits and the repo CONTRIBUTING.md

Questions: info@adara.ai
