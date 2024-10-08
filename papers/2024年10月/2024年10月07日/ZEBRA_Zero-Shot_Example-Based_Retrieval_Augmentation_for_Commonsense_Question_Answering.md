# ZEBRA：一种基于零-shot 示例的常识问答检索增强技术

发布时间：2024年10月07日

`LLM应用` `人工智能`

> ZEBRA: Zero-Shot Example-Based Retrieval Augmentation for Commonsense Question Answering

# 摘要

> 当前的 LLM 在常识问答中表现出色，但其推理过程仍不透明。为此，我们推出了 ZEBRA，一个无需额外训练的零-shot 问答框架，结合了知识检索、案例推理和内省。ZEBRA 从知识库中提取相关信息，通过推理生成新知识，进而提升问答的准确性和可解释性。在 8 个常识推理基准测试中，ZEBRA 表现优异，平均准确率提升高达 4.5 分，超越了现有 LLM 和知识整合方法。

> Current Large Language Models (LLMs) have shown strong reasoning capabilities in commonsense question answering benchmarks, but the process underlying their success remains largely opaque. As a consequence, recent approaches have equipped LLMs with mechanisms for knowledge retrieval, reasoning and introspection, not only to improve their capabilities but also to enhance the interpretability of their outputs. However, these methods require additional training, hand-crafted templates or human-written explanations. To address these issues, we introduce ZEBRA, a zero-shot question answering framework that combines retrieval, case-based reasoning and introspection and dispenses with the need for additional training of the LLM. Given an input question, ZEBRA retrieves relevant question-knowledge pairs from a knowledge base and generates new knowledge by reasoning over the relationships in these pairs. This generated knowledge is then used to answer the input question, improving the model's performance and interpretability. We evaluate our approach across 8 well-established commonsense reasoning benchmarks, demonstrating that ZEBRA consistently outperforms strong LLMs and previous knowledge integration approaches, achieving an average accuracy improvement of up to 4.5 points.

[Arxiv](https://arxiv.org/abs/2410.05077)