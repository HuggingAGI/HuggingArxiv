# 对于基于语言模型的软模块化机器人设计的探索

发布时间：2024年11月01日

`LLM应用` `机器人`

> On the Exploration of LM-Based Soft Modular Robot Design

# 摘要

> 近期的大型语言模型（LLMs）在对现实世界知识建模以及强化基于知识的生成任务方面，展现出了令人期待的能力。在本文里，我们进一步探究了借助 LLMs 辅助设计软模块机器人的可能性，将用户指令和物理定律都考虑在内，以降低对通常为达成满足特定结构或任务要求的机器人设计所必需的大量试错实验的依赖。具体来讲，我们把机器人设计流程设定为一个序列生成任务，发现 LLMs 能够抓取自然语言表述的关键需求，并在机器人的构建序列中予以体现。为了简便起见，我们没有开展真实世界的实验去评估设计质量，而是利用一个模拟工具给生成模型提供反馈，从而能够进行迭代改进，且无需大量人工标注。另外，我们引入了五个评估指标，从任务完成和遵循指令等多个角度评估机器人设计的质量，支持自动评估流程。我们的模型在设计具有单向和双向移动以及下楼梯能力的软模块机器人的评估中表现出色，凸显了运用自然语言和 LLMs 进行机器人设计的潜力。不过，我们也留意到了一些局限性，这指明了有待进一步改进的方向。

> Recent large language models (LLMs) have demonstrated promising capabilities in modeling real-world knowledge and enhancing knowledge-based generation tasks. In this paper, we further explore the potential of using LLMs to aid in the design of soft modular robots, taking into account both user instructions and physical laws, to reduce the reliance on extensive trial-and-error experiments typically needed to achieve robot designs that meet specific structural or task requirements. Specifically, we formulate the robot design process as a sequence generation task and find that LLMs are able to capture key requirements expressed in natural language and reflect them in the construction sequences of robots. To simplify, rather than conducting real-world experiments to assess design quality, we utilize a simulation tool to provide feedback to the generative model, allowing for iterative improvements without requiring extensive human annotations. Furthermore, we introduce five evaluation metrics to assess the quality of robot designs from multiple angles including task completion and adherence to instructions, supporting an automatic evaluation process. Our model performs well in evaluations for designing soft modular robots with uni- and bi-directional locomotion and stair-descending capabilities, highlighting the potential of using natural language and LLMs for robot design. However, we also observe certain limitations that suggest areas for further improvement.

[Arxiv](https://arxiv.org/abs/2411.00345)