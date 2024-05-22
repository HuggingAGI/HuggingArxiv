# 企业RAG中基于问题的检索采用原子单元进行优化
发布时间：2024年05月20日

`RAG`
> Question-Based Retrieval using Atomic Units for Enterprise RAG
>
> 企业检索增强生成（RAG）框架巧妙地将大型语言模型（LLMs）与内部动态变化的文档结合，首先将文档切分为块，再根据用户查询检索相关块，并以此为上下文，由LLM生成响应。但检索环节可能因错误块导致LLM生成错误答案。为此，本研究提出了一种零-shot密集检索改进方法，通过将块分解为原子陈述，并基于此生成合成问题，进而进行精确检索。实验表明，这种基于原子的检索方法召回率更高，且通过合成问题检索进一步提升了性能。这一改进显著提高了企业LLM在RAG框架下的整体表现。
>
> https://arxiv.org/abs/2405.12363


<hr />

- 论文原文: [https://arxiv.org/abs/2405.12363](https://arxiv.org/abs/2405.12363)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 公众号回复关键词获取论文原文： 8855212844428242