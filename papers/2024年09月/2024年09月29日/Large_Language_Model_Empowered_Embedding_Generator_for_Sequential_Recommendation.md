# 基于大型语言模型的嵌入生成器，助力序列推荐

发布时间：2024年09月29日

`LLM应用` `电子商务` `推荐系统`

> Large Language Model Empowered Embedding Generator for Sequential Recommendation

# 摘要

> 顺序推荐系统 (SRS) 通过建模用户交互序列来预测下一次交互，但常受困于长尾问题，难以推荐冷门商品。这不仅影响用户发现，还降低供应商收入，整体系统受损。大型语言模型 (LLM) 能理解商品间的语义联系，无论其热度，成为解决此问题的良方。我们提出 LLMEmb，利用 LLM 生成强化 SRS 的商品嵌入。为使 LLM 更贴合推荐需求，我们引入监督对比微调 (SCFT)，通过属性级数据增强和定制对比损失，优化 LLM 推荐性能。此外，我们强调协同过滤信号的重要性，并提出推荐适应训练 (RAT)，进一步优化嵌入。LLMEmb 嵌入可无缝集成到任何 SRS 模型，实用性强。实验证明，LLMEmb 在多个 SRS 模型中显著超越现有方法。

> Sequential Recommender Systems (SRS) are extensively applied across various domains to predict users' next interaction by modeling their interaction sequences. However, these systems typically grapple with the long-tail problem, where they struggle to recommend items that are less popular. This challenge results in a decline in user discovery and reduced earnings for vendors, negatively impacting the system as a whole. Large Language Model (LLM) has the potential to understand the semantic connections between items, regardless of their popularity, positioning them as a viable solution to this dilemma. In our paper, we present LLMEmb, an innovative technique that harnesses LLM to create item embeddings that bolster the performance of SRS. To align the capabilities of general-purpose LLM with the needs of the recommendation domain, we introduce a method called Supervised Contrastive Fine-Tuning (SCFT). This method involves attribute-level data augmentation and a custom contrastive loss designed to tailor LLM for enhanced recommendation performance. Moreover, we highlight the necessity of incorporating collaborative filtering signals into LLM-generated embeddings and propose Recommendation Adaptation Training (RAT) for this purpose. RAT refines the embeddings to be optimally suited for SRS. The embeddings derived from LLMEmb can be easily integrated with any SRS model, showcasing its practical utility. Extensive experimentation on three real-world datasets has shown that LLMEmb significantly improves upon current methods when applied across different SRS models.

[Arxiv](https://arxiv.org/abs/2409.19925)