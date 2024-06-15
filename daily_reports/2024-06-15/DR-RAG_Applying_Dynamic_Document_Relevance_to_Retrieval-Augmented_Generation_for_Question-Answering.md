# 动态相关性增强检索生成（DR-RAG）：优化问答系统的文档关联策略
发布时间：2024年06月11日

`RAG`
> DR-RAG: Applying Dynamic Document Relevance to Retrieval-Augmented Generation for Question-Answering
>
> Retrieval-Augmented Generation (RAG) 显著提升了大型语言模型在知识密集型任务，如问答中的表现。通过整合外部知识库，RAG 扩展了查询上下文，增强了回答的准确性。但每次查询多次调用 LLMs 效率不高，且单次查询难以检索所有相关文档。我们发现，尽管某些关键文档与查询关联度低，通过结合文档片段与查询，仍可检索到其他相关文档。为此，我们提出了 Dynamic-Relevant Retrieval-Augmented Generation (DR-RAG)，一种两阶段检索框架，旨在提升文档检索的召回率和答案准确性，同时保持高效。此外，一个小型分类器用于两种选择策略，以评估检索文档对回答查询的贡献，并筛选出相对相关的文档。DR-RAG 仅一次调用 LLMs，大幅提升了实验效率。在多跳 QA 数据集上的实验结果显示，DR-RAG 显著提高了答案的准确性，为 QA 系统带来了新的进步。
>
> https://arxiv.org/abs/2406.07348

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07348/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07348/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07348/x3.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.07348](https://arxiv.org/abs/2406.07348)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886