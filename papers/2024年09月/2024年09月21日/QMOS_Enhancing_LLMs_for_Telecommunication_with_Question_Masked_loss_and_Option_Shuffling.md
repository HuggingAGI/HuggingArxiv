# QMOS：通过问题掩码损失和选项洗牌，提升 LLM 在电信领域的性能

发布时间：2024年09月21日

`RAG` `问答系统`

> QMOS: Enhancing LLMs for Telecommunication with Question Masked loss and Option Shuffling

# 摘要

> 大型语言模型 (LLM) 在问答系统领域取得了显著进展，尤其在处理复杂问题时表现出色。然而，由于专业领域的词汇和技术概念复杂，LLM 在电信等领域的应用面临挑战。尽管 GPT-3.5 在 RAG 框架下对电信问题的回答准确性有所提升，但其专有性和高计算需求限制了实际应用。本文提出的 QMOS 方法，通过问题掩码损失和选项洗牌技巧，显著提升了 LLM 在电信领域多项选择题的回答性能。我们采用开源的小型语言模型 (Phi-2 和 Falcon-7B) 在增强的 RAG 框架内进行实验，对 LLM-RAG 管道的多个环节进行了改进。实验结果显示，Falcon-7B 的准确性从 24.70% 提升至 49.30%，Phi-2 的准确性从 42.07% 提升至 84.65%，显著超越了现有方法。

> Large Language models (LLMs) have brought about substantial advancements in the field of Question Answering (QA) systems. These models do remarkably well in addressing intricate inquiries in a variety of disciplines. However, because of domain-specific vocabulary, complex technological concepts, and the requirement for exact responses applying LLMs to specialized sectors like telecommunications presents additional obstacles. GPT-3.5 has been used in recent work, to obtain noteworthy accuracy for telecom-related questions in a Retrieval Augmented Generation (RAG) framework. Notwithstanding these developments, the practical use of models such as GPT-3.5 is restricted by their proprietary nature and high computing demands. This paper introduces QMOS, an innovative approach which uses a Question-Masked loss and Option Shuffling trick to enhance the performance of LLMs in answering Multiple-Choice Questions in the telecommunications domain. Our focus was on using opensource, smaller language models (Phi-2 and Falcon-7B) within an enhanced RAG framework. Our multi-faceted approach involves several enhancements to the whole LLM-RAG pipeline of finetuning, retrieval, prompt engineering and inference. Our approaches significantly outperform existing results, achieving accuracy improvements from baselines of 24.70% to 49.30% with Falcon-7B and from 42.07% to 84.65% with Phi-2.

[Arxiv](https://arxiv.org/abs/2409.14175)