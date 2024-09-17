# 借助大型语言模型，我们为包含人类指令与反馈的顺序操作规划生成行为树。

发布时间：2024年09月14日

`LLM应用` `机器人` `制造业`

> Behavior Tree Generation using Large Language Models for Sequential Manipulation Planning with Human Instructions and Feedback

# 摘要

> 我们提出了一种基于 LLM 的 BT 生成框架，旨在结合两者的优势进行顺序操作规划。该框架通过人类指令启动动作序列生成，并通过实时反馈优化 BT 生成，从而实现人机协作任务规划和非专家的直观机器人编程。所有方法均在一个真实的机器人装配示例中测试，使用西门子挑战赛的齿轮组模型。我们采用带有换工具机制的单臂操作器，以提高对多样物体的抓取稳定性。实验结果从成功率、逻辑一致性、可执行性、时间消耗和令牌消耗等方面进行了评估。据我们所知，这是首个由人类引导的 LLM 驱动的 BT 生成框架，整合了多种生成可执行 BT 的方法，并细致考虑了工具使用知识。

> In this work, we propose an LLM-based BT generation framework to leverage the strengths of both for sequential manipulation planning. To enable human-robot collaborative task planning and enhance intuitive robot programming by nonexperts, the framework takes human instructions to initiate the generation of action sequences and human feedback to refine BT generation in runtime. All presented methods within the framework are tested on a real robotic assembly example, which uses a gear set model from the Siemens Robot Assembly Challenge. We use a single manipulator with a tool-changing mechanism, a common practice in flexible manufacturing, to facilitate robust grasping of a large variety of objects. Experimental results are evaluated regarding success rate, logical coherence, executability, time consumption, and token consumption. To our knowledge, this is the first human-guided LLM-based BT generation framework that unifies various plausible ways of using LLMs to fully generate BTs that are executable on the real testbed and take into account granular knowledge of tool use.

[Arxiv](https://arxiv.org/abs/2409.09435)