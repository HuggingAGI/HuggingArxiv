# RATT：构建大型语言模型连贯正确推理的思维框架

发布时间：2024年06月04日

`RAG

理由：这篇论文主要介绍了一种新型的思维结构——检索增强思维树（RATT），它结合了检索增强生成（RAG）的事实核查能力与大型语言模型（LLM）的策略评估能力。论文的核心贡献在于通过RAG和LLM的结合，优化了思维树结构，提高了模型在逻辑推理中的连贯性和决策效率。因此，这篇论文更符合RAG分类，因为它主要探讨了RAG技术在提升LLM推理能力中的应用。` `人工智能` `逻辑推理`

> RATT: AThought Structure for Coherent and Correct LLMReasoning

# 摘要

> 大型语言模型（LLMs）通过思维结构大幅提升了推理与决策能力。然而，现有的思维树和检索增强思维等方法在复杂任务中常因事实知识的局部检索不足和策略选择的全局性不足而受限。这些限制使得这些方法难以在事实准确性与逻辑全面优化之间找到平衡。为此，我们提出了检索增强思维树（RATT），一种新型的思维结构，它确保在思考的每一步都兼顾逻辑的完整性和事实的准确性。具体而言，RATT在每个思维分支的节点上进行规划与前瞻，评估多种推理路径，并将检索增强生成（RAG）的事实核查能力与LLM的策略评估能力相结合。通过整合事实知识与策略可行性，RATT优化思维树结构，以在搜索空间中探寻最优分支。这一结构显著提升了模型在逻辑推理中的连贯性和决策效率，从而增强了LLM基于思维结构生成可靠推理与决策的能力。广泛的任务实验证明，RATT在事实正确性和逻辑连贯性方面均显著超越现有方法。

> Large Language Models (LLMs) gain substantial reasoning and decision-making capabilities from thought structures. However, existing methods such as Tree of Thought and Retrieval Augmented Thoughts often fall short in complex tasks due to the limitations of insufficient local retrieval of factual knowledge and inadequate global selection of strategies. These limitations make it challenging for these methods to balance factual accuracy and comprehensive logical optimization effectively. To address these limitations, we introduce the Retrieval Augmented Thought Tree (RATT), a novel thought structure that considers both overall logical soundness and factual correctness at each step of the thinking process. Specifically, at every point of a thought branch, RATT performs planning and lookahead to explore and evaluate multiple potential reasoning steps, and integrate the fact-checking ability of Retrieval-Augmented Generation (RAG) with LLM's ability to assess overall strategy. Through this combination of factual knowledge and strategic feasibility, the RATT adjusts and integrates the thought tree structure to search for the most promising branches within the search space. This thought structure significantly enhances the model's coherence in logical inference and efficiency in decision-making, and thus increases the limit of the capacity of LLM to generate reliable inferences and decisions based on thought structures. A broad range of experiments on different types of tasks showcases that the RATT structure significantly outperforms existing methods in factual correctness and logical coherence.

![RATT：构建大型语言模型连贯正确推理的思维框架](../../../paper_images/2406.02746/x1.png)

![RATT：构建大型语言模型连贯正确推理的思维框架](../../../paper_images/2406.02746/x2.png)

![RATT：构建大型语言模型连贯正确推理的思维框架](../../../paper_images/2406.02746/x4.png)

![RATT：构建大型语言模型连贯正确推理的思维框架](../../../paper_images/2406.02746/x5.png)

![RATT：构建大型语言模型连贯正确推理的思维框架](../../../paper_images/2406.02746/x6.png)

[Arxiv](https://arxiv.org/abs/2406.02746)