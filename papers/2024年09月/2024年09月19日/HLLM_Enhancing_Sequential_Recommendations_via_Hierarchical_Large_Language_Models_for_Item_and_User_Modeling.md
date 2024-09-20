# HLLM：利用分层大型语言模型，提升项目与用户建模的顺序推荐效果

发布时间：2024年09月19日

`LLM应用` `推荐系统` `电子商务`

> HLLM: Enhancing Sequential Recommendations via Hierarchical Large Language Models for Item and User Modeling

# 摘要

> 大型语言模型 (LLM) 在多个领域表现出色，激发了其在推荐系统中的应用研究。然而，这些研究仅带来了有限的改进。本文探讨了三个关键问题：LLM 预训练权重的实际价值、推荐任务中微调的必要性，以及 LLM 在推荐系统中的可扩展性。为此，我们提出了分层大型语言模型 (HLLM)，通过两层模型分别提取项目特征和预测用户兴趣。实验证明，HLLM 不仅有效利用了预训练能力，还通过微调显著提升了性能。HLLM 具备出色的可扩展性和效率，适用于实际应用。在 PixelRec 和 Amazon Reviews 数据集上的测试中，HLLM 表现卓越，大幅超越传统模型。在线 A/B 测试进一步验证了其应用价值。代码已开源，详见 https://github.com/bytedance/HLLM。

> Large Language Models (LLMs) have achieved remarkable success in various fields, prompting several studies to explore their potential in recommendation systems. However, these attempts have so far resulted in only modest improvements over traditional recommendation models. Moreover, three critical questions remain under-explored: firstly, the real value of LLMs' pre-trained weights, often considered to encapsulate world knowledge; secondly, the necessity of fine-tuning for recommendation tasks; lastly, whether LLMs can exhibit the same scalability benefits in recommendation systems as they do in other domains. In this paper, we propose a novel Hierarchical Large Language Model (HLLM) architecture designed to enhance sequential recommendation systems. Our approach employs a two-tier model: the first Item LLM extracts rich content features from the detailed text description of the item, while the second User LLM utilizes these features to predict users' future interests based on their interaction history. Extensive experiments demonstrate that our method effectively leverages the pre-trained capabilities of open-source LLMs, and further fine-tuning leads to significant performance boosts. Additionally, HLLM achieves excellent scalability, with the largest configuration utilizing 7B parameters for both item feature extraction and user interest modeling. Moreover, HLLM offers excellent training and serving efficiency, making it practical in real-world applications. Evaluations on two large-scale datasets, PixelRec and Amazon Reviews, show that HLLM achieves state-of-the-art results, outperforming traditional ID-based models by a wide margin. In online A/B testing, HLLM showcases notable gains, validating its practical impact in real-world recommendation scenarios. Codes are available at https://github.com/bytedance/HLLM.

[Arxiv](https://arxiv.org/abs/2409.12740)