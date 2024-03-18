# 无尽的实体化机器人学习

发布时间：2024年03月01日

`Agent`

> Never-Ending Embodied Robot Learning

> 借助LLMs的力量，具身机器人能够在处理复杂的多模态操作任务时展现出强大的泛化能力，仅凭视觉输入就能完成任务。但当面对一连串未曾遭遇的高难度任务时，多数基于视觉的行为模仿系统会面临操作性能下滑和技能知识遗忘的困境。为此，我们借助创新的NBCagent——首个基于语言引导的永续行为克隆智能体，深入探讨这一问题。NBCagent能从特定及共享技能属性中不断习得新的机器人操作技能知识。具体而言，我们开发了一款专门针对技能的独特进化规划器，它能持续从潜在的低秩空间中提取并将新颖的特定技能知识融入到NBCagent中。此外，我们还提出了共享技能语义渲染模块与共享技能表征蒸馏模块，有效传输抗遗忘的共享技能知识，从语义表达和内在结构两方面有力应对旧技能的灾难性遗忘。最终，我们构建了一个持续具身机器人操作评估平台，并通过一系列详尽实验验证了我们方法的卓越效果。相关可视化结果、源代码和数据集已发布在：https://neragent.github.io。

> Relying on large language models (LLMs), embodied robots could perform complex multimodal robot manipulation tasks from visual observations with powerful generalization ability. However, most visual behavior-cloning agents suffer from manipulation performance degradation and skill knowledge forgetting when adapting into a series of challenging unseen tasks. We here investigate the above challenge with NBCagent in embodied robots, a pioneering language-conditioned Never-ending Behavior-Cloning agent, which can continually learn observation knowledge of novel robot manipulation skills from skill-specific and skill-shared attributes. Specifically, we establish a skill-specific evolving planner to perform knowledge decoupling, which can continually embed novel skill-specific knowledge in our NBCagent agent from latent and low-rank space. Meanwhile, we propose a skill-shared semantics rendering module and a skill-shared representation distillation module to effectively transfer anti-forgetting skill-shared knowledge, further tackling catastrophic forgetting on old skills from semantics and representation aspects. Finally, we design a continual embodied robot manipulation benchmark, and several expensive experiments demonstrate the significant performance of our method. Visual results, code, and dataset are provided at: https://neragent.github.io.

[Arxiv](https://arxiv.org/abs/2403.00336)