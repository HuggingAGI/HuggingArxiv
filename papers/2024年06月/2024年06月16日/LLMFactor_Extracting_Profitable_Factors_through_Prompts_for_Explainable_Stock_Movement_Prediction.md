# LLMFactor：利用提示挖掘股票变动预测中的盈利因子，实现预测的可解释性

发布时间：2024年06月16日

`LLM应用

理由：这篇论文介绍了一个名为LLMFactor的框架，该框架利用大型语言模型（LLMs）的能力来分析金融领域的时间序列数据，特别是股票市场。它通过序列知识引导提示（SKGP）从LLMs中提取影响股票市场的关键因素，并使用这些信息进行股票走势分析预测。这种方法直接应用于实际的金融数据分析和预测，属于LLM在特定领域的应用，因此归类为LLM应用。` `股票市场`

> LLMFactor: Extracting Profitable Factors through Prompts for Explainable Stock Movement Prediction

# 摘要

> 大型语言模型（LLMs）近期因其出色的文本分析能力而备受瞩目，但金融领域因其对时间序列数据的依赖而面临特殊挑战。本研究推出的LLMFactor框架，通过序列知识引导提示（SKGP），直接从LLMs中提取影响股票市场的关键因素，不同于以往的关键词或情感分析方法。该框架采用填空策略构建背景知识，并从新闻中识别影响股价的因素，进而利用这些信息预测股票走势。在美中股市的四个数据集上的测试表明，LLMFactor不仅超越了现有技术，而且在金融时间序列预测中表现出色。

> Recently, Large Language Models (LLMs) have attracted significant attention for their exceptional performance across a broad range of tasks, particularly in text analysis. However, the finance sector presents a distinct challenge due to its dependence on time-series data for complex forecasting tasks. In this study, we introduce a novel framework called LLMFactor, which employs Sequential Knowledge-Guided Prompting (SKGP) to identify factors that influence stock movements using LLMs. Unlike previous methods that relied on keyphrases or sentiment analysis, this approach focuses on extracting factors more directly related to stock market dynamics, providing clear explanations for complex temporal changes. Our framework directs the LLMs to create background knowledge through a fill-in-the-blank strategy and then discerns potential factors affecting stock prices from related news. Guided by background knowledge and identified factors, we leverage historical stock prices in textual format to predict stock movement. An extensive evaluation of the LLMFactor framework across four benchmark datasets from both the U.S. and Chinese stock markets demonstrates its superiority over existing state-of-the-art methods and its effectiveness in financial time-series forecasting.

![LLMFactor：利用提示挖掘股票变动预测中的盈利因子，实现预测的可解释性](../../../paper_images/2406.10811/outline.jpg)

![LLMFactor：利用提示挖掘股票变动预测中的盈利因子，实现预测的可解释性](../../../paper_images/2406.10811/overall.jpg)

![LLMFactor：利用提示挖掘股票变动预测中的盈利因子，实现预测的可解释性](../../../paper_images/2406.10811/casestudy.jpg)

[Arxiv](https://arxiv.org/abs/2406.10811)