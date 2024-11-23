# 基于嵌入的分类器能够检测出提示注入攻击

发布时间：2024年10月29日

`LLM应用` `语言模型` `网络安全`

> Embedding-based classifiers can detect prompt injection attacks

# 摘要

> 大型语言模型（LLMs）凭借出色的生成能力，在各类组织中被大量采用。然而，LLMs易受多种对抗性攻击，尤其是提示注入攻击，会使其生成有害或不当内容。攻击者精心炮制恶意提示来欺骗LLMs从而发起此类攻击。在本文中，我们提出了一种基于嵌入的机器学习（ML）分类器的新颖方法，以保护基于LLM的应用抵御这一严重威胁。我们借助三种常用的嵌入模型生成恶意和良性提示的嵌入，并运用ML分类器来判别输入提示是否恶意。在若干传统ML方法中，使用随机森林和XGBoost构建的分类器表现最佳。我们的分类器优于开源实现中采用仅编码器神经网络的最先进提示注入分类器。

> Large Language Models (LLMs) are seeing significant adoption in every type of organization due to their exceptional generative capabilities. However, LLMs are found to be vulnerable to various adversarial attacks, particularly prompt injection attacks, which trick them into producing harmful or inappropriate content. Adversaries execute such attacks by crafting malicious prompts to deceive the LLMs. In this paper, we propose a novel approach based on embedding-based Machine Learning (ML) classifiers to protect LLM-based applications against this severe threat. We leverage three commonly used embedding models to generate embeddings of malicious and benign prompts and utilize ML classifiers to predict whether an input prompt is malicious. Out of several traditional ML methods, we achieve the best performance with classifiers built using Random Forest and XGBoost. Our classifiers outperform state-of-the-art prompt injection classifiers available in open-source implementations, which use encoder-only neural networks.

[Arxiv](https://arxiv.org/abs/2410.22284)