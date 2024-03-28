# 在运用 LLMs 探索 NetHack 游戏中，我们发掘其作为零样本代理的潜力与局限。这项研究聚焦于 LLMS 在未经专门训练情况下，即“零样本”状态下应对复杂游戏环境的能力及其限制。

发布时间：2024年03月01日

`Agent`

> Playing NetHack with LLMs: Potential & Limitations as Zero-Shot Agents

# 摘要

> LLMs作为零样本游戏策略家，在Minecraft等游戏中取得了显著成就，但此类智能体在面对如NetHack这类多元物品、复杂交互且充满变数的环境时，其表现仍有待提升。为此，我们创新研发出首个适用于NetHack这一硬核roguelike游戏的LLM驱动零样本智能体——NetPlay。NetPlay采用了一种针对动态机器人环境优化并适应NetHack特性的架构，通过提示LLM选用预设技能及记录过往交互，强化决策过程。同时，NetPlay能敏锐察觉关键游戏事件并适时打断执行中的技能，以应对突发状况。尽管NetPlay在掌握NetHack机制方面表现出色，但对于模糊任务说明和缺乏直接反馈的问题则略显吃力。研究表明，当提供详尽的上下文信息时，NetPlay的表现最为优秀，揭示了为NetHack这类复杂游戏动态供给上下文信息的重要性。

> Large Language Models (LLMs) have shown great success as high-level planners for zero-shot game-playing agents. However, these agents are primarily evaluated on Minecraft, where long-term planning is relatively straightforward. In contrast, agents tested in dynamic robot environments face limitations due to simplistic environments with only a few objects and interactions. To fill this gap in the literature, we present NetPlay, the first LLM-powered zero-shot agent for the challenging roguelike NetHack. NetHack is a particularly challenging environment due to its diverse set of items and monsters, complex interactions, and many ways to die.
  NetPlay uses an architecture designed for dynamic robot environments, modified for NetHack. Like previous approaches, it prompts the LLM to choose from predefined skills and tracks past interactions to enhance decision-making. Given NetHack's unpredictable nature, NetPlay detects important game events to interrupt running skills, enabling it to react to unforeseen circumstances. While NetPlay demonstrates considerable flexibility and proficiency in interacting with NetHack's mechanics, it struggles with ambiguous task descriptions and a lack of explicit feedback. Our findings demonstrate that NetPlay performs best with detailed context information, indicating the necessity for dynamic methods in supplying context information for complex games such as NetHack.

[Arxiv](https://arxiv.org/abs/2403.00690)