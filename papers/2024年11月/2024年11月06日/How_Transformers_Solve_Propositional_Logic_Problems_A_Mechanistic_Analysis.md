# 变压器如何解决命题逻辑问题：一种机制分析

发布时间：2024年11月06日

`LLM理论` `人工智能` `逻辑推理`

> How Transformers Solve Propositional Logic Problems: A Mechanistic Analysis

# 摘要

> 大型语言模型（LLMs）在需要规划和推理的任务上表现出了惊人的性能。受此启发，我们研究了支撑网络执行复杂逻辑推理能力的内部机制。我们首先构建了一个综合的命题逻辑问题，作为网络训练和评估的具体测试平台。至关重要的是，这个问题需要非平凡的规划来解决，但我们可以训练一个小的 Transformer 以达到完美的准确性。基于我们的设置，然后我们试图了解一个从头开始训练的三层 Transformer 究竟是如何解决这个问题的。我们能够识别网络中的某些“规划”和“推理”电路，这些电路需要注意力块之间的合作来实现所需的逻辑。为了扩展我们的发现，我们接着研究了一个更大的模型，Mistral 7B。使用激活修补，我们描述了在解决我们的逻辑问题中至关重要的内部组件。总的来说，我们的工作系统地揭示了小型和大型 Transformer 的新方面，并继续研究它们如何规划和推理。

> Large language models (LLMs) have shown amazing performance on tasks that require planning and reasoning. Motivated by this, we investigate the internal mechanisms that underpin a network's ability to perform complex logical reasoning. We first construct a synthetic propositional logic problem that serves as a concrete test-bed for network training and evaluation. Crucially, this problem demands nontrivial planning to solve, but we can train a small transformer to achieve perfect accuracy. Building on our set-up, we then pursue an understanding of precisely how a three-layer transformer, trained from scratch, solves this problem. We are able to identify certain "planning" and "reasoning" circuits in the network that necessitate cooperation between the attention blocks to implement the desired logic. To expand our findings, we then study a larger model, Mistral 7B. Using activation patching, we characterize internal components that are critical in solving our logic problem. Overall, our work systemically uncovers novel aspects of small and large transformers, and continues the study of how they plan and reason.

[Arxiv](https://arxiv.org/abs/2411.04105)