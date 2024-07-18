# RAGBench：一款专为增强检索生成系统设计的可解释基准测试
发布时间：2024年06月25日

`RAG`
> RAGBench: Explainable Benchmark for Retrieval-Augmented Generation Systems
>
> RAG 已成为将领域知识融入 LLM 驱动聊天应用的标准架构，其特点包括领域语料库查询和基于上下文的响应生成。然而，全面评估 RAG 系统因缺乏统一标准和数据集而受阻。为此，我们推出 RAGBench，首个包含 10 万示例的大规模 RAG 基准数据集，覆盖五个行业领域和多种任务类型，源自行业语料库如用户手册，特别适用于行业应用。同时，我们提出 TRACe 评估框架，一套跨领域的可解释评估指标。我们在 https://huggingface.co/datasets/rungalileo/ragbench 发布标注数据集，助力 RAG 系统全面评估和持续改进。通过广泛测试，我们发现基于 LLM 的 RAG 评估方法在性能上不及微调的 RoBERTa 模型。我们指出现有方法的不足，并建议采用 RAGBench 和 TRACe 以推动 RAG 评估系统的发展。
>
> https://arxiv.org/abs/2407.11005

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11005/RAG-diagram.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11005/RAGBenchDistributions.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11005/RelUtilExample.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.11005](https://arxiv.org/abs/2407.11005)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1