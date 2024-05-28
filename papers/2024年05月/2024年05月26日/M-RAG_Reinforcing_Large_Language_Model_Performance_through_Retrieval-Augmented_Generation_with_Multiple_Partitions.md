# M-RAG：借助多分区检索增强技术，提升大型语言模型的生成性能

发布时间：2024年05月26日

`RAG

理由：这篇论文主要介绍了一种改进的Retrieval-Augmented Generation (RAG)方法，即多分区RAG（M-RAG），并通过实验验证了其在文本摘要、机器翻译和对话生成等任务中的性能提升。论文的核心贡献在于RAG方法的改进和优化，因此最符合RAG分类。虽然论文中提到了结合多智能体强化学习，但这主要是为了优化RAG方法，并非论文的主要研究内容，因此不归类于Agent。同时，论文并未深入探讨LLM的理论问题，也不属于LLM理论。最后，虽然论文涉及LLM的应用，但其重点在于RAG方法的改进，而非LLM的直接应用，因此不归类于LLM应用。` `机器学习`

> M-RAG: Reinforcing Large Language Model Performance through Retrieval-Augmented Generation with Multiple Partitions

# 摘要

> Retrieval-Augmented Generation (RAG) 通过外部数据库中的相关记忆检索，提升了大型语言模型 (LLMs) 的性能。但现有 RAG 方法往往将所有记忆集中管理，可能导致关键信息被忽视并增加噪声。本文提出了一种多分区 RAG 方法（M-RAG），每个分区独立运作，提高了 RAG 的针对性。我们进一步开发了一个结合多智能体强化学习的框架，专门优化语言生成任务。实验结果显示，M-RAG 在文本摘要、机器翻译和对话生成三类任务中，分别提升了 11%、8% 和 12%，显著超越了其他方法。

> Retrieval-Augmented Generation (RAG) enhances Large Language Models (LLMs) by retrieving relevant memories from an external database. However, existing RAG methods typically organize all memories in a whole database, potentially limiting focus on crucial memories and introducing noise. In this paper, we introduce a multiple partition paradigm for RAG (called M-RAG), where each database partition serves as a basic unit for RAG execution. Based on this paradigm, we propose a novel framework that leverages LLMs with Multi-Agent Reinforcement Learning to optimize different language generation tasks explicitly. Through comprehensive experiments conducted on seven datasets, spanning three language generation tasks and involving three distinct language model architectures, we confirm that M-RAG consistently outperforms various baseline methods, achieving improvements of 11%, 8%, and 12% for text summarization, machine translation, and dialogue generation, respectively.

![M-RAG：借助多分区检索增强技术，提升大型语言模型的生成性能](../../../paper_images/2405.16420/x1.png)

![M-RAG：借助多分区检索增强技术，提升大型语言模型的生成性能](../../../paper_images/2405.16420/x2.png)

![M-RAG：借助多分区检索增强技术，提升大型语言模型的生成性能](../../../paper_images/2405.16420/x3.png)

![M-RAG：借助多分区检索增强技术，提升大型语言模型的生成性能](../../../paper_images/2405.16420/x4.png)

![M-RAG：借助多分区检索增强技术，提升大型语言模型的生成性能](../../../paper_images/2405.16420/x5.png)

[Arxiv](https://arxiv.org/abs/2405.16420)