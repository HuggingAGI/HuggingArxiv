# 利用微调的大型语言模型，精简负载曲线分析的数据需求

发布时间：2024年06月02日

`LLM应用

这篇论文主要探讨了如何通过微调大型语言模型（如GPT-3.5）来优化电力系统负载曲线分析中的数据处理，特别是在恢复缺失数据方面。论文中提到的两阶段微调策略和实证验证，以及对提示工程和微调样本优化利用的讨论，都直接关联到LLM在特定应用场景（即电力系统分析）中的实际应用。因此，这篇论文应归类于LLM应用。` `电力系统` `数据分析`

> Applying Fine-Tuned LLMs for Reducing Data Needs in Load Profile Analysis

# 摘要

> 本文介绍了一种创新方法，通过微调大型语言模型（如GPT-3.5）来减少电力系统负载曲线分析中的数据需求，特别是在恢复缺失数据方面。我们采用了一种两阶段微调策略，并通过实证验证了其有效性，展示了微调模型在恢复缺失数据上的准确性，性能媲美如BERT-PIN等专门设计的模型。研究发现，提示工程和微调样本的优化利用至关重要，凸显了少样本学习在知识转移中的高效性。此外，该方法在成本和时间上均优于从零开始训练模型，适用于数据和资源有限的情况。此研究不仅为电力系统分析提供了新视角，也推动了LLMs在提升电力分配系统效率和韧性方面的应用。

> This paper presents a novel method for utilizing fine-tuned Large Language Models (LLMs) to minimize data requirements in load profile analysis, demonstrated through the restoration of missing data in power system load profiles. A two-stage fine-tuning strategy is proposed to adapt a pre-trained LLMs, i.e., GPT-3.5, for missing data restoration tasks. Through empirical evaluation, we demonstrate the effectiveness of the fine-tuned model in accurately restoring missing data, achieving comparable performance to state-of-the-art specifically designed models such as BERT-PIN. Key findings include the importance of prompt engineering and the optimal utilization of fine-tuning samples, highlighting the efficiency of few-shot learning in transferring knowledge from general user cases to specific target users. Furthermore, the proposed approach demonstrates notable cost-effectiveness and time efficiency compared to training models from scratch, making it a practical solution for scenarios with limited data availability and computing resources. This research has significant potential for application to other power system load profile analysis tasks. Consequently, it advances the use of LLMs in power system analytics, offering promising implications for enhancing the resilience and efficiency of power distribution systems.

[Arxiv](https://arxiv.org/abs/2406.02479)