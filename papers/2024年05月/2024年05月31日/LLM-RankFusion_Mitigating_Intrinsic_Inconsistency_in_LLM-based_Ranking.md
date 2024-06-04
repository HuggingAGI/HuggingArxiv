# LLM-RankFusion：调和基于大型语言模型的排序系统中的内在矛盾

发布时间：2024年05月31日

`LLM应用

这篇论文主要探讨了大型语言模型（LLM）在信息检索系统中的应用，特别是在段落排序方面的挑战和解决方案。论文提出了LLM-RankFusion框架，旨在通过减少LLM在成对比较中的不一致性来提高排序的稳健性。这种方法涉及情境学习（ICL）和多排序器的聚合，以改善排序结果的质量。因此，这篇论文属于LLM应用类别，因为它专注于LLM在实际系统中的应用和改进。` `信息检索` `排序算法`

> LLM-RankFusion: Mitigating Intrinsic Inconsistency in LLM-based Ranking

# 摘要

> 在现代信息检索系统中，通过大型语言模型（LLM）提示对段落进行排序展现出巨大潜力。通常，这种方法依赖于LLM的成对比较来对列表进行排序。但问题在于，LLM在比较时往往缺乏一致性，导致排序错误。我们发现LLM的成对比较存在两种内在不一致性：顺序不一致性，即交换段落顺序后结果冲突；传递性不一致性，即偏好对之间出现非传递性三元组。为此，我们提出了LLM-RankFusion框架，旨在减少这些不一致性，生成更稳健的排序列表。该框架利用情境学习（ICL）进行顺序无关的比较和校准，以评估段落间的潜在偏好概率，并聚合多个排序器的结果以解决传递性问题。实验证明，LLM-RankFusion能有效减少不一致的比较结果，提升排序质量，使最终列表更为稳健。

> Ranking passages by prompting a large language model (LLM) can achieve promising performance in modern information retrieval (IR) systems. A common approach is to sort the ranking list by prompting LLMs for pairwise comparison. However, sorting-based methods require consistent comparisons to correctly sort the passages, which we show that LLMs often violate. We identify two kinds of intrinsic inconsistency in LLM-based pairwise comparisons: order inconsistency which leads to conflicting results when switching the passage order, and transitive inconsistency which leads to non-transitive triads among all preference pairs. In this paper, we propose LLM-RankFusion, an LLM-based ranking framework that mitigates these inconsistencies and produces a robust ranking list. LLM-RankFusion mitigates order inconsistency using in-context learning (ICL) to demonstrate order-agnostic comparisons and calibration to estimate the underlying preference probability between two passages. We then address transitive inconsistency by aggregating the ranking results from multiple rankers. In our experiments, we empirically show that LLM-RankFusion can significantly reduce inconsistent pairwise comparison results, and improve the ranking quality by making the final ranking list more robust.

![LLM-RankFusion：调和基于大型语言模型的排序系统中的内在矛盾](../../../paper_images/2406.00231/x1.png)

[Arxiv](https://arxiv.org/abs/2406.00231)