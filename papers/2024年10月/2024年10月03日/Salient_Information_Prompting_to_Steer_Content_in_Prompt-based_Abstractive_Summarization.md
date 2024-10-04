# 通过显著信息提示，精准引导基于提示的抽象摘要内容生成。

发布时间：2024年10月03日

`LLM应用` `文本摘要`

> Salient Information Prompting to Steer Content in Prompt-based Abstractive Summarization

# 摘要

> 大型语言模型 (LLM) 通过提示技术能够跨领域生成流畅的摘要，从而减少了对专门训练摘要模型的需求。然而，如何设计有效的提示，使 LLM 生成既详细又符合风格的摘要，仍是一大挑战。本文探讨了利用源文档中的显著信息来优化摘要提示的方法。实验表明，在提示中加入关键词能显著提升 ROUGE F1 和召回率，使生成的摘要更贴近参考标准且更全面。关键词的数量还能调节精确度与召回率之间的平衡。此外，研究发现，整合短语级别的显著信息比单词或句子级别更为有效。不过，这种优化对幻觉现象的影响在不同 LLM 中表现不一。为此，我们开发了轻量级模型关键词信号提取器 (SigExt)，通过微调提取显著关键词，从而在无需定制 LLM 的情况下，实现了跨数据集和不同类型 LLM 的一致性 ROUGE 提升。这些发现为构建基于提示的摘要系统提供了宝贵的见解。

> Large language models (LLMs) can generate fluent summaries across domains using prompting techniques, reducing the need to train models for summarization applications. However, crafting effective prompts that guide LLMs to generate summaries with the appropriate level of detail and writing style remains a challenge. In this paper, we explore the use of salient information extracted from the source document to enhance summarization prompts. We show that adding keyphrases in prompts can improve ROUGE F1 and recall, making the generated summaries more similar to the reference and more complete. The number of keyphrases can control the precision-recall trade-off. Furthermore, our analysis reveals that incorporating phrase-level salient information is superior to word- or sentence-level. However, the impact on hallucination is not universally positive across LLMs. To conduct this analysis, we introduce Keyphrase Signal Extractor (SigExt), a lightweight model that can be finetuned to extract salient keyphrases. By using SigExt, we achieve consistent ROUGE improvements across datasets and open-weight and proprietary LLMs without any LLM customization. Our findings provide insights into leveraging salient information in building prompt-based summarization systems.

[Arxiv](https://arxiv.org/abs/2410.02741)