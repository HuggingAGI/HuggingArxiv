# 深入探究大型语言模型所引发的嵌入技术背后的隐私隐患

发布时间：2024年04月25日

`LLM应用` `人工智能` `隐私保护`

> Understanding Privacy Risks of Embeddings Induced by Large Language Models

# 摘要

> 大型语言模型（LLMs）初显类人智能的端倪，却也易受幻觉之扰。一种可能的解决方案是将外部知识嵌入化，以增强LLMs的检索生成能力。但这种做法可能侵犯隐私，因为研究表明，预训练的语言模型能够从文本嵌入中部分还原原始文本。LLMs相较于传统模型的这一显著优势，可能会加重隐私泄露的风险。本研究旨在探究使用LLMs时，从嵌入中重建原始知识和预测实体属性的效果。实验结果显示，LLMs在两项任务的准确度上均有显著提升，无论是处理常见还是罕见文本。这进一步凸显了LLMs可能对用户隐私构成的威胁，并指出了它们普及应用的潜在风险。文章还提出了一些初步的策略，以降低这种风险。

> Large language models (LLMs) show early signs of artificial general intelligence but struggle with hallucinations. One promising solution to mitigate these hallucinations is to store external knowledge as embeddings, aiding LLMs in retrieval-augmented generation. However, such a solution risks compromising privacy, as recent studies experimentally showed that the original text can be partially reconstructed from text embeddings by pre-trained language models. The significant advantage of LLMs over traditional pre-trained models may exacerbate these concerns. To this end, we investigate the effectiveness of reconstructing original knowledge and predicting entity attributes from these embeddings when LLMs are employed. Empirical findings indicate that LLMs significantly improve the accuracy of two evaluated tasks over those from pre-trained models, regardless of whether the texts are in-distribution or out-of-distribution. This underscores a heightened potential for LLMs to jeopardize user privacy, highlighting the negative consequences of their widespread use. We further discuss preliminary strategies to mitigate this risk.

![深入探究大型语言模型所引发的嵌入技术背后的隐私隐患](../../../paper_images/2404.16587/x1.png)

![深入探究大型语言模型所引发的嵌入技术背后的隐私隐患](../../../paper_images/2404.16587/x2.png)

![深入探究大型语言模型所引发的嵌入技术背后的隐私隐患](../../../paper_images/2404.16587/x3.png)

![深入探究大型语言模型所引发的嵌入技术背后的隐私隐患](../../../paper_images/2404.16587/x4.png)

![深入探究大型语言模型所引发的嵌入技术背后的隐私隐患](../../../paper_images/2404.16587/x5.png)

![深入探究大型语言模型所引发的嵌入技术背后的隐私隐患](../../../paper_images/2404.16587/x6.png)

![深入探究大型语言模型所引发的嵌入技术背后的隐私隐患](../../../paper_images/2404.16587/x7.png)

[Arxiv](https://arxiv.org/abs/2404.16587)