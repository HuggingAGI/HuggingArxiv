# GOAT：自动红队测试中的生成性攻击代理

发布时间：2024年10月02日

`Agent` `网络安全` `人工智能`

> Automated Red Teaming with GOAT: the Generative Offensive Agent Tester

# 摘要

> 红队测试旨在揭示大型语言模型 (LLM) 如何生成违反安全规范的内容。然而，现有自动化方法多不符合人类与 AI 的实际交互方式。普通用户通常不具备对抗机器学习的高级知识，也不会耗时设计高效对抗提示，而是倾向于使用在线分享的常见技巧，并利用 LLM 的多轮对话特性。手动测试虽能弥补这一不足，但效率低且成本高。为此，我们推出了生成性攻击代理测试器 (GOAT)，一个自动化红队系统，模拟普通语言对抗对话，结合多种对抗提示技术，精准识别 LLM 漏洞。通过 7 种红队攻击实例化 GOAT，我们鼓励模型通过推理选择方法、响应和下一步骤。该方法高效可扩展，使人类测试者能专注新风险领域，而自动化负责已知风险的大规模对抗压力测试。GOAT 在 JailbreakBench 数据集上表现出色，Llama 3.1 的 ASR@10 达 97%，GPT-4 为 88%，有效识别了最先进 LLM 的漏洞。

> Red teaming assesses how large language models (LLMs) can produce content that violates norms, policies, and rules set during their safety training. However, most existing automated methods in the literature are not representative of the way humans tend to interact with AI models. Common users of AI models may not have advanced knowledge of adversarial machine learning methods or access to model internals, and they do not spend a lot of time crafting a single highly effective adversarial prompt. Instead, they are likely to make use of techniques commonly shared online and exploit the multiturn conversational nature of LLMs. While manual testing addresses this gap, it is an inefficient and often expensive process. To address these limitations, we introduce the Generative Offensive Agent Tester (GOAT), an automated agentic red teaming system that simulates plain language adversarial conversations while leveraging multiple adversarial prompting techniques to identify vulnerabilities in LLMs. We instantiate GOAT with 7 red teaming attacks by prompting a general-purpose model in a way that encourages reasoning through the choices of methods available, the current target model's response, and the next steps. Our approach is designed to be extensible and efficient, allowing human testers to focus on exploring new areas of risk while automation covers the scaled adversarial stress-testing of known risk territory. We present the design and evaluation of GOAT, demonstrating its effectiveness in identifying vulnerabilities in state-of-the-art LLMs, with an ASR@10 of 97% against Llama 3.1 and 88% against GPT-4 on the JailbreakBench dataset.

[Arxiv](https://arxiv.org/abs/2410.01606)