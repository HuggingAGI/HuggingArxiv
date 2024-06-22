# 多重元RAG：通过LLM提取的元数据优化数据库过滤，提升RAG对复杂多步查询的响应能力
发布时间：2024年06月19日

`RAG`
> Multi-Meta-RAG: Improving RAG for Multi-Hop Queries using Database Filtering with LLM-Extracted Metadata
>
> 检索增强生成（RAG）技术使大型语言模型（LLMs）能够从外部知识库中提取相关信息，并解答未曾接触过的文档集合上的查询。然而，传统RAG在应对需跨多个证据元素进行检索与推理的多跳问题时显得力不从心。为此，我们推出了Multi-Meta-RAG这一创新方法，它利用LLM提取的元数据进行精准的数据库筛选，从而优化了从多源中挑选出与问题紧密相关的文档的过程。尽管数据库筛选针对特定领域和格式的问题集，但我们的实验表明，Multi-Meta-RAG在MultiHop-RAG基准测试中显著提升了性能。相关代码已公开于https://github.com/mxpoliakov/Multi-Meta-RAG。
>
> https://arxiv.org/abs/2406.13213

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13213/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13213/x2.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.13213](https://arxiv.org/abs/2406.13213)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2