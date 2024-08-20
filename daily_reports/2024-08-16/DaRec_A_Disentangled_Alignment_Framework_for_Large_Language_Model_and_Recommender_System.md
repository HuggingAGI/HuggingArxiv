# DaRec：大型语言模型与推荐系统解耦对齐的创新框架
发布时间：2024年08月15日

`推荐系统`
> DaRec: A Disentangled Alignment Framework for Large Language Model and Recommender System
>
> 大型语言模型 (LLM) 凭借其强大的推理能力，在推荐系统中表现出色。为了从 LLM 中提炼知识以强化协同模型，研究者采用了对比学习等技术进行表示对齐。然而，我们发现直接对齐 LLM 与协同模型的表示并非最佳方案，这一结论基于信息论。因此，如何有效对齐这两者间的语义表示仍是一个未解之谜。受此启发，我们设计了一个创新的即插即用对齐框架。该框架首先通过投影层和表示正则化，将 LLM 和协同模型的潜在表示分解为特定与共享组件，然后对共享表示进行全局与局部结构对齐，以促进知识迁移。理论证明，这种分解能包含更多相关信息，减少无关信息，从而提升推荐任务的效能。实验结果显示，我们的方法超越了现有顶尖算法。
>
> https://arxiv.org/abs/2408.08231

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2408.08231](https://arxiv.org/abs/2408.08231)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)