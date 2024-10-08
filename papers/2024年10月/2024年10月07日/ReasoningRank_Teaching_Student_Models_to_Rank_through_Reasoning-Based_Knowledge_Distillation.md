# ReasoningRank：借助推理为基础的知识蒸馏，教导学生模型掌握排序技能

发布时间：2024年10月07日

`LLM应用` `信息检索` `人工智能`

> ReasoningRank: Teaching Student Models to Rank through Reasoning-Based Knowledge Distillation

# 摘要

> 在信息检索中，根据文档与查询的相关性进行重新排序至关重要。然而，传统方法虽能改进排名，却缺乏透明度，无法解释排名背后的原因。为此，我们提出了 ReasoningRank，一种通过生成显式推理和比较推理来增强透明度的新方法。我们利用大型语言模型 (LLM) 生成这些推理，并将其知识提炼到更小、更高效的学生模型中。尽管学生模型在速度上不及 LLM，但它们通过减少资源需求，显著降低了计算负担，更适合大规模或资源受限的环境。这些学生模型不仅能生成有意义的推理，还能有效重新排序文档，在多个数据集上表现出色。实验证明，ReasoningRank 不仅提高了排序准确性，还为决策过程提供了清晰的解释，为重新排序任务提供了一种结构化和可解释的解决方案。

> Reranking documents based on their relevance to a given query is critical in information retrieval. Traditional reranking methods often focus on improving the initial rankings but lack transparency, failing to explain why one document is ranked higher. In this paper, we introduce ReasoningRank, a novel reranking approach that enhances clarity by generating two types of reasoning: explicit reasoning, which explains how a document addresses the query, and comparison reasoning, which justifies the relevance of one document over another. We leverage large language models (LLMs) as teacher models to generate these explanations and distill this knowledge into smaller, more resource-efficient student models. While the student models may not outperform LLMs in speed, they significantly reduce the computational burden by requiring fewer resources, making them more suitable for large-scale or resource-constrained settings. These student models are trained to both generate meaningful reasoning and rerank documents, achieving competitive performance across multiple datasets, including MSMARCO and BRIGHT. Experiments demonstrate that ReasoningRank improves reranking accuracy and provides valuable insights into the decision-making process, offering a structured and interpretable solution for reranking tasks.

[Arxiv](https://arxiv.org/abs/2410.05168)