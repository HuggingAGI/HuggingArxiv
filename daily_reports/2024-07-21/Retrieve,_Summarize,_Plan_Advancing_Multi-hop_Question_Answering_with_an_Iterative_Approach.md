# 迭代三部曲：检索、总结、规划，助力多跳问答迈向新高度
发布时间：2024年07月17日

`RAG`
> Retrieve, Summarize, Plan: Advancing Multi-hop Question Answering with an Iterative Approach
>
> 多跳问答任务因其工业应用价值而备受挑战，而基于大型语言模型的检索增强生成（RAG）方法已成为解决这一问题的热门选择。然而，由于单次迭代可能无法获取所有必要信息，一系列迭代RAG方法应运而生，性能显著提升。尽管如此，现有方法仍面临上下文过载和规划冗余两大难题。为此，我们提出了一种新型迭代RAG方法——ReSP，其特色在于配备了一个双功能摘要器，能同时压缩总体问题和当前子问题的信息。实验证明，ReSP在HotpotQA和2WikiMultihopQA数据集上表现卓越，不仅超越了现有技术，还展现了出色的上下文长度适应性。
>
> https://arxiv.org/abs/2407.13101

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.13101/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.13101/x2.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.13101](https://arxiv.org/abs/2407.13101)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1