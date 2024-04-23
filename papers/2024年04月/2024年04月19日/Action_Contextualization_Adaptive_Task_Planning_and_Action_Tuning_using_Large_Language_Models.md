# 动作情境化：利用大型语言模型实现任务规划的智能适应与动作细节的精准调整。

发布时间：2024年04月19日

`Agent` `机器人技术` `任务规划`

> Action Contextualization: Adaptive Task Planning and Action Tuning using Large Language Models

# 摘要

> 大型语言模型（LLMs）利用丰富的人类知识，为机器人任务规划开辟了一片充满希望的新天地。尽管如此，现有研究往往忽略了机器人系统适应性和错误修正的重要性。本研究致力于解决这一问题，使机器人能够根据情境调整运动策略，从而选择最佳的任务规划。我们提出了一个创新的框架——动作情境化，它通过精确匹配特定任务的需求来定制机器人动作，利用LLM提供的情景洞察力，增强了机器人的适应性。我们设计的动态指标不仅确保了调整后运动的可行性和效率，而且通过评估机器人表现，有效减少了规划中的冗余。此外，该框架还支持机器人与LLM之间的即时在线反馈，允许对任务计划进行即时调整和错误修正。经过大量验证，我们的框架达到了81.25%的高成功率。最终，与基于动态系统的机器人控制器相结合，机器人臂手系统在执行LLM生成的连续桌面清理任务时表现出色，能够自主纠正错误，无需人工干预即可完成任务，显示出强大的抗干扰能力。我们提出的框架有望与模块化控制方法相结合，大幅提升机器人在执行连续任务时的适应性和自主性。

> Large Language Models (LLMs) present a promising frontier in robotic task planning by leveraging extensive human knowledge. Nevertheless, the current literature often overlooks the critical aspects of adaptability and error correction within robotic systems. This work aims to overcome this limitation by enabling robots to modify their motion strategies and select the most suitable task plans based on the context. We introduce a novel framework termed action contextualization, aimed at tailoring robot actions to the precise requirements of specific tasks, thereby enhancing adaptability through applying LLM-derived contextual insights. Our proposed motion metrics guarantee the feasibility and efficiency of adjusted motions, which evaluate robot performance and eliminate planning redundancies. Moreover, our framework supports online feedback between the robot and the LLM, enabling immediate modifications to the task plans and corrections of errors. Our framework has achieved an overall success rate of 81.25% through extensive validation. Finally, integrated with dynamic system (DS)-based robot controllers, the robotic arm-hand system demonstrates its proficiency in autonomously executing LLM-generated motion plans for sequential table-clearing tasks, rectifying errors without human intervention, and completing tasks, showcasing robustness against external disturbances. Our proposed framework features the potential to be integrated with modular control approaches, significantly enhancing robots' adaptability and autonomy in sequential task execution.

[Arxiv](https://arxiv.org/abs/2404.13191)