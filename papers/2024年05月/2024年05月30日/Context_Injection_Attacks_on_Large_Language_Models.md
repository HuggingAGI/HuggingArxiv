# 大型语言模型面临上下文注入攻击的挑战

发布时间：2024年05月30日

`Agent

理由：这篇论文主要探讨了基于大型语言模型（LLMs）的聊天系统在交互环境中可能受到的攻击，特别是通过伪造上下文信息来误导模型。这种研究关注的是模型在实际应用中的行为和安全性，特别是在面对恶意用户时的表现，这更符合Agent类别的定义，即关注模型在动态环境中的行为和响应。虽然涉及到了LLM的应用，但其核心在于模型的行为和对抗性攻击，因此更适合归类为Agent。` `网络安全` `人工智能安全`

> Context Injection Attacks on Large Language Models

# 摘要

> ChatGPT和Llama-2等大型语言模型（LLMs）在实际应用中已广泛流行，其文本生成能力令人瞩目。这些模型原本设计于静态且结构不明的数据输入环境。为了实现时间上的交互，基于LLM的聊天系统需按预定结构整合额外的上下文信息（如聊天历史）。本文揭示了这种整合可能使模型受到不可信来源的误导性上下文影响，无法区分系统与用户输入，从而允许用户注入上下文。我们提出了一套系统的攻击方法，通过伪造上下文诱导模型产生禁止的响应，可能导致非法行为、不当内容或技术滥用。我们的上下文伪造策略，包括接受性诱发和词匿名化，能有效构建误导性上下文，并与攻击者定制的提示模板结合，通过恶意用户消息实现注入。对ChatGPT和Llama-2等真实世界LLM的全面评估显示，这种攻击的成功率高达97%。我们还探讨了可能的防御措施，用于检测此类攻击并开发更安全的模型。我们的研究为在交互和结构化数据场景中部署LLMs所面临的挑战提供了深入的洞察。

> Large Language Models (LLMs) such as ChatGPT and Llama-2 have become prevalent in real-world applications, exhibiting impressive text generation performance. LLMs are fundamentally developed from a scenario where the input data remains static and lacks a clear structure. To behave interactively over time, LLM-based chat systems must integrate additional contextual information (i.e., chat history) into their inputs, following a pre-defined structure. This paper identifies how such integration can expose LLMs to misleading context from untrusted sources and fail to differentiate between system and user inputs, allowing users to inject context. We present a systematic methodology for conducting context injection attacks aimed at eliciting disallowed responses by introducing fabricated context. This could lead to illegal actions, inappropriate content, or technology misuse. Our context fabrication strategies, acceptance elicitation and word anonymization, effectively create misleading contexts that can be structured with attacker-customized prompt templates, achieving injection through malicious user messages. Comprehensive evaluations on real-world LLMs such as ChatGPT and Llama-2 confirm the efficacy of the proposed attack with success rates reaching 97%. We also discuss potential countermeasures that can be adopted for attack detection and developing more secure models. Our findings provide insights into the challenges associated with the real-world deployment of LLMs for interactive and structured data scenarios.

![大型语言模型面临上下文注入攻击的挑战](../../../paper_images/2405.20234/x1.png)

![大型语言模型面临上下文注入攻击的挑战](../../../paper_images/2405.20234/x2.png)

![大型语言模型面临上下文注入攻击的挑战](../../../paper_images/2405.20234/x3.png)

![大型语言模型面临上下文注入攻击的挑战](../../../paper_images/2405.20234/appr-word-sen.png)

![大型语言模型面临上下文注入攻击的挑战](../../../paper_images/2405.20234/x4.png)

![大型语言模型面临上下文注入攻击的挑战](../../../paper_images/2405.20234/x5.png)

![大型语言模型面临上下文注入攻击的挑战](../../../paper_images/2405.20234/x6.png)

![大型语言模型面临上下文注入攻击的挑战](../../../paper_images/2405.20234/appr-repeat-last.png)

![大型语言模型面临上下文注入攻击的挑战](../../../paper_images/2405.20234/x7.png)

![大型语言模型面临上下文注入攻击的挑战](../../../paper_images/2405.20234/x8.png)

![大型语言模型面临上下文注入攻击的挑战](../../../paper_images/2405.20234/x9.png)

![大型语言模型面临上下文注入攻击的挑战](../../../paper_images/2405.20234/x10.png)

[Arxiv](https://arxiv.org/abs/2405.20234)