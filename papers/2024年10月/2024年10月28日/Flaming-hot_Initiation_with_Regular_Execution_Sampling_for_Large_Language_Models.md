# 大型语言模型的火热启动及常规执行采样

发布时间：2024年10月28日

`LLM应用` `语言模型`

> Flaming-hot Initiation with Regular Execution Sampling for Large Language Models

# 摘要

> 自 ChatGPT 问世以来，大型语言模型（LLMs）在众多领域都彰显出了卓越的能力。开发这些通用能力的关键挑战之一，是高效获取多样且高质量的数据。这在诸如数学或代码等带有沙盒检查器的推理相关任务中尤为重要，其目标是以更高概率为特定问题生成正确的解决方案。在本研究中，我们推出了具有常规执行的火热启动（FIRE）采样，这是一种简便却极为有效的方法，能高效地获取良好的响应。我们的实证发现表明，FIRE 采样提升了推理时的生成质量，也有益于对齐阶段的训练。此外，我们探究了 FIRE 采样是如何通过增进多样性来提高性能的，并分析了在响应的不同位置使用 FIRE 的影响。

> Since the release of ChatGPT, large language models (LLMs) have demonstrated remarkable capabilities across various domains. A key challenge in developing these general capabilities is efficiently sourcing diverse, high-quality data. This becomes especially critical in reasoning-related tasks with sandbox checkers, such as math or code, where the goal is to generate correct solutions to specific problems with higher probability. In this work, we introduce Flaming-hot Initiation with Regular Execution (FIRE) sampling, a simple yet highly effective method to efficiently find good responses. Our empirical findings show that FIRE sampling enhances inference-time generation quality and also benefits training in the alignment stage. Furthermore, we explore how FIRE sampling improves performance by promoting diversity and analyze the impact of employing FIRE at different positions within a response.

[Arxiv](https://arxiv.org/abs/2410.21236)