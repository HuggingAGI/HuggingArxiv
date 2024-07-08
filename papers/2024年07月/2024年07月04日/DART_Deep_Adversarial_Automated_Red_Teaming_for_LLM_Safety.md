# DART：深度对抗技术助力 LLM 安全，实现自动化红队测试

发布时间：2024年07月04日

`LLM应用` `网络安全` `人工智能`

> DART: Deep Adversarial Automated Red Teaming for LLM Safety

# 摘要

> 手动红队测试虽常用于发现大型语言模型（LLM）的漏洞，但成本高昂且难以扩展。为此，我们转向自动化红队测试，利用红色LLM自动生成对抗性提示，为安全漏洞检测提供了一种可扩展的解决方案。然而，构建强大的自动化红色LLM面临挑战，因为目标LLM的安全漏洞随其演化而动态变化。为此，我们设计了深度对抗自动化红队测试（DART）框架，通过红色LLM与目标LLM的深度动态交互，迭代生成攻击并调整策略，同时通过主动学习机制增强目标LLM的安全性。实验显示，DART大幅降低了目标LLM的安全风险，在Anthropic Harmless数据集的人类评估中，违规风险降低了53.4%。我们即将发布DART的数据集和代码。

> Manual Red teaming is a commonly-used method to identify vulnerabilities in large language models (LLMs), which, is costly and unscalable. In contrast, automated red teaming uses a Red LLM to automatically generate adversarial prompts to the Target LLM, offering a scalable way for safety vulnerability detection. However, the difficulty of building a powerful automated Red LLM lies in the fact that the safety vulnerabilities of the Target LLM are dynamically changing with the evolution of the Target LLM. To mitigate this issue, we propose a Deep Adversarial Automated Red Teaming (DART) framework in which the Red LLM and Target LLM are deeply and dynamically interacting with each other in an iterative manner. In each iteration, in order to generate successful attacks as many as possible, the Red LLM not only takes into account the responses from the Target LLM, but also adversarially adjust its attacking directions by monitoring the global diversity of generated attacks across multiple iterations. Simultaneously, to explore dynamically changing safety vulnerabilities of the Target LLM, we allow the Target LLM to enhance its safety via an active learning based data selection mechanism. Experimential results demonstrate that DART significantly reduces the safety risk of the target LLM. For human evaluation on Anthropic Harmless dataset, compared to the instruction-tuning target LLM, DART eliminates the violation risks by 53.4\%. We will release the datasets and codes of DART soon.

[Arxiv](https://arxiv.org/abs/2407.03876)