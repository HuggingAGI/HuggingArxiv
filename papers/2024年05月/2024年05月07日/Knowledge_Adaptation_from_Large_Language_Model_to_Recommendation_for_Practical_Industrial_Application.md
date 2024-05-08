# 大型语言模型知识迁移至推荐系统：工业应用实践之路

发布时间：2024年05月07日

`LLM应用

这篇论文探讨了如何利用大型语言模型（LLMs）来改进推荐系统，特别是在处理冷启动和长尾推荐问题时。它提出了一种名为LEARN的框架，该框架通过冻结LLM参数来保持计算效率，同时利用LLMs的预训练能力来融合开放世界知识。这种方法旨在提高推荐系统的智能水平，并且通过实验证明了其有效性。因此，这篇论文属于LLM应用类别，因为它关注的是LLMs在推荐系统中的实际应用和改进。` `推荐系统` `电子商务`

> Knowledge Adaptation from Large Language Model to Recommendation for Practical Industrial Application

# 摘要

> 现代推荐系统多依赖协同过滤，却忽视了物品描述中的语义宝藏，导致冷启动和长尾推荐不尽人意。我们借助大型语言模型（LLMs）的预训练能力，提出了一种融合开放世界知识的LEARN框架，旨在提升推荐系统的智能。通过巧妙地冻结LLM参数，我们既避免了知识遗忘，又保持了计算效率。双塔结构的设计，如同桥梁，连接了开放世界与协同领域，专为工业应用量身打造。实验证明，我们的方法在数据海洋中乘风破浪，成效显著。

> Contemporary recommender systems predominantly rely on collaborative filtering techniques, employing ID-embedding to capture latent associations among users and items. However, this approach overlooks the wealth of semantic information embedded within textual descriptions of items, leading to suboptimal performance in cold-start scenarios and long-tail user recommendations. Leveraging the capabilities of Large Language Models (LLMs) pretrained on massive text corpus presents a promising avenue for enhancing recommender systems by integrating open-world domain knowledge. In this paper, we propose an Llm-driven knowlEdge Adaptive RecommeNdation (LEARN) framework that synergizes open-world knowledge with collaborative knowledge. We address computational complexity concerns by utilizing pretrained LLMs as item encoders and freezing LLM parameters to avoid catastrophic forgetting and preserve open-world knowledge. To bridge the gap between the open-world and collaborative domains, we design a twin-tower structure supervised by the recommendation task and tailored for practical industrial application. Through offline experiments on the large-scale industrial dataset and online experiments on A/B tests, we demonstrate the efficacy of our approach.

[Arxiv](https://arxiv.org/abs/2405.03988)