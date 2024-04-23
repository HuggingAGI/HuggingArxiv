# 动作情境化：通过大型语言模型实现任务规划与动作调整的智能适应。

发布时间：2024年04月19日

`Agent` `机器人技术` `任务规划`

> Action Contextualization: Adaptive Task Planning and Action Tuning using Large Language Models

# 摘要

> 大型语言模型（LLMs）以其丰富的人类知识库，为机器人任务规划开辟了新的前景。尽管如此，现有研究往往忽略了机器人系统在适应性和错误修正方面的重要性。本研究致力于解决这一问题，使机器人能够根据情境变化调整其运动策略，选择最佳的任务规划。我们提出了一个创新的框架——行动情境化，旨在精准匹配机器人动作与特定任务的需求，通过引入 LLM 提供的情境信息，提升机器人的适应性。我们设计的动态指标不仅确保了调整后运动的可行性和效率，而且通过评估机器人的表现，有效减少了规划中的重复工作。此外，该框架还支持机器人与 LLM 之间的即时在线反馈，允许对任务计划进行即时调整和错误修正。经过广泛的测试，我们的框架达到了 81.25% 的高成功率。最终，结合动态系统（DS）基础的机器人控制器，机器人臂手系统证明了其在自动执行 LLM 生成的连续桌面清理任务方面的专业能力，能够在无人干预的情况下纠正错误并完成任务，展现出对外部干扰的强大抵抗力。我们提出的框架有望与模块化控制方法相结合，显著提升机器人在执行连续任务时的适应性和自主性。

> Large Language Models (LLMs) present a promising frontier in robotic task planning by leveraging extensive human knowledge. Nevertheless, the current literature often overlooks the critical aspects of adaptability and error correction within robotic systems. This work aims to overcome this limitation by enabling robots to modify their motion strategies and select the most suitable task plans based on the context. We introduce a novel framework termed action contextualization, aimed at tailoring robot actions to the precise requirements of specific tasks, thereby enhancing adaptability through applying LLM-derived contextual insights. Our proposed motion metrics guarantee the feasibility and efficiency of adjusted motions, which evaluate robot performance and eliminate planning redundancies. Moreover, our framework supports online feedback between the robot and the LLM, enabling immediate modifications to the task plans and corrections of errors. Our framework has achieved an overall success rate of 81.25% through extensive validation. Finally, integrated with dynamic system (DS)-based robot controllers, the robotic arm-hand system demonstrates its proficiency in autonomously executing LLM-generated motion plans for sequential table-clearing tasks, rectifying errors without human intervention, and completing tasks, showcasing robustness against external disturbances. Our proposed framework features the potential to be integrated with modular control approaches, significantly enhancing robots' adaptability and autonomy in sequential task execution.

[Arxiv](https://arxiv.org/abs/2404.13191)