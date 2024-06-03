# MetRoBERTa：借助传统CRM数据，打造交通主题敏感的语言模型

发布时间：2023年08月09日

`LLM应用

这篇论文主要描述了如何利用大型语言模型（LLM）来处理和分类来自乘客的开放式文本反馈，以帮助交通机构评估和改进服务。论文中提出的方法包括使用半监督学习从大量反馈数据中提取特定的交通主题，并训练一个基于RoBERTa的模型（MetRoBERTa）来分类这些反馈。这种方法的应用场景和目的是为了自动化处理大规模的乘客反馈，从而提升客户体验，这明显属于LLM的应用范畴。因此，将其分类为LLM应用是合适的。` `客户关系管理`

> MetRoBERTa: Leveraging Traditional Customer Relationship Management Data to Develop a Transit-Topic-Aware Language Model

# 摘要

> 乘客通过调查、CRM渠道及社交媒体提供的反馈，对交通机构评估服务和举措的有效性至关重要。然而，由于反馈文本的开放性和非结构化，全面理解这些体验颇具挑战。本文提出利用CRM反馈，开发一个能将开放式文本反馈分类至特定交通主题的大型语言模型（LLM）。我们首先通过半监督学习，从WMATA六年的反馈中提取11个交通主题，构建训练数据集。随后，我们训练并评估基于RoBERTa的模型MetRoBERTa，并与传统机器学习方法比较，结果显示MetRoBERTa在所有评估指标上均表现更佳，平均分类准确率达90%。最后，我们展示了如何将此语言模型与文本处理工具结合，应用于Twitter等反馈源，为其添加结构。这一框架和结果为交通机构提供了一种自动化、可推广的方法，以大规模处理和改善乘客反馈，从而提升客户体验。

> Transit riders' feedback provided in ridership surveys, customer relationship management (CRM) channels, and in more recent times, through social media is key for transit agencies to better gauge the efficacy of their services and initiatives. Getting a holistic understanding of riders' experience through the feedback shared in those instruments is often challenging, mostly due to the open-ended, unstructured nature of text feedback. In this paper, we propose leveraging traditional transit CRM feedback to develop and deploy a transit-topic-aware large language model (LLM) capable of classifying open-ended text feedback to relevant transit-specific topics. First, we utilize semi-supervised learning to engineer a training dataset of 11 broad transit topics detected in a corpus of 6 years of customer feedback provided to the Washington Metropolitan Area Transit Authority (WMATA). We then use this dataset to train and thoroughly evaluate a language model based on the RoBERTa architecture. We compare our LLM, MetRoBERTa, to classical machine learning approaches utilizing keyword-based and lexicon representations. Our model outperforms those methods across all evaluation metrics, providing an average topic classification accuracy of 90%. Finally, we provide a value proposition of this work demonstrating how the language model, alongside additional text processing tools, can be applied to add structure to open-ended text sources of feedback like Twitter. The framework and results we present provide a pathway for an automated, generalizable approach for ingesting, visualizing, and reporting transit riders' feedback at scale, enabling agencies to better understand and improve customer experience.

[Arxiv](https://arxiv.org/abs/2308.05012)