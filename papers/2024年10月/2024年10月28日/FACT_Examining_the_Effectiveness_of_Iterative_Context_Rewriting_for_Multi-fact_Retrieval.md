# 事实：检验迭代上下文重写对多事实检索的有效性

发布时间：2024年10月28日

`LLM应用` `语言模型` `信息检索`

> FACT: Examining the Effectiveness of Iterative Context Rewriting for Multi-fact Retrieval

# 摘要

> 大型语言模型（LLMs）擅长从扩展的上下文中检索单个事实，但在需要同时检索多个事实的任务中，尤其是在生成过程中，它们会遇到困难。本文确定了一种新颖的“迷失在中间”现象，其中 LLMs 在整个生成过程中逐渐失去对关键信息的跟踪，导致检索不完整或不准确。为了应对这一挑战，我们引入了“查找所有关键文本（FACT）”，这是一种迭代检索方法，通过连续的重写轮次来优化上下文。这种方法使模型能够逐步捕获关键事实，而这些事实在单次检索中经常被忽略。实验表明，FACT 在各种任务中显著提高了多事实检索性能，尽管在通用 QA 场景中的改进不太显著。我们的研究结果揭示了 LLMs 在多事实检索方面的局限性，并强调了需要更具弹性的长上下文检索策略。

> Large Language Models (LLMs) are proficient at retrieving single facts from extended contexts, yet they struggle with tasks requiring the simultaneous retrieval of multiple facts, especially during generation. This paper identifies a novel "lost-in-the-middle" phenomenon, where LLMs progressively lose track of critical information throughout the generation process, resulting in incomplete or inaccurate retrieval. To address this challenge, we introduce Find All Crucial Texts (FACT), an iterative retrieval method that refines context through successive rounds of rewriting. This approach enables models to capture essential facts incrementally, which are often overlooked in single-pass retrieval. Experiments demonstrate that FACT substantially enhances multi-fact retrieval performance across various tasks, though improvements are less notable in general-purpose QA scenarios. Our findings shed light on the limitations of LLMs in multi-fact retrieval and underscore the need for more resilient long-context retrieval strategies.

[Arxiv](https://arxiv.org/abs/2410.21012)