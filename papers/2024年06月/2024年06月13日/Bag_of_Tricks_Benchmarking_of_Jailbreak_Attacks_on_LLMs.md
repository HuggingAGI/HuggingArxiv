# 技巧大全：大型语言模型越狱攻击的基准评测

发布时间：2024年06月13日

`LLM应用

这篇论文主要关注大型语言模型（LLMs）在面对越狱攻击时的安全问题，并探讨了防御策略。它通过实验评估了不同攻击场景对LLMs的影响，并提出了一个标准化评估框架。虽然涉及到了模型的安全性和防御技术，但其核心在于应用层面的安全评估和防御措施，而非理论研究或Agent的设计与实现，也不是关于检索增强生成（RAG）的具体应用。因此，最合适的分类是LLM应用。` `网络安全` `人工智能安全`

> Bag of Tricks: Benchmarking of Jailbreak Attacks on LLMs

# 摘要

> 大型语言模型（LLMs）虽在零-shot任务中表现出色，却易受越狱攻击，可能产生有害结果。近期研究将此类攻击细分为令牌级和提示级，但多聚焦于模型漏洞，忽视了防御策略。为此，我们分析了多种攻击场景对LLM的影响，并设定了越狱攻击的基准，推动标准化评估框架的发展。我们详细考察了LLMs上越狱攻击的八大关键因素，并针对六种防御技术，在两大常用数据集上进行了七项典型攻击，进行了约320次实验，耗时约50,000 GPU小时。实验表明，对防御增强型LLMs进行越狱攻击的标准化评估至关重要。相关代码已公开于https://github.com/usail-hkust/Bag_of_Tricks_for_LLM_Jailbreaking。

> Although Large Language Models (LLMs) have demonstrated significant capabilities in executing complex tasks in a zero-shot manner, they are susceptible to jailbreak attacks and can be manipulated to produce harmful outputs. Recently, a growing body of research has categorized jailbreak attacks into token-level and prompt-level attacks. However, previous work primarily overlooks the diverse key factors of jailbreak attacks, with most studies concentrating on LLM vulnerabilities and lacking exploration of defense-enhanced LLMs. To address these issues, we evaluate the impact of various attack settings on LLM performance and provide a baseline benchmark for jailbreak attacks, encouraging the adoption of a standardized evaluation framework. Specifically, we evaluate the eight key factors of implementing jailbreak attacks on LLMs from both target-level and attack-level perspectives. We further conduct seven representative jailbreak attacks on six defense methods across two widely used datasets, encompassing approximately 320 experiments with about 50,000 GPU hours on A800-80G. Our experimental results highlight the need for standardized benchmarking to evaluate these attacks on defense-enhanced LLMs. Our code is available at https://github.com/usail-hkust/Bag_of_Tricks_for_LLM_Jailbreaking.

[Arxiv](https://arxiv.org/abs/2406.09324)