# DART：深度对抗技术助力 LLM 安全，实现自动红队测试

发布时间：2024年07月04日

`LLM应用` `网络安全` `人工智能`

> DART: Deep Adversarial Automated Red Teaming for LLM Safety

# 摘要

> 手动红队虽常用于发现大型语言模型（LLM）的漏洞，但成本高昂且难以扩展。自动化红队则通过红色LLM自动生成对抗提示，为安全漏洞检测提供了可扩展的解决方案。然而，构建强大的自动化红色LLM面临挑战，因为目标LLM的安全漏洞随其发展而动态变化。为此，我们设计了深度对抗自动化红队（DART）框架，使红色LLM与目标LLM在迭代中深度动态交互。每次迭代中，红色LLM不仅依据目标LLM的反馈，还通过监控多轮攻击的全球多样性来调整攻击策略，以最大化成功攻击的数量。同时，目标LLM通过基于主动学习的数据选择机制增强安全性，以应对动态变化的安全漏洞。实验显示，DART大幅降低了目标LLM的安全风险。在Anthropic Harmless数据集的人类评估中，DART相比指令调优的目标LLM，违规风险降低了53.4%。我们即将发布DART的数据集和代码。

> Manual Red teaming is a commonly-used method to identify vulnerabilities in large language models (LLMs), which, is costly and unscalable. In contrast, automated red teaming uses a Red LLM to automatically generate adversarial prompts to the Target LLM, offering a scalable way for safety vulnerability detection. However, the difficulty of building a powerful automated Red LLM lies in the fact that the safety vulnerabilities of the Target LLM are dynamically changing with the evolution of the Target LLM. To mitigate this issue, we propose a Deep Adversarial Automated Red Teaming (DART) framework in which the Red LLM and Target LLM are deeply and dynamically interacting with each other in an iterative manner. In each iteration, in order to generate successful attacks as many as possible, the Red LLM not only takes into account the responses from the Target LLM, but also adversarially adjust its attacking directions by monitoring the global diversity of generated attacks across multiple iterations. Simultaneously, to explore dynamically changing safety vulnerabilities of the Target LLM, we allow the Target LLM to enhance its safety via an active learning based data selection mechanism. Experimential results demonstrate that DART significantly reduces the safety risk of the target LLM. For human evaluation on Anthropic Harmless dataset, compared to the instruction-tuning target LLM, DART eliminates the violation risks by 53.4\%. We will release the datasets and codes of DART soon.

[Arxiv](https://arxiv.org/abs/2407.03876)