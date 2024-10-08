# BloomWise：借助布鲁姆分类法启发的提示，提升大型语言模型的问题解决能力

发布时间：2024年10月05日

`LLM应用` `人工智能`

> BloomWise: Enhancing Problem-Solving capabilities of Large Language Models using Bloom's-Taxonomy-Inspired Prompts

# 摘要

> 尽管 LLM 在多任务中不断进步，但在数学和推理任务上仍显不足。这主要因为这些问题的复杂性和多步骤性，单一提示技术难以应对。为此，我们推出了 BloomWise，一种受 Bloom 分类法启发的提示技术，旨在通过引导 LLM 从简单记忆逐步升级到高级分析，直至找到正确答案，从而提升其解决复杂问题的能力。LLM 通过自我评估决定是否需要更高级的认知技能，从而灵活运用认知过程。在四个热门数学推理数据集上的实验表明，我们的方法效果显著。此外，我们还深入分析了系统各模块的优势。

> Despite the continuous progress of Large Language Models (LLMs) across various tasks, their performance on mathematical problems and reasoning tasks remains limited. This limitation can be attributed, among other factors, to the inherent difficulty of these problems and the fact that solutions often consist of multiple steps, potentially of varying nature, making it challenging for a single prompting technique to execute all required steps. To address this, we introduce BloomWise, a new prompting technique, inspired by Bloom's Taxonomy, aiming to improve LLMs' performance in solving such problems by encouraging them to approach the problem starting from simple, i.e., remembering, and progressing to higher cognitive skills, i.e., analyzing, until the correct solution is reached. The decision regarding the need to employ more sophisticated cognitive skills is based on self-evaluation performed by the LLM. Thus, we encourage the LLM to deploy the appropriate cognitive processes. In extensive experiments across 4 popular math reasoning datasets, we have demonstrated the effectiveness of our proposed approach. We also present extensive ablations, analyzing the strengths of each module within our system.

[Arxiv](https://arxiv.org/abs/2410.04094)