# 少样本持续关系提取中，如何保持语言模型的泛化能力？

发布时间：2024年09月30日

`LLM应用` `人工智能`

> Preserving Generalization of Language models in Few-shot Continual Relation Extraction

# 摘要

> Few-shot Continual Relations Extraction (FCRE) 是一个充满活力的研究领域，模型能在有限标注数据下整合新知识，同时避免遗忘并保留预训练知识。我们提出了一种新方法，利用常被忽视的语言模型头部，通过互信息最大化策略，保持预训练知识的连续性，并优化分类性能。此外，我们探索了大型语言模型 (LLM) 在 FCRE 中的应用潜力。实验结果表明，该方法有效，并为未来研究提供了重要启示。

> Few-shot Continual Relations Extraction (FCRE) is an emerging and dynamic area of study where models can sequentially integrate knowledge from new relations with limited labeled data while circumventing catastrophic forgetting and preserving prior knowledge from pre-trained backbones. In this work, we introduce a novel method that leverages often-discarded language model heads. By employing these components via a mutual information maximization strategy, our approach helps maintain prior knowledge from the pre-trained backbone and strategically aligns the primary classification head, thereby enhancing model performance. Furthermore, we explore the potential of Large Language Models (LLMs), renowned for their wealth of knowledge, in addressing FCRE challenges. Our comprehensive experimental results underscore the efficacy of the proposed method and offer valuable insights for future work.

[Arxiv](https://arxiv.org/abs/2410.00334)