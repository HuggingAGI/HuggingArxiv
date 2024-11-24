# 甄别坏种子：加密货币滥用报告的自动分类

发布时间：2024年10月28日

`LLM应用` `加密货币`

> Sorting Out the Bad Seeds: Automatic Classification of Cryptocurrency Abuse Reports

# 摘要

> 滥用举报服务会收集有关受虐受害者所遭受情况的报告。对提交的报告进行准确分类，对于分析不同滥用类型（如性勒索、投资、浪漫骗局等）的流行程度和财务影响至关重要。当前的分类方法存在问题，因为它们要么要求举报人从列表中选择滥用类型，假定举报人具备分类所需的经验，而我们发现实际往往并非如此；要么需要分析师手动分类，这难以大规模开展。为解决这些问题，本文提出了一种新的方法，用于自动对加密货币滥用报告进行分类。我们首先构建了 19 种常见的滥用类型分类体系。以举报人所写的文本描述为输入，我们的分类器借助大型语言模型（LLM）来解读文本，并在我们的分类体系中为其分配滥用类型。我们从两个热门的举报服务——BitcoinAbuse 和 BBB 的 ScamTracker 收集了 29 万份加密货币滥用报告。我们为其中 2 万份报告构建了真实数据集，并利用它们来评估我们基于 LLM 的分类器的三种设计、四个 LLM 以及作为基线的监督式 ML 分类器。我们基于 LLM 的分类器实现了 0.92 的精度、0.87 的召回率和 0.89 的 F1 分数，而基线的 F1 分数为 0.55。我们在两个应用中展示了我们的分类器：为细粒度的滥用类型提供财务损失统计数据，以及为加密货币分析平台生成标记地址。

> Abuse reporting services collect reports about abuse victims have suffered. Accurate classification of the submitted reports is fundamental to analyzing the prevalence and financial impact of different abuse types (e.g., sextortion, investment, romance). Current classification approaches are problematic because they require the reporter to select the abuse type from a list, assuming the reporter has the necessary experience for the classification, which we show is frequently not the case, or require manual classification by analysts, which does not scale. To address these issues, this paper presents a novel approach to classify cryptocurrency abuse reports automatically. We first build a taxonomy of 19 frequently reported abuse types. Given as input the textual description written by the reporter, our classifier leverages a large language model (LLM) to interpret the text and assign it an abuse type in our taxonomy. We collect 290K cryptocurrency abuse reports from two popular reporting services: BitcoinAbuse and BBB's ScamTracker. We build ground truth datasets for 20K of those reports and use them to evaluate three designs for our LLM-based classifier and four LLMs, as well as a supervised ML classifier used as a baseline. Our LLM-based classifier achieves a precision of 0.92, a recall of 0.87, and an F1 score of 0.89, compared to an F1 score of 0.55 for the baseline. We demonstrate our classifier in two applications: providing financial loss statistics for fine-grained abuse types and generating tagged addresses for cryptocurrency analysis platforms.

[Arxiv](https://arxiv.org/abs/2410.21041)