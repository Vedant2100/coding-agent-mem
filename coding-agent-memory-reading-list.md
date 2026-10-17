# Coding-Agent Memory — Recent Literature & Industry Work
*Reading list | October 17, 2026*

## 1. Surveys — Start here

| Survey | What it covers |
|---|---|
| [Self-Evolving Coding Agents](https://arxiv.org/abs/2608.03392) (Aug 2026) | Surveys how coding agents improve through persistent memory, skills, tools, workflows and execution feedback. |
| [From Private Experience to Collective State](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7432218) (Sep 2026) | Surveys how private agent experiences become shared knowledge through admission, scoping, propagation, revision and revocation. |

## 2. Research papers

| Paper | What it investigates |
|---|---|
| [SEPM — Self-Evolving Procedural Memory](https://arxiv.org/abs/2610.14515) (Oct 2026) | Learns reusable procedures from multi-agent execution, using task graphs and a shared blackboard to preserve coordination context. |
| [Chronos — Code Agents Reasoning over Software Evolution](https://arxiv.org/abs/2610.11578) (Oct 2026) | Converts historical pull requests into structured, interconnected knowledge that helps coding agents understand repository evolution. |
| [AECG — Asymmetric Experience Consolidation and Governance](https://arxiv.org/abs/2610.05176) (Oct 2026) | Governs shared multi-agent memories using reliability estimates, scope preservation, degradation monitoring and validated revisions. |
| [SEDM — Selective Self-Evolving Distributed Memory](https://arxiv.org/abs/2509.09498v4) (Oct 2026 revision) | Uses execution-based memory admission, utility-aware consolidation and selective recipient exposure to manage transferable experience. |
| [Scope Before You Persist](https://arxiv.org/abs/2609.29144) (Sep 2026) | Shows how a locally valid learned skill can harm unrelated tasks when applied outside its supported scope. |
| [VibeMemBench — Memory Systems for Coding Agents](https://arxiv.org/abs/2609.23570) (Sep 2026) | Benchmarks whether persistent memory actually improves executable repository tasks, finding that most tested configurations fail to beat no memory. |
| [Jev-Mem — System-One-Controlled Agentic Memory](https://arxiv.org/abs/2609.23986) (Sep 2026) | Separates fast memory-control decisions from slower reasoning to make agent memory use more efficient. |
| [Grounding Agent Memory](https://arxiv.org/abs/2609.11060) (Sep 2026) | Checks candidate memories against environment evidence before admitting them into long-term agent memory. |
| [MemGuard — Persisting Verifier Signals](https://arxiv.org/abs/2608.21867) (Aug 2026) | Uses persistent verification signals to decide which agent memories to retain, retrieve, revise or retire, including software-engineering evaluations. |
| [Shared Organizational Memory for Enterprise Coding Agents](https://arxiv.org/abs/2608.00122) (Aug 2026) | Describes an enterprise deployment for capturing, curating and sharing coding knowledge across different agents and sessions. |

## 3. Industry engineering blogs

| Engineering blog | What it describes |
|---|---|
| [Snowflake — Experience Cards](https://www.snowflake.com/en/blog/engineering/ai-agent-memory-experience-cards/) | Extracts team-owned lessons from merged PRs and reviewer feedback for reuse in later AI code reviews. |
| [Snowflake — ArcticMem](https://www.snowflake.com/en/blog/engineering/arcticmem-persistent-memory-ai-agents/) | Combines repository knowledge with automatically extracted lessons from past coding sessions for persistent retrieval. |
| [Mem0 — Coding Agents That Remember](https://mem0.ai/library/coding-agents/ai-coding-agents-that-actually-remember-your-codebase) | Shows how coding assistants can persist repository conventions, architectural decisions and debugging lessons between sessions. |
| [Cognee — Memory Tooling for AI Coding Agents](https://www.cognee.ai/memory-tooling-ai-coding-agents) | Uses graph-based memory to connect source code, dependencies, documentation and historical knowledge for coding agents. |
| [Supermemory — Large-Repository Coding Agents](https://supermemory.ai/blog/memory-bottleneck-large-repo-coding-agents/) | Discusses retrieval and memory reliability challenges in large, changing repositories, emphasizing provenance, freshness and context. |

**Research focus:** How coding agents accumulate experience across tasks, how that experience becomes shared knowledge, and whether retrieving it genuinely improves later software-engineering outcomes.

*These are pointers for discussion, not claims that all the papers address an unsolved research gap. The surveys and research papers include preprints; the company articles are engineering reports rather than independently peer-reviewed studies.*
