# 检索增强生成还是长上下文LLMs？我们进行了一项全面研究，并提出了一种混合方法。
发布时间：2024年07月23日

`RAG`
> Retrieval Augmented Generation or Long-Context LLMs? A Comprehensive Study and Hybrid Approach
>
> RAG 一直是 LLM 处理冗长上下文的高效工具，但 Gemini-1.5 和 GPT-4 等模型已能直接理解长篇内容。我们对比了 RAG 与 LC LLM，旨在融合两者的优势。通过在多个数据集上测试三种最新 LLM，我们发现资源充足时，LC 性能更胜一筹，但 RAG 的成本优势明显。为此，我们设计了 Self-Route 方法，根据模型自我评估智能选择 RAG 或 LC，既降低成本又保持高效。这一发现为 LLM 在长上下文应用中提供了实用指南。
>
> https://arxiv.org/abs/2407.16833

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16833/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16833/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16833/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16833/x4.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.16833](https://arxiv.org/abs/2407.16833)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1