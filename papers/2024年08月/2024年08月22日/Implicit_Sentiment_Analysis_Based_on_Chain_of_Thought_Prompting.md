# 思维链提示驱动下的隐式情感分析

发布时间：2024年08月22日

`LLM应用` `电子产品`

> Implicit Sentiment Analysis Based on Chain of Thought Prompting

# 摘要

> 隐式情感分析（ISA）在自然语言处理领域至关重要。本文受大型语言模型思维链（CoT）启发，提出了思维情感分析（SAoT）框架。该框架首先通过常识和思维链能力解析文本中的隐含方面和观点，进而反思分析过程，最终确定情感极性。在SemEval 2014数据集上，该模型表现卓越，特别是在餐厅评论和笔记本电脑评论数据集上，F1分数和ISA分数均显著提升。与BERTAsp + SCAPt基线相比，ERNIE-Bot-4+SAoT模型平均性能提升达47.99%。

> Implicit Sentiment Analysis (ISA) is a crucial research area in natural language processing. Inspired by the idea of large language model Chain of Thought (CoT), this paper introduces a Sentiment Analysis of Thinking (SAoT) framework. The framework first analyzes the implicit aspects and opinions in the text using common sense and thinking chain capabilities. Then, it reflects on the process of implicit sentiment analysis and finally deduces the polarity of sentiment. The model is evaluated on the SemEval 2014 dataset, consisting of 1120 restaurant reviews and 638 laptop reviews. The experimental results demonstrate that the utilization of the ERNIE-Bot-4+SAoT model yields a notable performance improvement. Specifically, on the restaurant dataset, the F1 score reaches 75.27, accompanied by an ISA score of 66.29. Similarly, on the computer dataset, the F1 score achieves 76.50, while the ISA score amounts to 73.46. Comparatively, the ERNIE-Bot-4+SAoT model surpasses the BERTAsp + SCAPt baseline by an average margin of 47.99%.

[Arxiv](https://arxiv.org/abs/2408.12157)