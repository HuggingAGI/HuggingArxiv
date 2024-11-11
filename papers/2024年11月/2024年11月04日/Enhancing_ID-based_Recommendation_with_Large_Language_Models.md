# 用大型语言模型增强基于 ID 的推荐

发布时间：2024年11月04日

`LLM应用` `推荐系统` `语言模型`

> Enhancing ID-based Recommendation with Large Language Models

# 摘要

> 大型语言模型（LLMs）最近在包括推荐系统在内的各个领域引起了极大的关注。最近的研究利用 LLMs 的能力来提高推荐系统的性能和用户建模方面。这些研究主要侧重于利用 LLMs 在推荐任务中解释文本数据。然而，值得注意的是，在基于 ID 的推荐中，不存在文本数据，只有 ID 数据可用。LLMs 在基于 ID 的推荐范式中对于 ID 数据的未开发潜力仍然相对未被探索。为此，我们引入了一种开创性的方法，称为“基于 ID 推荐的 LLMs”（LLM4IDRec）。这种创新方法整合了 LLMs 的能力，同时仅依赖于 ID 数据，从而与之前对文本数据的依赖不同。LLM4IDRec 的基本思想是，通过使用 LLMs 来增强 ID 数据，如果增强的 ID 数据可以提高推荐性能，这表明 LLMs 有效地解释 ID 数据的能力，为 LLMs 在基于 ID 的推荐中的整合探索了一种创新方式。我们使用三个广泛使用的数据集评估了我们的 LLM4IDRec 方法的有效性。我们的结果表明推荐性能有显著提高，我们的方法仅通过增强输入数据就在基于 ID 的推荐中始终优于现有方法。

> Large Language Models (LLMs) have recently garnered significant attention in various domains, including recommendation systems. Recent research leverages the capabilities of LLMs to improve the performance and user modeling aspects of recommender systems. These studies primarily focus on utilizing LLMs to interpret textual data in recommendation tasks. However, it's worth noting that in ID-based recommendations, textual data is absent, and only ID data is available. The untapped potential of LLMs for ID data within the ID-based recommendation paradigm remains relatively unexplored. To this end, we introduce a pioneering approach called "LLM for ID-based Recommendation" (LLM4IDRec). This innovative approach integrates the capabilities of LLMs while exclusively relying on ID data, thus diverging from the previous reliance on textual data. The basic idea of LLM4IDRec is that by employing LLM to augment ID data, if augmented ID data can improve recommendation performance, it demonstrates the ability of LLM to interpret ID data effectively, exploring an innovative way for the integration of LLM in ID-based recommendation. We evaluate the effectiveness of our LLM4IDRec approach using three widely-used datasets. Our results demonstrate a notable improvement in recommendation performance, with our approach consistently outperforming existing methods in ID-based recommendation by solely augmenting input data.

[Arxiv](https://arxiv.org/abs/2411.02041)