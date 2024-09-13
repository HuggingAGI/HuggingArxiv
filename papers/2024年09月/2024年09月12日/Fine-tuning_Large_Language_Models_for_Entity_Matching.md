# 微调大型语言模型以实现实体匹配

发布时间：2024年09月12日

`LLM应用` `实体匹配`

> Fine-tuning Large Language Models for Entity Matching

# 摘要

> 生成式 LLM 因其卓越的零-shot 性能和泛化能力，成为实体匹配的理想选择。现有研究多聚焦于提示工程和上下文学习。本文深入探讨了微调 LLM 进行实体匹配的潜力，从训练示例的表示和生成两个维度展开分析。实验显示，微调显著提升了小型模型的性能，但对大型模型的影响不一。此外，微调增强了模型在同领域数据集上的泛化能力，却削弱了跨领域迁移能力。有趣的是，添加结构化解释对多数 LLM 性能有正面影响，而示例选择和生成方法则仅对 Llama 3.1 8B 有效，对 GPT-4o Mini 则适得其反。

> Generative large language models (LLMs) are a promising alternative to pre-trained language models for entity matching due to their high zero-shot performance and their ability to generalize to unseen entities. Existing research on using LLMs for entity matching has focused on prompt engineering and in-context learning. This paper explores the potential of fine-tuning LLMs for entity matching. We analyze fine-tuning along two dimensions: 1) The representation of training examples, where we experiment with adding different types of LLM-generated explanations to the training set, and 2) the selection and generation of training examples using LLMs. In addition to the matching performance on the source dataset, we investigate how fine-tuning affects the model's ability to generalize to other in-domain datasets as well as across topical domains. Our experiments show that fine-tuning significantly improves the performance of the smaller models while the results for the larger models are mixed. Fine-tuning also improves the generalization to in-domain datasets while hurting cross-domain transfer. We show that adding structured explanations to the training set has a positive impact on the performance of three out of four LLMs, while the proposed example selection and generation methods only improve the performance of Llama 3.1 8B while decreasing the performance of GPT-4o Mini.

[Arxiv](https://arxiv.org/abs/2409.08185)