# 探索基于 ChatGPT 的增强策略，应用于对比方面情感分析

发布时间：2024年09月17日

`LLM应用` `情感分析` `数据增强`

> Exploring ChatGPT-based Augmentation Strategies for Contrastive Aspect-based Sentiment Analysis

# 摘要

> 基于方面的情感分析 (ABSA) 旨在识别句子中对特定方面的情感，揭示产品、服务或主题的细微视角。然而，标签数据的稀缺性对模型训练构成挑战。为此，我们利用 ChatGPT 进行数据增强，探索了三种策略：以上下文为中心、以方面为中心和上下文-方面数据增强。实验结果显示，所有策略均提升了性能，其中上下文-方面数据增强效果最佳，超越了基线模型。

> Aspect-based sentiment analysis (ABSA) involves identifying sentiment towards specific aspect terms in a sentence and allows us to uncover nuanced perspectives and attitudes on particular aspects of a product, service, or topic. However, the scarcity of labeled data poses a significant challenge to training high-quality models. To address this issue, we explore the potential of data augmentation using ChatGPT, a well-performing large language model (LLM), to enhance the sentiment classification performance towards aspect terms. Specifically, we explore three data augmentation strategies based on ChatGPT: context-focused, aspect-focused, and context-aspect data augmentation techniques. Context-focused data augmentation focuses on changing the word expression of context words in the sentence while keeping aspect terms unchanged. In contrast, aspect-focused data augmentation aims to change aspect terms but keep context words unchanged. Context-Aspect data augmentation integrates the above two data augmentations to generate augmented samples. Furthermore, we incorporate contrastive learning into the ABSA tasks to improve performance. Extensive experiments show that all three data augmentation techniques lead to performance improvements, with the context-aspect data augmentation strategy performing best and surpassing the performance of the baseline models.

[Arxiv](https://arxiv.org/abs/2409.11218)