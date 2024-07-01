# 利用知识图谱增强的检索增强生成技术，优化故障模式与影响分析流程
发布时间：2024年06月26日

`RAG`
> Knowledge Graph Enhanced Retrieval-Augmented Generation for Failure Mode and Effects Analysis
>
> 故障模式与影响分析（FMEA）在新产品爬坡阶段预防潜在故障方面至关重要，但其效果常因FMEA工具的推理能力不足而受限，这些工具多为表格结构。大型语言模型（LLMs）为定制数据集上的推理提供了新机遇，但在需要事实知识的任务上仍显不足，检索增强生成（RAG）方法正是为了弥补这一缺陷。RAG从非参数数据存储中提取信息，并结合语言模型生成答案。我们进一步提出，通过集成知识图谱（KG）来强化RAG框架，旨在提升FMEA数据上的分析和语义问答能力。本文贡献包括提出新的FMEA观察本体、从FMEA KG生成向量嵌入的算法以及KG增强的RAG框架。通过人类研究验证了我们的方法，并评估了上下文检索的召回率和精确度。
>
> https://arxiv.org/abs/2406.18114

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.18114/fmea_chatbot.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.18114/x2.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.18114](https://arxiv.org/abs/2406.18114)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1