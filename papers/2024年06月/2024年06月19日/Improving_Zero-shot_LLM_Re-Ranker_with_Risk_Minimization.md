# 利用风险最小化策略，优化零-shot大型语言模型的重排能力

发布时间：2024年06月19日

`RAG

理由：这篇论文主要讨论了在RAG（Retrieval-Augmented Generation）系统中使用大型语言模型（LLMs）作为无监督的查询似然模型（QLMs）时存在的问题，并提出了一种新的框架$\mathrm{UR^3}$来减少偏差并优化查询与文档生成概率。这直接关联到RAG系统的改进和优化，因此属于RAG分类。` `问答系统` `信息检索`

> Improving Zero-shot LLM Re-Ranker with Risk Minimization

# 摘要

> 在RAG系统中，大型语言模型（LLMs）作为无监督的查询似然模型（QLMs），根据文档内容生成查询的概率对文档进行重新排序。但直接使用LLMs模拟QLMs存在固有偏差，可能导致估计分布与实际文档分布不符。本研究提出的新框架$\mathrm{UR^3}$，运用贝叶斯决策理论来量化并减少这种偏差，通过最大化文档生成概率，统一优化查询与文档生成概率，实现风险最小化。实证显示，$\mathrm{UR^3}$ 在提升Top-1准确性方面效果显著，尤其在问答任务中，通过减少所需文档数量提高了准确性。

> In the Retrieval-Augmented Generation (RAG) system, advanced Large Language Models (LLMs) have emerged as effective Query Likelihood Models (QLMs) in an unsupervised way, which re-rank documents based on the probability of generating the query given the content of a document. However, directly prompting LLMs to approximate QLMs inherently is biased, where the estimated distribution might diverge from the actual document-specific distribution. In this study, we introduce a novel framework, $\mathrm{UR^3}$, which leverages Bayesian decision theory to both quantify and mitigate this estimation bias. Specifically, $\mathrm{UR^3}$ reformulates the problem as maximizing the probability of document generation, thereby harmonizing the optimization of query and document generation probabilities under a unified risk minimization objective. Our empirical results indicate that $\mathrm{UR^3}$ significantly enhances re-ranking, particularly in improving the Top-1 accuracy. It benefits the QA tasks by achieving higher accuracy with fewer input documents.

![利用风险最小化策略，优化零-shot大型语言模型的重排能力](../../../paper_images/2406.13331/x1.png)

![利用风险最小化策略，优化零-shot大型语言模型的重排能力](../../../paper_images/2406.13331/x2.png)

![利用风险最小化策略，优化零-shot大型语言模型的重排能力](../../../paper_images/2406.13331/x3.png)

![利用风险最小化策略，优化零-shot大型语言模型的重排能力](../../../paper_images/2406.13331/x4.png)

![利用风险最小化策略，优化零-shot大型语言模型的重排能力](../../../paper_images/2406.13331/x5.png)

![利用风险最小化策略，优化零-shot大型语言模型的重排能力](../../../paper_images/2406.13331/x6.png)

![利用风险最小化策略，优化零-shot大型语言模型的重排能力](../../../paper_images/2406.13331/x7.png)

![利用风险最小化策略，优化零-shot大型语言模型的重排能力](../../../paper_images/2406.13331/appendix1.png)

![利用风险最小化策略，优化零-shot大型语言模型的重排能力](../../../paper_images/2406.13331/appendix2.png)

![利用风险最小化策略，优化零-shot大型语言模型的重排能力](../../../paper_images/2406.13331/x8.png)

![利用风险最小化策略，优化零-shot大型语言模型的重排能力](../../../paper_images/2406.13331/x9.png)

![利用风险最小化策略，优化零-shot大型语言模型的重排能力](../../../paper_images/2406.13331/x10.png)

[Arxiv](https://arxiv.org/abs/2406.13331)