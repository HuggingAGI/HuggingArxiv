# garak：大型语言模型安全探测的框架

发布时间：2024年06月16日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在对抗性攻击下的安全性问题，并提出了一种新的评估框架（garak）来系统地揭示和评估这些模型的潜在漏洞。这种研究直接关联到LLMs的实际应用场景，特别是在安全性评估方面，因此属于LLM应用分类。论文中提到的“生成式AI红队与评估工具包”（garak）是一个具体的应用工具，用于评估和增强LLMs的安全性，这进一步支持了其分类为LLM应用。` `人工智能安全` `对话系统`

> garak: A Framework for Security Probing Large Language Models

# 摘要

> 随着大型语言模型（LLMs）广泛应用于各种场景，对其在对抗性攻击下的表现进行可扩展评估的需求日益迫切。但LLM的安全性如同移动靶，模型输出难以预测，持续更新，而潜在的攻击者则遍布网络，精通自然语言。在某一情境下的安全漏洞，在另一情境中可能无关紧要，通用的防护措施尚属理论。本文主张，应重新定义“LLM安全”，并采取全面的安全评估策略，以探索和发现为核心。为此，我们推出了garak（生成式AI红队与评估工具包），这一框架能系统地揭示目标LLM或对话系统的潜在漏洞。garak的分析结果不仅揭示了模型的弱点，还促进了关于特定情境下漏洞构成的深入讨论，并为LLM部署的策略制定提供了依据。

> As Large Language Models (LLMs) are deployed and integrated into thousands of applications, the need for scalable evaluation of how models respond to adversarial attacks grows rapidly. However, LLM security is a moving target: models produce unpredictable output, are constantly updated, and the potential adversary is highly diverse: anyone with access to the internet and a decent command of natural language. Further, what constitutes a security weak in one context may not be an issue in a different context; one-fits-all guardrails remain theoretical. In this paper, we argue that it is time to rethink what constitutes ``LLM security'', and pursue a holistic approach to LLM security evaluation, where exploration and discovery of issues are central. To this end, this paper introduces garak (Generative AI Red-teaming and Assessment Kit), a framework which can be used to discover and identify vulnerabilities in a target LLM or dialog system. garak probes an LLM in a structured fashion to discover potential vulnerabilities. The outputs of the framework describe a target model's weaknesses, contribute to an informed discussion of what composes vulnerabilities in unique contexts, and can inform alignment and policy discussions for LLM deployment.

![garak：大型语言模型安全探测的框架](../../../paper_images/2406.11036/garak_diagram.png)

![garak：大型语言模型安全探测的框架](../../../paper_images/2406.11036/x1.png)

![garak：大型语言模型安全探测的框架](../../../paper_images/2406.11036/x2.png)

![garak：大型语言模型安全探测的框架](../../../paper_images/2406.11036/cli1.png)

![garak：大型语言模型安全探测的框架](../../../paper_images/2406.11036/cli2.png)

[Arxiv](https://arxiv.org/abs/2406.11036)