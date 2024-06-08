# 利用微调的大型语言模型，精简负载曲线分析的数据需求

发布时间：2024年06月02日

`LLM应用

这篇论文介绍了一种通过微调大型语言模型（如GPT-3.5）来减少电力系统负载曲线分析的数据需求的方法。这种方法特别关注于恢复缺失数据，并通过两阶段微调策略进行了实证验证。论文强调了提示工程和微调样本的优化利用在少样本学习中的重要性，并展示了这种方法在成本和时间上的优势。因此，这项研究扩展了LLMs在特定应用领域（即电力系统分析）的应用，属于LLM应用分类。` `电力系统` `数据分析`

> Applying Fine-Tuned LLMs for Reducing Data Needs in Load Profile Analysis

# 摘要

> 本文介绍了一种创新方法，通过微调大型语言模型（如GPT-3.5）来减少电力系统负载曲线分析的数据需求，特别是在恢复缺失数据方面。我们采用了一种两阶段微调策略，并通过实证验证了其准确恢复缺失数据的能力，性能媲美如BERT-PIN等专业模型。研究发现，提示工程和微调样本的优化利用对于少样本学习至关重要，有效促进了从通用案例到特定用户的知识转移。此外，该方法在成本和时间上均优于传统训练方式，为资源有限的环境提供了一个实用的解决方案。此研究不仅扩展了LLMs在电力系统分析中的应用，也为提升电力分配系统的效率和韧性开辟了新途径。

> This paper presents a novel method for utilizing fine-tuned Large Language Models (LLMs) to minimize data requirements in load profile analysis, demonstrated through the restoration of missing data in power system load profiles. A two-stage fine-tuning strategy is proposed to adapt a pre-trained LLMs, i.e., GPT-3.5, for missing data restoration tasks. Through empirical evaluation, we demonstrate the effectiveness of the fine-tuned model in accurately restoring missing data, achieving comparable performance to state-of-the-art specifically designed models such as BERT-PIN. Key findings include the importance of prompt engineering and the optimal utilization of fine-tuning samples, highlighting the efficiency of few-shot learning in transferring knowledge from general user cases to specific target users. Furthermore, the proposed approach demonstrates notable cost-effectiveness and time efficiency compared to training models from scratch, making it a practical solution for scenarios with limited data availability and computing resources. This research has significant potential for application to other power system load profile analysis tasks. Consequently, it advances the use of LLMs in power system analytics, offering promising implications for enhancing the resilience and efficiency of power distribution systems.

[Arxiv](https://arxiv.org/abs/2406.02479)