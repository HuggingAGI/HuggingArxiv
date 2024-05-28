# 利用稀疏上下文选择技术，加速检索增强生成模型的推理过程

发布时间：2024年05月25日

`RAG

理由：这篇论文主要介绍了一种名为Sparse RAG的创新模式，该模式通过稀疏性策略降低计算负担，并优化了大型语言模型（LLMs）的检索增强功能。论文的核心在于改进RAG（检索增强生成）系统，通过稀疏机制设计减少加载文档的数量，加速推理过程，并提高模型对相关情境的关注，从而提升生成质量。这与RAG系统的优化和改进直接相关，因此归类为RAG。` `信息检索`

> Accelerating Inference of Retrieval-Augmented Generation via Sparse Context Selection

# 摘要

> 通过整合外部信息，大型语言模型（LLMs）的检索增强功能展现出卓越的性能和广泛的灵活性。但随着检索文档数量的增加，输入长度的线性增长导致了显著的延迟问题。为此，我们提出了一种名为Sparse RAG的创新模式，旨在通过稀疏性策略降低计算负担。Sparse RAG采用并行编码方式处理检索文档，有效避免了长距离注意力带来的延迟。随后，LLMs通过特殊控制标记引导，仅自回归地关注高度相关的缓存来解码输出。这一模式将文档评估与响应生成融为一体，RAG系统中的稀疏机制设计减少了加载文档的数量，加速了推理过程，同时通过过滤无关内容，提升了模型对相关情境的关注，从而提高了生成质量。对两个数据集的评估表明，Sparse RAG在生成质量和计算效率之间实现了理想平衡，适用于各种长短形式的生成任务。

> Large language models (LLMs) augmented with retrieval exhibit robust performance and extensive versatility by incorporating external contexts. However, the input length grows linearly in the number of retrieved documents, causing a dramatic increase in latency. In this paper, we propose a novel paradigm named Sparse RAG, which seeks to cut computation costs through sparsity. Specifically, Sparse RAG encodes retrieved documents in parallel, which eliminates latency introduced by long-range attention of retrieved documents. Then, LLMs selectively decode the output by only attending to highly relevant caches auto-regressively, which are chosen via prompting LLMs with special control tokens. It is notable that Sparse RAG combines the assessment of each individual document and the generation of the response into a single process. The designed sparse mechanism in a RAG system can facilitate the reduction of the number of documents loaded during decoding for accelerating the inference of the RAG system. Additionally, filtering out undesirable contexts enhances the model's focus on relevant context, inherently improving its generation quality. Evaluation results of two datasets show that Sparse RAG can strike an optimal balance between generation quality and computational efficiency, demonstrating its generalizability across both short- and long-form generation tasks.

![利用稀疏上下文选择技术，加速检索增强生成模型的推理过程](../../../paper_images/2405.16178/x1.png)

![利用稀疏上下文选择技术，加速检索增强生成模型的推理过程](../../../paper_images/2405.16178/graph1-1.png)

![利用稀疏上下文选择技术，加速检索增强生成模型的推理过程](../../../paper_images/2405.16178/graph2.png)

[Arxiv](https://arxiv.org/abs/2405.16178)