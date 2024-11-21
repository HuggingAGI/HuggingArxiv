# 留意差距：跨模态嵌入对齐的通用之法

发布时间：2024年10月30日

`RAG` `迁移学习`

> Mind the Gap: A Generalized Approach for Cross-Modal Embedding Alignment

# 摘要

> 检索增强生成（RAG）系统借助融合外部知识来优化文本生成，然而因语义差异，在跨不同文本模态检索上下文时常常遭遇难题。受迁移学习中的适配器模块启发，我们推出了一种基于广义投影的办法，能有效填补诸如编程代码与伪代码，或者英语和法语句子等不同文本类型之间的这些鸿沟。我们的方法注重速度、精准度和数据效率，训练与推理所需资源极少。通过轻量级投影网络将来自异构文本模态的嵌入对齐到统一空间，我们的模型大幅超越传统检索方法（如Okapi BM25算法）和模型（如密集段落检索（DPR）），同时接近句子转换器的精度。大量评估表明我们的方法在不同任务中的有效性和通用性，凸显了其在实时、资源受限应用中的潜力。

> Retrieval-Augmented Generation (RAG) systems enhance text generation by incorporating external knowledge but often struggle when retrieving context across different text modalities due to semantic gaps. We introduce a generalized projection-based method, inspired by adapter modules in transfer learning, that efficiently bridges these gaps between various text types, such as programming code and pseudocode, or English and French sentences. Our approach emphasizes speed, accuracy, and data efficiency, requiring minimal resources for training and inference. By aligning embeddings from heterogeneous text modalities into a unified space through a lightweight projection network, our model significantly outperforms traditional retrieval methods like the Okapi BM25 algorithm and models like Dense Passage Retrieval (DPR), while approaching the accuracy of Sentence Transformers. Extensive evaluations demonstrate the effectiveness and generalizability of our method across different tasks, highlighting its potential for real-time, resource-constrained applications.

[Arxiv](https://arxiv.org/abs/2410.23437)