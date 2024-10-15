# NT-LLM：一种创新节点分词器，旨在将图结构融入大型语言模型。

发布时间：2024年10月14日

`LLM应用` `图学习`

> NT-LLM: A Novel Node Tokenizer for Integrating Graph Structure into Large Language Models

# 摘要

> 图是现实世界中关系表示的基础。随着大型语言模型 (LLM) 在自然语言处理 (NLP) 任务中的成功，LLM 在图学习中的应用引起了广泛关注。然而，将 LLM 应用于图任务面临重大挑战，因为这些模型并非为捕捉图的复杂结构而设计。现有方法通过两种策略应对这一挑战：一是使用图神经网络 (GNN) 编码图结构，减轻 LLM 理解空间位置的负担；二是将图结构转换为语义文本，便于 LLM 处理。尽管有所进展，这些方法往往难以完全保留图的拓扑信息，或需要大量计算资源，限制了其实际应用。为此，我们提出了节点标记器 (NT-LLM)，通过选择关键节点作为锚点，并根据节点与锚点的相对距离进行编码，有效捕捉图的拓扑结构，增强 LLM 在图数据上的推理能力。此外，我们还实施了特定任务的调优程序，进一步提升 LLM 的结构理解能力。实证评估显示，NT-LLM 在多种图任务中表现显著提升。

> Graphs are a fundamental data structure for representing relationships in real-world scenarios. With the success of Large Language Models (LLMs) across various natural language processing (NLP) tasks, there has been growing interest in integrating LLMs for graph learning. However, applying LLMs to graph-related tasks poses significant challenges, as these models are not inherently designed to capture the complex structural information present in graphs. Existing approaches address this challenge through two strategies: the chain of tasks approach, which uses Graph Neural Networks (GNNs) to encode the graph structure so that LLMs are relieved from understanding spatial positions; and Graph-to-Text Conversion, which translates graph structures into semantic text representations that LLMs can process. Despite their progress, these methods often struggle to fully preserve the topological information of graphs or require extensive computational resources, limiting their practical applicability.
  In this work, we introduce Node Tokenizer for Large Language Models (NT-LLM), a novel framework that efficiently encodes graph structures by selecting key nodes as anchors and representing each node based on its relative distance to these anchors. This position-anchored encoding effectively captures the graph topology, enabling enhanced reasoning capabilities in LLMs over graph data. Additionally, we implement a task-specific tuning procedure to further improve structural understanding within LLMs. Through extensive empirical evaluations, NT-LLM demonstrates significant performance improvements across a variety of graph-related tasks.

[Arxiv](https://arxiv.org/abs/2410.10743)