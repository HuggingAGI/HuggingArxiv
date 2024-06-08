# 利用微调的大型语言模型，精简负载曲线分析的数据需求

发布时间：2024年06月02日

`LLM应用

这篇论文介绍了一种利用大型语言模型（如GPT-3.5）进行电力系统负载曲线分析的方法，特别是在恢复缺失数据方面的应用。通过微调策略，该方法展示了在精确恢复缺失数据上的高效性，并且相比传统模型训练，在成本和时间上具有优势。这表明了LLMs在特定领域的应用潜力，因此属于LLM应用分类。` `电力系统` `数据分析`

> Applying Fine-Tuned LLMs for Reducing Data Needs in Load Profile Analysis

# 摘要

> 本文介绍了一种创新方法，通过微调大型语言模型（如GPT-3.5）来减少电力系统负载曲线分析中的数据需求，特别是在恢复缺失数据方面。我们提出了一种双阶段微调策略，并通过实证研究展示了微调模型在精确恢复缺失数据上的高效性，其性能可与BERT-PIN等专业模型媲美。研究发现，提示工程和微调样本的优化使用对于少样本学习至关重要，它能有效将通用案例知识迁移至特定用户。此外，该方法在成本和时间上均优于传统模型训练，适用于数据和计算资源有限的环境。此研究不仅为电力系统分析开辟了新途径，也预示着LLMs在提升电力分配系统效率和韧性方面的巨大潜力。

> This paper presents a novel method for utilizing fine-tuned Large Language Models (LLMs) to minimize data requirements in load profile analysis, demonstrated through the restoration of missing data in power system load profiles. A two-stage fine-tuning strategy is proposed to adapt a pre-trained LLMs, i.e., GPT-3.5, for missing data restoration tasks. Through empirical evaluation, we demonstrate the effectiveness of the fine-tuned model in accurately restoring missing data, achieving comparable performance to state-of-the-art specifically designed models such as BERT-PIN. Key findings include the importance of prompt engineering and the optimal utilization of fine-tuning samples, highlighting the efficiency of few-shot learning in transferring knowledge from general user cases to specific target users. Furthermore, the proposed approach demonstrates notable cost-effectiveness and time efficiency compared to training models from scratch, making it a practical solution for scenarios with limited data availability and computing resources. This research has significant potential for application to other power system load profile analysis tasks. Consequently, it advances the use of LLMs in power system analytics, offering promising implications for enhancing the resilience and efficiency of power distribution systems.

[Arxiv](https://arxiv.org/abs/2406.02479)