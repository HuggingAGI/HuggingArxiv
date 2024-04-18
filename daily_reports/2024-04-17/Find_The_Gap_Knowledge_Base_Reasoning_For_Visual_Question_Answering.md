# 揭秘背后：视觉问答中的知识库逻辑推理
发布时间：2024年04月15日
`RAG`
> 我们深入探讨了知识驱动的视觉问答系统，该系统需将问题与视觉内容结合，并从庞大的知识库中提取相关信息以解答问题。研究分为两部分：一是设计并训练新的神经网络架构；二是利用预训练的大型语言模型。我们探求的答案包括：1）通过直接监督检索知识库信息，能否有效提升模型解决视觉问答问题的效能？2）针对特定任务的模型和基于LLM的模型，在融合视觉信息与外部知识以及进行跨信息源的多步推理方面表现如何？3）LLMs内在的知识是否足够应对KB-VQA挑战，它能否在某种程度上取代显式的知识库？研究结果显示，为特定任务和LLM模型引入监督式外部知识与视觉信息检索机制，能显著提升其性能。尽管LLMs在一步推理上表现更佳，但在两步推理上，即便模型可以获取两种模态的全部相关信息，其表现仍不如经过精细调整的神经网络模型。此外，我们还发现，LLMs在处理与知识库相关的问题时，性能超过了神经网络模型，这验证了LLMs内在知识的效用，但同时也表明，外部知识库依然是不可或缺的。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.10226/Ret_arch.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.10226/data.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.10226/NN.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.10226/LLM.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/5122511244148214](https://wx.zsxq.com/dweb2/index/topic_detail/5122511244148214)

[https://arxiv.org/abs/2404.10226](https://arxiv.org/abs/2404.10226)