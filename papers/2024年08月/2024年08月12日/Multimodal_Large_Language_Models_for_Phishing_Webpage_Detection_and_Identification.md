# 多模态大型语言模型在钓鱼网页检测与识别中的应用

发布时间：2024年08月12日

`LLM应用` `网络安全` `机器学习`

> Multimodal Large Language Models for Phishing Webpage Detection and Identification

# 摘要

> 面对检测钓鱼网页的挑战，研究者们已开发出多种基于机器学习的解决方案，尤其是那些利用计算机视觉模型来识别网页是否模仿知名品牌的方法。然而，这些模型维护成本高且复杂，需要不断更新带标签的数据集，并保持一个详尽的知名网站及其元数据列表。本研究聚焦于大型语言模型（尤其是多模态LLMs）在钓鱼网页检测中的应用。鉴于LLMs的广泛预训练基础，我们计划利用其对网页元素（如标志、主题等）的深刻理解来识别品牌，并通过与URL域名的对比来揭示潜在的钓鱼行为。我们设计了一个双阶段系统，第一阶段进行品牌识别，第二阶段验证域名。实验结果显示，该系统不仅检测率高且精度卓越，还提供了决策的可解释依据。此外，它在性能上超越了当前顶尖的基于品牌的钓鱼检测系统，并能抵御两种常见的对抗攻击。

> To address the challenging problem of detecting phishing webpages, researchers have developed numerous solutions, in particular those based on machine learning (ML) algorithms. Among these, brand-based phishing detection that uses models from Computer Vision to detect if a given webpage is imitating a well-known brand has received widespread attention. However, such models are costly and difficult to maintain, as they need to be retrained with labeled dataset that has to be regularly and continuously collected. Besides, they also need to maintain a good reference list of well-known websites and related meta-data for effective performance.
  In this work, we take steps to study the efficacy of large language models (LLMs), in particular the multimodal LLMs, in detecting phishing webpages. Given that the LLMs are pretrained on a large corpus of data, we aim to make use of their understanding of different aspects of a webpage (logo, theme, favicon, etc.) to identify the brand of a given webpage and compare the identified brand with the domain name in the URL to detect a phishing attack. We propose a two-phase system employing LLMs in both phases: the first phase focuses on brand identification, while the second verifies the domain. We carry out comprehensive evaluations on a newly collected dataset. Our experiments show that the LLM-based system achieves a high detection rate at high precision; importantly, it also provides interpretable evidence for the decisions. Our system also performs significantly better than a state-of-the-art brand-based phishing detection system while demonstrating robustness against two known adversarial attacks.

[Arxiv](https://arxiv.org/abs/2408.05941)