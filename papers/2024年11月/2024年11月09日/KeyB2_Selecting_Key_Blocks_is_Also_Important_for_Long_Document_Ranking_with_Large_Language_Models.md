# KeyB2：对于使用大型语言模型进行长文档排名，选择关键块也很重要。

发布时间：2024年11月09日

`LLM应用` `信息检索` `语言模型`

> KeyB2: Selecting Key Blocks is Also Important for Long Document Ranking with Large Language Models

# 摘要

> 像 Llama 这样的大型语言模型（LLM）的快速发展极大地推动了信息检索（IR）系统的进步。然而，在 RankLLaMA 等中，将 LLM 用于长文档仍然具有挑战性，这是由于计算复杂性，特别是关于输入令牌长度。此外，LLM 在排名期间的内部机制仍未完全理解。在本文中，我们首先探索了 LLM 在相关性判断期间的内部工作原理，并确定特定的注意力头在对齐相关令牌方面起着关键作用。这一观察启发我们重新审视 KeyB 中使用的块预排名策略，该策略在 TREC 2019 DL 文档排名数据集上仍然是最先进的（SOTA）。基于这些见解，我们开发了 KeyB2，这是一种先进的长文档 IR 方法，将块预排名与 LLM 的性能相结合。KeyB2 有效地识别和处理最相关的块，降低了计算成本并提高了排名效果。此外，我们为 KeyB2 引入了一种新的双编码器块匹配策略。在包括 TREC 2019 DL、Robust04 和 MLDR-zh 在内的长文档数据集上的综合实验表明，KeyB2 优于 RankLLaMA 和 KeyB 等基线，减少了重新排名时间和 GPU 内存使用，同时提高了检索性能，在 TREC 2019 DL 上实现了新的 SOTA 结果，具有更高的 NDCG@10 和 MAP 分数。

> The rapid development of large language models (LLMs) like Llama has significantly advanced information retrieval (IR) systems. However, using LLMs for long documents, as in RankLLaMA, remains challenging due to computational complexity, especially concerning input token length. Furthermore, the internal mechanisms of LLMs during ranking are still not fully understood. In this paper, we first explore the internal workings of LLMs during relevance judgement and identify that specific attention heads play a crucial role in aligning relevant tokens. This observation inspires us to revisit the block pre-ranking strategy used in KeyB, which remains state-of-the-art (SOTA) on the TREC 2019 DL document ranking dataset. Building on these insights, we develop KeyB2, an advanced long document IR approach that integrates block pre-ranking with the performance of LLMs. KeyB2 efficiently identifies and processes the most relevant blocks, reducing computational costs and improving ranking effectiveness. Additionally, we introduce a new bi-encoder block matching strategy for KeyB2. Comprehensive experiments on long-document datasets, including TREC 2019 DL, Robust04, and MLDR-zh, show that KeyB2 outperforms baselines like RankLLaMA and KeyB by reducing reranking time and GPU memory usage while enhancing retrieval performance, achieving new SOTA results on TREC 2019 DL with higher NDCG@10 and MAP scores.

[Arxiv](https://arxiv.org/abs/2411.06254)