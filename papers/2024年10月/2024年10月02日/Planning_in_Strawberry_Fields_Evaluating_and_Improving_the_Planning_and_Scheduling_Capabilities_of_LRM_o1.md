# 草莓田中的规划：探索并提升 LRM o1 的规划与调度能力

发布时间：2024年10月02日

`Agent` `人工智能` `智能代理`

> Planning in Strawberry Fields: Evaluating and Improving the Planning and Scheduling Capabilities of LRM o1

# 摘要

> 规划能力，即实现期望状态的行动方案，一直是智能代理的核心，也是人工智能研究的核心。随着大型语言模型 (LLM) 的兴起，人们对其规划能力充满好奇，但进展依旧缓慢。OpenAI 的 o1 (Strawberry) 模型旨在突破自回归 LLM 的局限，成为新型的大型推理模型 (LRM)。本文评估了 o1-preview 和 o1-mini 在规划与调度任务中的表现。尽管 o1 在性能上有所提升，但推理成本高昂且无法保证输出质量。通过结合外部验证器，即 LRM-Modulo 系统，不仅能确保输出正确性，还能进一步提升性能。

> The ability to plan a course of action that achieves a desired state of affairs has long been considered a core competence of intelligent agents and has been an integral part of AI research since its inception. With the advent of large language models (LLMs), there has been considerable interest in the question of whether or not they possess such planning abilities, but -- despite the slew of new private and open source LLMs since GPT3 -- progress has remained slow. OpenAI claims that their recent o1 (Strawberry) model has been specifically constructed and trained to escape the normal limitations of autoregressive LLMs -- making it a new kind of model: a Large Reasoning Model (LRM). In this paper, we evaluate the planning capabilities of two LRMs (o1-preview and o1-mini) on both planning and scheduling benchmarks. We see that while o1 does seem to offer significant improvements over autoregressive LLMs, this comes at a steep inference cost, while still failing to provide any guarantees over what it generates. We also show that combining o1 models with external verifiers -- in a so-called LRM-Modulo system -- guarantees the correctness of the combined system's output while further improving performance.

[Arxiv](https://arxiv.org/abs/2410.02162)