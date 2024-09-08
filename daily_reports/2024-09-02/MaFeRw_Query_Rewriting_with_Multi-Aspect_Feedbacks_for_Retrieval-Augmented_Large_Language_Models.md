# MaFeRw：通过多方面反馈优化查询，提升检索增强型大型语言模型的性能
发布时间：2024年08月30日

`RAG`
> MaFeRw: Query Rewriting with Multi-Aspect Feedbacks for Retrieval-Augmented Large Language Models
>
> 在实际应用的RAG系统中，查询常包含口语省略和模糊引用，需重写以精准反映用户需求。传统重写方法因流程冗长，对生成任务的提升有限。虽有研究尝试通过强化学习改进重写，但稀疏奖励常导致训练不稳定。我们发现，用户需求亦体现在黄金文档和检索结果中，通过密集反馈可优化重写，提升响应质量。本文提出的MaFeRw方法，通过整合检索与生成反馈，显著提升RAG性能。我们首先用人工数据初始化T5模型，再设计三项强化学习指标：重写查询与黄金文档的相似度、排名指标及生成与真实答案的ROUGE值。借鉴RLAIF，我们训练三种奖励模型以加速训练。最终，结合这些模型的分数，运用PPO算法探索最优重写策略。实验显示，MaFeRw在生成质量和训练稳定性上均超越基线方法。
>
> https://arxiv.org/abs/2408.17072

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2408.17072](https://arxiv.org/abs/2408.17072)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)