# TacoERE：事件关系抽取的集群感知压缩技术
发布时间：2024年05月10日

`知识图谱`
> TacoERE: Cluster-aware Compression for Event Relation Extraction
>
> 事件关系抽取（ERE）是自然语言处理领域的一项关键挑战。传统方法直接对文档整体建模，难以应对长距离依赖和信息冗余问题。为此，我们提出了一种新颖的集群感知压缩方法——TacoERE，它采用先压缩后抽取的策略。首先，通过文档聚类划分内部与外部集群，强化集群内关系，同时捕捉任意距离的事件关联。接着，利用集群摘要精炼并凸显关键信息，减少冗余，缩短事件间距。我们在RoBERTa、ChatGPT和GPT-4等模型上，针对MAVEN-ERE、EventStoryLine和HiEve等数据集进行了深入实验。结果显示，TacoERE在ERE任务上表现出色，有效提升了性能。
>
> https://arxiv.org/abs/2405.06890


<hr />

- 论文原文: [https://arxiv.org/abs/2405.06890](https://arxiv.org/abs/2405.06890)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 公众号回复关键词获取论文原文： 5122541811512214