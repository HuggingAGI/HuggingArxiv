# 探索大型语言模型在检索判断中的知识边界

发布时间：2024年11月09日

`RAG` `语言模型` `知识检索`

> Exploring Knowledge Boundaries in Large Language Models for Retrieval Judgment

# 摘要

> 大型语言模型（LLMs）因其实际应用而日益受到认可。然而，这些模型在动态变化的知识以及管理未知的静态知识方面经常遇到挑战。检索增强生成（RAG）解决了这一挑战，并对 LLMs 产生了重大影响。实际上，我们发现 RAG 对 LLMs 问答能力的影响可分为三组：有益的、中性的和有害的。通过最小化产生中性或有害结果的检索请求，我们可以有效地减少时间和计算成本，同时也提高 LLMs 的整体性能。这一见解促使我们使用某些指标作为指标来区分问题类型，以在不影响性能的情况下降低检索率。在我们的工作中，我们提出了一种能够从这个角度通过训练知识边界模型（KBM）来识别不同类型问题的方法。在 11 个英语和中文数据集上进行的实验表明，KBM 有效地描绘了知识边界，显著降低了实现最佳端到端性能所需的检索比例。具体而言，我们在三个复杂场景中评估了 KBM 的有效性：动态知识、长尾静态知识和多跳问题，以及其作为外部 LLMs 插件的功能。

> Large Language Models (LLMs) are increasingly recognized for their practical applications. However, these models often encounter challenges in dynamically changing knowledge, as well as in managing unknown static knowledge. Retrieval-Augmented Generation (RAG) tackles this challenge and has shown a significant impact on LLMs. Actually, we find that the impact of RAG on the question answering capabilities of LLMs can be categorized into three groups: beneficial, neutral, and harmful. By minimizing retrieval requests that yield neutral or harmful results, we can effectively reduce both time and computational costs, while also improving the overall performance of LLMs. This insight motivates us to differentiate between types of questions using certain metrics as indicators, to decrease the retrieval ratio without compromising performance. In our work, we propose a method that is able to identify different types of questions from this view by training a Knowledge Boundary Model (KBM). Experiments conducted on 11 English and Chinese datasets illustrate that the KBM effectively delineates the knowledge boundary, significantly decreasing the proportion of retrievals required for optimal end-to-end performance. Specifically, we evaluate the effectiveness of KBM in three complex scenarios: dynamic knowledge, long-tail static knowledge, and multi-hop problems, as well as its functionality as an external LLM plug-in.

[Arxiv](https://arxiv.org/abs/2411.06207)