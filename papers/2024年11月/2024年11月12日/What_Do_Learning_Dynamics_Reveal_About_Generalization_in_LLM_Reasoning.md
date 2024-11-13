# 关于大型语言模型推理中的泛化，学习动态揭示了什么？

发布时间：2024年11月12日

`LLM理论` `数据管理` `模型训练`

> What Do Learning Dynamics Reveal About Generalization in LLM Reasoning?

# 摘要

> 尽管现代大型语言模型（LLM）具有显著的能力，但其解决问题能力背后的机制仍然难以捉摸。在这项工作中，我们旨在更好地理解 LLM 微调的学习动态如何塑造下游的泛化能力。我们的分析侧重于推理任务，其问题结构使我们能够区分记忆（从训练数据中精确复制推理步骤）和性能（最终解决方案的正确性）。我们发现，模型的泛化行为可以通过我们称为预记忆训练准确率的训练指标有效地表征：在模型样本开始从训练集中复制确切的推理步骤之前，它们在训练查询上的准确率。在数据集层面，该指标能够可靠地预测测试准确率，在各种模型（Llama3 8、Gemma2 9B）、数据集（GSM8k、MATH）和训练配置中，实现约或超过 0.9 的 R^2。在每个示例层面，该指标也表明单个模型预测对于训练查询中的扰动是否稳健。通过将模型的学习行为与其泛化能力联系起来，预记忆训练准确率可以指导对训练策略的有针对性的改进。我们以数据管理为例，表明优先处理预记忆准确率低的示例，与独立同分布数据缩放相比，数据效率提高了 1.5 - 2 倍，并优于其他标准数据管理技术。

> Despite the remarkable capabilities of modern large language models (LLMs), the mechanisms behind their problem-solving abilities remain elusive. In this work, we aim to better understand how the learning dynamics of LLM finetuning shapes downstream generalization. Our analysis focuses on reasoning tasks, whose problem structure allows us to distinguish between memorization (the exact replication of reasoning steps from the training data) and performance (the correctness of the final solution). We find that a model's generalization behavior can be effectively characterized by a training metric we call pre-memorization train accuracy: the accuracy of model samples on training queries before they begin to copy the exact reasoning steps from the training set. On the dataset level, this metric is able to reliably predict test accuracy, achieving $R^2$ of around or exceeding 0.9 across various models (Llama3 8, Gemma2 9B), datasets (GSM8k, MATH), and training configurations. On a per-example level, this metric is also indicative of whether individual model predictions are robust to perturbations in the training query. By connecting a model's learning behavior to its generalization, pre-memorization train accuracy can guide targeted improvements to training strategies. We focus on data curation as an example, and show that prioritizing examples with low pre-memorization accuracy leads to 1.5-2x improvements in data efficiency compared to i.i.d. data scaling, and outperforms other standard data curation techniques.

[Arxiv](https://arxiv.org/abs/2411.07681)