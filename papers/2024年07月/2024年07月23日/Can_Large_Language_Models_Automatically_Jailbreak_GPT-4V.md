# 大型语言模型是否能自动解除 GPT-4V 的限制？

发布时间：2024年07月23日

`LLM应用` `网络安全` `人工智能`

> Can Large Language Models Automatically Jailbreak GPT-4V?

# 摘要

> GPT-4V凭借其非凡的多模态信息处理能力备受关注，但其人脸识别功能也带来了隐私泄露的新风险。尽管有RLHF和预处理过滤器等安全措施，漏洞仍可能被利用。我们研究中提出的AutoJailbreak技术，通过提示优化自动越狱，利用LLM进行红队测试优化提示，并采用渐进式上下文学习提升效率。我们还设计了结合早期停止的搜索方法，以减少优化成本。实验显示，AutoJailbreak的攻击成功率高达95.3%，远超传统方法。此研究强调了强化GPT-4V安全性的紧迫性，并警示LLM可能被用于破坏其完整性。

> GPT-4V has attracted considerable attention due to its extraordinary capacity for integrating and processing multimodal information. At the same time, its ability of face recognition raises new safety concerns of privacy leakage. Despite researchers' efforts in safety alignment through RLHF or preprocessing filters, vulnerabilities might still be exploited. In our study, we introduce AutoJailbreak, an innovative automatic jailbreak technique inspired by prompt optimization. We leverage Large Language Models (LLMs) for red-teaming to refine the jailbreak prompt and employ weak-to-strong in-context learning prompts to boost efficiency. Furthermore, we present an effective search method that incorporates early stopping to minimize optimization time and token expenditure. Our experiments demonstrate that AutoJailbreak significantly surpasses conventional methods, achieving an Attack Success Rate (ASR) exceeding 95.3\%. This research sheds light on strengthening GPT-4V security, underscoring the potential for LLMs to be exploited in compromising GPT-4V integrity.

![大型语言模型是否能自动解除 GPT-4V 的限制？](../../../paper_images/2407.16686/x1.png)

![大型语言模型是否能自动解除 GPT-4V 的限制？](../../../paper_images/2407.16686/x2.png)

![大型语言模型是否能自动解除 GPT-4V 的限制？](../../../paper_images/2407.16686/x3.png)

![大型语言模型是否能自动解除 GPT-4V 的限制？](../../../paper_images/2407.16686/x4.png)

![大型语言模型是否能自动解除 GPT-4V 的限制？](../../../paper_images/2407.16686/x5.png)

![大型语言模型是否能自动解除 GPT-4V 的限制？](../../../paper_images/2407.16686/x6.png)

![大型语言模型是否能自动解除 GPT-4V 的限制？](../../../paper_images/2407.16686/x7.png)

[Arxiv](https://arxiv.org/abs/2407.16686)