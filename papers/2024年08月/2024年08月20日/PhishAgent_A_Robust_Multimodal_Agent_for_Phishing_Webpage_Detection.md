# PhishAgent：一款强大的多模态代理，专为钓鱼网页检测而设计。

发布时间：2024年08月20日

`Agent` `网络安全` `信息安全`

> PhishAgent: A Robust Multimodal Agent for Phishing Webpage Detection

# 摘要

> 钓鱼攻击严重威胁在线安全，利用用户漏洞窃取敏感信息。尽管已有多种反钓鱼方法，但各有局限。本研究引入PhishAgent，一个集成了在线与离线知识库及多模态大型语言模型的多模态代理，大幅提升品牌识别与记忆。我们还设计了一个多模态信息检索框架，从离线知识库中高效提取网页相关信息，包括标志、HTML和URL。实证结果显示，该框架显著提升检测准确性，减少误报与漏报，同时保持高效。此外，PhishAgent对多种对抗攻击展现出强大抵抗力。

> Phishing attacks are a major threat to online security, exploiting user vulnerabilities to steal sensitive information. Various methods have been developed to counteract phishing, each with varying levels of accuracy, but they also encounter notable limitations. In this study, we introduce PhishAgent, a multimodal agent that combines a wide range of tools, integrating both online and offline knowledge bases with Multimodal Large Language Models (MLLMs). This combination leads to broader brand coverage, which enhances brand recognition and recall. Furthermore, we propose a multimodal information retrieval framework designed to extract the top k relevant items from offline knowledge bases, utilizing all available information from a webpage, including logos, HTML, and URLs. Our empirical results, based on three real-world datasets, demonstrate that the proposed framework significantly enhances detection accuracy and reduces both false positives and false negatives, while maintaining model efficiency. Additionally, PhishAgent shows strong resilience against various types of adversarial attacks.

[Arxiv](https://arxiv.org/abs/2408.10738)