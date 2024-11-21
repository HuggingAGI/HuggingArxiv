# : 通用机器人控制的视觉-语言-动作流模型

发布时间：2024年10月31日

`LLM应用` `机器人` `人工智能`

> : A Vision-Language-Action Flow Model for General Robot Control

# 摘要

> 机器人学习蕴含着巨大的希望，能够充分挖掘灵活、通用且灵巧的机器人系统的全部潜能，还能解决人工智能中的一些深层次问题。不过，要让机器人学习达到有效现实世界系统所要求的通用程度，在数据、泛化和鲁棒性方面遭遇了重大阻碍。在本文中，我们探讨了通用机器人策略（也就是机器人基础模型）怎样应对这些挑战，以及如何为复杂且高度灵巧的任务设计有效的通用机器人策略。我们构建了一种基于预训练视觉语言模型（VLM）的新型流匹配架构，以承袭互联网规模的语义知识。接着，我们论述了如何在来自多个灵巧机器人平台（涵盖单臂机器人、双臂机器人和移动操作器）的大规模多样化数据集中训练这个模型。我们从预训练后的零样本任务执行能力、遵循来自人类和高级 VLM 策略的语言指令的能力以及通过微调获取新技能的能力等方面对我们的模型进行了评估。我们的成果涵盖了诸如衣物折叠、桌面清理和盒子组装等各类任务。

> Robot learning holds tremendous promise to unlock the full potential of flexible, general, and dexterous robot systems, as well as to address some of the deepest questions in artificial intelligence. However, bringing robot learning to the level of generality required for effective real-world systems faces major obstacles in terms of data, generalization, and robustness. In this paper, we discuss how generalist robot policies (i.e., robot foundation models) can address these challenges, and how we can design effective generalist robot policies for complex and highly dexterous tasks. We propose a novel flow matching architecture built on top of a pre-trained vision-language model (VLM) to inherit Internet-scale semantic knowledge. We then discuss how this model can be trained on a large and diverse dataset from multiple dexterous robot platforms, including single-arm robots, dual-arm robots, and mobile manipulators. We evaluate our model in terms of its ability to perform tasks in zero shot after pre-training, follow language instructions from people and from a high-level VLM policy, and its ability to acquire new skills via fine-tuning. Our results cover a wide variety of tasks, such as laundry folding, table cleaning, and assembling boxes.

[Arxiv](https://arxiv.org/abs/2410.24164)