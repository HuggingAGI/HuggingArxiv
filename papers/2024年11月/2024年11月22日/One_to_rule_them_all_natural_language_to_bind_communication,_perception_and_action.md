# 一个统御全局：用自然语言联结通信、感知与行动

发布时间：2024年11月22日

`LLM应用` `机器人` `人机交互`

> One to rule them all: natural language to bind communication, perception and action

# 摘要

> 近年来，人机交互领域的研究重点是开发能理解复杂人类指令，并在动态多元环境中执行任务的机器人。此类系统应用广泛，涵盖个人协助到工业机器人等领域，凸显了机器人与人类灵活、自然、安全交互的重要性。本文呈现了一种将通信、感知和规划与大型语言模型（LLMs）相融合的先进机器人动作规划架构。我们的系统旨在把自然语言表述的命令转化为可执行的机器人动作，融入环境信息，并依据实时反馈动态更新规划。规划器模块是系统核心，其中在改良的 ReAct 框架中嵌入的 LLMs 用于解读和执行用户命令。凭借其丰富的预训练知识，LLMs 能够高效处理用户请求，无需针对变化的环境引入新知识。改良的 ReAct 框架通过提供实时环境感知和物理动作的结果，进一步拓展了执行空间。通过将强大且动态的语义图表示（如图形）与控制组件及故障解释相结合，该架构提升了机器人在共享和动态环境中的适应性、任务执行能力以及与人类用户的无缝协作水平。借助与环境集成的连续反馈回路，系统能够动态调整规划以应对意外变化，优化机器人的任务执行能力。利用过往经验的数据集能够提供有关故障的详尽反馈，并为下一轮迭代更新 LLMs 上下文，给出如何克服问题的建议。

> In recent years, research in the area of human-robot interaction has focused on developing robots capable of understanding complex human instructions and performing tasks in dynamic and diverse environments. These systems have a wide range of applications, from personal assistance to industrial robotics, emphasizing the importance of robots interacting flexibly, naturally and safely with humans. This paper presents an advanced architecture for robotic action planning that integrates communication, perception, and planning with Large Language Models (LLMs). Our system is designed to translate commands expressed in natural language into executable robot actions, incorporating environmental information and dynamically updating plans based on real-time feedback. The Planner Module is the core of the system where LLMs embedded in a modified ReAct framework are employed to interpret and carry out user commands. By leveraging their extensive pre-trained knowledge, LLMs can effectively process user requests without the need to introduce new knowledge on the changing environment. The modified ReAct framework further enhances the execution space by providing real-time environmental perception and the outcomes of physical actions. By combining robust and dynamic semantic map representations as graphs with control components and failure explanations, this architecture enhances a robot adaptability, task execution, and seamless collaboration with human users in shared and dynamic environments. Through the integration of continuous feedback loops with the environment the system can dynamically adjusts the plan to accommodate unexpected changes, optimizing the robot ability to perform tasks. Using a dataset of previous experience is possible to provide detailed feedback about the failure. Updating the LLMs context of the next iteration with suggestion on how to overcame the issue.

[Arxiv](https://arxiv.org/abs/2411.15033)