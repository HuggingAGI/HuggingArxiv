# APrompt4EM：通用实体匹配的增强提示调优技术

发布时间：2024年05月08日

`Agent

理由：这篇论文主要讨论了广义实体匹配（GEM）任务，并提出了一个增强提示调优框架来解决现有模型在提示设计和信息差距上的挑战。虽然提到了预训练语言模型（PLMs）和微调LLMs，但重点在于提出和改进一个框架来执行特定的数据管理任务，即GEM。这更符合Agent的分类，因为它涉及创建一个能够执行特定任务的智能系统，而不是专注于LLM的理论研究或应用开发。此外，论文中提到的上下文化软令牌和成本效益信息增强策略，都是为了提高Agent在特定任务上的性能，进一步支持了这一分类。` `数据管理`

> APrompt4EM: Augmented Prompt Tuning for Generalized Entity Matching

# 摘要

> 广义实体匹配（GEM）是数据管理的关键任务，它判断不同格式的记录是否指向同一实体。预训练语言模型（PLMs）的提示调优，如PromptEM，为低资源GEM提供了有效解决方案。但现有模型在提示设计和信息差距上仍有挑战。本文提出的增强提示调优框架，通过上下文化软令牌和成本效益信息增强策略，有效应对这些挑战。实验证明，我们的模型在低资源GEM上表现出色，不仅在无信息增强下超越现有方法5.24%以上，而且在信息增强后，以不到14%的API费用，与微调LLMs的性能相媲美。

> Generalized Entity Matching (GEM), which aims at judging whether two records represented in different formats refer to the same real-world entity, is an essential task in data management. The prompt tuning paradigm for pre-trained language models (PLMs), including the recent PromptEM model, effectively addresses the challenges of low-resource GEM in practical applications, offering a robust solution when labeled data is scarce. However, existing prompt tuning models for GEM face the challenges of prompt design and information gap. This paper introduces an augmented prompt tuning framework for the challenges, which consists of two main improvements. The first is an augmented contextualized soft token-based prompt tuning method that extracts a guiding soft token benefit for the PLMs' prompt tuning, and the second is a cost-effective information augmentation strategy leveraging large language models (LLMs). Our approach performs well on the low-resource GEM challenges. Extensive experiments show promising advancements of our basic model without information augmentation over existing methods based on moderate-size PLMs (average 5.24%+), and our model with information augmentation achieves comparable performance compared with fine-tuned LLMs, using less than 14% of the API fee.

[Arxiv](https://arxiv.org/abs/2405.04820)