# DocNet：揭示归纳偏差检测模型中的语义结构之谜

发布时间：2024年06月16日

`RAG

理由：这篇论文主要关注的是新闻文章的语义结构和偏见检测，并介绍了一种名为DocNet的模型，该模型专注于文档嵌入和偏见检测。这与RAG（Retrieval-Augmented Generation）模型的应用场景相似，因为RAG模型也涉及文本的语义理解和生成，尤其是在处理和生成与特定主题或偏见相关的信息时。虽然论文中没有直接提到RAG模型，但其研究内容和目标与RAG的应用领域相符，即通过改进文本理解和生成来提高信息处理的准确性和效率。因此，将这篇论文归类为RAG是合适的。` `新闻媒体` `社交媒体分析`

> DocNet: Semantic Structure in Inductive Bias Detection Models

# 摘要

> 人们的观点导致新闻不可避免地带有偏见。随着社交媒体成为获取新闻的首选渠道，党派分歧日益扩大，识别新闻偏见对明智的公民而言变得尤为关键。了解新闻偏见的方式有助于人们避免陷入极端化的信息泡沫。本文深入探讨了新闻文章语义结构这一常被忽视的偏见检测领域，并介绍了DocNet——一种创新、高效且资源需求低的文档嵌入与偏见检测模型，其性能超越了大型语言模型。研究显示，来自不同党派的新闻文章在语义结构上呈现出显著的相似性，这一发现有助于在资源有限的环境中提升偏见检测的准确性。相关代码和数据已发布于https://github.com/nlpresearchanon。

> News will have biases so long as people have opinions. However, as social media becomes the primary entry point for news and partisan gaps increase, it is increasingly important for informed citizens to be able to identify bias. People will be able to take action to avoid polarizing echo chambers if they know how the news they are consuming is biased. In this paper, we explore an often overlooked aspect of bias detection in documents: the semantic structure of news articles. We present DocNet, a novel, inductive, and low-resource document embedding and bias detection model that outperforms large language models. We also demonstrate that the semantic structure of news articles from opposing partisan sides, as represented in document-level graph embeddings, have significant similarities. These results can be used to advance bias detection in low-resource environments. Our code and data are made available at https://github.com/nlpresearchanon.

![DocNet：揭示归纳偏差检测模型中的语义结构之谜](../../../paper_images/2406.10965/basil_domain_graph_nytime_correct.png)

![DocNet：揭示归纳偏差检测模型中的语义结构之谜](../../../paper_images/2406.10965/basil_domain_graph_fox_correct.png)

![DocNet：揭示归纳偏差检测模型中的语义结构之谜](../../../paper_images/2406.10965/basil_domain_graph_nytime_incorrect.png)

![DocNet：揭示归纳偏差检测模型中的语义结构之谜](../../../paper_images/2406.10965/basil_domain_graph_huf_incorrect.png)

![DocNet：揭示归纳偏差检测模型中的语义结构之谜](../../../paper_images/2406.10965/graph_corr_plot.png)

![DocNet：揭示归纳偏差检测模型中的语义结构之谜](../../../paper_images/2406.10965/graph_corr_plot_basil.png)

[Arxiv](https://arxiv.org/abs/2406.10965)