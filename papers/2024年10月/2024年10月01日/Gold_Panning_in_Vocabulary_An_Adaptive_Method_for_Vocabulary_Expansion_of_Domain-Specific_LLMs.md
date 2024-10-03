# 词汇淘金术：一种专为特定领域 LLM 词汇扩展量身定制的自适应方法

发布时间：2024年10月01日

`LLM应用` `人工智能`

> Gold Panning in Vocabulary: An Adaptive Method for Vocabulary Expansion of Domain-Specific LLMs

# 摘要

> 尽管 LLM 在生成任务中表现出色，但在特定领域却常因知识有限而受限。现有研究多在微调前扩展词汇，以缩短序列长度并提高解码效率，却未深入探讨词汇扩展对不同领域 LLM 的影响。我们的初步研究发现，仅扩展部分词汇即可显著提升性能。基于此，本文探讨了如何精准选择词汇子集以达到最佳效果。我们提出了 VEGAD，一种自动识别领域词汇中有价值单词的自适应方法。实验证明，VEGAD 在三个中文数据集上表现出色，且经过全面分析，扩展最佳子集不仅能提升特定领域任务性能，还能增强一般任务表现，充分展现了 VEGAD 的潜力。

> While Large Language Models (LLMs) demonstrate impressive generation abilities, they frequently struggle when it comes to specialized domains due to their limited domain-specific knowledge. Studies on domain-specific LLMs resort to expanding the vocabulary before fine-tuning on domain-specific corpus, aiming to decrease the sequence length and enhance efficiency during decoding, without thoroughly investigating the results of vocabulary expansion to LLMs over different domains. Our pilot study reveals that expansion with only a subset of the entire vocabulary may lead to superior performance. Guided by the discovery, this paper explores how to identify a vocabulary subset to achieve the optimal results. We introduce VEGAD, an adaptive method that automatically identifies valuable words from a given domain vocabulary. Our method has been validated through experiments on three Chinese datasets, demonstrating its effectiveness. Additionally, we have undertaken comprehensive analyses of the method. The selection of a optimal subset for expansion has shown to enhance performance on both domain-specific tasks and general tasks, showcasing the potential of VEGAD.

[Arxiv](https://arxiv.org/abs/2410.01188)