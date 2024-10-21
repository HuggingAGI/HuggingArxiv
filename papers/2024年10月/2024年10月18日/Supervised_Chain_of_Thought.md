# 思维链监督

发布时间：2024年10月18日

`LLM理论` `人工智能`

> Supervised Chain of Thought

# 摘要

> 大型语言模型（LLM）在自然语言处理领域掀起了一场革命，为人工智能的进步带来了巨大潜力。然而，主流 LLM 的核心架构——Transformer——在计算深度上存在固有局限，使其在理论上难以应对需要深度计算的复杂推理任务。为此，Chain of Thought（CoT）提示技术应运而生，通过几项理论研究证明其能有效弥补这一架构缺陷。CoT 为解决以往模型难以企及的复杂推理任务提供了新思路。尽管 CoT 及其变体（如 Tree of Thought、Graph of Thought 等）在实践中取得了成功，但它们依赖的“一提示适用于所有”策略，即使用单一提示结构（如“一步一步思考”）来应对多种任务，从简单的计数排序到复杂的数学算法问题，却给模型生成正确推理步骤带来了巨大挑战。模型必须在庞大的提示模板空间中寻找适合每个任务的模板，这无疑增加了难度。在本研究中，我们基于对 CoT 的理论分析，揭示了“一提示适用于所有”策略对 LLM 计算能力的负面影响。我们将解决方案搜索空间划分为提示空间和答案空间，并发现任务特定的监督对于准确导航提示空间、实现最佳性能至关重要。通过与最先进的 LLM 进行实验，我们进一步揭示了在应用监督与不应用监督时推理性能的显著差异。

> Large Language Models (LLMs) have revolutionized natural language processing and hold immense potential for advancing Artificial Intelligence. However, the core architecture of most mainstream LLMs -- the Transformer -- has inherent limitations in computational depth, rendering them theoretically incapable of solving many reasoning tasks that demand increasingly deep computations. Chain of Thought (CoT) prompting has emerged as a technique to address these architectural limitations, as evidenced by several theoretical studies. It offers a promising approach to solving complex reasoning tasks that were previously beyond the capabilities of these models. Despite its successes, CoT and its variants (such as Tree of Thought, Graph of Thought, etc.) rely on a "one-prompt-for-all" approach, using a single prompt structure (e.g., "think step by step") for a wide range of tasks -- from counting and sorting to solving mathematical and algorithmic problems. This approach poses significant challenges for models to generate the correct reasoning steps, as the model must navigate through a vast prompt template space to find the appropriate template for each task. In this work, we build upon previous theoretical analyses of CoT to demonstrate how the one-prompt-for-all approach can negatively affect the computability of LLMs. We partition the solution search space into two: the prompt space and the answer space. Our findings show that task-specific supervision is essential for navigating the prompt space accurately and achieving optimal performance. Through experiments with state-of-the-art LLMs, we reveal a gap in reasoning performance when supervision is applied versus when it is not.

[Arxiv](https://arxiv.org/abs/2410.14198)