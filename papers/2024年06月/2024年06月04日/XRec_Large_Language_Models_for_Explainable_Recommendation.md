# XRec：利用大型语言模型实现推荐系统的透明解析

发布时间：2024年06月04日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLMs）来增强推荐系统的可解释性，提出了一个名为XRec的框架，该框架能够为用户的推荐行为提供详细的解释。这表明论文的重点在于应用LLMs来解决实际问题，即推荐系统的可解释性，而不是探讨LLMs的理论基础或Agent的设计与实现。因此，它属于LLM应用分类。` `推荐系统`

> XRec: Large Language Models for Explainable Recommendation

# 摘要

> 推荐系统通过个性化推荐帮助用户应对信息泛滥，而协同过滤（CF）是其中的常用手段。尽管图神经网络（GNNs）和自监督学习（SSL）等技术提升了CF的用户表示能力，但它们往往难以解释推荐理由。可解释推荐通过揭示推荐决策的内幕，增进用户理解。本研究利用大型语言模型（LLMs）的语言天赋，拓展了可解释推荐系统的疆界。我们提出的XRec框架，让LLMs能为用户行为提供详尽解释。通过巧妙融合协同信号与轻量级适配器设计，XRec赋予LLMs洞察用户与物品互动的复杂模式，深入挖掘用户偏好。实验结果显示，XRec在生成有深度且有意义的解释方面表现卓越，超越了同类基线。我们已在GitHub上开源XRec模型，地址为https://github.com/HKUDS/XRec。

> Recommender systems help users navigate information overload by providing personalized recommendations aligned with their preferences. Collaborative Filtering (CF) is a widely adopted approach, but while advanced techniques like graph neural networks (GNNs) and self-supervised learning (SSL) have enhanced CF models for better user representations, they often lack the ability to provide explanations for the recommended items. Explainable recommendations aim to address this gap by offering transparency and insights into the recommendation decision-making process, enhancing users' understanding. This work leverages the language capabilities of Large Language Models (LLMs) to push the boundaries of explainable recommender systems. We introduce a model-agnostic framework called XRec, which enables LLMs to provide comprehensive explanations for user behaviors in recommender systems. By integrating collaborative signals and designing a lightweight collaborative adaptor, the framework empowers LLMs to understand complex patterns in user-item interactions and gain a deeper understanding of user preferences. Our extensive experiments demonstrate the effectiveness of XRec, showcasing its ability to generate comprehensive and meaningful explanations that outperform baseline approaches in explainable recommender systems. We open-source our model implementation at https://github.com/HKUDS/XRec.

![XRec：利用大型语言模型实现推荐系统的透明解析](../../../paper_images/2406.02377/x1.png)

![XRec：利用大型语言模型实现推荐系统的透明解析](../../../paper_images/2406.02377/x2.png)

![XRec：利用大型语言模型实现推荐系统的透明解析](../../../paper_images/2406.02377/x3.png)

![XRec：利用大型语言模型实现推荐系统的透明解析](../../../paper_images/2406.02377/x4.png)

![XRec：利用大型语言模型实现推荐系统的透明解析](../../../paper_images/2406.02377/x5.png)

![XRec：利用大型语言模型实现推荐系统的透明解析](../../../paper_images/2406.02377/x6.png)

![XRec：利用大型语言模型实现推荐系统的透明解析](../../../paper_images/2406.02377/x7.png)

[Arxiv](https://arxiv.org/abs/2406.02377)