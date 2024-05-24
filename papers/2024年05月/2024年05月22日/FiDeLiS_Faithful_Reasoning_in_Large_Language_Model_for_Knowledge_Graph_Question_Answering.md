# FiDeLiS：大型语言模型在知识图谱问答中的忠实推理探索

发布时间：2024年05月22日

`RAG

理由：这篇论文主要介绍了一种名为FiDelis的检索-探索交互方法，该方法特别设计了Path-RAG模块，用于从知识图谱（KG）中提取对大型语言模型（LLM）推理至关重要的中间知识。这种方法结合了LLMs的逻辑推理和常识推理能力以及KG的拓扑结构，旨在提高知识检索的准确性。此外，论文还强调了演绎推理能力在指导推理过程中的作用，以及如何通过演绎验证的精确性来优化推理过程。这些内容与RAG（Retrieval-Augmented Generation）框架紧密相关，该框架通常涉及使用外部知识源来增强语言模型的生成能力。因此，这篇论文应归类为RAG。` `知识图谱` `人工智能推理`

> FiDeLiS: Faithful Reasoning in Large Language Model for Knowledge Graph Question Answering

# 摘要

> 大型语言模型（LLMs）虽在多领域取得显著成就，但在深度和负责任推理场景中常遭遇幻觉问题。通过整合外部知识图谱（KG），这些问题得以部分缓解，但整合方式仍待深入研究。本文提出了一种名为FiDelis的检索-探索交互方法，专为基于KG的推理中间步骤设计。特别地，我们开发了Path-RAG模块，旨在从KG中提取对LLM推理至关重要的中间知识。此方法融合了LLMs的逻辑推理、常识推理与KG的拓扑结构，显著提升了知识检索的准确性。我们还引入了LLMs的演绎推理能力，作为指导推理过程的更优标准，确保推理步骤的逐步性和可推广性。演绎验证的精确性有助于及时终止推理，避免误导和无效计算。实验结果显示，我们的方法在无需额外训练、计算成本更低的情况下，在三个基准测试中均优于现有基线。

> While large language models (LLMs) have achieved significant success in various applications, they often struggle with hallucinations, especially in scenarios that require deep and responsible reasoning. These issues could be partially mitigate by integrating external knowledge graphs (KG) in LLM reasoning. However, the method of their incorporation is still largely unexplored. In this paper, we propose a retrieval-exploration interactive method, FiDelis to handle intermediate steps of reasoning grounded by KGs. Specifically, we propose Path-RAG module for recalling useful intermediate knowledge from KG for LLM reasoning. We incorporate the logic and common-sense reasoning of LLMs and topological connectivity of KGs into the knowledge retrieval process, which provides more accurate recalling performance. Furthermore, we propose to leverage deductive reasoning capabilities of LLMs as a better criterion to automatically guide the reasoning process in a stepwise and generalizable manner. Deductive verification serve as precise indicators for when to cease further reasoning, thus avoiding misleading the chains of reasoning and unnecessary computation. Extensive experiments show that our method, as a training-free method with lower computational cost and better generality outperforms the existing strong baselines in three benchmarks.

[Arxiv](https://arxiv.org/abs/2405.13873)