# 利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐

发布时间：2024年05月29日

`LLM应用

这篇论文介绍了一个名为KALM4Rec的框架，该框架专门设计来解决推荐系统中的冷启动问题，特别是在餐厅推荐领域。它利用大型语言模型（LLMs）的能力，通过关键词驱动的检索和基于LLM的重新排序两个阶段来提升推荐质量。这种方法特别针对那些缺乏历史数据的用户，通过LLMs的零-shot和few-shot提示策略来优化推荐结果。因此，这篇论文属于LLM应用类别，因为它展示了LLMs在实际应用中的具体使用和效果。` `推荐系统` `餐饮业`

> Keyword-driven Retrieval-Augmented Large Language Models for Cold-start User Recommendations

# 摘要

> 大型语言模型（LLMs）的进步已经极大地提升了推荐系统的潜力，但面对用户缺乏历史数据的冷启动问题，仍是一大挑战。为此，我们提出了KALM4Rec框架，专为解决冷启动用户在餐厅推荐中的问题而设计，仅需用户提供少量关键词。该框架分为两个主要阶段：候选检索和基于LLM的重新排序。首先，通过关键词驱动的检索模型筛选潜在候选，克服了LLMs处理大量数据的局限，并降低了误导信息的风险。其次，利用LLMs结合零-shot和few-shot等提示策略，将多例直接融入提示中，对候选进行重新排序。我们基于Yelp餐厅数据集的评估显示，KALM4Rec显著提升了推荐质量，尤其是通过LLMs的上下文指令进行重新排序，大幅增强了冷启动用户推荐系统的性能。

> Recent advancements in Large Language Models (LLMs) have shown significant potential in enhancing recommender systems. However, addressing the cold-start recommendation problem, where users lack historical data, remains a considerable challenge. In this paper, we introduce KALM4Rec (Keyword-driven Retrieval-Augmented Large Language Models for Cold-start User Recommendations), a novel framework specifically designed to tackle this problem by requiring only a few input keywords from users in a practical scenario of cold-start user restaurant recommendations. KALM4Rec operates in two main stages: candidates retrieval and LLM-based candidates re-ranking. In the first stage, keyword-driven retrieval models are used to identify potential candidates, addressing LLMs' limitations in processing extensive tokens and reducing the risk of generating misleading information. In the second stage, we employ LLMs with various prompting strategies, including zero-shot and few-shot techniques, to re-rank these candidates by integrating multiple examples directly into the LLM prompts. Our evaluation, using a Yelp restaurant dataset with user reviews from three English-speaking cities, shows that our proposed framework significantly improves recommendation quality. Specifically, the integration of in-context instructions with LLMs for re-ranking markedly enhances the performance of the cold-start user recommender system.

![利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐](../../../paper_images/2405.19612/x1.png)

![利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐](../../../paper_images/2405.19612/x2.png)

![利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐](../../../paper_images/2405.19612/x3.png)

![利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐](../../../paper_images/2405.19612/x4.png)

![利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐](../../../paper_images/2405.19612/x5.png)

![利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐](../../../paper_images/2405.19612/x6.png)

![利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐](../../../paper_images/2405.19612/x7.png)

![利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐](../../../paper_images/2405.19612/x8.png)

![利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐](../../../paper_images/2405.19612/x9.png)

![利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐](../../../paper_images/2405.19612/x10.png)

![利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐](../../../paper_images/2405.19612/x11.png)

![利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐](../../../paper_images/2405.19612/x12.png)

![利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐](../../../paper_images/2405.19612/x13.png)

![利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐](../../../paper_images/2405.19612/x14.png)

![利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐](../../../paper_images/2405.19612/x15.png)

![利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐](../../../paper_images/2405.19612/x16.png)

![利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐](../../../paper_images/2405.19612/x17.png)

![利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐](../../../paper_images/2405.19612/x18.png)

![利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐](../../../paper_images/2405.19612/x19.png)

[Arxiv](https://arxiv.org/abs/2405.19612)