# LargePiG：你的大型语言模型其实是个隐藏的指针生成器

发布时间：2024年10月15日

`LLM应用` `问答系统` `数据挖掘`

> LargePiG: Your Large Language Model is Secretly a Pointer Generator

# 摘要

> 近期研究利用大型语言模型 (LLM) 进行查询生成，虽然性能卓越，但也带来了生成查询中的幻觉问题。为此，我们提出了相关性幻觉和事实性幻觉的新分类，并设计了一种方法，将 LLM 生成的查询内容与形式分离，保留事实信息，同时优化句法结构。具体而言，我们开发了无需训练的模型无关方法，将 LLM 转化为指针生成器 (LargePiG)，利用其固有注意力权重和词汇分布差异来减少幻觉。通过构建涵盖文档和视频场景的数据集，实证研究显示 LargePiG 在减少幻觉和提升问答及事实性评估任务准确性方面表现优异。

> Recent research on query generation has focused on using Large Language Models (LLMs), which despite bringing state-of-the-art performance, also introduce issues with hallucinations in the generated queries. In this work, we introduce relevance hallucination and factuality hallucination as a new typology for hallucination problems brought by query generation based on LLMs. We propose an effective way to separate content from form in LLM-generated queries, which preserves the factual knowledge extracted and integrated from the inputs and compiles the syntactic structure, including function words, using the powerful linguistic capabilities of the LLM. Specifically, we introduce a model-agnostic and training-free method that turns the Large Language Model into a Pointer-Generator (LargePiG), where the pointer attention distribution leverages the LLM's inherent attention weights, and the copy probability is derived from the difference between the vocabulary distribution of the model's high layers and the last layer. To validate the effectiveness of LargePiG, we constructed two datasets for assessing the hallucination problems in query generation, covering both document and video scenarios. Empirical studies on various LLMs demonstrated the superiority of LargePiG on both datasets. Additional experiments also verified that LargePiG could reduce hallucination in large vision language models and improve the accuracy of document-based question-answering and factuality evaluation tasks.

[Arxiv](https://arxiv.org/abs/2410.11366)