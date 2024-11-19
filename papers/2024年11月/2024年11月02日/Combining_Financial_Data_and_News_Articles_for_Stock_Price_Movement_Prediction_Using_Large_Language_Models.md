# 利用大型语言模型，将金融数据与新闻文章相结合来预测股票价格走势

发布时间：2024年11月02日

`LLM应用`

> Combining Financial Data and News Articles for Stock Price Movement Prediction Using Large Language Models

# 摘要

> 预测金融市场和股票价格的变动，得分析公司业绩、历史价格走势、行业特定事件，还有像社交媒体和新闻报道这类人为因素的影响。我们认为财务报告（像损益表、资产负债表、现金流量表）、历史价格数据和近期新闻文章能共同体现上述因素。我们把表格形式的财务数据跟文本新闻文章结合起来，运用预训练的大型语言模型（LLMs）去预测市场动态。LLMs 的最新研究显示，它们能完成表格和文本分类任务，所以成了我们给多模态数据分类的主要模型。我们使用检索增强技术，检索并把与公司有关的新闻文章的相关部分附加到财务指标上，在零、二和四样本的设定下提示 LLMs。我们的数据集涵盖了从不同来源收集的新闻文章、历史股票价格以及 20 家在股票市场不同行业交易量最高的公司的财务报告数据。我们为基于 LLM 的分类器采用了近期发布的语言模型，包括 GPT-3 和 4 以及 LLaMA-2 和 3 模型。我们推出了一个基于 LLM 的分类器，能够利用表格（结构化）和文本（非结构化）数据的组合执行分类任务。通过使用这个模型，我们预测了数据集中给定股票的价格走势，在 3 个月和 6 个月期间的加权 F1 分数分别是 58.5％和 59.1％，马修斯相关系数都是 0.175。

> Predicting financial markets and stock price movements requires analyzing a company's performance, historic price movements, industry-specific events alongside the influence of human factors such as social media and press coverage. We assume that financial reports (such as income statements, balance sheets, and cash flow statements), historical price data, and recent news articles can collectively represent aforementioned factors. We combine financial data in tabular format with textual news articles and employ pre-trained Large Language Models (LLMs) to predict market movements. Recent research in LLMs has demonstrated that they are able to perform both tabular and text classification tasks, making them our primary model to classify the multi-modal data. We utilize retrieval augmentation techniques to retrieve and attach relevant chunks of news articles to financial metrics related to a company and prompt the LLMs in zero, two, and four-shot settings. Our dataset contains news articles collected from different sources, historic stock price, and financial report data for 20 companies with the highest trading volume across different industries in the stock market. We utilized recently released language models for our LLM-based classifier, including GPT- 3 and 4, and LLaMA- 2 and 3 models. We introduce an LLM-based classifier capable of performing classification tasks using combination of tabular (structured) and textual (unstructured) data. By using this model, we predicted the movement of a given stock's price in our dataset with a weighted F1-score of 58.5% and 59.1% and Matthews Correlation Coefficient of 0.175 for both 3-month and 6-month periods.

[Arxiv](https://arxiv.org/abs/2411.01368)