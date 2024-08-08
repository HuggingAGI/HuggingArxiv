# ULLME：一个集成了生成增强学习的大型语言模型嵌入统一框架

发布时间：2024年08月06日

`LLM应用` `信息技术`

> ULLME: A Unified Framework for Large Language Model Embeddings with Generation-Augmented Learning

# 摘要

> 大型语言模型 (LLM) 在自然语言处理领域表现卓越，但在密集段落嵌入方面仍面临挑战。这主要源于其因果注意力机制与预训练目标和文本排名任务之间的不匹配。尽管已有一些尝试解决这些问题，但现有基于 LLM 的文本嵌入框架因仅支持有限架构和微调策略，限制了其实际应用和灵活性。为此，我们推出了统一的大型语言模型嵌入框架 (ULLME)，一个灵活的即插即用系统，支持多种 LLM 架构间的双向注意力，并兼容多种微调策略。此外，我们创新性地提出了生成增强表示学习 (GRL)，通过强化表示与生成相关性的一致性，充分利用 LLM 的生成能力，提升文本嵌入效果。为验证 ULLME 的灵活性与高效性，我们发布了三个参数规模从 1.5B 到 8B 的预训练模型，均在 Massive Text Embedding Benchmark 上表现优异。ULLME 框架现已公开，详情请访问：https://github.com/nlp-uoregon/ullme，并可观看演示视频：https://rb.gy/ws1ile。

> Large Language Models (LLMs) excel in various natural language processing tasks, but leveraging them for dense passage embedding remains challenging. This is due to their causal attention mechanism and the misalignment between their pre-training objectives and the text ranking tasks. Despite some recent efforts to address these issues, existing frameworks for LLM-based text embeddings have been limited by their support for only a limited range of LLM architectures and fine-tuning strategies, limiting their practical application and versatility. In this work, we introduce the Unified framework for Large Language Model Embedding (ULLME), a flexible, plug-and-play implementation that enables bidirectional attention across various LLMs and supports a range of fine-tuning strategies. We also propose Generation-augmented Representation Learning (GRL), a novel fine-tuning method to boost LLMs for text embedding tasks. GRL enforces consistency between representation-based and generation-based relevance scores, leveraging LLMs' powerful generative abilities for learning passage embeddings. To showcase our framework's flexibility and effectiveness, we release three pre-trained models from ULLME with different backbone architectures, ranging from 1.5B to 8B parameters, all of which demonstrate strong performance on the Massive Text Embedding Benchmark. Our framework is publicly available at: https://github.com/nlp-uoregon/ullme. A demo video for ULLME can also be found at https://rb.gy/ws1ile.

[Arxiv](https://arxiv.org/abs/2408.03402)