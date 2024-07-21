# 《Mindful-RAG》：探究检索增强生成技术中的关键失败点研究
发布时间：2024年07月16日

`RAG`
> Mindful-RAG: A Study of Points of Failure in Retrieval Augmented Generation
>
> 大型语言模型虽擅长生成连贯文本，但在处理特定领域和事实问答任务时，面对知识密集型查询仍显力不从心。检索增强生成系统通过引入外部知识源如知识图谱来缓解这一难题，但即便拥有必要事实信息，LLM 仍常难以给出准确答案。我们研究发现，现有基于知识图谱的 RAG 方法存在八大关键失误，主要源于对问题意图的辨识不足及对相关上下文的收集不充分。为此，我们提出 Mindful-RAG 框架，专注于基于意图和上下文对齐的知识检索，旨在精准定位并改善这些失误，从而提升 LLM 响应的准确性与相关性，较现有方法实现显著进步。
>
> https://arxiv.org/abs/2407.12216

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.12216/x1.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.12216](https://arxiv.org/abs/2407.12216)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1