# 大型语言模型知识迁移至推荐系统：工业应用实践之路

发布时间：2024年05月07日

`Agent

这篇论文主要讨论了如何将大型语言模型（LLMs）应用于推荐系统中，以提升其性能，特别是在处理冷启动和长尾用户推荐问题时。它提出了一种名为LEARN的框架，该框架结合了LLMs的开放世界知识和协同知识，并通过双塔结构将这些知识应用于推荐任务。因此，这篇论文更偏向于Agent的分类，因为它描述了一个系统或代理如何利用LLMs来执行特定的任务，即推荐系统的优化。` `推荐系统`

> Knowledge Adaptation from Large Language Model to Recommendation for Practical Industrial Application

# 摘要

> 现代推荐系统多采用协同过滤技术，通过ID嵌入揭示用户与物品间的隐秘联系。但此法忽视了物品文本描述中的深层语义，致使其在冷启动和长尾用户推荐中表现平平。本文提出一种LEARN框架，巧妙融合大型语言模型（LLMs）的开放世界知识与协同知识，以提升推荐系统性能。我们采用预训练LLMs作为物品编码器，并固定其参数，既避免了知识遗忘，又保留了开放世界知识的广博。为连接开放世界与协同领域，我们设计了双塔结构，专为工业应用定制，由推荐任务精准引导。通过大规模数据集的离线测试与在线A/B测试，我们的方法展现了其卓越效能。

> Contemporary recommender systems predominantly rely on collaborative filtering techniques, employing ID-embedding to capture latent associations among users and items. However, this approach overlooks the wealth of semantic information embedded within textual descriptions of items, leading to suboptimal performance in cold-start scenarios and long-tail user recommendations. Leveraging the capabilities of Large Language Models (LLMs) pretrained on massive text corpus presents a promising avenue for enhancing recommender systems by integrating open-world domain knowledge. In this paper, we propose an Llm-driven knowlEdge Adaptive RecommeNdation (LEARN) framework that synergizes open-world knowledge with collaborative knowledge. We address computational complexity concerns by utilizing pretrained LLMs as item encoders and freezing LLM parameters to avoid catastrophic forgetting and preserve open-world knowledge. To bridge the gap between the open-world and collaborative domains, we design a twin-tower structure supervised by the recommendation task and tailored for practical industrial application. Through offline experiments on the large-scale industrial dataset and online experiments on A/B tests, we demonstrate the efficacy of our approach.

[Arxiv](https://arxiv.org/abs/2405.03988)