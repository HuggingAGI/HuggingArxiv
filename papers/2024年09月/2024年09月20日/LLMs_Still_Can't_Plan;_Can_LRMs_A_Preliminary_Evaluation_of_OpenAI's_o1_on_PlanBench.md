# LLM 在规划方面仍显不足，那么 LRM 能否胜任？本文对 OpenAI 的 o1 在 PlanBench 上的表现进行了初步评估。

发布时间：2024年09月20日

`LLM应用` `人工智能` `智能代理`

> LLMs Still Can't Plan; Can LRMs? A Preliminary Evaluation of OpenAI's o1 on PlanBench

# 摘要

> 规划能力一直被视为智能代理的核心，自人工智能诞生之初便是研究重点。随着大型语言模型（LLM）的兴起，其规划能力备受关注。2022年，我们推出了PlanBench基准，成为评估LLM规划能力的关键工具。尽管GPT3后涌现了众多LLM，但在此基准上的进展却出奇缓慢。OpenAI的o1（Strawberry）模型旨在突破自回归LLM的局限，成为新型的大型推理模型（LRM）。本文以此为契机，全面审视了当前LLM及新LRM在PlanBench上的表现。虽然o1在基准测试中表现卓越，但仍未达饱和。这一进步也引发了关于准确性、效率和保障的讨论，这些都是在部署此类系统前必须深思的问题。

> The ability to plan a course of action that achieves a desired state of affairs has long been considered a core competence of intelligent agents and has been an integral part of AI research since its inception. With the advent of large language models (LLMs), there has been considerable interest in the question of whether or not they possess such planning abilities. PlanBench, an extensible benchmark we developed in 2022, soon after the release of GPT3, has remained an important tool for evaluating the planning abilities of LLMs. Despite the slew of new private and open source LLMs since GPT3, progress on this benchmark has been surprisingly slow. OpenAI claims that their recent o1 (Strawberry) model has been specifically constructed and trained to escape the normal limitations of autoregressive LLMs--making it a new kind of model: a Large Reasoning Model (LRM). Using this development as a catalyst, this paper takes a comprehensive look at how well current LLMs and new LRMs do on PlanBench. As we shall see, while o1's performance is a quantum improvement on the benchmark, outpacing the competition, it is still far from saturating it. This improvement also brings to the fore questions about accuracy, efficiency, and guarantees which must be considered before deploying such systems.

[Arxiv](https://arxiv.org/abs/2409.13373)