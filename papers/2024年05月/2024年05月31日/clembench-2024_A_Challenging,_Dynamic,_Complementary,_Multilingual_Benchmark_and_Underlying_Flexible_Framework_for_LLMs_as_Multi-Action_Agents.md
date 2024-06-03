# clembench-2024：一款挑战性十足、动态互补的多语言基准，其灵活的底层框架旨在将大型语言模型（LLMs）打造为高效的多动作代理。

发布时间：2024年05月31日

`Agent

这篇论文探讨了大型语言模型（LLMs）通过“自我对话”游戏进行自我评估的能力，并构建了一个框架来创建这样的游戏环境。这种方法不仅能够适应新的发展，避免数据污染，还能测试模型的多个维度，如提示语言对性能的影响。这种自我评估和交互系统的设计与开发，涉及到模型的自主行为和决策，因此属于Agent的范畴。Agent通常指的是能够自主执行任务、做出决策并与环境交互的实体，这里的大型语言模型通过自我对话游戏进行自我评估和性能测试，符合Agent的定义。` `人工智能` `模型评估`

> clembench-2024: A Challenging, Dynamic, Complementary, Multilingual Benchmark and Underlying Flexible Framework for LLMs as Multi-Action Agents

# 摘要

> 近期研究证实，大型语言模型（LLMs）能通过“自我对话”游戏自动评估其能力，如遵循指令、战略目标导向及语言理解。本文采用一框架构建此类游戏环境，并探讨其在多个评估维度上的实用性：它既能适应新发展，又避免数据污染；测试尚未饱和，人类表现远超模型；并适宜探究如提示语言对性能的影响等额外问题。我们相信，此方法为选择模型构建交互系统提供了坚实基础，并有望打造系统与模拟评估器的闭环开发环境。

> It has been established in recent work that Large Language Models (LLMs) can be prompted to "self-play" conversational games that probe certain capabilities (general instruction following, strategic goal orientation, language understanding abilities), where the resulting interactive game play can be automatically scored. In this paper, we take one of the proposed frameworks for setting up such game-play environments, and further test its usefulness as an evaluation instrument, along a number of dimensions: We show that it can easily keep up with new developments while avoiding data contamination, we show that the tests implemented within it are not yet saturated (human performance is substantially higher than that of even the best models), and we show that it lends itself to investigating additional questions, such as the impact of the prompting language on performance. We believe that the approach forms a good basis for making decisions on model choice for building applied interactive systems, and perhaps ultimately setting up a closed-loop development environment of system and simulated evaluator.

![clembench-2024：一款挑战性十足、动态互补的多语言基准，其灵活的底层框架旨在将大型语言模型（LLMs）打造为高效的多动作代理。](../../../paper_images/2405.20859/clemb_arena_bump.png)

![clembench-2024：一款挑战性十足、动态互补的多语言基准，其灵活的底层框架旨在将大型语言模型（LLMs）打造为高效的多动作代理。](../../../paper_images/2405.20859/clemb_helm_bump.png)

[Arxiv](https://arxiv.org/abs/2405.20859)