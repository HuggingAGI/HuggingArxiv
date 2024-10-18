# BenTo：利用上下文可迁移性进行基准任务的简化

发布时间：2024年10月17日

`LLM理论` `人工智能` `软件工程`

> BenTo: Benchmark Task Reduction with In-Context Transferability

# 摘要

> 评估 LLM 成本高昂，需在大规模任务基准上生成和检查其输出。本文探讨了如何在不降低评估质量的前提下，精简基准任务。研究发现，任务的可转移性和相关性是识别最具代表性任务子集的关键，通过优化设施位置函数实现。我们提出了一种基于 ICL 的实用指标，用于估算任务间的可转移性。通过分析任务间的可转移性，可将现代 LLM 基准（如 MMLU 或 FLAN）中的任务数量减少至 5%，且评估差异仅增加不到 4%。相比以往方法，我们的方案无需训练、无需梯度，高效且仅需 ICL。

> Evaluating large language models (LLMs) is costly: it requires the generation and examination of LLM outputs on a large-scale benchmark of various tasks. This paper investigates how to efficiently reduce the tasks used to benchmark LLMs without affecting the evaluation quality. Our study reveals that task transferability and relevance provide critical information to identify the most representative subset of tasks via optimizing a facility location function. We propose a practically efficient metric for estimating the transferability between two tasks via in-context learning (ICL). By analyzing the pairwise transferability, we can reduce tasks in a modern LLM benchmark (e.g., MMLU or FLAN) to 5% while inducing only a <4% difference to the evaluation on the original benchmark. Compared to prior works, our method is training-free, gradient-free, and highly efficient requiring ICL only.

[Arxiv](https://arxiv.org/abs/2410.13804)