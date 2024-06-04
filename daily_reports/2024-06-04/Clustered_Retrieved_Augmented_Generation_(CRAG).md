# 集群检索增强生成（CRAG）技术
发布时间：2024年05月24日

`RAG`
> Clustered Retrieved Augmented Generation (CRAG)
>
> 在实际应用中，为大型语言模型（LLMs）注入外部知识至关重要，这包括实时更新内容、获取专业知识以及避免信息失真。基于向量数据库的检索增强生成（RAG）方法虽广受欢迎，但在某些场景下可能因上下文窗口需求过大而显得力不从心。即便上下文适配窗口，庞大的令牌数量也会导致成本和时间上的负担。为此，我们推出了CRAG，一种创新策略，它能在保持响应质量的同时，显著削减令牌数量，实验表明，CRAG能减少至少46%的令牌，某些情况下甚至高达90%以上。与RAG不同，随着分析评论的增多，CRAG的令牌数量增长微乎其微，而RAG在处理75条评论时，令牌数量是处理4条评论时的近9倍。
>
> https://arxiv.org/abs/2406.00029

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00029/x1.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.00029](https://arxiv.org/abs/2406.00029)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886