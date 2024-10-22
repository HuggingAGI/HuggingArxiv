# 借助人机协作鉴别器，优化大型语言模型以应对动态约束。

发布时间：2024年10月19日

`LLM应用` `人工智能`

> Optimizing Large Language Models for Dynamic Constraints through Human-in-the-Loop Discriminators

# 摘要

> 大型语言模型（LLM）在现实应用中表现出色，但面对动态复杂的约束条件时，仍难以设计出满足系统目标的通用解决方案。当前的微调与反思推理方法虽能解决问题，但通用性有限。为此，我们设计了一个灵活框架，让 LLM 与系统接口互动，提炼约束概念，并与人类专家协作，持续优化性能。以旅行计划为例，我们通过评估接口设定约束，利用 LLM 和人类判别器识别关键案例，不断改进代理性能。一次迭代后，人类判别器通过率提升至 $7.78\%$，LLM 判别器通过率提升至 $6.11\%$。这一框架的适应性使其能广泛应用于各类约束场景，为性能敏感数据的模型微调奠定基础。

> Large Language Models (LLMs) have recently demonstrated impressive capabilities across various real-world applications. However, due to the current text-in-text-out paradigm, it remains challenging for LLMs to handle dynamic and complex application constraints, let alone devise general solutions that meet predefined system goals. Current common practices like model finetuning and reflection-based reasoning often address these issues case-by-case, limiting their generalizability. To address this issue, we propose a flexible framework that enables LLMs to interact with system interfaces, summarize constraint concepts, and continually optimize performance metrics by collaborating with human experts. As a case in point, we initialized a travel planner agent by establishing constraints from evaluation interfaces. Then, we employed both LLM-based and human discriminators to identify critical cases and continuously improve agent performance until the desired outcomes were achieved. After just one iteration, our framework achieved a $7.78\%$ pass rate with the human discriminator (a $40.2\%$ improvement over baseline) and a $6.11\%$ pass rate with the LLM-based discriminator. Given the adaptability of our proposal, we believe this framework can be applied to a wide range of constraint-based applications and lay a solid foundation for model finetuning with performance-sensitive data samples.

[Arxiv](https://arxiv.org/abs/2410.15163)