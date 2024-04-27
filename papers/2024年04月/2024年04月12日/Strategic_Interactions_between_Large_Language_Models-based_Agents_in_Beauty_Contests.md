# 在选美比赛中，基于大型语言模型的智能体之间的策略性互动

发布时间：2024年04月12日

`分类：Agent

这篇论文主要研究了基于大型语言模型（LLMs）的代理在博弈论视角下的行为模式，特别是在经典选美比赛游戏中的代理之间的战略互动。论文探讨了不同类型和智能水平的代理在竞争性游戏中的表现，以及它们在多次重复情境中的策略趋同。这些研究结果有助于理解算法间的策略互动，因此将这篇论文归类为Agent更为合适。` `博弈论` `人工智能`

> Strategic Interactions between Large Language Models-based Agents in Beauty Contests

# 摘要

> 随着大型语言模型（LLMs）的广泛应用，我们有机会通过模拟来深入探究博弈论视角下的人类行为模式。本文聚焦于多样化的LLM类型，填补了关于竞争性游戏研究的空白，通过经典选美比赛游戏，分析了基于LLM的多种代理之间的战略互动。与人类参与者的实验相比较，这些基于LLM的代理在战略层面上得到了类似的评估，表现出从0级到1级的不同程度的推理能力，并在多次重复的情境中趋于行动一致。研究还发现，固定策略对手比例的提高有助于LLM代理的策略趋同，而不同战略水平的代理混合环境则能加速所有代理的策略统一。更为智能的代理可能会获得更高的平均收益，但这通常以牺牲那些智能较低的代理为代价。这些发现不仅揭示了特定情境下模拟代理的行为结果，还为理解算法间的策略互动提供了重要的启示。

> The growing adoption of large language models (LLMs) presents substantial potential for deeper understanding of human behaviours within game theory frameworks through simulations. Leveraging on the diverse pool of LLM types and addressing the gap in research on competitive games, this paper examines the strategic interactions among multiple types of LLM-based agents in a classical game of beauty contest. Drawing parallels to experiments involving human subjects, LLM-based agents are assessed similarly in terms of strategic levels. They demonstrate varying depth of reasoning that falls within a range of level-0 and 1, and show convergence in actions in repeated settings. Furthermore, I also explore how variations in group composition of agent types influence strategic behaviours, where I found higher proportion of fixed-strategy opponents enhances convergence for LLM-based agents, and having a mixed environment with agents of differing relative strategic levels accelerates convergence for all agents. There could also be higher average payoffs for the more intelligent agents, albeit at the expense of the less intelligent agents. These results not only provide insights into outcomes for simulated agents under specified scenarios, it also offer valuable implications for understanding strategic interactions between algorithms.

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/histogram_of_choices_multillm.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/same_upperbound_c.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/mean_strategic_level_reference_average_c.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/fig2_mixed_one_shot_c.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/mean_payoffs_c.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/period1_average_n_c.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/average_normalized_chosen_number.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/freq_choices_6periods.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/freq_n_6periods.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/average_n_across_sessions_n.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/average_payoffs_across_periods.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/fixed_strategy_choices.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/fixed_strategy_choices_weak.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/fixed_strategy_convergence_rates.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/fixed_strategy_convergence_rates_weak.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/fixed_strategy_n_values.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/fixed_strategy_n_values_weak.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/payoffs_set_up1_static.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/payoffs_set_up2_static.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/payoffs_set_up3_static.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/payoffs_set_up1_static_weak.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/payoffs_set_up2_static_weak.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/payoffs_set_up3_static_weak.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/setup1_mixedllm_choices.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/setup2_mixedllm_choices.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/setup3_mixedllm_choices.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/setup4_mixedllm_choices.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/setup5_mixedllm_choices.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/convergence_mixedllm.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/n_values_mixedllm1.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/n_values_mixedllm2.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/payoffs_mixedllm_setup1.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/payoffs_mixedllm_setup2.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/payoffs_mixedllm_setup3.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/payoffs_mixedllm_setup4.png)

![在选美比赛中，基于大型语言模型的智能体之间的策略性互动](../../../paper_images/2404.08492/payoffs_mixedllm_setup5.png)

[Arxiv](https://arxiv.org/abs/2404.08492)