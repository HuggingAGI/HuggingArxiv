# 蒸馏视觉-语言预训练，提升跨模态检索效率

发布时间：2024年05月23日

`LLM应用

这篇论文探讨了如何利用大型预训练模型（如视觉-语言预训练模型）来提升跨模态搜索中的哈希学习技术。通过提出一种名为跨模态量化蒸馏（DCMQ）的方法，该论文展示了如何利用VLP模型的语义知识来优化哈希表示学习，并通过引入新的技术如配对一致性归一化（NPC）和带有Gumbel的乘积量化（PQG）来提高检索性能。这些应用性质的研究和方法的提出，使得该论文适合归类于LLM应用。` `图像搜索` `跨模态学习`

> Distilling Vision-Language Pretraining for Efficient Cross-Modal Retrieval

# 摘要

> “学习哈希”技术以其快速搜索和低成本存储的优势，在图像与文本跨模态搜索等领域得到广泛应用。本文探讨了如何借助如视觉-语言预训练模型等大型预训练模型的强大能力，进一步提升哈希学习的性能。我们提出了一种名为跨模态量化蒸馏（DCMQ）的创新方法，该方法通过VLP模型的丰富语义知识来优化哈希表示学习。具体而言，VLP模型作为“教师”，将其知识传授给配备码本的“学生”哈希模型，取代了原本缺乏语义的多热点向量监督标签。我们还引入了配对一致性归一化（NPC）技术，以实现更精准的蒸馏目标。此外，新提出的带有Gumbel的乘积量化（PQG）方法，通过平衡码本学习，显著提升了检索性能。大量基准测试结果显示，DCMQ在性能上超越了现有的监督跨模态哈希方法，展现了其巨大的潜力。

> ``Learning to hash'' is a practical solution for efficient retrieval, offering fast search speed and low storage cost. It is widely applied in various applications, such as image-text cross-modal search. In this paper, we explore the potential of enhancing the performance of learning to hash with the proliferation of powerful large pre-trained models, such as Vision-Language Pre-training (VLP) models. We introduce a novel method named Distillation for Cross-Modal Quantization (DCMQ), which leverages the rich semantic knowledge of VLP models to improve hash representation learning. Specifically, we use the VLP as a `teacher' to distill knowledge into a `student' hashing model equipped with codebooks. This process involves the replacement of supervised labels, which are composed of multi-hot vectors and lack semantics, with the rich semantics of VLP. In the end, we apply a transformation termed Normalization with Paired Consistency (NPC) to achieve a discriminative target for distillation. Further, we introduce a new quantization method, Product Quantization with Gumbel (PQG) that promotes balanced codebook learning, thereby improving the retrieval performance. Extensive benchmark testing demonstrates that DCMQ consistently outperforms existing supervised cross-modal hashing approaches, showcasing its significant potential.

[Arxiv](https://arxiv.org/abs/2405.14726)