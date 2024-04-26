# 深入探究大型语言模型所引发嵌入的隐私风险

发布时间：2024年04月25日

`分类：LLM应用` `人工智能` `隐私保护`

> Understanding Privacy Risks of Embeddings Induced by Large Language Models

# 摘要

> 大型语言模型（LLMs）初显人工智能的通用性，却也易产生幻觉。一种缓解幻觉的潜在方法是将外部知识嵌入化，以辅助LLMs进行增强检索生成。但这种做法可能侵犯隐私，因为最新研究实验表明，预训练语言模型能够从文本嵌入中部分复原原始文本。LLMs相较于传统预训练模型的明显优势可能会加重这种隐私风险。本研究旨在探讨当LLMs投入使用时，从嵌入中重建原始知识和预测实体属性的有效性。实证结果揭示，LLMs在两项评估任务的准确度上显著超越了预训练模型，无论文本是否符合分布。这增加了LLMs威胁用户隐私的风险，凸显了它们普及可能带来的负面效应。我们进一步探讨了减轻这一风险的初步策略。

> Large language models (LLMs) show early signs of artificial general intelligence but struggle with hallucinations. One promising solution to mitigate these hallucinations is to store external knowledge as embeddings, aiding LLMs in retrieval-augmented generation. However, such a solution risks compromising privacy, as recent studies experimentally showed that the original text can be partially reconstructed from text embeddings by pre-trained language models. The significant advantage of LLMs over traditional pre-trained models may exacerbate these concerns. To this end, we investigate the effectiveness of reconstructing original knowledge and predicting entity attributes from these embeddings when LLMs are employed. Empirical findings indicate that LLMs significantly improve the accuracy of two evaluated tasks over those from pre-trained models, regardless of whether the texts are in-distribution or out-of-distribution. This underscores a heightened potential for LLMs to jeopardize user privacy, highlighting the negative consequences of their widespread use. We further discuss preliminary strategies to mitigate this risk.

![深入探究大型语言模型所引发嵌入的隐私风险](../../../paper_images/2404.16587/x1.png)

![深入探究大型语言模型所引发嵌入的隐私风险](../../../paper_images/2404.16587/x2.png)

![深入探究大型语言模型所引发嵌入的隐私风险](../../../paper_images/2404.16587/x3.png)

![深入探究大型语言模型所引发嵌入的隐私风险](../../../paper_images/2404.16587/x4.png)

![深入探究大型语言模型所引发嵌入的隐私风险](../../../paper_images/2404.16587/x5.png)

![深入探究大型语言模型所引发嵌入的隐私风险](../../../paper_images/2404.16587/x6.png)

![深入探究大型语言模型所引发嵌入的隐私风险](../../../paper_images/2404.16587/x7.png)

[Arxiv](https://arxiv.org/abs/2404.16587)