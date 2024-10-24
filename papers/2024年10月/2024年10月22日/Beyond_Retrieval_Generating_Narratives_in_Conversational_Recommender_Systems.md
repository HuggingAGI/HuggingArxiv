# 超越检索：在会话推荐系统中生成叙述

发布时间：2024年10月22日

`LLM应用` `推荐系统`

> Beyond Retrieval: Generating Narratives in Conversational Recommender Systems

# 摘要

> 大型语言模型的生成和推理能力的最新进展为开发真正的对话式推荐系统提供了机会。然而，将推荐系统知识有效地整合到针对推荐任务进行自然语言生成的大型语言模型中仍然是一个挑战。本文通过做出两个关键贡献来应对这一挑战。首先，我们为对话式推荐中的自然语言生成任务引入了一个新的数据集（REGEN）。REGEN（通过生成性叙述增强的评论）用丰富的用户叙述扩展了亚马逊产品评论数据集，包括产品偏好的个性化解释、推荐项目的产品背书以及用户购买历史的总结。REGEN 已公开提供以促进进一步研究。此外，我们使用著名的生成指标建立了基准，并使用评级大型语言模型对新数据集进行了自动评估。其次，本文引入了一种融合架构（带有大型语言模型的 CF 模型），作为 REGEN 的基线。据我们所知，这是首次尝试分析大型语言模型在理解推荐信号和生成丰富叙述方面的能力。我们证明，大型语言模型可以有效地从利用基于交互的 CF 嵌入的简单融合架构中学习，并且使用与项目相关的元数据和个性化数据可以进一步增强这一点。我们的实验表明，与单独使用任何一种类型的嵌入相比，结合 CF 和内容嵌入在关键语言指标上可提高 4-12％。我们还提供了一个分析来解释 CF 和内容嵌入如何为这个新的生成任务做出贡献。

> The recent advances in Large Language Model's generation and reasoning capabilities present an opportunity to develop truly conversational recommendation systems. However, effectively integrating recommender system knowledge into LLMs for natural language generation which is tailored towards recommendation tasks remains a challenge. This paper addresses this challenge by making two key contributions.
  First, we introduce a new dataset (REGEN) for natural language generation tasks in conversational recommendations. REGEN (Reviews Enhanced with GEnerative Narratives) extends the Amazon Product Reviews dataset with rich user narratives, including personalized explanations of product preferences, product endorsements for recommended items, and summaries of user purchase history. REGEN is made publicly available to facilitate further research. Furthermore, we establish benchmarks using well-known generative metrics, and perform an automated evaluation of the new dataset using a rater LLM. Second, the paper introduces a fusion architecture (CF model with an LLM) which serves as a baseline for REGEN. And to the best of our knowledge, represents the first attempt to analyze the capabilities of LLMs in understanding recommender signals and generating rich narratives. We demonstrate that LLMs can effectively learn from simple fusion architectures utilizing interaction-based CF embeddings, and this can be further enhanced using the metadata and personalization data associated with items. Our experiments show that combining CF and content embeddings leads to improvements of 4-12% in key language metrics compared to using either type of embedding individually. We also provide an analysis to interpret how CF and content embeddings contribute to this new generative task.

[Arxiv](https://arxiv.org/abs/2410.16780)