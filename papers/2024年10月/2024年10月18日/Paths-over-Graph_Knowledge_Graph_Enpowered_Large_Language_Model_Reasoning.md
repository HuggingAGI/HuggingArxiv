# Paths-over-Graph：知识图谱助力大型语言模型推理

发布时间：2024年10月18日

`LLM应用` `人工智能` `知识图谱`

> Paths-over-Graph: Knowledge Graph Enpowered Large Language Model Reasoning

# 摘要

> 大型语言模型 (LLM) 在多项任务中表现出色，但在深度复杂推理和知识密集型任务中，常因幻觉问题和知识匮乏而受限。知识图谱 (KG) 以结构化方式存储大量事实，为推理提供可靠知识。然而，现有基于 KG 的 LLM 推理方法在处理多跳推理、多实体问题和图结构利用方面存在挑战。为此，我们提出 Paths-over-Graph (PoG)，通过整合 KG 中的知识推理路径，提升 LLM 推理的可解释性和忠实性。PoG 通过三阶段动态多跳路径探索，结合 LLM 固有知识和 KG 事实，解决多跳和多实体问题。为提高效率，PoG 先修剪无关信息，并采用三步高效修剪技术，确保推理路径高度相关。PoG 创新利用图结构修剪噪声，首次实现多实体深度路径检测。实验表明，PoG 在 GPT-3.5-Turbo 和 GPT-4 上均优于 ToG，平均准确率提升 18.9%，最高达 23.9%。

> Large Language Models (LLMs) have achieved impressive results in various tasks but struggle with hallucination problems and lack of relevant knowledge, especially in deep complex reasoning and knowledge-intensive tasks. Knowledge Graphs (KGs), which capture vast amounts of facts in a structured format, offer a reliable source of knowledge for reasoning. However, existing KG-based LLM reasoning methods face challenges like handling multi-hop reasoning, multi-entity questions, and effectively utilizing graph structures. To address these issues, we propose Paths-over-Graph (PoG), a novel method that enhances LLM reasoning by integrating knowledge reasoning paths from KGs, improving the interpretability and faithfulness of LLM outputs. PoG tackles multi-hop and multi-entity questions through a three-phase dynamic multi-hop path exploration, which combines the inherent knowledge of LLMs with factual knowledge from KGs. In order to improve the efficiency, PoG prunes irrelevant information from the graph exploration first and introduces efficient three-step pruning techniques that incorporate graph structures, LLM prompting, and a pre-trained language model (e.g., SBERT) to effectively narrow down the explored candidate paths. This ensures all reasoning paths contain highly relevant information captured from KGs, making the reasoning faithful and interpretable in problem-solving. PoG innovatively utilizes graph structure to prune the irrelevant noise and represents the first method to implement multi-entity deep path detection on KGs for LLM reasoning tasks. Comprehensive experiments on five benchmark KGQA datasets demonstrate PoG outperforms the state-of-the-art method ToG across GPT-3.5-Turbo and GPT-4, achieving an average accuracy improvement of 18.9%. Notably, PoG with GPT-3.5-Turbo surpasses ToG with GPT-4 by up to 23.9%.

[Arxiv](https://arxiv.org/abs/2410.14211)