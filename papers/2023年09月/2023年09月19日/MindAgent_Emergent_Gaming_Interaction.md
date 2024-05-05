# MindAgent：探索游戏互动的新境界

发布时间：2023年09月19日

`Agent` `人工智能`

> MindAgent: Emergent Gaming Interaction

# 摘要

> 大型语言模型（LLMs）展现出在多智能体系统中进行复杂调度的能力，能够协调智能体完成需要密切合作的复杂任务。尽管众多游戏框架相继问世，但社区在构建包含LLM和人类NPC协作的通用多智能体协作基础设施方面，仍缺乏足够的基准。本研究提出了一个创新的基础设施——MindAgent，旨在评估游戏互动中的规划和协调能力。该基础设施特别利用现有游戏框架，实现对多智能体系统协调者的理解，与人类玩家通过未经微调的正确指令进行协作，以及在少量提示和反馈的基础上建立上下文学习。我们还引入了CUISINEWORLD，这是一个新的游戏场景及相关基准，旨在提高多智能体协作效率，并同时监督多个代理的游戏表现。通过新的自动度量标准CoS，我们进行了全面的评估，以计算协作效率。最终，我们的基础设施可以部署到现实世界的游戏场景中，如CUISINEWORLD的定制虚拟现实版本，以及现有的更广泛的Minecraft游戏领域。我们期望，对于LLMs的研究成果以及新的通用调度和协调基础设施，能够为如何通过学习大型语言语料库来掌握这些技能提供洞见。

> Large Language Models (LLMs) have the capacity of performing complex scheduling in a multi-agent system and can coordinate these agents into completing sophisticated tasks that require extensive collaboration. However, despite the introduction of numerous gaming frameworks, the community has insufficient benchmarks towards building general multi-agents collaboration infrastructure that encompass both LLM and human-NPCs collaborations. In this work, we propose a novel infrastructure - MindAgent - to evaluate planning and coordination emergent capabilities for gaming interaction. In particular, our infrastructure leverages existing gaming framework, to i) require understanding of the coordinator for a multi-agent system, ii) collaborate with human players via un-finetuned proper instructions, and iii) establish an in-context learning on few-shot prompt with feedback. Furthermore, we introduce CUISINEWORLD, a new gaming scenario and related benchmark that dispatch a multi-agent collaboration efficiency and supervise multiple agents playing the game simultaneously. We conduct comprehensive evaluations with new auto-metric CoS for calculating the collaboration efficiency. Finally, our infrastructure can be deployed into real-world gaming scenarios in a customized VR version of CUISINEWORLD and adapted in existing broader Minecraft gaming domain. We hope our findings on LLMs and the new infrastructure for general-purpose scheduling and coordination can help shed light on how such skills can be obtained by learning from large language corpora.

[Arxiv](https://arxiv.org/abs/2309.09971)