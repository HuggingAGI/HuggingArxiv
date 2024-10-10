# GNN 助力：大型语言模型在图上下文学习中的新篇章

发布时间：2024年10月09日

`LLM应用` `图数据` `人工智能`

> Let's Ask GNN: Empowering Large Language Model for Graph In-Context Learning

# 摘要

> 文本属性图 (TAGs) 在建模复杂系统中至关重要，但利用大型语言模型 (LLMs) 处理 TAGs 因文本与图结构数据间的差异而充满挑战。我们提出了 AskGNN，一种通过 In-Context Learning (ICL) 整合图数据与任务信息的新方法。AskGNN 使用图神经网络 (GNN) 增强的检索器，跨图选择标记节点，融合复杂图结构与监督信号。我们的学习-检索算法优化检索器，精选提升 LLM 图任务性能的节点。实验显示，AskGNN 在多个任务与 LLMs 中表现卓越，为无需繁琐微调的图数据应用 LLMs 提供了新思路。

> Textual Attributed Graphs (TAGs) are crucial for modeling complex real-world systems, yet leveraging large language models (LLMs) for TAGs presents unique challenges due to the gap between sequential text processing and graph-structured data. We introduce AskGNN, a novel approach that bridges this gap by leveraging In-Context Learning (ICL) to integrate graph data and task-specific information into LLMs. AskGNN employs a Graph Neural Network (GNN)-powered structure-enhanced retriever to select labeled nodes across graphs, incorporating complex graph structures and their supervision signals. Our learning-to-retrieve algorithm optimizes the retriever to select example nodes that maximize LLM performance on graph. Experiments across three tasks and seven LLMs demonstrate AskGNN's superior effectiveness in graph task performance, opening new avenues for applying LLMs to graph-structured data without extensive fine-tuning.

[Arxiv](https://arxiv.org/abs/2410.07074)