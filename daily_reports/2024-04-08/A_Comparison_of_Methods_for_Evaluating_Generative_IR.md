# 本研究对比了不同的生成式信息检索评估方法。
`RAG`
> 信息检索系统正逐步融入创新的生成组件。以检索增强生成（RAG）系统为例，检索部分负责提供真实信息，而生成部分则负责总结与扩展回答。在某些系统中，大型语言模型（LLM）能够独立生成回答，无需外部检索。本文聚焦于那些不依赖固定文档集生成回答的Gen-IR系统。在这种模式下，查询的回应可能是全新的文本内容。由于传统评估方法不适用于此，我们研究了将传统离线评估扩展到Gen-IR领域的多种方法。虽然传统评估依赖人工评估，但LLM的评估能力正逐渐替代人工评估，且表现出相当的或更高的效能。考虑到Gen-IR系统的回答不基于固定集，我们认为其评估方法应主要基于LLM生成的标签。我们尝试了基于二元和分级相关性的方法，并探索了基于明确子主题、成对偏好和嵌入的方法。我们先在多个TREC深度学习任务中用人工评估来验证这些方法，然后将它们应用于评估几个纯生成系统的结果。对于每种方法，我们既考虑其无需人工标签或其他输入的自主性，也考虑其支持人工审计的能力。为了确保对这些方法的信任，我们必须确信它们的评估结果与人工评估保持一致。为此，评估标准需保持透明，以便人类评估员能够进行审计。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.04044/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.04044/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.04044/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.04044/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.04044/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.04044/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.04044/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.04044/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.04044/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.04044/x10.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/1522588118218812](https://wx.zsxq.com/dweb2/index/topic_detail/1522588118218812)

[https://arxiv.org/abs/2404.04044](https://arxiv.org/abs/2404.04044)