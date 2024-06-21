# 增强生成检索的统一主动检索方法
发布时间：2024年06月18日

`RAG`
> Unified Active Retrieval for Retrieval Augmented Generation
>
> 在RAG中，并非每次指令都适合应用检索，盲目检索并非最佳选择。因此，决定何时进行检索，即主动检索，对RAG至关重要。但现有方法存在两大难题：一是依赖单一标准，难以应对多样指令；二是流程复杂且高度特化，增加了系统复杂度和响应延迟。为此，我们提出统一主动检索（UAR），它采用四个独立标准，并将其转化为易于整合的分类任务，实现了高效的检索时机判断，几乎不增加额外成本。我们还设计了统一主动检索标准（UAR-Criteria），通过标准化流程应对各种检索场景。实验证明，UAR在检索时机判断和下游任务表现上均显著优于现有方法，展现了其有效性和对下游任务的积极影响。
>
> https://arxiv.org/abs/2406.12534

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12534/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12534/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12534/snowflake.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12534/flame.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.12534/x3.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.12534](https://arxiv.org/abs/2406.12534)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验（3天）：公众号号菜单回复1
- 最新论文订阅新人优惠：公众号号菜单回复2