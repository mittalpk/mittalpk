# Praveen Mittal

AI Solutions Architect / Senior AI Engineer — LLM orchestration, RAG, agentic systems, and production MLOps.

## Open Source Contributions

Real, merged fixes to production AI/ML open-source infrastructure — found via direct code audits, not the issue tracker.

| Project | Contribution |
|---|---|
| [deepset-ai/haystack](https://github.com/deepset-ai/haystack) | Fixed a crash in `MSGToDocument`'s attachment-metadata handling on `ByteStream` sources — [#12207](https://github.com/deepset-ai/haystack/pull/12207) |
| [mistralai/mistral-vibe](https://github.com/mistralai/mistral-vibe) | Fixed a CVSS 8.8 remote code execution vulnerability (git `core.fsmonitor` hook injection) — credited as co-author on the next release — [#962](https://github.com/mistralai/mistral-vibe/pull/962) |
| [Meta's llama-stack](https://github.com/ogx-ai/ogx) (now independently governed as `ogx-ai/ogx`) | Fixed an indirect prompt-injection vulnerability via unsanitized tool output — [#6337](https://github.com/ogx-ai/ogx/pull/6337) |
| [alibaba/open-code-review](https://github.com/alibaba/open-code-review) | Added HCL/Terraform and Bicep language support — [#524](https://github.com/alibaba/open-code-review/pull/524), [#525](https://github.com/alibaba/open-code-review/pull/525) |
| [567-labs/instructor](https://github.com/567-labs/instructor) | Fixed an Anthropic tool-calling bug where forced single-tool requests didn't disable parallel tool use — [#2478](https://github.com/567-labs/instructor/pull/2478) |
| [process-intelligence-solutions/pm4py](https://github.com/process-intelligence-solutions/pm4py) | Fixed a timezone-corrupting default-path bug in timestamp normalization — [#562](https://github.com/process-intelligence-solutions/pm4py/pull/562) |

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
