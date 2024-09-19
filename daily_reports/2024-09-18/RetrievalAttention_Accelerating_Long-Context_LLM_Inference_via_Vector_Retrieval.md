# RetrievalAttention：利用向量检索技术，加速长上下文 LLM 的推理过程。
发布时间：2024年09月16日


> RetrievalAttention: Accelerating Long-Context LLM Inference via Vector Retrieval
>
> 基于Transformer的LLMs在各领域日益重要，但注意力操作的二次时间复杂度限制了其在长上下文中的应用，主要因为推理延迟和GPU内存消耗过高。本文提出RetrievalAttention，一种无需训练的注意力计算加速方法。通过在CPU内存中构建KV向量的ANNS索引，RetrievalAttention在生成时通过向量搜索高效检索相关向量。针对查询与键向量间的OOD问题，RetrievalAttention采用注意力感知向量搜索算法，仅访问1-3%的数据，实现亚线性时间复杂度。这不仅大幅降低推理成本，还保持了模型精度，仅需16GB GPU内存即可处理8B参数LLM中的128K标记，单个RTX4090上生成一个标记仅需0.188秒。
>
> https://arxiv.org/abs/2409.10516

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2409.10516](https://arxiv.org/abs/2409.10516)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)