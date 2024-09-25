# 微调大型语言模型进行问答的经验洞察

发布时间：2024年09月24日

`LLM理论` `人工智能` `问答系统`

> Empirical Insights on Fine-Tuning Large Language Models for Question-Answering

# 摘要

> LLM 通过预训练编码了大量世界知识，可用于 QA 任务的微调。然而，针对 QA 任务的有效微调策略仍未充分探索。为此，我们根据 LLM 记忆的知识量对 SFT 数据进行分类，并进行了实证分析。实验涉及四个 LLM，重点研究了 SFT 数据量、不同数据集的影响及 LLM 间的数据需求差异。结果表明，仅需 60 个数据点即可激活预训练知识，使 LLM 执行 QA 任务。不同记忆水平的数据对 LLM 性能影响显著，最佳数据集因模型而异。未来研究将深入探讨这些现象的内在机制。

> Large language models (LLMs) encode extensive world knowledge through pre-training on massive datasets, which can then be fine-tuned for the question-answering (QA) task. However, effective strategies for fine-tuning LLMs for the QA task remain largely unexplored. To address this gap, we categorize supervised fine-tuning (SFT) data based on the extent of knowledge memorized by the pretrained LLMs and conduct a series of empirical analyses. Our experiments, involving four LLMs from three different model families, focus on three key factors: the amount of data required for SFT, the impact of different SFT datasets on model performance, and how data requirements vary across LLMs. The results show that as few as 60 data points during the SFT stage can activate the knowledge encoded during pre-training, enabling LLMs to perform the QA task. Additionally, SFT with data of varying memory levels has a significant impact on LLM performance, with the optimal dataset differing based on the specific model being fine-tuned. Future research will delve deeper into the mechanisms underlying these phenomena.

[Arxiv](https://arxiv.org/abs/2409.15825)