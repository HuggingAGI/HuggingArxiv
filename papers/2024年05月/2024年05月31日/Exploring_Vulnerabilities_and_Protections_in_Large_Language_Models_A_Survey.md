# 大型语言模型漏洞与防护探索：一份综述

发布时间：2024年05月31日

`LLM理论

这篇论文的摘要主要关注大型语言模型（LLMs）的安全性问题，包括提示词攻击和对抗性攻击等安全挑战，并详细分析了这些威胁类型及其防御机制。这种类型的研究更多地属于理论探讨，因为它涉及对LLMs安全漏洞的深入分析和防御策略的提出，而不是直接应用于特定的Agent或RAG系统，也不是关于LLM的具体应用案例。因此，将其归类为LLM理论是合适的。` `人工智能`

> Exploring Vulnerabilities and Protections in Large Language Models: A Survey

# 摘要

> 随着大型语言模型（LLMs）在AI应用中的地位日益重要，其安全漏洞和防御机制的有效性成为研究焦点。本调查深入探讨了LLMs面临的安全挑战，特别关注提示词攻击和对抗性攻击两大领域，并详细分析了各自的威胁类型。在提示词攻击方面，我们详细讨论了提示注入和越狱攻击的机制、影响及防范措施。对抗性攻击则被细分为数据投毒和后门攻击进行分析。通过这种结构化的审查，我们揭示了这些漏洞间的关联及相应的防御策略。调查不仅强调了这些安全挑战，还提出了保护LLMs的强大防御框架，为构建能够抵御复杂攻击的弹性AI系统提供了重要见解。

> As Large Language Models (LLMs) increasingly become key components in various AI applications, understanding their security vulnerabilities and the effectiveness of defense mechanisms is crucial. This survey examines the security challenges of LLMs, focusing on two main areas: Prompt Hacking and Adversarial Attacks, each with specific types of threats. Under Prompt Hacking, we explore Prompt Injection and Jailbreaking Attacks, discussing how they work, their potential impacts, and ways to mitigate them. Similarly, we analyze Adversarial Attacks, breaking them down into Data Poisoning Attacks and Backdoor Attacks. This structured examination helps us understand the relationships between these vulnerabilities and the defense strategies that can be implemented. The survey highlights these security challenges and discusses robust defensive frameworks to protect LLMs against these threats. By detailing these security issues, the survey contributes to the broader discussion on creating resilient AI systems that can resist sophisticated attacks.

![大型语言模型漏洞与防护探索：一份综述](../../../paper_images/2406.00240/digram.png)

![大型语言模型漏洞与防护探索：一份综述](../../../paper_images/2406.00240/jailbreak.png)

[Arxiv](https://arxiv.org/abs/2406.00240)