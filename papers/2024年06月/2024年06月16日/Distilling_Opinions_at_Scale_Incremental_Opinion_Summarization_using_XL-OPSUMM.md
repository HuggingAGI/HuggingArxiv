# 利用XL-OPSUMM技术，我们实现了大规模的意见提取与增量摘要，高效汇聚众声。

发布时间：2024年06月16日

`LLM应用

这篇论文主要介绍了在电子商务领域中，针对大量简短评论的意见总结任务，开发了一个可扩展框架Xl-OpSumm，并创建了新的测试集Xl-Flipkart来验证其性能。该框架利用了大型语言模型（LLMs），并在特定的数据集上展示了优于其他模型的性能。因此，这项工作属于LLM应用类别，因为它专注于开发和应用LLM技术来解决实际问题，即在电子商务中的意见总结任务。` `电子商务` `文本摘要`

> Distilling Opinions at Scale: Incremental Opinion Summarization using XL-OPSUMM

# 摘要

> 在电子商务领域，意见总结旨在提炼众多用户基于评论对产品的集体看法。尽管大型语言模型（LLMs）在总结任务上表现出色，但面对每件商品数千条、每条仅10-15字的评论时，它们因上下文限制而力不从心。为此，我们开发了可扩展框架Xl-OpSumm，它能逐步生成总结。然而，现有测试集AMASUM每个产品平均仅包含560条评论，远不足以验证。因此，我们创建了新的测试集Xl-Flipkart，通过Flipkart网站数据和GPT-4生成总结。经过自动评估和深入分析，我们的框架Xl-OpSumm（搭载Llama-3-8B-8k）在AMASUM和Xl-Flipkart数据集上表现卓越，ROUGE-1 F1得分平均提升4.38%，ROUGE-L F1得分提升3.70%，超越了其他模型。

> Opinion summarization in e-commerce encapsulates the collective views of numerous users about a product based on their reviews. Typically, a product on an e-commerce platform has thousands of reviews, each review comprising around 10-15 words. While Large Language Models (LLMs) have shown proficiency in summarization tasks, they struggle to handle such a large volume of reviews due to context limitations. To mitigate, we propose a scalable framework called Xl-OpSumm that generates summaries incrementally. However, the existing test set, AMASUM has only 560 reviews per product on average. Due to the lack of a test set with thousands of reviews, we created a new test set called Xl-Flipkart by gathering data from the Flipkart website and generating summaries using GPT-4. Through various automatic evaluations and extensive analysis, we evaluated the framework's efficiency on two datasets, AMASUM and Xl-Flipkart. Experimental results show that our framework, Xl-OpSumm powered by Llama-3-8B-8k, achieves an average ROUGE-1 F1 gain of 4.38% and a ROUGE-L F1 gain of 3.70% over the next best-performing model.

![利用XL-OPSUMM技术，我们实现了大规模的意见提取与增量摘要，高效汇聚众声。](../../../paper_images/2406.10886/x1.png)

[Arxiv](https://arxiv.org/abs/2406.10886)