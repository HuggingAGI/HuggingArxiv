# 无约束模型合并：提升 LLM 推理能力

发布时间：2024年10月17日

`LLM理论` `人工智能` `推理任务`

> Unconstrained Model Merging for Enhanced LLM Reasoning

# 摘要

> 近期，领域特定的大型语言模型 (LLM) 在推理任务中表现出色，如逻辑推理和多步骤问题解决。然而，全能 LLM 的构建因专有数据和计算资源需求而受限。为此，我们探索了将多个专家模型合并为单一 LLM 的潜力。现有研究多聚焦于通用 LLM，而非领域专家。我们提出无约束模型合并框架，适用于同质与异质架构，并专注于推理任务。通过细粒度逐层权重合并策略和基于概率分布知识的异质模型合并，我们在 7 个基准和 9 个推理优化的 LLM 中验证了组合推理的涌现效应。无约束模型合并有望成为去中心化 LLM 的基础，推动人工智能领域的广泛参与和进一步发展，突破集中式模型的限制。

> Recent advancements in building domain-specific large language models (LLMs) have shown remarkable success, especially in tasks requiring reasoning abilities like logical inference over complex relationships and multi-step problem solving. However, creating a powerful all-in-one LLM remains challenging due to the need for proprietary data and vast computational resources. As a resource-friendly alternative, we explore the potential of merging multiple expert models into a single LLM. Existing studies on model merging mainly focus on generalist LLMs instead of domain experts, or the LLMs under the same architecture and size. In this work, we propose an unconstrained model merging framework that accommodates both homogeneous and heterogeneous model architectures with a focus on reasoning tasks. A fine-grained layer-wise weight merging strategy is designed for homogeneous models merging, while heterogeneous model merging is built upon the probabilistic distribution knowledge derived from instruction-response fine-tuning data. Across 7 benchmarks and 9 reasoning-optimized LLMs, we reveal key findings that combinatorial reasoning emerges from merging which surpasses simple additive effects. We propose that unconstrained model merging could serve as a foundation for decentralized LLMs, marking a notable progression from the existing centralized LLM framework. This evolution could enhance wider participation and stimulate additional advancement in the field of artificial intelligence, effectively addressing the constraints posed by centralized models.

[Arxiv](https://arxiv.org/abs/2410.13699)