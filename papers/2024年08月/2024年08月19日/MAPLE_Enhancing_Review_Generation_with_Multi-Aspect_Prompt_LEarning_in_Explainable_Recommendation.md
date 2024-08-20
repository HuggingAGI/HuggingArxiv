# MAPLE：借助多方面提示学习，在可解释推荐系统中提升评论生成质量

发布时间：2024年08月19日

`LLM应用` `电子商务`

> MAPLE: Enhancing Review Generation with Multi-Aspect Prompt LEarning in Explainable Recommendation

# 摘要

> 可解释推荐任务旨在为用户和物品配对提供推荐理由。尽管现有模型能生成流畅的评论，但普遍性和真实性问题仍存。我们提出的MAPLE模型，通过整合方面类别，提升了细粒度术语的记忆，实验显示其在多样性和连贯性上超越了传统模型。此外，结合LLM的阅读能力，MAPLE能提供更丰富、个性化的解释。项目获批后，我们将公开代码和数据。

> Explainable Recommendation task is designed to receive a pair of user and item and output explanations to justify why an item is recommended to a user. Many models treat review-generation as a proxy of explainable recommendation. Although they are able to generate fluent and grammatical sentences, they suffer from generality and hallucination issues. We propose a personalized, aspect-controlled model called Multi-Aspect Prompt LEarner (MAPLE), in which it integrates aspect category as another input dimension to facilitate the memorization of fine-grained aspect terms. Experiments on two real-world review datasets in restaurant domain show that MAPLE outperforms the baseline review-generation models in terms of text and feature diversity while maintaining excellent coherence and factual relevance. We further treat MAPLE as a retriever component in the retriever-reader framework and employ a Large-Language Model (LLM) as the reader, showing that MAPLE's explanation along with the LLM's comprehension ability leads to enriched and personalized explanation as a result. We will release the code and data in this http upon acceptance.

[Arxiv](https://arxiv.org/abs/2408.09865)