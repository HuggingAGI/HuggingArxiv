# LLM-RankFusion：调和基于大型语言模型的排序系统中的内在矛盾

发布时间：2024年05月31日

`LLM应用

这篇论文主要探讨了如何利用大型语言模型（LLM）来改进信息检索系统中的段落排序问题。具体来说，论文关注了LLM在成对比较中的不一致性问题，并提出了一种名为LLM-RankFusion的框架来减少这些不一致性，从而生成更稳健的排名列表。这种方法涉及情境学习（ICL）和校准估计段落间的潜在偏好概率，以及整合多个排名器的结果。因此，这篇论文的内容属于LLM在实际应用中的一个具体场景，即信息检索系统的排名优化，故应归类为LLM应用。` `信息检索` `排序算法`

> LLM-RankFusion: Mitigating Intrinsic Inconsistency in LLM-based Ranking

# 摘要

> 利用大型语言模型（LLM）提示对段落进行排序，在现代信息检索系统中展现出潜力。通常，这种方法依赖于LLM的成对比较来对排名列表进行排序。但问题在于，LLM在比较时往往无法保持一致性，导致排名结果不稳定。我们发现了两种基于LLM的成对比较中的内在不一致性：顺序不一致性，即交换段落顺序时结果冲突；传递性不一致性，即偏好对之间出现非传递性关系。为此，我们提出了LLM-RankFusion框架，旨在减少这些不一致性，生成更稳健的排名列表。该框架通过情境学习（ICL）实现顺序无关的比较，并通过校准估计段落间的潜在偏好概率，以缓解顺序不一致性。同时，通过整合多个排名器的结果来解决传递性不一致性。实验证明，LLM-RankFusion能有效减少不一致的比较结果，提升排名质量，使最终排名更加可靠。

> Ranking passages by prompting a large language model (LLM) can achieve promising performance in modern information retrieval (IR) systems. A common approach is to sort the ranking list by prompting LLMs for pairwise comparison. However, sorting-based methods require consistent comparisons to correctly sort the passages, which we show that LLMs often violate. We identify two kinds of intrinsic inconsistency in LLM-based pairwise comparisons: order inconsistency which leads to conflicting results when switching the passage order, and transitive inconsistency which leads to non-transitive triads among all preference pairs. In this paper, we propose LLM-RankFusion, an LLM-based ranking framework that mitigates these inconsistencies and produces a robust ranking list. LLM-RankFusion mitigates order inconsistency using in-context learning (ICL) to demonstrate order-agnostic comparisons and calibration to estimate the underlying preference probability between two passages. We then address transitive inconsistency by aggregating the ranking results from multiple rankers. In our experiments, we empirically show that LLM-RankFusion can significantly reduce inconsistent pairwise comparison results, and improve the ranking quality by making the final ranking list more robust.

![LLM-RankFusion：调和基于大型语言模型的排序系统中的内在矛盾](../../../paper_images/2406.00231/x1.png)

[Arxiv](https://arxiv.org/abs/2406.00231)