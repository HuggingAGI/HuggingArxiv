# BadRAG：揭示大型语言模型增强检索生成中的安全隐患
发布时间：2024年06月02日

`RAG`
> BadRAG: Identifying Vulnerabilities in Retrieval Augmented Generation of Large Language Models
>
> 大型语言模型（LLMs）常因过时信息和“幻觉”现象受限，即产生错误数据。检索增强生成（RAG）通过融合检索与生成模型的优势，从最新数据集中提取信息，优化生成过程，提升响应的准确性和上下文适宜性。然而，RAG也带来了新的安全风险，尤其是其数据库常源自公开网络数据。本文提出\TrojRAG{}，旨在揭示RAG数据库及其对LLMs生成部分的间接攻击的脆弱性。我们发现，通过精心设计的内容段落，可以植入检索后门，对正常查询表现良好，但对特定对抗查询则始终返回预设的有害内容。这些触发器和有害段落可根据攻击需求高度定制，如将“共和党、唐纳德·特朗普等”作为触发语义组。对抗段落不仅与触发器相关，还能在不修改LLMs的情况下，间接影响其生成。这些攻击手段包括对RAG的拒绝服务攻击和通过触发器引导LLMs生成特定内容的语义攻击。实验证明，仅需毒害10个对抗段落，即可实现98.2%的成功检索率，显著提高RAG-based GPT-4的拒绝率（从0.01%至74.6%）或负面响应率（从0.22%至72%）。
>
> https://arxiv.org/abs/2406.00083

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00083/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00083/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00083/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00083/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00083/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00083/x6.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.00083](https://arxiv.org/abs/2406.00083)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886