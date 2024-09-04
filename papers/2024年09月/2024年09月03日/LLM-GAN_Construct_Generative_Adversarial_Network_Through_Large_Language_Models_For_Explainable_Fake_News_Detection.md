# LLM-GAN：利用大型语言模型构建生成对抗网络，旨在提升假新闻检测的可解释性。

发布时间：2024年09月03日

`LLM应用` `云计算`

> LLM-GAN: Construct Generative Adversarial Network Through Large Language Models For Explainable Fake News Detection

# 摘要

> 可解释的假新闻检测通过附带解释来判断新闻真伪。大型语言模型 (LLM) 因其卓越的自然语言理解和解释生成能力而备受瞩目。但将其应用于假新闻检测仍存难题：假新闻的合理性易误导 LLM，且生成的解释质量参差不齐，需大量人工干预。为此，我们创新提出 LLM-GAN 框架，通过提示机制让 LLM 兼具生成与检测功能，有效应对假新闻。实验证明，LLM-GAN 在预测准确性和解释质量上表现出色。此外，我们还将 LLM-GAN 融入云原生 AI 平台，以云服务形式提供更精准的假新闻检测。

> Explainable fake news detection predicts the authenticity of news items with annotated explanations. Today, Large Language Models (LLMs) are known for their powerful natural language understanding and explanation generation abilities. However, presenting LLMs for explainable fake news detection remains two main challenges. Firstly, fake news appears reasonable and could easily mislead LLMs, leaving them unable to understand the complex news-faking process. Secondly, utilizing LLMs for this task would generate both correct and incorrect explanations, which necessitates abundant labor in the loop. In this paper, we propose LLM-GAN, a novel framework that utilizes prompting mechanisms to enable an LLM to become Generator and Detector and for realistic fake news generation and detection. Our results demonstrate LLM-GAN's effectiveness in both prediction performance and explanation quality. We further showcase the integration of LLM-GAN to a cloud-native AI platform to provide better fake news detection service in the cloud.

[Arxiv](https://arxiv.org/abs/2409.01787)