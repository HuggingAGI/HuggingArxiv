# 基于模型内部机制的答案归属，助力可信检索增强生成
发布时间：2024年06月19日

`RAG`
> Model Internals-based Answer Attribution for Trustworthy Retrieval-Augmented Generation
>
> 在问答领域，确保模型答案的可验证性是检索增强生成（RAG）面临的一项基本挑战。近期，自我引用提示被提出，旨在让大型语言模型（LLMs）在提供答案时附带引用支持文档。但这些模型往往难以遵循特定格式，错误引用不存在的来源，且未能准确反映其在生成过程中的上下文使用。为此，我们开发了MIRAGE——一种基于模型内部解释的RAG解释方法，它利用模型内部信息实现忠实的答案归属。MIRAGE能识别上下文敏感的答案标记，并通过显著性分析将其与预测中起作用的检索文档关联。我们在多语言抽取式QA数据集上测试了这一方法，结果显示与人类答案归属高度一致。在开放式QA任务中，MIRAGE不仅在引用质量和效率上与自我引用相媲美，还允许对归属参数进行更精细的调整。定性评估证实了MIRAGE归属的忠实性，并展示了模型内部在RAG答案归属中的巨大潜力。
>
> https://arxiv.org/abs/2406.13663

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13663/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13663/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13663/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13663/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13663/x5.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.13663](https://arxiv.org/abs/2406.13663)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2