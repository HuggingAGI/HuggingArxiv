# 探究大型语言模型的泛化复杂性

发布时间：2024年10月02日

`LLM理论` `人工智能`

> Quantifying Generalization Complexity for Large Language Models

# 摘要

> 尽管 LLM 在处理复杂查询和任务上表现出色，但其泛化能力常与记忆紧密相关，需更精准评估。为此，我们推出 Scylla 动态评估框架，量化 LLM 的泛化能力。Scylla 通过 20 个跨 5 级复杂度的任务，分别评估 ID 和 OOD 数据上的表现，从而区分泛化与记忆。实验揭示了任务复杂度与 ID/OOD 性能差距间的非单调关系，即泛化谷。此现象指出关键复杂度，即非泛化行为依赖峰值，标志 LLM 泛化上限。模型越大，关键复杂度越高，表明更大模型在依赖记忆前能处理更复杂任务。借助 Scylla 和关键复杂度，我们评估了 28 个 LLM，包括 LLaMA、Qwen 等开源模型及 Claude、GPT 等闭源模型，提供更稳健评估，深化对 LLM 泛化能力的理解。

> While large language models (LLMs) have shown exceptional capabilities in understanding complex queries and performing sophisticated tasks, their generalization abilities are often deeply entangled with memorization, necessitating more precise evaluation. To address this challenge, we introduce Scylla, a dynamic evaluation framework that quantitatively measures the generalization abilities of LLMs. Scylla disentangles generalization from memorization via assessing model performance on both in-distribution (ID) and out-of-distribution (OOD) data through 20 tasks across 5 levels of complexity. Through extensive experiments, we uncover a non-monotonic relationship between task complexity and the performance gap between ID and OOD data, which we term the generalization valley. Specifically, this phenomenon reveals a critical threshold - referred to as critical complexity - where reliance on non-generalizable behavior peaks, indicating the upper bound of LLMs' generalization capabilities. As model size increases, the critical complexity shifts toward higher levels of task complexity, suggesting that larger models can handle more complex reasoning tasks before over-relying on memorization. Leveraging Scylla and the concept of critical complexity, we benchmark 28LLMs including both open-sourced models such as LLaMA and Qwen families, and close-sourced models like Claude and GPT, providing a more robust evaluation and establishing a clearer understanding of LLMs' generalization capabilities.

[Arxiv](https://arxiv.org/abs/2410.01769)