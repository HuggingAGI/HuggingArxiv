# 知识密集型 LLM 生成的迭代规划与回答框架：Retrieve-Plan-Generation
发布时间：2024年06月21日

`RAG`
> Retrieve-Plan-Generation: An Iterative Planning and Answering Framework for Knowledge-Intensive LLM Generation
>
> 大型语言模型（LLMs）虽在多任务中取得显著进步，却常因内部知识局限而产生事实错误。检索增强生成（RAG）通过引入外部知识源，为解决此问题提供了新思路。但这些方法易受检索文档中无关段落的影响。LLM生成的不确定性可能导致输入整个文档时引入离题信息，使模型偏离主题，降低生成内容的相关性。为此，我们提出检索-规划-生成（RPG）框架，通过生成计划令牌在规划阶段指导后续生成，并在回答阶段根据计划精选相关段落，用于进一步回答生成。此过程迭代进行，直至完成，专注于特定主题以提升生成相关性。我们采用了一种高效的多任务提示调优方法，使现有LLMs能同时处理规划与回答，并在五个知识密集型任务上验证了RPG的有效性。
>
> https://arxiv.org/abs/2406.14979

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14979/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14979/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14979/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14979/x4.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.14979](https://arxiv.org/abs/2406.14979)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2