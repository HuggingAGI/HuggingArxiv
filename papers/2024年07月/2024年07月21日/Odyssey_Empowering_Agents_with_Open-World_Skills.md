# Odyssey：助力代理掌握开放世界技能

发布时间：2024年07月21日

`Agent` `人工智能`

> Odyssey: Empowering Agents with Open-World Skills

# 摘要

> 近期研究致力于为《我的世界》这类开放世界环境打造全能代理。尽管成果喜人，但现有研究多聚焦于基础编程任务，如遵循游戏科技树收集资源和制作工具，并将获取钻石视为终极目标。这种局限性源于代理动作范围的狭隘定义，迫使它们从零开始学习长期策略，从而在开放世界中探索多样游戏机会变得困难重重。为此，我们推出了ODYSSEY框架，赋予基于大型语言模型的代理开放世界技能，助其畅游《我的世界》的广阔天地。ODYSSEY框架由三大核心组成：（1）配备开放世界技能库的交互代理，内含40种基础技能与183种复合技能。（2）基于《我的世界》维基39万+指令条目的大型问答数据集微调的LLaMA-3模型。（3）涵盖数千长期规划、数十动态即时规划及一项自主探索任务的全新开放世界基准。实验证明，ODYSSEY框架能有效评估代理的规划与探索能力。我们公开了所有数据集、模型权重及代码，旨在推动未来更先进的自主代理研究。

> Recent studies have delved into constructing generalist agents for open-world embodied environments like Minecraft. Despite the encouraging results, existing efforts mainly focus on solving basic programmatic tasks, e.g., material collection and tool-crafting following the Minecraft tech-tree, treating the ObtainDiamond task as the ultimate goal. This limitation stems from the narrowly defined set of actions available to agents, requiring them to learn effective long-horizon strategies from scratch. Consequently, discovering diverse gameplay opportunities in the open world becomes challenging. In this work, we introduce ODYSSEY, a new framework that empowers Large Language Model (LLM)-based agents with open-world skills to explore the vast Minecraft world. ODYSSEY comprises three key parts: (1) An interactive agent with an open-world skill library that consists of 40 primitive skills and 183 compositional skills. (2) A fine-tuned LLaMA-3 model trained on a large question-answering dataset with 390k+ instruction entries derived from the Minecraft Wiki. (3) A new open-world benchmark includes thousands of long-term planning tasks, tens of dynamic-immediate planning tasks, and one autonomous exploration task. Extensive experiments demonstrate that the proposed ODYSSEY framework can effectively evaluate the planning and exploration capabilities of agents. All datasets, model weights, and code are publicly available to motivate future research on more advanced autonomous agent solutions.

[Arxiv](https://arxiv.org/abs/2407.15325)