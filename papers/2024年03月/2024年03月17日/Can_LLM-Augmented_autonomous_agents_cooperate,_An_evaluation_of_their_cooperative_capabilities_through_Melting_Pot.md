# 在 Melting Pot 环境中检验 LLMA（大型语言模型增强）自主代理能否有效合作？本研究通过一系列实验评估其合作能力。注：这里我将 "Can LLM-Augmented autonomous agents cooperate?" 翻译为“LLM 增强型自主代理能否有效合作？”以更符合中文口语表达，并将 "An evaluation of their cooperative capabilities through Melting Pot" 翻译为“本研究通过一系列 Melting Pot 实验评估其合作能力”，以更贴合中文阅读习惯，同时保持原句主旨。

发布时间：2024年03月17日

`Agent` `多智能体系统`

> Can LLM-Augmented autonomous agents cooperate?, An evaluation of their cooperative capabilities through Melting Pot

> 随着AI领域的迅速发展，大型语言模型在提升多智能体系统性能方面展现出巨大潜力。本研究借助Meltin Pot环境及其代表性模型如GPT4和GPT3.5，探究了搭载大型语言模型的自主智能体（LAAs）的合作效能。初期实验揭示，尽管LAAs具备一定的合作倾向，但在具体环境下高效协作尚存困难，凸显了构建更强大稳定架构的必要性。本文的核心贡献在于设计了一套针对LLMs的Melting Pot游戏场景适配层，搭建了一个支持LLM驱动的智能体开发的可复用架构，其中整合了短长期记忆和多种认知模块，并通过关联“Commons Harvest”游戏的一系列评价指标对合作能力进行了深入评估。文章结尾部分探讨了当前架构体系的局限，并展望了一组有望大幅增进LAAs间合作的新模块潜力。

> As the field of AI continues to evolve, a significant dimension of this progression is the development of Large Language Models and their potential to enhance multi-agent artificial intelligence systems. This paper explores the cooperative capabilities of Large Language Model-augmented Autonomous Agents (LAAs) using the well-known Meltin Pot environments along with reference models such as GPT4 and GPT3.5. Preliminary results suggest that while these agents demonstrate a propensity for cooperation, they still struggle with effective collaboration in given environments, emphasizing the need for more robust architectures. The study's contributions include an abstraction layer to adapt Melting Pot game scenarios for LLMs, the implementation of a reusable architecture for LLM-mediated agent development - which includes short and long-term memories and different cognitive modules, and the evaluation of cooperation capabilities using a set of metrics tied to the Melting Pot's "Commons Harvest" game. The paper closes, by discussing the limitations of the current architectural framework and the potential of a new set of modules that fosters better cooperation among LAAs.

![在 Melting Pot 环境中检验 LLMA（大型语言模型增强）自主代理能否有效合作？本研究通过一系列实验评估其合作能力。注：这里我将 "Can LLM-Augmented autonomous agents cooperate?" 翻译为“LLM 增强型自主代理能否有效合作？”以更符合中文口语表达，并将 "An evaluation of their cooperative capabilities through Melting Pot" 翻译为“本研究通过一系列 Melting Pot 实验评估其合作能力”，以更贴合中文阅读习惯，同时保持原句主旨。](../../../paper_images/2403.11381/environment.png)

![在 Melting Pot 环境中检验 LLMA（大型语言模型增强）自主代理能否有效合作？本研究通过一系列实验评估其合作能力。注：这里我将 "Can LLM-Augmented autonomous agents cooperate?" 翻译为“LLM 增强型自主代理能否有效合作？”以更符合中文口语表达，并将 "An evaluation of their cooperative capabilities through Melting Pot" 翻译为“本研究通过一系列 Melting Pot 实验评估其合作能力”，以更贴合中文阅读习惯，同时保持原句主旨。](../../../paper_images/2403.11381/Decision_flow_diagram.jpg)

![在 Melting Pot 环境中检验 LLMA（大型语言模型增强）自主代理能否有效合作？本研究通过一系列实验评估其合作能力。注：这里我将 "Can LLM-Augmented autonomous agents cooperate?" 翻译为“LLM 增强型自主代理能否有效合作？”以更符合中文口语表达，并将 "An evaluation of their cooperative capabilities through Melting Pot" 翻译为“本研究通过一系列 Melting Pot 实验评估其合作能力”，以更贴合中文阅读习惯，同时保持原句主旨。](../../../paper_images/2403.11381/set1_percapita_reward.png)

