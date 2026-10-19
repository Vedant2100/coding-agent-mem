# Coding-Agent Memory Governance

**Research question:** When should a coding agent's experience be shared with other agents, and when should a later agent actually see that memory?

## Why this matters

Persistent memory can help coding agents reuse hard-won experience, but a remembered detail can also be irrelevant, stale, or misleading. More remembered context is not automatically better. This project studies **memory promotion** (SHARE / DO_NOT_SHARE) and **memory exposure** (EXPOSE / WITHHOLD) as separate decisions.

## Evaluation setup

- **Setting:** Sequential coding-agent tasks on SWE-ContextBench, using earlier same-repository experiences as candidate memories for later tasks.
- **Development set:** 11 clean target tasks, each with 13–114 earlier same-repository experiences.
- **Controls:** Compare with no-memory execution and examine the effect of known-relevant memories before interpreting governor quality.
- **Questions:** Does a selection policy retain useful experience? Does exposing selected memory change what the coding agent does? What fails when seemingly relevant memory is shared?

## What we learned

The evaluated memory conditions **did not improve full-task resolution over the no-memory baseline**. This is a negative result, not evidence that persistent memory cannot help. It suggests memory-selection accuracy alone is an inadequate success metric: the downstream agent may fail to use a useful memory, or the shared content may introduce distraction.

This repository is a public research summary. The complete benchmark artifacts and runnable harness are **not yet published here**, so the note should not be treated as an independently reproducible benchmark release.

## Relevance to production agent memory

For memory infrastructure such as [Mem0](https://mem0.ai/), the distinction between storing, retrieving, and *using* memory suggests three measurable evaluation layers: memory relevance/consistency, token or latency cost, and downstream task success. A useful next test is to compare a conservative memory governor with retrieval and forgetting baselines while measuring all three.

*Independent research project; not affiliated with Mem0.* 
