# 合成数据的多样性如何影响大型语言模型的训练？

发布时间：2024年10月19日

`LLM理论` `人工智能` `数据科学`

> On the Diversity of Synthetic Data and its Impact on Training Large Language Models

# 摘要

> 随着大型语言模型（LLM）的崛起，对多样化、高质量预训练数据的需求日益迫切。合成数据应运而生，成为解决数据稀缺和不可访问问题的有效途径。以往研究多聚焦于真实数据的质量与数量，而我们的工作则开创性地测量了合成数据的多样性，并深入探讨其对LLM性能的影响。我们引入全新多样性指标——LLM cluster-agent，评估合成数据集的多样性，进而分析其在预训练与微调阶段对下游任务的效应。实验结果显示，基于聚类的LLM多样性评分与预训练及监督微调表现均呈正相关。更有趣的是，预训练阶段合成数据的多样性对后续监督微调的影响，甚至超越了预训练本身，且这一现象在较小模型中同样显著。此项研究不仅深化了我们对合成数据在LLM训练中应用的理解，更为高效数据生成策略的探索打开了新的大门。

> The rise of Large Language Models (LLMs) has accentuated the need for diverse, high-quality pre-training data. Synthetic data emerges as a viable solution to the challenges of data scarcity and inaccessibility. While previous literature has focused predominantly on the quality and quantity of real data, our work enables the measurement of diversity in synthetic data and explores its impact on LLM performance. We study the downstream effects of synthetic data diversity during both the pre-training and fine-tuning stages by introducing a new diversity metric, \textit{LLM cluster-agent}, designed to evaluate the diversity of synthetic datasets. Through a series of controlled experiments with models of 350M and 1.4B parameters, we demonstrate that the proposed cluster-based LLM scoring of diversity correlates positively with both pre-training and supervised fine-tuning performance. Our findings also reveal that synthetic data diversity in pre-training affects supervised fine-tuning more significantly than pre-training itself, even for smaller models. We hope this study advances our understanding of the optimal use of synthetic data in LLM training and opens new avenues for efficient data generation processes.

[Arxiv](https://arxiv.org/abs/2410.15226)