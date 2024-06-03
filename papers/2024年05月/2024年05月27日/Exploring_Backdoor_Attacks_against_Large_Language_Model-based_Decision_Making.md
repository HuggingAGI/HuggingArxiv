# 揭秘大型语言模型决策中的后门攻击之谜

发布时间：2024年05月27日

`Agent

这篇论文主要探讨了大型语言模型（LLMs）在特定应用微调后在决策任务中的应用，以及如何通过后门攻击框架（BALD）来攻击这些系统。论文详细介绍了三种攻击策略及相应的后门优化技术，这些策略针对LLM决策流程的不同环节，包括词注入、场景操纵和知识注入。这些内容涉及到如何操纵和利用LLMs进行决策，因此更符合Agent分类，即关注于模型作为决策代理的应用和安全性问题。` `人工智能`

> Exploring Backdoor Attacks against Large Language Model-based Decision Making

# 摘要

> 大型语言模型（LLMs）在特定应用微调后，展现出在决策任务中的显著潜力，得益于其从海量数据中习得的常识与推理能力。然而，微调阶段却让这些系统暴露于严重的安全和风险之中。本研究首次提出针对LLM决策系统的全面后门攻击框架（BALD），深入探讨了微调过程中如何通过多渠道引入攻击。我们设计了三种攻击策略及相应的后门优化技术，分别针对LLM决策流程的不同环节：词注入、场景操纵和知识注入。词注入将触发词巧妙植入查询提示；场景操纵则在现实环境中构建高级后门语义场景以触发攻击；知识注入则针对基于RAG的LLM系统，策略性地在受污染知识中植入词触发器，同时保持信息的事实准确性以增强隐蔽性。通过使用GPT-3.5、LLaMA2、PaLM2等模型及HighwayEnv、nuScenes数据集进行广泛实验，我们验证了所提后门触发器和机制的有效性与隐蔽性。最后，我们深入分析了所提方法的优劣，揭示了LLMs在决策任务中的潜在漏洞，并探讨了可能的防御措施，以确保LLM决策系统的安全。

> Large Language Models (LLMs) have shown significant promise in decision-making tasks when fine-tuned on specific applications, leveraging their inherent common sense and reasoning abilities learned from vast amounts of data. However, these systems are exposed to substantial safety and security risks during the fine-tuning phase. In this work, we propose the first comprehensive framework for Backdoor Attacks against LLM-enabled Decision-making systems (BALD), systematically exploring how such attacks can be introduced during the fine-tuning phase across various channels. Specifically, we propose three attack mechanisms and corresponding backdoor optimization methods to attack different components in the LLM-based decision-making pipeline: word injection, scenario manipulation, and knowledge injection. Word injection embeds trigger words directly into the query prompt. Scenario manipulation occurs in the physical environment, where a high-level backdoor semantic scenario triggers the attack. Knowledge injection conducts backdoor attacks on retrieval augmented generation (RAG)-based LLM systems, strategically injecting word triggers into poisoned knowledge while ensuring the information remains factually accurate for stealthiness. We conduct extensive experiments with three popular LLMs (GPT-3.5, LLaMA2, PaLM2), using two datasets (HighwayEnv, nuScenes), and demonstrate the effectiveness and stealthiness of our backdoor triggers and mechanisms. Finally, we critically assess the strengths and weaknesses of our proposed approaches, highlight the inherent vulnerabilities of LLMs in decision-making tasks, and evaluate potential defenses to safeguard LLM-based decision making systems.

[Arxiv](https://arxiv.org/abs/2405.20774)