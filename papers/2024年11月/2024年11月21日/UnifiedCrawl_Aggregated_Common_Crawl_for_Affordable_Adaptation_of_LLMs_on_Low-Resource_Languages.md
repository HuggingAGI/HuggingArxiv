# UnifiedCrawl：聚合 Common Crawl 以经济实惠地适配大型语言模型于低资源语言

发布时间：2024年11月21日

`LLM应用` `低资源语言`

> UnifiedCrawl: Aggregated Common Crawl for Affordable Adaptation of LLMs on Low-Resource Languages

# 摘要

> 大型语言模型（LLMs）在低资源语言方面表现欠佳，这是由于训练数据有限。我们给出了一种能从整个 Common Crawl 语料库为低资源语言高效收集文本数据的办法。我们的方法，即 UnifiedCrawl，凭借最少的计算资源对 Common Crawl 进行过滤与提取，所生成的单语数据集比以往的可用资源大得多。我们证实，借助高效的适配器方法（QLoRA）利用这些数据对多语言 LLMs 进行微调，能够显著提升低资源语言的性能，同时最大程度减少 VRAM 的使用。我们的实验显示，语言建模的困惑度大幅改善，少样本提示的分数也有所提高。我们的工作以及发布的源代码为使用消费级硬件改进低资源语言的 LLMs 提供了一种实惠的途径。我们的源代码可在 https://github.com/bethelmelesse/unifiedcrawl 处获取。

> Large language models (LLMs) under-perform on low-resource languages due to limited training data. We present a method to efficiently collect text data for low-resource languages from the entire Common Crawl corpus. Our approach, UnifiedCrawl, filters and extracts common crawl using minimal compute resources, yielding mono-lingual datasets much larger than previously available sources. We demonstrate that leveraging this data to fine-tuning multilingual LLMs via efficient adapter methods (QLoRA) significantly boosts performance on the low-resource language, while minimizing VRAM usage. Our experiments show large improvements in language modeling perplexity and an increase in few-shot prompting scores. Our work and released source code provide an affordable approach to improve LLMs for low-resource languages using consumer hardware. Our source code is available here at https://github.com/bethelmelesse/unifiedcrawl.

[Arxiv](https://arxiv.org/abs/2411.14343)