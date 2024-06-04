# 粒度混合优化：提升检索增强生成中的分块效率
发布时间：2024年06月01日

`RAG`
> Mix-of-Granularity: Optimize the Chunking Granularity for Retrieval-Augmented Generation
>
> 在检索增强生成（RAG）系统中，整合来自不同数据源的信息是一大挑战，因为每个知识源都有其独特的数据结构和约定。单一的检索策略往往无法充分利用这些信息。为此，我们借鉴了混合专家（Mix-of-Expert）的概念，提出了混合粒度（Mix-of-Granularity，MoG）方法，它通过一个路由器根据查询动态选择知识库的最佳粒度。该路由器利用一种新的软标签损失函数进行训练。此外，我们将MoG扩展为混合粒度图（Mix-of-Granularity-Graph，MoGG），将参考文档预处理成图，从而能够从远距离的数据块中检索信息。实验证明，MoG和MoGG都能有效提升RAG系统在下游任务中的表现，相关代码也将公开。
>
> https://arxiv.org/abs/2406.00456

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00456/Showcase.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00456/MoG_principal.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00456/build_MoGG.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00456/granularity_distribution.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00456/rag_k.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00456/flag_plot.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.00456](https://arxiv.org/abs/2406.00456)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886