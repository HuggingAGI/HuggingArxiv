# DoPAMine：基于种子数据引导的领域特定预训练适应

发布时间：2024年09月30日

`LLM应用`

> DoPAMine: Domain-specific Pre-training Adaptation from seed-guided data Mining

# 摘要

> 大型语言模型 (LLM) 在跨行业执行任务时展现了卓越的泛化能力，这些能力大多源自预训练阶段的数据。然而，在专业或低资源领域，这些模型表现受限。近期方法尝试用 LLM 生成特定领域数据，但常缺乏真实性和复杂性。在医疗和金融等有数据的领域，LM 多为专有，需可扩展方法来获取真实世界数据。为此，我们提出自动化框架 DoPAMine，从大数据库中挖掘特定领域数据，用于 LM 的领域适应。该框架利用 LLM 知识生成多样化种子数据，进而挖掘真实数据。实验显示，与基线相比，DoPAMine 在医疗和金融任务中显著提升了 LLM 性能，分别在零-shot 和 5-shot 设置下平均提升 4.9% 和 5.1%，以及 2.9% 和 6.7%。

> Large Language Models (LLMs) have shown remarkable ability to generalize effectively across numerous industry domains while executing a range of tasks. Many of these competencies are obtained from the data utilized during the pre-training phase of the Language Models (LMs). However, these models exhibit limitations when tasked with performing in specialized or low-resource industry domains. More recent approaches use LLMs for generating domain-specific synthetic data but most often they lack in truthfulness and complexity. Alternatively, in cases where domain data is available like healthcare and finance most of the LMs are proprietary necessitating the need for a scalable method to curate real world industry specific pre-training data. In this work, we propose an automated and scalable framework - DoPAMine:Domain-specific Pre-training Adaptation from seed-guided data Mining, to mine domain specific training data from a large data corpus for domain adaptation of a LM. The framework leverages the parametric knowledge of a LLM to generate diverse and representative seed data tailored to a specific domain which is then used to mine real world data from a large data corpus like Common Crawl. We evaluated our framework's performance in the continual pre-training (CPT) setting by training two domain specific 7B parameter LMs in healthcare and finance with data mined via DoPAMine. Our experiments show that DoPAMine boosts the performance of pre-trained LLMs on average by 4.9% and 5.1% in zero-shot and 5-shot settings respectively on healthcare tasks from MMLU, MedQA, MedMCQA and PubMedQA datasets, and 2.9% and 6.7% for zero-shot and 5-shot settings respectively on finance tasks from FiQA-SA, FPB and Headlines datasets when compared to the baseline.

[Arxiv](https://arxiv.org/abs/2410.00260)