# 01.AI (01-ai)

01.AI, founded by Kai-Fu Lee, is the creator of the Yi family of open-source and proprietary LLMs. The Lingyiwanwu open platform exposes OpenAI-compatible inference for Yi-Lightning, Yi-Lightning-Lite, Yi-Large, Yi-Large-Turbo, and Yi-Vision.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/01-ai/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=01-ai-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## Tags
- AI, LLM, Yi, Open Source, Foundation Models, Inference

## APIs
- **Lingyiwanwu Platform API** — OpenAI-compatible chat completions and vision. Base URL `https://api.lingyiwanwu.com/v1`. [Docs](https://platform.lingyiwanwu.com/docs) · [GitHub](https://github.com/01-ai/Yi)

### Models
Proprietary: Yi-Lightning, Yi-Lightning-Lite, Yi-Large, Yi-Large-Turbo, Yi-Vision. Open-weights: Yi-34B, Yi-9B, Yi-6B (Yi license).

## Plans, Rate Limits, FinOps
- [Plans](plans/01-ai-plans-pricing.yml) — PAYG per-token (Yi-Lightning ~$0.14/M); free open-weight self-hosting.
- [RateLimits](rate-limits/01-ai-rate-limits.yml) — Tiered on the platform console (English docs limited).
- [FinOps](finops/01-ai-finops.yml) — FOCUS-aligned usage-based prepaid recharge.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://www.01.ai/)
- [Documentation](https://platform.lingyiwanwu.com/docs)
- [GitHub](https://github.com/01-ai)

## Notes
- 01.AI's English-language API documentation is limited; the Lingyiwanwu console is the canonical source.
- No public OpenAPI specification was discovered at the time of profiling.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
