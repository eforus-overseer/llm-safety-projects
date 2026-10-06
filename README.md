# Open LLM Safety & Security Projects

Eleven small, open-source project seeds for people who want to work on safer LLM applications and agents. Each repository has a scoped first milestone, contribution guide, security policy, and issue template. These are starting points for community collaboration, not finished products or claims of protection.

## The 11 project seeds

| Project | Focus | Potential collaborators |
|---|---|---|
| [Agent Injection Arena](https://github.com/eforus-overseer/agent-injection-arena) | A small, reproducible benchmark for indirect prompt injection in tool-using agents. | agent-framework builders, red-teamers, evaluators, and people who can review realistic but safely synthetic tasks |
| [MCP Scope Map](https://github.com/eforus-overseer/mcp-scope-map) | Turn MCP tool catalogs into a readable permission and trust-boundary review. | MCP maintainers, security reviewers, UX designers, and contributors familiar with JSON Schema |
| [RAG Poisoning Lab](https://github.com/eforus-overseer/rag-poisoning-lab) | Measure how a controlled, synthetic corpus edit changes retrieval and answers. | RAG developers, data provenance researchers, evaluation engineers, and technical writers |
| [LLM Egress Canary](https://github.com/eforus-overseer/llm-egress-canary) | Use synthetic canary values to map where sensitive-looking data can escape an AI workflow. | privacy engineers, appsec testers, observability maintainers, and contributors with data-handling experience |
| [Agent Action Gate](https://github.com/eforus-overseer/agent-action-gate) | A deterministic policy checkpoint between an agent proposal and a side effect. | agent developers, policy-as-code practitioners, UX contributors, and testers |
| [Injection Languages](https://github.com/eforus-overseer/injection-languages) | A community-reviewed dataset of multilingual prompt injection and hard benign examples. | multilingual NLP researchers, native-language reviewers, red-teamers, and dataset stewards |
| [LLM Red-Team Evidence](https://github.com/eforus-overseer/llm-redteam-evidence) | A portable, privacy-aware format for reproducible LLM security test findings. | red-team tool maintainers, evaluators, schema designers, and privacy reviewers |
| [LLM Output Sink Scan](https://github.com/eforus-overseer/llm-output-sink-scan) | Find risky flows from model-generated strings into code and markup sinks. | Semgrep contributors, secure-coding reviewers, language maintainers, and application developers |
| [Prompt Diff Review](https://github.com/eforus-overseer/prompt-diff-review) | Make meaningful security changes in system prompts and agent configs reviewable in CI. | GitHub Actions developers, agent-framework teams, security reviewers, and technical writers |
| [Citation Provenance Bench](https://github.com/eforus-overseer/citation-provenance-bench) | Test whether cited sources actually support answer claims and remain traceable. | RAG builders, librarians, fact-checkers, evaluation researchers, and annotation reviewers |
| [Agent Budget Guard](https://github.com/eforus-overseer/agent-budget-guard) | A local simulator for runaway tool loops, request limits, and predictable stop rules. | agent framework developers, FinOps-minded engineers, reliability teams, and evaluation contributors |

## Why these areas

I reviewed the open-source landscape on **7 October 2026**. GitHub API star counts were: promptfoo 25,760; DeepEval 18,663; garak 9,465; LLM Guard 3,215; OWASP's LLM Top 10 1,436; and Promptmap 1,278. [Star History comparison](https://star-history.com/#promptfoo/promptfoo&confident-ai/deepeval&NVIDIA/garak&protectai/llm-guard&OWASP/www-project-top-10-for-large-language-model-applications). The signal suggests sustained developer interest in evaluation and red teaming; stars do not measure safety or technical quality.

The ideas also account for work already on my profile: [empathy-captcha](https://github.com/eforus-overseer/empathy-captcha) probes agent behavior; [Literary-LLM-Knowledge-Data-Poisoning](https://github.com/eforus-overseer/Literary-LLM-Knowledge-Data-Poisoning) explores training-data poisoning; [RAG-QA-Wikipedia](https://github.com/eforus-overseer/RAG-QA-Wikipedia) covers retrieval QA; [llm-hallucination-sketches](https://github.com/eforus-overseer/llm-hallucination-sketches) studies streaming hallucination signals; and [octobrowser-mcp](https://github.com/eforus-overseer/octobrowser-mcp) builds an MCP integration. The new seeds explore adjacent layers: permissions, data flow, provenance, review, and collaboration.

## Research and references

- [OWASP GenAI Security Project](https://genai.owasp.org/) — current LLM and Agentic Application security guidance.
- [NVIDIA garak](https://github.com/NVIDIA/garak), [promptfoo](https://github.com/promptfoo/promptfoo), [ProtectAI LLM Guard](https://github.com/protectai/llm-guard), [Microsoft PyRIT](https://github.com/microsoft/PyRIT), and [Promptmap](https://github.com/utkusen/promptmap) — established tools informing the project boundaries.
- [Star History](https://www.star-history.com/) — public charts for comparing GitHub star growth over time. Counts above are snapshots from the GitHub API, not Star History estimates.

Every project is MIT-licensed and welcomes narrow pull requests from engineers, security practitioners, researchers, reviewers, designers, and technical writers. Start with its `README.md` and `CONTRIBUTING.md`.
