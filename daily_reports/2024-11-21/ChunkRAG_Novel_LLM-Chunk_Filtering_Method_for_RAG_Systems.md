# ChunkRAG：RAG 系统的全新 LLM-Chunk 过滤之法
发布时间：2024年10月30日

`RAG`
> ChunkRAG: Novel LLM-Chunk Filtering Method for RAG Systems
>
> 在使用大型语言模型（LLMs）的检索增强生成（RAG）系统中，常因检索到不相关或关联松散的信息而生成不准确的回应。现有的在文档层面运作的方法，难以有效滤除这类内容。我们提出了由 LLM 驱动的块过滤——ChunkRAG，这是一个能在块级别评估和过滤检索信息从而增强 RAG 系统的框架。我们的方法运用语义分块将文档分成连贯的部分，并借助基于 LLM 的相关性评分来评估每个块与用户查询的契合度。在生成阶段之前滤除不太相关的块，显著减少了幻觉，提高了事实准确性。实验显示，我们的方法优于现有的 RAG 模型，在需要精准信息检索的任务中达到了更高的准确率。这一进展提升了 RAG 系统的可靠性，使其在事实核查和多跳推理等应用中尤为有益。
>
> https://arxiv.org/abs/2410.19572

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2410.19572](https://arxiv.org/abs/2410.19572)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)