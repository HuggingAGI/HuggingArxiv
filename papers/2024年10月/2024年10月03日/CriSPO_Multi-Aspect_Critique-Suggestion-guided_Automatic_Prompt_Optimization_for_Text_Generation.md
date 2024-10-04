# CriSPO：一种多角度批评与建议引导的文本生成自动提示优化工具

发布时间：2024年10月03日

`LLM应用` `文本摘要`

> CriSPO: Multi-Aspect Critique-Suggestion-guided Automatic Prompt Optimization for Text Generation

# 摘要

> 大型语言模型 (LLM) 通过提示技术能够跨领域生成流畅的摘要，从而减少了对专门训练摘要模型的需求。然而，如何设计有效的提示，使 LLM 生成既详细又符合风格的摘要，仍是一个难题。本文探讨了利用源文档中的显著信息来优化摘要提示的方法。实验表明，在提示中加入关键词能显著提升 ROUGE F1 和召回率，使生成的摘要更接近参考标准且更完整。关键词的数量还能调节精确度与召回率之间的平衡。此外，研究发现，整合短语级别的显著信息比单词或句子级别更为有效。不过，这种优化对幻觉现象的影响在不同 LLM 中表现不一。为此，我们开发了关键词信号提取器 (CriSPO)，一个轻量级模型，可微调以提取显著关键词。使用 CriSPO，我们实现了在各类数据集和开源及专有 LLM 上的一致 ROUGE 提升，且无需对 LLM 进行定制。这些发现为构建基于提示的摘要系统提供了宝贵的见解。

> Large language models (LLMs) can generate fluent summaries across domains using prompting techniques, reducing the need to train models for summarization applications. However, crafting effective prompts that guide LLMs to generate summaries with the appropriate level of detail and writing style remains a challenge. In this paper, we explore the use of salient information extracted from the source document to enhance summarization prompts. We show that adding keyphrases in prompts can improve ROUGE F1 and recall, making the generated summaries more similar to the reference and more complete. The number of keyphrases can control the precision-recall trade-off. Furthermore, our analysis reveals that incorporating phrase-level salient information is superior to word- or sentence-level. However, the impact on hallucination is not universally positive across LLMs. To conduct this analysis, we introduce Keyphrase Signal Extractor (CriSPO), a lightweight model that can be finetuned to extract salient keyphrases. By using CriSPO, we achieve consistent ROUGE improvements across datasets and open-weight and proprietary LLMs without any LLM customization. Our findings provide insights into leveraging salient information in building prompt-based summarization systems.

[Arxiv](https://arxiv.org/abs/2410.02748)