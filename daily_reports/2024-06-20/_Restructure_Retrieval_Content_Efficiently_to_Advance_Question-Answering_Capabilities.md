# 优化检索内容的结构，以增强问答系统的效能
发布时间：2024年06月17日

`RAG`
> : Restructure Retrieval Content Efficiently to Advance Question-Answering Capabilities
>
> 大型语言模型（LLMs）因参数知识有限，在知识密集型任务中常出现幻觉。为此，检索增强生成（RAG）通过整合外部文档片段来扩充LLM的知识库。通过提取或总结这些片段的信息，LLM的性能得以提升。但LLMs仍难以捕捉并利用分散的关键信息，这一挑战被称为“中途迷失”。为此，我们通常需重新组织信息，以便LLM识别关键点。我们提出的“精炼器”（Refiner）是一种端到端的提取与重组机制，它在RAG的后检索阶段发挥作用。“精炼器”使用单一的解码器专用LLM，自适应地提取与查询紧密相关的内容及其上下文，并根据内容间的关联性进行分节，从而凸显信息差异，并确保下游LLMs与原始上下文精准对齐。实验结果显示，经过训练的“精炼器”（拥有70亿参数）在提升下游LLM的答案准确性方面取得了显著成效，并在多种单跳和多跳问答任务中超越了其他顶尖的RAG和压缩技术。特别地，“精炼器”在多跳任务中实现了80.5%的令牌减少，并相比次优方案提升了1.6%至7.0%。作为一种即插即用的解决方案，“精炼器”能无缝融入RAG系统，广泛适用于各类开源框架。
>
> https://arxiv.org/abs/2406.11357

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11357/How_Refiner_Works.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11357/Data_Preparation.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11357/Ratio_of_Verbatim_Output.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.11357/Refiner_structure.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.11357](https://arxiv.org/abs/2406.11357)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验（3天）：公众号号菜单回复1
- 最新论文订阅新人优惠：公众号号菜单回复2