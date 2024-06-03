# 图神经检索 GNN-RAG：助力大型语言模型推理
发布时间：2024年05月30日

`RAG`
> GNN-RAG: Graph Neural Retrieval for Large Language Model Reasoning
>
> 知识图谱（KGs）以三元组形式呈现人工构建的事实知识，形成图结构。知识图谱问答（KGQA）旨在基于知识图谱信息推理，回答自然语言问题。大型语言模型（LLMs）因其卓越的自然语言理解能力，成为问答任务的尖端技术。同时，图神经网络（GNNs）因能处理知识图谱中的复杂图形信息，广泛应用于KGQA。本研究引入GNN-RAG，一种结合LLMs语言理解与GNNs推理能力的新方法，采用检索增强生成（RAG）模式。首先，GNN在密集知识图谱子图上推理，为问题检索答案候选。其次，提取连接问题实体与答案候选的最短路径，作为知识图谱推理路径。这些路径被表述后，作为LLM在RAG中推理的输入。在GNN-RAG框架中，GNN负责提取有用图形信息，LLM则利用其自然语言处理能力完成KGQA。我们还开发了检索增强（RA）技术，进一步提升GNN-RAG在KGQA上的表现。实验显示，GNN-RAG在WebQSP和CWQ两个KGQA基准上达到顶尖水平，性能超越或媲美7B调优的LLM的GPT-4。特别是在处理多跳和多实体问题时，GNN-RAG的答案F1分数比其他方法高出8.9至15.5个百分点。
>
> https://arxiv.org/abs/2405.20139

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.20139/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.20139/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.20139/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.20139/x4.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.20139](https://arxiv.org/abs/2405.20139)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886