# 探索大型语言模型在产品属性值识别中的应用

发布时间：2024年09月19日

`LLM应用` `电子商务`

> Exploring Large Language Models for Product Attribute Value Identification

# 摘要

> 产品属性值识别 (PAVI) 通过自动提取产品信息中的属性和值，支持搜索、推荐和比较等功能。现有方法多依赖于 BART 和 T5 等预训练模型的微调，但这些方法需要大量特定任务数据，且难以适应新属性。本文探索了 LLaMA 和 Mistral 等大型语言模型 (LLM) 作为高效且稳健的 PAVI 解决方案。我们提出多种策略：在零-shot 环境下比较一步和两步提示法，并利用 in-context learning 示例中的参数和非参数知识。此外，我们引入基于 T5 模型的密集演示检索器，并进行指令微调，以强化 LLM 在特定任务上的表现。实验结果显示，两步法在零-shot 环境下显著提升性能，指令微调进一步增强了使用训练数据时的表现，验证了 LLM 在 PAVI 中的实际应用价值。

> Product attribute value identification (PAVI) involves automatically identifying attributes and their values from product information, enabling features like product search, recommendation, and comparison. Existing methods primarily rely on fine-tuning pre-trained language models, such as BART and T5, which require extensive task-specific training data and struggle to generalize to new attributes. This paper explores large language models (LLMs), such as LLaMA and Mistral, as data-efficient and robust alternatives for PAVI. We propose various strategies: comparing one-step and two-step prompt-based approaches in zero-shot settings and utilizing parametric and non-parametric knowledge through in-context learning examples. We also introduce a dense demonstration retriever based on a pre-trained T5 model and perform instruction fine-tuning to explicitly train LLMs on task-specific instructions. Extensive experiments on two product benchmarks show that our two-step approach significantly improves performance in zero-shot settings, and instruction fine-tuning further boosts performance when using training data, demonstrating the practical benefits of using LLMs for PAVI.

[Arxiv](https://arxiv.org/abs/2409.12695)