# 大型语言模型优化了对长尾用户及物品的序列推荐策略

发布时间：2024年05月31日

`LLM应用

这篇论文主要探讨了如何利用大型语言模型（LLMs）来改进序列推荐系统（SRS），特别是在处理“长尾用户”和“长尾商品”问题上的应用。论文提出了一种名为LLM-ESR的框架，该框架利用LLMs的语义嵌入来提升SRS的性能，并针对长尾问题提出了具体的解决方案。这些内容主要集中在LLMs的实际应用层面，因此归类为LLM应用。` `社交网络`

> Large Language Models Enhanced Sequential Recommendation for Long-tail User and Item

# 摘要

> 序列推荐系统（SRS）通过分析用户历史交互来预测其未来偏好，广泛应用于电商和社交网络等领域。但实际应用中，多数用户仅与少数商品互动，而大量商品鲜有人问津，这一现象被称为“长尾用户”和“长尾商品”困境，给传统SRS带来挑战。解决这些问题对提升用户满意度和商业盈利至关重要。尽管已有研究尝试缓解，但仍面临交互数据稀缺导致的平衡问题和噪音干扰。大型语言模型（LLMs）的出现为解决这些问题提供了新思路。本研究提出了一种名为LLM-ESR的框架，利用LLMs的语义嵌入提升SRS性能，同时不增加计算负担。针对长尾商品问题，我们采用了结合LLMs语义信息与传统SRS协作信号的双重视图建模方法。对于长尾用户问题，我们开发了一种检索增强的自蒸馏技术，通过整合相似用户的丰富交互数据来优化用户偏好表示。通过在三个真实数据集上对三种主流SRS模型进行广泛测试，我们的增强框架显示出优于现有技术的性能。

> Sequential recommendation systems (SRS) serve the purpose of predicting users' subsequent preferences based on their past interactions and have been applied across various domains such as e-commerce and social networking platforms. However, practical SRS encounters challenges due to the fact that most users engage with only a limited number of items, while the majority of items are seldom consumed. These challenges, termed as the long-tail user and long-tail item dilemmas, often create obstacles for traditional SRS methods. Mitigating these challenges is crucial as they can significantly impact user satisfaction and business profitability. While some research endeavors have alleviated these issues, they still grapple with issues such as seesaw or noise stemming from the scarcity of interactions. The emergence of large language models (LLMs) presents a promising avenue to address these challenges from a semantic standpoint. In this study, we introduce the Large Language Models Enhancement framework for Sequential Recommendation (LLM-ESR), which leverages semantic embeddings from LLMs to enhance SRS performance without increasing computational overhead. To combat the long-tail item challenge, we propose a dual-view modeling approach that fuses semantic information from LLMs with collaborative signals from traditional SRS. To address the long-tail user challenge, we introduce a retrieval augmented self-distillation technique to refine user preference representations by incorporating richer interaction data from similar users. Through comprehensive experiments conducted on three authentic datasets using three widely used SRS models, our proposed enhancement framework demonstrates superior performance compared to existing methodologies.

[Arxiv](https://arxiv.org/abs/2405.20646)