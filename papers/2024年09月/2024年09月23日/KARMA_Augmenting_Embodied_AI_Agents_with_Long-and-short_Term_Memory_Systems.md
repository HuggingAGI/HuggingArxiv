# KARMA：为具身 AI 代理注入长期与短期记忆系统，提升其智能表现。

发布时间：2024年09月23日

`Agent` `机器人` `智能家居`

> KARMA: Augmenting Embodied AI Agents with Long-and-short Term Memory Systems

# 摘要

> 具身AI代理在执行长时间序列家庭任务时，常因上下文记忆问题导致效率低下和错误。为此，我们推出了KARMA，一种结合长期和短期记忆的创新系统，通过记忆增强提示提升大型语言模型（LLMs）在具身代理中的规划能力。KARMA的长期记忆捕捉3D场景图，短期记忆动态记录物体变化，双记忆结构使代理能检索过往经验，提升规划准确性和效率。短期记忆采用自适应替换策略，保留关键信息。与现有技术相比，KARMA在AI2-THOR模拟器中分别将复合和复杂任务的成功率提高了1.3倍和2.3倍，执行效率提升了3.4倍和62.7倍。KARMA的即插即用特性使其能无缝部署于现实机器人系统，如移动操作平台，显著提升代理生成连贯计划的能力，使家庭任务执行更高效。实验视频见https://youtu.be/4BT7fnw9ehs。

> Embodied AI agents responsible for executing interconnected, long-sequence household tasks often face difficulties with in-context memory, leading to inefficiencies and errors in task execution. To address this issue, we introduce KARMA, an innovative memory system that integrates long-term and short-term memory modules, enhancing large language models (LLMs) for planning in embodied agents through memory-augmented prompting. KARMA distinguishes between long-term and short-term memory, with long-term memory capturing comprehensive 3D scene graphs as representations of the environment, while short-term memory dynamically records changes in objects' positions and states. This dual-memory structure allows agents to retrieve relevant past scene experiences, thereby improving the accuracy and efficiency of task planning. Short-term memory employs strategies for effective and adaptive memory replacement, ensuring the retention of critical information while discarding less pertinent data. Compared to state-of-the-art embodied agents enhanced with memory, our memory-augmented embodied AI agent improves success rates by 1.3x and 2.3x in Composite Tasks and Complex Tasks within the AI2-THOR simulator, respectively, and enhances task execution efficiency by 3.4x and 62.7x. Furthermore, we demonstrate that KARMA's plug-and-play capability allows for seamless deployment on real-world robotic systems, such as mobile manipulation platforms.Through this plug-and-play memory system, KARMA significantly enhances the ability of embodied agents to generate coherent and contextually appropriate plans, making the execution of complex household tasks more efficient. The experimental videos from the work can be found at https://youtu.be/4BT7fnw9ehs.

[Arxiv](https://arxiv.org/abs/2409.14908)