# CausalStock：用于新闻驱动的股票走势预测的深度端到端因果发现

发布时间：2024年11月10日

`LLM应用`

> CausalStock: Deep End-to-end Causal Discovery for News-driven Stock Movement Prediction

# 摘要

> 在新闻驱动的多股票走势预测任务中，现有工作中存在两个未得到很好解决的问题。一方面，在利用其他股票的价格信息实现准确的股票走势预测时，“关系发现”是关键部分。鉴于股票关系通常是单向的，例如“供应商 - 消费者”关系，因果关系更适合捕捉股票之间的影响。另一方面，新闻数据中存在大量噪声，导致难以提取有效信息。考虑到这两个问题，我们提出了一个名为 CausalStock 的新型框架用于新闻驱动的多股票走势预测，它发现了股票之间的时间因果关系。我们设计了一个依赖滞后的时间因果发现机制来对时间因果图分布进行建模。然后采用功能因果模型来封装发现的因果关系并预测股票走势。此外，我们利用大型语言模型（LLM）出色的文本评估能力，提出了一种去噪新闻编码器，从大量新闻数据中提取有用信息。实验结果表明，CausalStock 在从美国、中国、日本和英国市场收集的六个真实世界数据集中，对于新闻驱动的多股票走势预测和多股票走势预测任务，都优于强大的基线。此外，得益于因果关系，CausalStock 可以提供具有良好可解释性的清晰预测机制。

> There are two issues in news-driven multi-stock movement prediction tasks that are not well solved in the existing works. On the one hand, "relation discovery" is a pivotal part when leveraging the price information of other stocks to achieve accurate stock movement prediction. Given that stock relations are often unidirectional, such as the "supplier-consumer" relationship, causal relations are more appropriate to capture the impact between stocks. On the other hand, there is substantial noise existing in the news data leading to extracting effective information with difficulty. With these two issues in mind, we propose a novel framework called CausalStock for news-driven multi-stock movement prediction, which discovers the temporal causal relations between stocks. We design a lag-dependent temporal causal discovery mechanism to model the temporal causal graph distribution. Then a Functional Causal Model is employed to encapsulate the discovered causal relations and predict the stock movements. Additionally, we propose a Denoised News Encoder by taking advantage of the excellent text evaluation ability of large language models (LLMs) to extract useful information from massive news data. The experiment results show that CausalStock outperforms the strong baselines for both news-driven multi-stock movement prediction and multi-stock movement prediction tasks on six real-world datasets collected from the US, China, Japan, and UK markets. Moreover, getting benefit from the causal relations, CausalStock could offer a clear prediction mechanism with good explainability.

[Arxiv](https://arxiv.org/abs/2411.06391)