# 借助知识图谱，激发大型语言模型解答长尾事实相关问题
发布时间：2024年05月10日

`RAG`
> Prompting Large Language Models with Knowledge Graphs for Question Answering Involving Long-tail Facts
>
> 大型语言模型（LLMs）虽在多种自然语言处理任务中表现卓越，但在处理需要深厚现实世界知识的长尾事实任务时仍显力不从心。这表明，LLMs需要非参数知识的加持。为此，我们探讨了文本段落和知识图谱（KGs）等非参数知识对LLMs的影响。鉴于LLMs可能已接触过众多事实问答数据集，我们设计了一套全自动流程，用以构建一个依赖长尾事实知识的基准——LTGen。通过此基准，我们评估了在不同知识配置下的顶尖LLMs。实验结果显示，LLMs在面对高长尾级别或知识密集型问题时，表现不佳。然而，一旦引入非参数知识，模型的性能便大幅提升。我们发现，在多数情况下，使用KG三元组提示LLMs的效果优于基于段落的提示。同时，尽管结合KG三元组和文档的提示方式未能持续扩大知识覆盖面，但它显著减少了生成内容中的错误信息。
>
> https://arxiv.org/abs/2405.06524

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.06524/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.06524/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.06524/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.06524/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.06524/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.06524/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.06524/x7.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.06524](https://arxiv.org/abs/2405.06524)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886