# Praveen Mittal

AI Solutions Architect / Senior AI Engineer — LLM orchestration, RAG, agentic systems, and production MLOps.

## Open Source Contributions

Real, merged fixes to production AI/ML open-source infrastructure — found via direct code audits, not the issue tracker.

| Project | Contribution |
|---|---|
| [xai-org/grok-build-plugin-cc](https://github.com/xai-org/grok-build-plugin-cc) | Fixed headless (non-interactive) plugin runs that could never get tool-call approval — [#12](https://github.com/xai-org/grok-build-plugin-cc/pull/12) |
| [mistralai/mistral-vibe](https://github.com/mistralai/mistral-vibe) | Fixed a CVSS 8.8 remote code execution vulnerability (git `core.fsmonitor` hook injection) — landed on `main` — [#962](https://github.com/mistralai/mistral-vibe/pull/962) |
| [deepset-ai/haystack](https://github.com/deepset-ai/haystack) | Fixed two `KeyError` crashes on `ByteStream` sources — attachment-metadata handling in `MSGToDocument` ([#12207](https://github.com/deepset-ai/haystack/pull/12207)) and error-path logging in `JSONConverter` ([#12208](https://github.com/deepset-ai/haystack/pull/12208)) |
| [deepset-ai/haystack-cookbook](https://github.com/deepset-ai/haystack-cookbook) | Audited 5 notebooks flagged by an org-wide maintainer pickup board and removed a genuinely-redundant `DocumentJoiner` after verifying the other 4 still needed it — [#309](https://github.com/deepset-ai/haystack-cookbook/pull/309) |
| [Meta's llama-stack](https://github.com/ogx-ai/ogx) (now independently governed as `ogx-ai/ogx`) | Fixed an indirect prompt-injection vulnerability via unsanitized tool output — [#6337](https://github.com/ogx-ai/ogx/pull/6337) |
| [alibaba/open-code-review](https://github.com/alibaba/open-code-review) | Added HCL/Terraform and Bicep language support — [#524](https://github.com/alibaba/open-code-review/pull/524), [#525](https://github.com/alibaba/open-code-review/pull/525) |
| [567-labs/instructor](https://github.com/567-labs/instructor) | Fixed an Anthropic tool-calling bug where forced single-tool requests didn't disable parallel tool use — consolidated into [#2495](https://github.com/567-labs/instructor/pull/2495) |
| [process-intelligence-solutions/pm4py](https://github.com/process-intelligence-solutions/pm4py) | Fixed a timezone-corrupting default-path bug in timestamp normalization — [#562](https://github.com/process-intelligence-solutions/pm4py/pull/562) |
| [deepset-ai/deepset-mcp-server](https://github.com/deepset-ai/deepset-mcp-server) | Fixed a lone top-level bracket index (`obj[0]`) breaking 5 object-store MCP tools with a misleading "no value at path" error — [#236](https://github.com/deepset-ai/deepset-mcp-server/pull/236) |
| [docling-project/docling](https://github.com/docling-project/docling) (IBM) | Fixed the METS/GBS backend crashing on a page with no OCR layer instead of marking it invalid, matching a sibling backend's existing graceful-degradation pattern — [#3930](https://github.com/docling-project/docling/pull/3930) |
| [cloudflare/workers-sdk](https://github.com/cloudflare/workers-sdk) | Fixed `caseInsensitiveEnv()` leaking stale duplicate keys into `process.env` on Windows when an env var's casing changed between loads — [#14999](https://github.com/cloudflare/workers-sdk/pull/14999) |
| [cloudflare/langchain-cloudflare](https://github.com/cloudflare/langchain-cloudflare) | Fixed three bugs in Cloudflare's LangChain/LangGraph integration — a D1 checkpoint saver silently ignoring filters, a Vectorize store crash on an empty search, and a reranker that never actually sorted results — landed on `main` via [#53](https://github.com/cloudflare/langchain-cloudflare/pull/53) |

## Security Research

| Finding | Status |
|---|---|
| CVSS 8.8 remote code execution in [mistralai/mistral-vibe](https://github.com/mistralai/mistral-vibe) via git `core.fsmonitor` hook execution | Fixed — [#962](https://github.com/mistralai/mistral-vibe/pull/962), integrated into Mistral's internal repo, credited as co-author on an upcoming release |
| Vulnerability in [microsoft/graphrag](https://github.com/microsoft/graphrag) | Reported via MSRC responsible disclosure (2026-07-24) — in triage, technical details withheld until a coordinated disclosure |
| Vulnerability in [deepset-ai/hayhooks](https://github.com/deepset-ai/hayhooks) | Reported via a private GitHub Security Advisory — in triage, technical details withheld until a fix ships |

## Projects

| Project | Description |
|---|---|
| [ARGUS](https://github.com/mittalpk/ARGUS) | Identity-document fraud detection (computer vision ensemble) with a full TOGAF + MLOps + compliance delivery chain (DVC, MLflow, drift detection, EU AI Act/GDPR/ISO 42001 evidence packaging). Finished top 14% of 269 teams on the FREUID Challenge 2026 (IJCAI-ECAI) final private leaderboard, with the smallest public-to-private score degradation of any benchmarked team. |

## Focus Areas

- Agentic orchestration and multi-agent systems (LangGraph, LangChain)
- RAG architecture, retrieval, and evaluation
- Multi-provider LLM routing and structured output
- Production MLOps: observability, drift detection, CI/CD for ML systems
- AI governance and compliance (EU AI Act, GDPR-aligned system design)
