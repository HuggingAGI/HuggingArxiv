# EmbSum：借助大型语言模型的摘要能力，实现基于内容的精准推荐

发布时间：2024年05月19日

`Agent

理由：EmbSum 框架通过预计算用户和候选项目，并利用预训练的编码器-解码器模型和多注意力层来计算用户与候选项目间的相关性，生成用户兴趣摘要，这表明它是一个用于个性化内容推荐的智能代理系统。它通过分析用户的历史参与数据来提供个性化推荐，这符合Agent的定义，即一个能够感知环境、做出决策并执行动作以达到目标的系统。因此，该论文应归类于Agent。` `个性化推荐` `数字内容`

> EmbSum: Leveraging the Summarization Capabilities of Large Language Models for Content-Based Recommendations

# 摘要

> EmbSum 框架在数字世界中通过离线预计算用户和候选项目，并捕捉用户参与历史中的交互，为个性化内容推荐提供了创新途径。借助预训练的编码器-解码器模型和多注意力层，EmbSum 计算用户与候选项目间的相关性，通过 LLM 监督生成用户兴趣摘要，深入挖掘用户长期参与历史。在不同领域的两个数据集上，EmbSum 以更高的准确性和更少的参数超越了现有技术，其生成的用户兴趣摘要更是锦上添花，极大提升了个性化推荐的效能。

> Content-based recommendation systems play a crucial role in delivering personalized content to users in the digital world. In this work, we introduce EmbSum, a novel framework that enables offline pre-computations of users and candidate items while capturing the interactions within the user engagement history. By utilizing the pretrained encoder-decoder model and poly-attention layers, EmbSum derives User Poly-Embedding (UPE) and Content Poly-Embedding (CPE) to calculate relevance scores between users and candidate items. EmbSum actively learns the long user engagement histories by generating user-interest summary with supervision from large language model (LLM). The effectiveness of EmbSum is validated on two datasets from different domains, surpassing state-of-the-art (SoTA) methods with higher accuracy and fewer parameters. Additionally, the model's ability to generate summaries of user interests serves as a valuable by-product, enhancing its usefulness for personalized content recommendations.

[Arxiv](https://arxiv.org/abs/2405.11441)