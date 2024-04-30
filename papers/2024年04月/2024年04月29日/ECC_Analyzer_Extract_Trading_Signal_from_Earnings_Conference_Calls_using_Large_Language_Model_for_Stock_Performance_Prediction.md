# ECC分析器：利用大型语言模型分析收益电话会议，从中提取交易信号，以预测股票市场表现。

发布时间：2024年04月29日

`LLM应用` `金融分析` `多模态技术`

> ECC Analyzer: Extract Trading Signal from Earnings Conference Calls using Large Language Model for Stock Performance Prediction

# 摘要

> 在金融分析界，运用诸如收益电话会议（ECCs）这类非结构化数据来预测股票走势，是一个至关重要且充满挑战的任务，它不仅吸引了学术界的目光，也引起了投资者的广泛关注。尽管先前的研究已经借助基于深度学习的模型对ECCs进行了概览性分析，但这些研究往往忽略了更为细致和复杂的信息。本研究提出了一个创新的框架——\textbf{ECC分析器}，它融合了大型语言模型（LLMs）和多模态技术，以提取更深层次、更具前瞻性的洞见。该模型首先通过分析音频中的音调和音高变化，来概括通话记录的结构，并评估发言者的态度和信心水平，帮助投资者构建对ECCs的宏观理解。此外，模型采用基于检索增强生成（RAG）的方法，细致地筛选出从专家视角看对股票表现有显著影响的关键点，进行更为精准的分析。模型不止步于此，它还通过情感分析和音频片段特征等更多层次的分析，进一步丰富了这些关键点。通过综合这些洞见，ECC分析器能够对股票表现进行多任务预测，包括波动性、风险价值（VaR）和不同时间间隔的回报。研究结果表明，我们的模型在性能上超越了传统分析方法，验证了在金融分析中应用高级LLM技术的有效性。

> In the realm of financial analytics, leveraging unstructured data, such as earnings conference calls (ECCs), to forecast stock performance is a critical challenge that has attracted both academics and investors. While previous studies have used deep learning-based models to obtain a general view of ECCs, they often fail to capture detailed, complex information. Our study introduces a novel framework: \textbf{ECC Analyzer}, combining Large Language Models (LLMs) and multi-modal techniques to extract richer, more predictive insights. The model begins by summarizing the transcript's structure and analyzing the speakers' mode and confidence level by detecting variations in tone and pitch for audio. This analysis helps investors form an overview perception of the ECCs. Moreover, this model uses the Retrieval-Augmented Generation (RAG) based methods to meticulously extract the focuses that have a significant impact on stock performance from an expert's perspective, providing a more targeted analysis. The model goes a step further by enriching these extracted focuses with additional layers of analysis, such as sentiment and audio segment features. By integrating these insights, the ECC Analyzer performs multi-task predictions of stock performance, including volatility, value-at-risk (VaR), and return for different intervals. The results show that our model outperforms traditional analytic benchmarks, confirming the effectiveness of using advanced LLM techniques in financial analytics.

[Arxiv](https://arxiv.org/abs/2404.18470)