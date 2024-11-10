# CaPo：用于高效具身多智能体合作的协同计划优化

发布时间：2024年11月07日

`Agent` `智能体` `合作规划`

> CaPo: Cooperative Plan Optimization for Efficient Embodied Multi-Agent Cooperation

# 摘要

> 在这项工作中，我们解决了基于大型语言模型（LLM）的具身智能体之间的合作问题，在这种情况下，智能体必须合作以实现共同目标。以前的方法通常临时和不连贯地执行动作，没有长期的战略和合作规划，导致在像搜索和救援任务这样复杂的任务中出现冗余步骤、失败甚至严重的后果，在这些任务中讨论和合作计划至关重要。为了解决这个问题，我们提出了合作计划优化（CaPo）来提高基于 LLM 的具身智能体的合作效率。受人类合作方案的启发，CaPo 通过两个阶段提高合作效率：1）元计划生成，2）进展自适应元计划和执行。在第一阶段，所有智能体分析任务、进行讨论，并合作创建一个将任务分解为具有详细步骤的子任务的元计划，确保为有效协调制定长期的战略和连贯的计划。在第二阶段，智能体根据元计划执行任务，并根据其最新进展（例如，发现目标对象）通过多轮讨论动态调整。这种基于进展的适应消除了冗余动作，提高了智能体的整体合作效率。在 ThreeDworld 多智能体运输和交流观察与帮助任务上的实验结果表明，与最先进的技术相比，CaPo 实现了更高的任务完成率和效率。

> In this work, we address the cooperation problem among large language model (LLM) based embodied agents, where agents must cooperate to achieve a common goal. Previous methods often execute actions extemporaneously and incoherently, without long-term strategic and cooperative planning, leading to redundant steps, failures, and even serious repercussions in complex tasks like search-and-rescue missions where discussion and cooperative plan are crucial. To solve this issue, we propose Cooperative Plan Optimization (CaPo) to enhance the cooperation efficiency of LLM-based embodied agents. Inspired by human cooperation schemes, CaPo improves cooperation efficiency with two phases: 1) meta-plan generation, and 2) progress-adaptive meta-plan and execution. In the first phase, all agents analyze the task, discuss, and cooperatively create a meta-plan that decomposes the task into subtasks with detailed steps, ensuring a long-term strategic and coherent plan for efficient coordination. In the second phase, agents execute tasks according to the meta-plan and dynamically adjust it based on their latest progress (e.g., discovering a target object) through multi-turn discussions. This progress-based adaptation eliminates redundant actions, improving the overall cooperation efficiency of agents. Experimental results on the ThreeDworld Multi-Agent Transport and Communicative Watch-And-Help tasks demonstrate that CaPo achieves much higher task completion rate and efficiency compared with state-of-the-arts.

[Arxiv](https://arxiv.org/abs/2411.04679)