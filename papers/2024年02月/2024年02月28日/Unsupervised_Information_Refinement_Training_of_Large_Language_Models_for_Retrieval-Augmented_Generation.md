# [针对增强检索式生成任务，我们对大型语言模型进行无监督的信息提炼训练，旨在提升其从海量数据中自动提炼关键信息的能力，并将其应用于生成过程以提高输出质量。](https://arxiv.org/abs/2402.18150)

发布时间：2024年02月28日

`RAG`

> Unsupervised Information Refinement Training of Large Language Models for Retrieval-Augmented Generation

> RAG技术借助检索信息强化了LLMs的表现力，但研究发现LLMs在有效使用甚至可能忽视或受检索信息误导上仍有难题，症结在于LLMs训练时未教会它们如何处理不同质量的检索文本。本文创新性地将LLMs在RAG中的角色定位为“信息提炼器”，意味着无论检索文本的质量如何，LLMs都能结合这些文本与模型参数，提炼出更为精炼、精准和全面的输出文本。因此，我们提出了一种低成本且广泛适用的无监督信息提炼训练方法——InFO-RAG，专为优化LLMs在RAG任务上的表现而设计。实验证明，在涵盖问答、槽填充、语言建模、对话及代码生成等多元任务的11个数据集的零样本预测场景下，InFO-RAG使LLaMA2模型的性能平均提升了9.39个百分点，并且在RAG的上下文学习及鲁棒性方面表现出色。

> Retrieval-augmented generation (RAG) enhances large language models (LLMs) by incorporating additional information from retrieval. However, studies have shown that LLMs still face challenges in effectively using the retrieved information, even ignoring it or being misled by it. The key reason is that the training of LLMs does not clearly make LLMs learn how to utilize input retrieved texts with varied quality. In this paper, we propose a novel perspective that considers the role of LLMs in RAG as ``Information Refiner'', which means that regardless of correctness, completeness, or usefulness of retrieved texts, LLMs can consistently integrate knowledge within the retrieved texts and model parameters to generate the texts that are more concise, accurate, and complete than the retrieved texts. To this end, we propose an information refinement training method named InFO-RAG that optimizes LLMs for RAG in an unsupervised manner. InFO-RAG is low-cost and general across various tasks. Extensive experiments on zero-shot prediction of 11 datasets in diverse tasks including Question Answering, Slot-Filling, Language Modeling, Dialogue, and Code Generation show that InFO-RAG improves the performance of LLaMA2 by an average of 9.39\% relative points. InFO-RAG also shows advantages in in-context learning and robustness of RAG.