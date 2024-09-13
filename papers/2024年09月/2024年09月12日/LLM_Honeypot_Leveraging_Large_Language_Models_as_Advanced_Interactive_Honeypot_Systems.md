# LLM 蜜罐：将大型语言模型转化为高级交互式蜜罐系统

发布时间：2024年09月12日

`LLM应用` `网络安全` `人工智能`

> LLM Honeypot: Leveraging Large Language Models as Advanced Interactive Honeypot Systems

# 摘要

> 网络威胁的迅速变化催生了创新的检测和分析方法。蜜罐作为诱饵系统，已成为网络安全的重要工具。本文介绍了一种利用大型语言模型（LLM）构建真实互动蜜罐的新方法。通过微调开源语言模型，使其学习攻击者的命令和响应，我们开发了一个能与攻击者深度互动的蜜罐。该方法包括数据收集、提示设计、模型选择和监督微调等步骤。评估结果显示，该蜜罐能生成准确且有价值的响应。这不仅展示了LLM在蜜罐技术中的革命性潜力，也为网络安全提供了强有力的工具，有助于提升整体安全防护。

> The rapid evolution of cyber threats necessitates innovative solutions for detecting and analyzing malicious activity. Honeypots, which are decoy systems designed to lure and interact with attackers, have emerged as a critical component in cybersecurity. In this paper, we present a novel approach to creating realistic and interactive honeypot systems using Large Language Models (LLMs). By fine-tuning a pre-trained open-source language model on a diverse dataset of attacker-generated commands and responses, we developed a honeypot capable of sophisticated engagement with attackers. Our methodology involved several key steps: data collection and processing, prompt engineering, model selection, and supervised fine-tuning to optimize the model's performance. Evaluation through similarity metrics and live deployment demonstrated that our approach effectively generates accurate and informative responses. The results highlight the potential of LLMs to revolutionize honeypot technology, providing cybersecurity professionals with a powerful tool to detect and analyze malicious activity, thereby enhancing overall security infrastructure.

[Arxiv](https://arxiv.org/abs/2409.08234)