![在 Melting Pot 环境中检验 LLMA（大型语言模型增强）自主代理能否有效合作？本研究通过一系列实验评估其合作能力。注：这里我将 "Can LLM-Augmented autonomous agents cooperate?" 翻译为“LLM 增强型自主代理能否有效合作？”以更符合中文口语表达，并将 "An evaluation of their cooperative capabilities through Melting Pot" 翻译为“本研究通过一系列 Melting Pot 实验评估其合作能力”，以更贴合中文阅读习惯，同时保持原句主旨。](../../../paper_images/2403.11381/set1_attacks.png)

![在 Melting Pot 环境中检验 LLMA（大型语言模型增强）自主代理能否有效合作？本研究通过一系列实验评估其合作能力。注：这里我将 "Can LLM-Augmented autonomous agents cooperate?" 翻译为“LLM 增强型自主代理能否有效合作？”以更符合中文口语表达，并将 "An evaluation of their cooperative capabilities through Melting Pot" 翻译为“本研究通过一系列 Melting Pot 实验评估其合作能力”，以更贴合中文阅读习惯，同时保持原句主旨。](../../../paper_images/2403.11381/set1_moves_towards_last_apple.png)

![在 Melting Pot 环境中检验 LLMA（大型语言模型增强）自主代理能否有效合作？本研究通过一系列实验评估其合作能力。注：这里我将 "Can LLM-Augmented autonomous agents cooperate?" 翻译为“LLM 增强型自主代理能否有效合作？”以更符合中文口语表达，并将 "An evaluation of their cooperative capabilities through Melting Pot" 翻译为“本研究通过一系列 Melting Pot 实验评估其合作能力”，以更贴合中文阅读习惯，同时保持原句主旨。](../../../paper_images/2403.11381/set2_combined_one_tree.png)

![在 Melting Pot 环境中检验 LLMA（大型语言模型增强）自主代理能否有效合作？本研究通过一系列实验评估其合作能力。注：这里我将 "Can LLM-Augmented autonomous agents cooperate?" 翻译为“LLM 增强型自主代理能否有效合作？”以更符合中文口语表达，并将 "An evaluation of their cooperative capabilities through Melting Pot" 翻译为“本研究通过一系列 Melting Pot 实验评估其合作能力”，以更贴合中文阅读习惯，同时保持原句主旨。](../../../paper_images/2403.11381/set2_rwd_agents_vs_bots.png)

![在 Melting Pot 环境中检验 LLMA（大型语言模型增强）自主代理能否有效合作？本研究通过一系列实验评估其合作能力。注：这里我将 "Can LLM-Augmented autonomous agents cooperate?" 翻译为“LLM 增强型自主代理能否有效合作？”以更符合中文口语表达，并将 "An evaluation of their cooperative capabilities through Melting Pot" 翻译为“本研究通过一系列 Melting Pot 实验评估其合作能力”，以更贴合中文阅读习惯，同时保持原句主旨。](../../../paper_images/2403.11381/set2_attacks_agents_vs_bots.png)

![在 Melting Pot 环境中检验 LLMA（大型语言模型增强）自主代理能否有效合作？本研究通过一系列实验评估其合作能力。注：这里我将 "Can LLM-Augmented autonomous agents cooperate?" 翻译为“LLM 增强型自主代理能否有效合作？”以更符合中文口语表达，并将 "An evaluation of their cooperative capabilities through Melting Pot" 翻译为“本研究通过一系列 Melting Pot 实验评估其合作能力”，以更贴合中文阅读习惯，同时保持原句主旨。](../../../paper_images/2403.11381/set2_took_last_apple_agents_vs_bots.png)

![在 Melting Pot 环境中检验 LLMA（大型语言模型增强）自主代理能否有效合作？本研究通过一系列实验评估其合作能力。注：这里我将 "Can LLM-Augmented autonomous agents cooperate?" 翻译为“LLM 增强型自主代理能否有效合作？”以更符合中文口语表达，并将 "An evaluation of their cooperative capabilities through Melting Pot" 翻译为“本研究通过一系列 Melting Pot 实验评估其合作能力”，以更贴合中文阅读习惯，同时保持原句主旨。](../../../paper_images/2403.11381/set2_attacks_graph___pedro_is_selfish.png)

![在 Melting Pot 环境中检验 LLMA（大型语言模型增强）自主代理能否有效合作？本研究通过一系列实验评估其合作能力。注：这里我将 "Can LLM-Augmented autonomous agents cooperate?" 翻译为“LLM 增强型自主代理能否有效合作？”以更符合中文口语表达，并将 "An evaluation of their cooperative capabilities through Melting Pot" 翻译为“本研究通过一系列 Melting Pot 实验评估其合作能力”，以更贴合中文阅读习惯，同时保持原句主旨。](../../../paper_images/2403.11381/Cooperative_architecture.png)

[Arxiv](https://arxiv.org/abs/2403.11381)