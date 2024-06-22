# HIRO：优化分层信息检索策略
发布时间：2024年06月14日

`RAG`
> HIRO: Hierarchical Information Retrieval Optimization
>
> 大型语言模型（LLMs）虽在自然语言处理任务中表现卓越，但受限于静态训练数据，其响应常显陈旧或浅显。检索增强生成（RAG）通过实时整合外部知识，显著提升了模型在知识密集任务中的准确性与可信度。然而，RAG增强的LLMs在面对长篇上下文时显得力不从心，信息过载导致响应质量受损。近期，RAG应用开始采用分层数据结构存储文档，以不同层次的总结和信息密度进行组织。在此基础上，我们推出了HIRO（分层信息检索优化），一种利用分层结构存储文档的新型查询方法。HIRO通过深度优先搜索的递归相似度计算和分支修剪，有效减少了返回给LLM的上下文量，同时确保信息无损。在NarrativeQA数据集上，HIRO相较现有查询机制实现了10.85%的性能提升。
>
> https://arxiv.org/abs/2406.09979

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09979/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09979/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09979/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09979/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09979/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09979/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09979/x7.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.09979](https://arxiv.org/abs/2406.09979)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2