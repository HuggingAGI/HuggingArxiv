# AI 在投资分析领域：用于股票评级的大型语言模型

发布时间：2024年10月30日

`LLM应用`

> AI in Investment Analysis: LLMs for Equity Stock Ratings

# 摘要

> 投资分析乃金融服务行业的基石。先进机器学习技术，尤其是大型语言模型（LLMs）的迅速融合，为优化股票评级流程带来契机。此文探讨借助摄取各类数据集来运用 LLMs 生成多时期股票评级。传统股票评级方法高度依赖金融分析师的专长，且面临诸多挑战，如数据过载、文件不一致以及对市场事件反应迟缓等。我们的研究借助 LLMs 来化解这些难题，以提升股票评级的精准度和一致性。另外，我们还评估了在金融领域采用不同数据模式搭配 LLMs 的成效。
  我们运用涵盖 2022 年 1 月至 2024 年 6 月的基础财务、市场和新闻数据等多样数据集，以及 GPT-4-32k（v0613）（训练截止于 2021 年 9 月以防信息泄露）。我们的成果显示，以前瞻性回报评估，我们的基准方法优于传统股票评级方法，尤其在纳入财务基本面时。虽说整合新闻数据能提升短期表现，但用情绪评分替代详尽的新闻摘要可减少令牌使用且不影响性能。在不少情形下，完全舍弃新闻数据能通过降低偏差来增强性能。
  我们的研究表明，LLMs 能够被用于有效利用大量多模式金融数据，其在股票评级预测任务中的出色表现便是明证。我们的工作为生成准确的股票评级提供了可重现且高效的框架，是传统方法经济有效的替代之选。未来工作将延伸至更长时间跨度，纳入多元数据，并运用更新的模型以获取更深刻的洞察。

> Investment Analysis is a cornerstone of the Financial Services industry. The rapid integration of advanced machine learning techniques, particularly Large Language Models (LLMs), offers opportunities to enhance the equity rating process. This paper explores the application of LLMs to generate multi-horizon stock ratings by ingesting diverse datasets. Traditional stock rating methods rely heavily on the expertise of financial analysts, and face several challenges such as data overload, inconsistencies in filings, and delayed reactions to market events. Our study addresses these issues by leveraging LLMs to improve the accuracy and consistency of stock ratings. Additionally, we assess the efficacy of using different data modalities with LLMs for the financial domain.
  We utilize varied datasets comprising fundamental financial, market, and news data from January 2022 to June 2024, along with GPT-4-32k (v0613) (with a training cutoff in Sep. 2021 to prevent information leakage). Our results show that our benchmark method outperforms traditional stock rating methods when assessed by forward returns, specially when incorporating financial fundamentals. While integrating news data improves short-term performance, substituting detailed news summaries with sentiment scores reduces token use without loss of performance. In many cases, omitting news data entirely enhances performance by reducing bias.
  Our research shows that LLMs can be leveraged to effectively utilize large amounts of multimodal financial data, as showcased by their effectiveness at the stock rating prediction task. Our work provides a reproducible and efficient framework for generating accurate stock ratings, serving as a cost-effective alternative to traditional methods. Future work will extend to longer timeframes, incorporate diverse data, and utilize newer models for enhanced insights.

[Arxiv](https://arxiv.org/abs/2411.00856)