# ERASMO：借助大型语言模型，实现更精准的聚类分割

发布时间：2024年09月30日

`LLM应用` `市场营销` `数据分析`

> ERASMO: Leveraging Large Language Models for Enhanced Clustering Segmentation

# 摘要

> 聚类分析在多个领域中至关重要，如市场营销中的客户细分。然而，处理多模态数据（包括表格和文本）以揭示隐藏模式仍具挑战。为此，我们推出了ERASMO框架，通过微调预训练语言模型，将表格数据转化为文本格式，生成丰富且结构化的嵌入。实验证明，ERASMO能精准捕捉表格数据的独特上下文，提升聚类效果，揭示复杂关系。

> Cluster analysis plays a crucial role in various domains and applications, such as customer segmentation in marketing. These contexts often involve multimodal data, including both tabular and textual datasets, making it challenging to represent hidden patterns for obtaining meaningful clusters. This study introduces ERASMO, a framework designed to fine-tune a pretrained language model on textually encoded tabular data and generate embeddings from the fine-tuned model. ERASMO employs a textual converter to transform tabular data into a textual format, enabling the language model to process and understand the data more effectively. Additionally, ERASMO produces contextually rich and structurally representative embeddings through techniques such as random feature sequence shuffling and number verbalization. Extensive experimental evaluations were conducted using multiple datasets and baseline approaches. Our results demonstrate that ERASMO fully leverages the specific context of each tabular dataset, leading to more precise and nuanced embeddings for accurate clustering. This approach enhances clustering performance by capturing complex relationship patterns within diverse tabular data.

[Arxiv](https://arxiv.org/abs/2410.03738)