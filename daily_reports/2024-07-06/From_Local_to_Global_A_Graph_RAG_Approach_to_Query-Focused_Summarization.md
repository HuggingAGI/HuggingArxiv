# 从局部到全局：探索一种基于图 RAG 的查询聚焦摘要方法
发布时间：2024年04月24日

`RAG`
> From Local to Global: A Graph RAG Approach to Query-Focused Summarization
>
> 摘要：通过检索增强生成（RAG），大型语言模型（LLM）能够从外部知识源检索信息，从而回答涉及私有或未见文档的问题。然而，RAG在处理全局问题（如“数据集的主要主题是什么？”）时表现不佳，因为这类问题本质上是查询聚焦的摘要任务，而非直接检索。现有的QFS方法也难以处理大规模文本。为此，我们提出图RAG方法，该方法结合了两种方法的优势，能够随着问题普遍性和文本量的增加而扩展。图RAG通过LLM构建图索引，先从文档中提取实体图，再预生成相关实体的摘要。在回答问题时，每个摘要生成部分答案，最终汇总为完整回答。实验表明，图RAG在处理大规模数据集的全局问题时，能显著提升答案的全面性和多样性。全球和本地图RAG的开源Python实现即将发布。
>
> https://arxiv.org//pdf/2404.16130

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.16130/Level0Multihop.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.16130/Level1Multihop.jpg)

<hr />

- 论文原文: [https://arxiv.org//pdf/2404.16130](https://arxiv.org//pdf/2404.16130)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1