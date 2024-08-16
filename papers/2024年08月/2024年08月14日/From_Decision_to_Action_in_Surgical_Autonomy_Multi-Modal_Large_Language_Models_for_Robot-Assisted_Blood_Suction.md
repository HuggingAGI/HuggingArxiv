# 手术自主性：多模态大型语言模型助力机器人辅助抽血

发布时间：2024年08月14日

`Agent` `机器人`

> From Decision to Action in Surgical Autonomy: Multi-Modal Large Language Models for Robot-Assisted Blood Suction

# 摘要

> 大型语言模型 (LLM) 的兴起对机器人和自动化研究产生了深远影响。尽管 LLM 在通用机器人任务中的应用已取得进展，但在手术等特定领域，由于推理、可解释性和安全性等关键因素，其应用仍显不足。实现机器人手术的自主性，即具备推理和适应环境变化的能力，仍面临巨大挑战。本研究提出在机器人辅助手术中集成多模态 LLM 以实现自主吸血。高级任务规划 LLM 负责推理和优先级分配，而低级深度强化学习模型负责运动规划和执行，两者协同工作。考虑到手术的高度动态性和可能出现的不可预见情况，如血块和活动性出血，多模态 LLM 作为高级推理单元，能够应对这些复杂情况，实现以往机器人辅助手术中难以企及的推理水平。这些成果展示了多模态 LLM 在提升机器人辅助手术情境理解和决策能力方面的巨大潜力，为自主手术系统的发展迈出了重要一步。

> The rise of Large Language Models (LLMs) has impacted research in robotics and automation. While progress has been made in integrating LLMs into general robotics tasks, a noticeable void persists in their adoption in more specific domains such as surgery, where critical factors such as reasoning, explainability, and safety are paramount. Achieving autonomy in robotic surgery, which entails the ability to reason and adapt to changes in the environment, remains a significant challenge. In this work, we propose a multi-modal LLM integration in robot-assisted surgery for autonomous blood suction. The reasoning and prioritization are delegated to the higher-level task-planning LLM, and the motion planning and execution are handled by the lower-level deep reinforcement learning model, creating a distributed agency between the two components. As surgical operations are highly dynamic and may encounter unforeseen circumstances, blood clots and active bleeding were introduced to influence decision-making. Results showed that using a multi-modal LLM as a higher-level reasoning unit can account for these surgical complexities to achieve a level of reasoning previously unattainable in robot-assisted surgeries. These findings demonstrate the potential of multi-modal LLMs to significantly enhance contextual understanding and decision-making in robotic-assisted surgeries, marking a step toward autonomous surgical systems.

[Arxiv](https://arxiv.org/abs/2408.07806)