# 对大型语言模型在物理知识与推理上的不确定性进行测试

发布时间：2024年11月18日

`LLM应用` `语言模型`

> Testing Uncertainty of Large Language Models for Physics Knowledge and Reasoning

# 摘要

> 大型语言模型（LLMs）近些年来因能在众多领域回答问题而备受青睐。不过，这些模型常有“胡编乱造”回答的情况，这让评估其性能变得困难重重。一大挑战在于如何判定模型预测的确定性以及它与准确性的关联。在本研究中，我们引入了一种分析，用于评估热门开源 LLMs 以及 gpt-3.5 Turbo 在多项选择物理问卷上的表现。我们着重研究了与物理相关主题中答案的准确性和变异性的关系。我们的发现表明，多数模型在有把握时能给出准确回答，但这绝非普遍现象。准确性和不确定性的关系呈现出广泛的水平钟形分布。我们报告了随着问题对 LLM 代理的逻辑推理要求提高，准确性和不确定性之间的不对称性如何加剧，而在知识检索任务中，相同的关系依然显著。

> Large Language Models (LLMs) have gained significant popularity in recent years for their ability to answer questions in various fields. However, these models have a tendency to "hallucinate" their responses, making it challenging to evaluate their performance. A major challenge is determining how to assess the certainty of a model's predictions and how it correlates with accuracy. In this work, we introduce an analysis for evaluating the performance of popular open-source LLMs, as well as gpt-3.5 Turbo, on multiple choice physics questionnaires. We focus on the relationship between answer accuracy and variability in topics related to physics. Our findings suggest that most models provide accurate replies in cases where they are certain, but this is by far not a general behavior. The relationship between accuracy and uncertainty exposes a broad horizontal bell-shaped distribution. We report how the asymmetry between accuracy and uncertainty intensifies as the questions demand more logical reasoning of the LLM agent, while the same relationship remains sharp for knowledge retrieval tasks.

[Arxiv](https://arxiv.org/abs/2411.14465)