# LAR-ECHR：欧洲人权法院案件的新法律论证推理任务与数据集

发布时间：2024年10月17日

`LLM应用` `人工智能`

> LAR-ECHR: A New Legal Argument Reasoning Task and Dataset for Cases of the European Court of Human Rights

# 摘要

> 我们推出了法律论证推理 (LAR) 任务，旨在测试 LLM 的法律推理能力。该任务要求在给定案件事实的情况下，从法庭诉讼中的一系列法律论证中选择正确的下一个陈述。我们基于欧洲人权法院 (ECHR) 的案件构建了 LAR-ECHR 数据集。评估结果显示，(a) 模型排名与美国 LegalBench 基准一致，尽管 LAR-ECHR 基于欧盟法律，(b) LAR-ECHR 更清晰地区分了顶级模型，(c) 最佳模型 GPT-4o 在 LAR-ECHR 上的准确率仅为 75.8%，显示出显著的改进空间。LAR-ECHR 的构建方法可应用于其他法律体系。

> We present Legal Argument Reasoning (LAR), a novel task designed to evaluate the legal reasoning capabilities of Large Language Models (LLMs). The task requires selecting the correct next statement (from multiple choice options) in a chain of legal arguments from court proceedings, given the facts of the case. We constructed a dataset (LAR-ECHR) for this task using cases from the European Court of Human Rights (ECHR). We evaluated seven general-purpose LLMs on LAR-ECHR and found that (a) the ranking of the models is aligned with that of LegalBench, an established US-based legal reasoning benchmark, even though LAR-ECHR is based on EU law, (b) LAR-ECHR distinguishes top models more clearly, compared to LegalBench, (c) even the best model (GPT-4o) obtains 75.8% accuracy on LAR-ECHR, indicating significant potential for further model improvement. The process followed to construct LAR-ECHR can be replicated with cases from other legal systems.

[Arxiv](https://arxiv.org/abs/2410.13352)