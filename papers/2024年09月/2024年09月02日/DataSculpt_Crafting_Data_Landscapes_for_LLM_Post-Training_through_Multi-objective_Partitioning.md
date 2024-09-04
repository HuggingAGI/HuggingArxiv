# DataSculpt：利用多目标分区技术，为大型语言模型后训练阶段精心打造数据环境

发布时间：2024年09月02日

`LLM应用` `人工智能` `数据管理`

> DataSculpt: Crafting Data Landscapes for LLM Post-Training through Multi-objective Partitioning

# 摘要

> 在众多应用中，大型语言模型（LLM）的长上下文建模效果至关重要。然而，LLM 在处理长文本时的表现往往不尽如人意，给长序列训练的高效管理带来挑战。加之，适合长序列的全面且多样化的训练数据集稀缺，这源于数据源的长度偏差及大规模数据管理的复杂性。为此，我们推出了 DataSculpt 框架，旨在优化长上下文训练的数据结构。评估结果显示，DataSculpt 大幅提升了长上下文训练效果，包括检索增强、摘要、阅读理解和代码完成的显著提升，同时确保了模型整体性能的稳步提高。

> The effectiveness of long-context modeling is important for Large Language Models (LLMs) in various applications. Despite their potential, LLMs' efficacy in processing long context does not consistently meet expectations, posing significant challenges for efficient management of prolonged sequences in training. This difficulty is compounded by the scarcity of comprehensive and diverse training datasets suitable for long sequences, which stems from inherent length biases across different data sources, and the logistical complexities associated with massive data management for training in extended contexts. In this work, we introduce DataSculpt, a data construction framework designed to strategically augment the data architecture for extended-context training. Our thorough evaluations demonstrate DataSculpt's remarkable capacity to boost long-context training performance, achieving improvements including an 18.09% increase in retrieval augmentation, 21.23% in summarization, 21.27% in reading comprehension, and a 3.81% rise in code completion, all while preserving the models' overall proficiency with a 4.88% improvement.

[Arxiv](https://arxiv.org/abs/2409.00997)