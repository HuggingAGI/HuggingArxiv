# 通过后门在检索增强生成中的数据提取攻击
发布时间：2024年11月03日

`RAG`
> Data Extraction Attacks in Retrieval-Augmented Generation via Backdoors
>
> 尽管取得了显著进展，但大型语言模型（LLM）在缺乏特定领域或最新知识时仍难以提供准确答案。检索增强生成（RAG）通过结合外部知识库解决了这一限制，但它也引入了新的攻击面。在本文中，我们研究了针对 RAG 系统知识数据库的数据提取攻击。我们证明，之前对 RAG 的攻击在很大程度上依赖于 LLM 的指令遵循能力，并且简单的微调可以将此类攻击的成功率降低到几乎为零。这使得这些攻击不切实际，因为在特定领域部署 LLM 时微调是常见做法。为了进一步揭示漏洞，我们提议对 RAG 进行后门攻击，即在微调阶段注入一小部分中毒数据，在 LLM 内创建一个后门。当这个受损的 LLM 集成到 RAG 系统中时，攻击者可以利用提示中的特定触发因素来操纵 LLM 从检索数据库中泄露文档。通过精心设计中毒数据，我们实现了原文和改写的文档提取。我们表明，仅使用 3％的中毒数据，我们的方法在 Llama2-7B 上的原文提取平均成功率达到 79.7％，ROUGE-L 分数为 64.21，改写提取的平均成功率为 68.6％，四个数据集的平均 ROUGE 分数为 52.6。这些结果强调了部署 RAG 系统时供应链相关的隐私风险。
>
> https://arxiv.org/abs/2411.01705

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.01705](https://arxiv.org/abs/2411.01705)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)