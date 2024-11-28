# 打破 ID - 语言的壁垒：序列推荐的适配框架

发布时间：2024年11月27日

`LLM应用` `推荐系统`

> Break the ID-Language Barrier: An Adaption Framework for Sequential Recommendation

# 摘要

> 大型语言模型（LLMs）在自然语言处理领域的最新突破，促使人们在推荐系统方面展开探索。然而，LLMs 特定领域知识的有限性仍是关键瓶颈，尤其是缺乏诸如用户行为模式等对序列推荐至关重要的关键信息。为填补这一关键空缺，我们提出了 IDLE-Adapter 这一创新框架，将富含特定领域知识的预训练 ID 嵌入整合进 LLMs，以提升推荐的准确性。IDLE-Adapter 如同桥梁一般，借助预训练的 ID 序列模型、维度对齐、分层嵌入细化以及分层分布对齐，把稀疏的用户-项目交互数据转化为密集且与 LLM 适配的表示。此外，IDLE-Adapter 能无缝融合来自不同基于 ID 的序列模型和 LLM 架构的 ID 嵌入，展现出了显著的灵活性。在各类数据集上开展的大量实验表明了 IDLE-Adapter 的优越性，与前沿方法相比，在 HitRate@5 和 NDCG@5 指标上分别实现了超 10％和 20％的改进。

> The recent breakthrough of large language models (LLMs) in natural language processing has sparked exploration in recommendation systems, however, their limited domain-specific knowledge remains a critical bottleneck. Specifically, LLMs lack key pieces of information crucial for sequential recommendations, such as user behavior patterns. To address this critical gap, we propose IDLE-Adapter, a novel framework that integrates pre-trained ID embeddings, rich in domain-specific knowledge, into LLMs to improve recommendation accuracy. IDLE-Adapter acts as a bridge, transforming sparse user-item interaction data into dense, LLM-compatible representations through a Pre-trained ID Sequential Model, Dimensionality Alignment, Layer-wise Embedding Refinement, and Layer-wise Distribution Alignment. Furthermore, IDLE-Adapter demonstrates remarkable flexibility by seamlessly integrating ID embeddings from diverse ID-based sequential models and LLM architectures. Extensive experiments across various datasets demonstrate the superiority of IDLE-Adapter, achieving over 10\% and 20\% improvements in HitRate@5 and NDCG@5 metrics, respectively, compared to state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2411.18262)