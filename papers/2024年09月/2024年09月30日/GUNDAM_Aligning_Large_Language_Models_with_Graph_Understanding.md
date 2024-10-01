# GUNDAM：让大型语言模型与图理解完美契合

发布时间：2024年09月30日

`LLM应用` `图学习`

> GUNDAM: Aligning Large Language Models with Graph Understanding

# 摘要

> 大型语言模型 (LLM) 在处理文本数据方面表现出色，激发了将其应用于图等非文本数据的兴趣。在图学习领域，利用 LLM 理解和操作图结构数据的研究日益增多。现有研究主要集中在具有丰富文本特征的图上，如知识图谱，但忽视了图结构本身的重要性。本研究旨在提升 LLM 对图数据结构的理解和利用能力，而非仅关注文本丰富的图。为此，我们提出了 \textbf{G}raph \textbf{U}nderstanding for \textbf{N}atural Language \textbf{D}riven \textbf{A}nalytical \textbf{M}odel (\model)，该模型使 LLM 能更好地与图结构互动，从而执行复杂推理任务。实验结果表明，\model~ 在图推理基准上超越了现有最佳基线，并揭示了影响 LLM 图推理能力的关键因素。此外，我们还从理论上分析了推理路径如何增强 LLM 的推理能力。

> Large Language Models (LLMs) have achieved impressive results in processing text data, which has sparked interest in applying these models beyond textual data, such as graphs. In the field of graph learning, there is a growing interest in harnessing LLMs to comprehend and manipulate graph-structured data. Existing research predominantly focuses on graphs with rich textual features, such as knowledge graphs or text attribute graphs, leveraging LLMs' ability to process text but inadequately addressing graph structure. This work specifically aims to assess and enhance LLMs' abilities to comprehend and utilize the structural knowledge inherent in graph data itself, rather than focusing solely on graphs rich in textual content. To achieve this, we introduce the \textbf{G}raph \textbf{U}nderstanding for \textbf{N}atural Language \textbf{D}riven \textbf{A}nalytical \textbf{M}odel (\model). This model adapts LLMs to better understand and engage with the structure of graph data, enabling them to perform complex reasoning tasks by leveraging the graph's structure itself. Our experimental evaluations on graph reasoning benchmarks not only substantiate that \model~ outperforms the SOTA baselines for comparisons. But also reveals key factors affecting the graph reasoning capabilities of LLMs. Moreover, we provide a theoretical analysis illustrating how reasoning paths can enhance LLMs' reasoning capabilities.

[Arxiv](https://arxiv.org/abs/2409.20053)