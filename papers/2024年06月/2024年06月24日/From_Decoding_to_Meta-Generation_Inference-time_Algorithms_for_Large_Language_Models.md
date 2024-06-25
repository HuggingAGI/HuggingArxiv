# 从解码迈向元生成：大型语言模型的推理时刻算法探索

发布时间：2024年06月24日

`LLM理论

这篇论文摘要主要探讨了大型语言模型（LLMs）在推理阶段的计算量扩展策略，包括令牌级生成算法、元生成算法及高效生成方法。这些内容涉及LLM的理论和算法层面，而非具体的应用实例或Agent的设计，也不是关于RAG（Retrieval-Augmented Generation）的讨论。因此，将其归类为LLM理论是合适的。` `机器学习`

> From Decoding to Meta-Generation: Inference-time Algorithms for Large Language Models

# 摘要

> 现代研究揭示，大型语言模型（LLMs）在训练时增加计算量能显著提升性能，但推理时的计算量扩展却鲜为人关注。本调查深入探讨了推理阶段的策略，涵盖三大领域：令牌级生成算法、元生成算法及高效生成方法。令牌级生成算法，即解码算法，通过逐令牌采样或构建搜索空间来选择输出，依赖于语言模型的对数或概率分布。元生成算法则处理序列，融入领域知识，支持回溯，并整合外部信息。高效生成方法则旨在降低成本、提速。我们的研究整合了传统自然语言处理、现代LLMs及机器学习系统的视角，为这一领域提供了全面洞察。

> One of the most striking findings in modern research on large language models (LLMs) is that scaling up compute during training leads to better results. However, less attention has been given to the benefits of scaling compute during inference. This survey focuses on these inference-time approaches. We explore three areas under a unified mathematical formalism: token-level generation algorithms, meta-generation algorithms, and efficient generation. Token-level generation algorithms, often called decoding algorithms, operate by sampling a single token at a time or constructing a token-level search space and then selecting an output. These methods typically assume access to a language model's logits, next-token distributions, or probability scores. Meta-generation algorithms work on partial or full sequences, incorporating domain knowledge, enabling backtracking, and integrating external information. Efficient generation methods aim to reduce token costs and improve the speed of generation. Our survey unifies perspectives from three research communities: traditional natural language processing, modern LLMs, and machine learning systems.

[Arxiv](https://arxiv.org/abs/2406.16838)