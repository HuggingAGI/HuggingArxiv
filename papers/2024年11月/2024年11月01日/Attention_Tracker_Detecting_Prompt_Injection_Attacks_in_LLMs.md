# 注意力追踪器：侦测大型语言模型中的提示注入式攻击

发布时间：2024年11月01日

`LLM应用` `语言模型` `网络安全`

> Attention Tracker: Detecting Prompt Injection Attacks in LLMs

# 摘要

> 大型语言模型（LLMs）在诸多领域掀起了变革浪潮，但仍易受提示注入攻击的威胁，恶意输入会驱使模型无视原始指令而执行特定操作。本文中，我们通过剖析 LLMs 内部的注意力模式来探究此类攻击的深层机制。我们引入了分心效应这一概念，即特定的注意力头（称为重要头）会将关注点从原始指令转向注入的指令。基于此发现，我们提出了 Attention Tracker，这是一种无需训练的检测手段，它通过追踪指令上的注意力模式来侦测提示注入攻击，无需额外的 LLM 推理。我们的方法在各类模型、数据集和攻击类型中都能有效泛化，AUROC 较现有方法最高提升 10.0％，在小型 LLMs 上也有出色表现。我们通过大量评估验证了该方法的稳健性，并就如何保护集成 LLM 的系统免受提示注入漏洞侵害提供了见解。

> Large Language Models (LLMs) have revolutionized various domains but remain vulnerable to prompt injection attacks, where malicious inputs manipulate the model into ignoring original instructions and executing designated action. In this paper, we investigate the underlying mechanisms of these attacks by analyzing the attention patterns within LLMs. We introduce the concept of the distraction effect, where specific attention heads, termed important heads, shift focus from the original instruction to the injected instruction. Building on this discovery, we propose Attention Tracker, a training-free detection method that tracks attention patterns on instruction to detect prompt injection attacks without the need for additional LLM inference. Our method generalizes effectively across diverse models, datasets, and attack types, showing an AUROC improvement of up to 10.0% over existing methods, and performs well even on small LLMs. We demonstrate the robustness of our approach through extensive evaluations and provide insights into safeguarding LLM-integrated systems from prompt injection vulnerabilities.

[Arxiv](https://arxiv.org/abs/2411.00348)