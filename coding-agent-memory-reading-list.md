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


---

## 4. Potential publication venues (2027 cycles)

**Checked October 17, 2026.** Selected for recognizable research communities and concrete fit to shared memory / learning across coding-agent tasks; **not** an exhaustive CFP directory. All dates below are **2026** unless explicitly marked **2027**. Dates follow each CFP's timezone (usually **AoE = UTC−12**); MLSys specifies **20:00 UTC**. **—** means no *separate* abstract-registration deadline was listed; **TBA** means the individual workshop CFP/deadline is not confirmed. A short or vision paper still needs a differentiated contribution.

### Near-term calls, ordered roughly by paper deadline

| Venue / official CFP | Abstract deadline | Paper deadline | What they ask for | Fleet-memory fit | Publication / important caveat |
|---|---|---|---|---|---|
| [SANER 2027 — Agentic AI4SE](https://conf.researchr.org/track/saner-2027/saner-2027-agentic-ai4se-track) | **Oct 19** (mandatory) | **Oct 23** | Up to **10 pages**: sound methods/evidence for agentic software evolution, reliability, tools or evaluation. | **High — empirical coding-agent study.** | IEEE proceedings; very tight deadline. |
| [ICSE 2027 — New Ideas & Emerging Results (NIER)](https://conf.researchr.org/track/icse-2027/icse-2027-new-ideas-and-emerging-results--nier-) | — | **Oct 23** | **4 pages + references**; original SE idea/emerging result, supporting rationale, mandatory **Future Plans** section. | **High — genuinely new question or preliminary result.** | Archival ICSE track; **not** a lower-standard full paper. |
| [Agent Evaluation Science — Fall Symposium](https://evalscience.org/2026fall-nyc/submissions/) | **Oct 20** (registration) | **Oct 25** | **2-page** extended abstract or **4–6-page** short paper on audits, benchmarks, failures, negative results. | **High — diagnostic of coding-memory evaluation.** | **Non-archival**, presentation-only; remote presentation possible. |
| [FORGE 2027 — Research / New Idea](https://conf.researchr.org/track/forge-2027/forge-2027-research-papers) | **Oct 25** | **Oct 30** | **4-page New Idea** (preliminary evaluation optional) or **10-page Full** research paper on foundation models for SE. | **High — new coding-agent memory concept.** | Archival conference; do not mistake a new-idea paper for an unevidenced literature summary. |
| [MLSys 2027 — Research](https://mlsys.org/Conferences/2027/CallForResearchPapers) | — | **Oct 30, 20:00 UTC** | **10-page** original ML-systems research; agent infrastructure, storage, reliability, scalability, cost/latency tradeoffs. | **Conditional — substantial implemented systems result.** | Major archival systems venue; existing small pilot insufficient. |
| [SANER 2027 — Registered Reports](https://conf.researchr.org/track/saner-2027/saner-2027-registered-report-track) | **Oct 30** | **Nov 6** (study plan) | **6-page Stage-1 protocol**, with research questions, prior work, planned methods and analyses **before** study execution. | **High — pre-registered memory-transfer evaluation.** | **Not** a completed-results research paper; journal pathway and stage requirements apply. |
| [AAMAS 2027 — Blue Sky Ideas](https://warwick.ac.uk/fac/sci/dcs/aamas2027/calls/call-for-blue-sky-ideas/) | **Nov 5** | **Nov 12** | **4-page** ambitious, novel, well-grounded multi-agent research vision; explain its novelty and authors' relevant expertise. | **Very high — organizational learning across agent fleets.** | Archival AAMAS proceedings; **OpenReview author registration Oct 20** is a separate prerequisite. |
| [AGENTVERIFY @ ICSE 2027](https://agentverify2027.github.io/cfp.html) | — | **Nov 13** | **2-page** extended abstract, **4-page** short/demo, or **8-page** full on agent validation, memory/skill reliability, harnesses and evaluations. | **High — causal failure analysis or verified memory.** | IEEE proceedings by default, **non-archival option**. **Current live CFP** says Nov 13 (supersedes earlier Nov 1/6 dates). |
| [AGENT @ ICSE 2027](https://conf.researchr.org/track/icse-2027/agent-2027-papers) | — | **Nov 13** | **5-page** short position/emerging research/benchmark or **8-page** full on engineering, memory, coordination and governance of agents. | **High — write/share/read engineering questions.** | Archival IEEE workshop. |
| [LLM4Code @ ICSE 2027](https://llm4code.github.io/call/) | — | **Nov 13** | **1–4-page** position, **1–5-page** extended abstract, or **4–8-page** research; coding-agent memory, context, evaluation, negative findings. | **Very high — direct coding-agent memory fit.** | IEEE proceedings with **non-archival option**. |
| [ICSE 2027 — Industry Challenge](https://conf.researchr.org/track/icse-2027/icse-2027-industry-challenge) | — | **Nov 13** | **5–10-page solution paper** responding to a specific accepted industry challenge. | **Very high topic match, demanding execution:** *Agent Memory in the Wild: Reliability, Efficiency, and Evaluation*. | Must satisfy **challenge specification**; not a free-form idea submission. |
| [FORGE 2027 — Data & Benchmarking](https://conf.researchr.org/track/forge-2027/forge-2027-data-and-benchmarking-track) | — | **Nov 15** | **4 pages + 1 reference page**: original benchmark, reproducible evaluation protocol, empirical audit, replication or meaningful negative findings. | **Very high — rigorous coding-memory evaluation.** | Archival; needs substantive reproducible artifact/evidence. |
| [MSR 2027 — Registered Reports](https://2027.msrconf.org/track/msr-2027-registered-reports) | **Nov 13** | **Nov 20** (study plan) | **6-page Stage-1 study protocol** reviewed before data collection/analysis; future path to *Empirical Software Engineering*. | **High — planned causal study across repositories.** | Stage-1 feedback/in-principle acceptance is **not** a completed findings publication. |
| [WMAC @ AAAI 2027](https://multiagents.org/2027/) | — | **Nov 20** | **4-page** short/demo/position or **8-page** full paper on collective intelligence in multi-agent systems. | **Very high — fleet-level knowledge sharing.** | **Non-archival**, suitable for early work. |
| [AgenticSE @ AAAI 2027](https://agenticse-aaai.github.io/) | — | **Nov 20** | **4-page** short/position or **8-page** long on reliable software-engineering agents and repository-level benchmarks. | **High — software-agent experiments.** | **Non-archival** workshop. |

### Later deadlines / more time to develop evidence

| Venue / official CFP | Abstract deadline | Paper deadline | What they ask for | Fleet-memory fit | Publication / important caveat |
|---|---|---|---|---|---|
| [IJCAI 2027 — Main Research](https://2027.ijcai.org/) | **Jan 4, 2027** | **Jan 11, 2027** | Substantial original AI research with convincing theory or experiments. | **Conditional — mature collective-memory mechanism.** | Major archival AI conference; needs a robust contribution. |
| [EASE 2027 — Research](https://conf.researchr.org/home/ease-2027) | **Jan 15, 2027** | **Jan 22, 2027** | Rigorous evidence-based SE research: experiments, validity, replications and actionable insights. | **High — empirical benefits/failures of coding memory.** | Archival; also has later short/emerging and negative-results tracks with separate CFPs. |
| [AAMAS 2027 — Workshops](https://warwick.ac.uk/fac/sci/dcs/aamas2027/) | **TBA** | **TBA** (**Jan 24, 2027 suggested**) | Individual workshop research, early results, positions or demos depending on accepted CFP. | **Very high if a multi-agent learning/memory workshop is accepted.** | Workshops expected to post CFPs by **Dec 9, 2026**; Jan 24 is **not a universal firm deadline**. |
| [ICLR 2027 — Workshops](https://iclr.cc/Conferences/2027/WorkshopGuidelines) | **TBA** | **TBA** (**Feb 1, 2027 suggested**) | Individual workshop short/tiny papers, preliminary studies, reanalysis or agent-learning research. | **High if an agent-memory / lifelong-learning workshop is accepted.** | Accepted workshop decisions due **Nov 29, 2026**; individual CFPs control deadlines and archival policy. |

### How to select a target (not a claim of novelty)

- **Vision / research agenda:** AAMAS Blue Sky; FORGE New Idea.
- **Executable benchmark, replication, negative transfer or failure analysis:** FORGE Data & Benchmarking; AGENTVERIFY; LLM4Code; Agent Evaluation Science.
- **Research design not yet executed:** MSR or SANER Registered Reports.
- **Production-scale memory substrate:** MLSys (only with a substantial systems contribution).
- **Collective-agent theory/behavior:** WMAC or a future AAMAS workshop.
- **More time and a completed empirical study:** IJCAI or EASE.

**Important:** A matching CFP does not establish a publishable research gap. Check the venue's originality, preprint, and concurrent-submission policies before reusing substantially overlapping manuscripts. Dates and formats can change; click each official CFP before submitting.
