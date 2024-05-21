# EmbSum：借助大型语言模型的摘要技术，优化基于内容的推荐系统

发布时间：2024年05月19日

`Agent

解析：这篇论文摘要描述了一个名为 EmbSum 的框架，该框架通过预计算用户和候选项目来捕捉用户参与历史的交互，并利用预训练的编码器-解码器模型和多注意力层来计算用户与候选项目之间的相关性。这个框架在 LLM（大型语言模型）的监督下生成用户兴趣摘要，以提升个性化内容推荐的准确性和吸引力。这里的 EmbSum 框架可以被视为一个智能代理（Agent），因为它能够处理用户数据并做出决策（推荐内容），以满足用户的需求。因此，这篇论文应归类为Agent。` `个性化推荐` `数字营销`

> EmbSum: Leveraging the Summarization Capabilities of Large Language Models for Content-Based Recommendations

# 摘要

> EmbSum 框架在数字世界中通过离线预计算用户和候选项目，巧妙捕捉用户参与历史的交互，为个性化内容推荐提供了新思路。借助预训练的编码器-解码器模型和多注意力层，EmbSum 计算用户与候选项目间的相关性，通过 LLM 监督下的用户兴趣摘要，深入挖掘用户长期兴趣。在两个领域的数据集测试中，EmbSum 不仅超越了现有技术，还以更少的参数实现了更高的准确性。其生成的用户兴趣摘要，更是锦上添花，极大提升了个性化推荐的吸引力。

> Content-based recommendation systems play a crucial role in delivering personalized content to users in the digital world. In this work, we introduce EmbSum, a novel framework that enables offline pre-computations of users and candidate items while capturing the interactions within the user engagement history. By utilizing the pretrained encoder-decoder model and poly-attention layers, EmbSum derives User Poly-Embedding (UPE) and Content Poly-Embedding (CPE) to calculate relevance scores between users and candidate items. EmbSum actively learns the long user engagement histories by generating user-interest summary with supervision from large language model (LLM). The effectiveness of EmbSum is validated on two datasets from different domains, surpassing state-of-the-art (SoTA) methods with higher accuracy and fewer parameters. Additionally, the model's ability to generate summaries of user interests serves as a valuable by-product, enhancing its usefulness for personalized content recommendations.

[Arxiv](https://arxiv.org/abs/2405.11441)