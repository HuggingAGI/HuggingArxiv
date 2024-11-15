# ClevrSkills：机器人领域的组合语言与视觉推理

发布时间：2024年11月13日

`Agent` `机器人` `组合推理`

> ClevrSkills: Compositional Language and Visual Reasoning in Robotics

# 摘要

> 机器人任务本质上具有高度的组合性。比如，要完成像清理桌子这类高级任务，机器人得运用把执行器移向桌上物体、捡起物体然后逐个将其从桌上移开的低级能力，同时在此过程中重新评估随之产生的动态场景。鉴于大型视觉语言模型（VLMs）在众多需要高级、类人推理的任务中已有所进展，我们不禁发问：倘若给模型传授必要的低级能力，它们能否以新颖的方式加以组合，从而完成像清理桌子这样有趣的高级任务，且无需明确教导？为此，我们推出了 ClevrSkills——一套用于机器人组合推理的基准套件。ClevrSkills 是基于 ManiSkill2 模拟器开发的环境套件及配套数据集。数据集中包含一系列机器人任务生成的轨迹，带有语言和视觉注释以及作为任务规范的多模态提示。该套件涵盖了具有三个组合理解层级的任务课程，从需要基本运动技能的简单任务起步。我们在 ClevrSkills 上对多个不同的 VLM 基线进行了测试，结果表明，即便这些模型在大量任务上做过预训练，在机器人任务的组合推理方面依然表现不佳。

> Robotics tasks are highly compositional by nature. For example, to perform a high-level task like cleaning the table a robot must employ low-level capabilities of moving the effectors to the objects on the table, pick them up and then move them off the table one-by-one, while re-evaluating the consequently dynamic scenario in the process. Given that large vision language models (VLMs) have shown progress on many tasks that require high level, human-like reasoning, we ask the question: if the models are taught the requisite low-level capabilities, can they compose them in novel ways to achieve interesting high-level tasks like cleaning the table without having to be explicitly taught so? To this end, we present ClevrSkills - a benchmark suite for compositional reasoning in robotics. ClevrSkills is an environment suite developed on top of the ManiSkill2 simulator and an accompanying dataset. The dataset contains trajectories generated on a range of robotics tasks with language and visual annotations as well as multi-modal prompts as task specification. The suite includes a curriculum of tasks with three levels of compositional understanding, starting with simple tasks requiring basic motor skills. We benchmark multiple different VLM baselines on ClevrSkills and show that even after being pre-trained on large numbers of tasks, these models fail on compositional reasoning in robotics tasks.

[Arxiv](https://arxiv.org/abs/2411.09052)