# 探究开源LLMs在企业定制RAG系统中的效能与扩展性：一场性能与可扩展性的较量
发布时间：2024年06月17日

`RAG`
> Evaluating the Efficacy of Open-Source LLMs in Enterprise-Specific RAG Systems: A Comparative Study of Performance and Scalability
>
> 本文深入分析了开源大型语言模型（LLMs）在企业特定数据集上的应用，特别是在基于检索增强生成（RAG）任务中。随着LLMs在自然语言处理中的日益重要，评估其在特定组织环境中的表现、可及性和整合能力变得尤为关键。研究涵盖了多种开源LLMs，并探讨了它们如何与企业数据结合，优化RAG框架。通过评估不同的开源嵌入技术，我们发现这些技术能显著提升RAG系统的性能，为企业提供了一个高效且经济的替代方案。
>
> https://arxiv.org/abs/2406.11424

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/reason_dense_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/reason_sparse_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/fact_dense_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/fact_sparse_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/reason_dense_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/reason_sparse_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/fact_dense_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/fact_sparse_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/reason_dense_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/reason_sparse_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/fact_dense_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/fact_sparse_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/reason_dense_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/reason_sparse_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/fact_dense_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/fact_sparse_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/reason_dense_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/reason_sparse_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/fact_dense_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/fact_sparse_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/reason_dense_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/reason_sparse_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/fact_dense_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/fact_sparse_double.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11424/Designer.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.11424](https://arxiv.org/abs/2406.11424)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验（3天）：公众号号菜单回复1
- 最新论文订阅新人优惠：公众号号菜单回复2