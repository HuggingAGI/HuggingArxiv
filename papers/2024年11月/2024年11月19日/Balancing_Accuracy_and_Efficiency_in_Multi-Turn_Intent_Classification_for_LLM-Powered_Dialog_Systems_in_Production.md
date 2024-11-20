# 在生产环境中由 LLM 驱动的对话系统的多轮意图分类里，实现准确性与效率的平衡

发布时间：2024年11月19日

`LLM应用` `对话系统` `人工智能`

> Balancing Accuracy and Efficiency in Multi-Turn Intent Classification for LLM-Powered Dialog Systems in Production

# 摘要

> 准确的多轮意图分类对于推动对话式人工智能系统的发展至关重要。然而，综合数据集的稀缺以及对话轮次间上下文依赖的复杂性等难题，阻碍了其发展进程。本文呈现了两种借助大型语言模型（LLMs）的新颖方法，旨在增强生产对话系统的可扩展性并降低延迟。其一，我们引入了符号调优，它简化了意图标签，降低了任务的复杂性，提升了多轮对话中的表现。其二，我们提出了 C-LARA（一致性感知、语言学自适应检索增强）框架，利用 LLMs 进行数据增强和伪标记，从而生成合成的多轮对话。这些丰富的数据集被用于微调一个适合部署的小型高效模型。在多语言对话数据集上开展的实验显示，分类准确率和资源效率显著提升。我们的方法使多轮意图分类准确率提高了 5.09%，标注成本降低了 40%，并且能够在低资源多语言工业系统中实现可扩展部署，凸显了其实用性和影响力。

> Accurate multi-turn intent classification is essential for advancing conversational AI systems. However, challenges such as the scarcity of comprehensive datasets and the complexity of contextual dependencies across dialogue turns hinder progress. This paper presents two novel approaches leveraging Large Language Models (LLMs) to enhance scalability and reduce latency in production dialogue systems. First, we introduce Symbol Tuning, which simplifies intent labels to reduce task complexity and improve performance in multi-turn dialogues. Second, we propose C-LARA (Consistency-aware, Linguistics Adaptive Retrieval Augmentation), a framework that employs LLMs for data augmentation and pseudo-labeling to generate synthetic multi-turn dialogues. These enriched datasets are used to fine-tune a small, efficient model suitable for deployment. Experiments conducted on multilingual dialogue datasets demonstrate significant improvements in classification accuracy and resource efficiency. Our methods enhance multi-turn intent classification accuracy by 5.09%, reduce annotation costs by 40%, and enable scalable deployment in low-resource multilingual industrial systems, highlighting their practicality and impact.

[Arxiv](https://arxiv.org/abs/2411.12307)