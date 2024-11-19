# 基于语义、几何和物理驱动，借助技能库和触觉表征实现机器人操作技能的转移

发布时间：2024年11月18日

`LLM应用` `机器人` `知识图谱`

> Semantic-Geometric-Physical-Driven Robot Manipulation Skill Transfer via Skill Library and Tactile Representation

# 摘要

> 在开放世界环境中部署机器人，其任务复杂，具有长序列和丰富交互的特点，因此需要在多样且复杂的场景中高效转移机器人技能。为应对此挑战，我们提出基于知识图谱的技能库框架，赋予机器人高级技能认知和空间语义理解能力。该框架通过构建“任务图”和“场景图”分别对操作知识进行分层组织，以表示任务和场景的语义信息。我们还引入“状态图”，促进高级任务规划与低级场景信息的交互。此外，我们提出了操作技能的分层转移框架。在任务层面，框架在四阶段提示范式中融合上下文学习和思维链提示，借助大型语言模型（LLMs）的推理与泛化能力，实现任务级子任务序列转移。在运动层面，利用 A*算法和技能库开发自适应轨迹转移方法，达成运动级自适应轨迹转移。在物理层面，我们引入基于触觉感知的自适应轮廓提取和姿态感知方法。此方法能从视觉触觉纹理数据动态获取高精度轮廓和姿态信息，并调整诸如接触位置和姿态等转移的技能，确保在新环境中的有效性。实验结果证实了所提方法的有效性。项目网站:https://github.com/MingchaoQi/skill_transfer

> Deploying robots in open-world environments involves complex tasks characterized by long sequences and rich interactions, necessitating efficient transfer of robotic skills across diverse and complex scenarios. To address this challenge, we propose a skill library framework based on knowledge graphs, which endows robots with high-level skill awareness and spatial semantic understanding. The framework hierarchically organizes operational knowledge by constructing a "task graph" and a "scene graph" to represent task and scene semantic information, respectively. We introduce a "state graph" to facilitate interaction between high-level task planning and low-level scene information. Furthermore, we propose a hierarchical transfer framework for operational skills. At the task level, the framework integrates contextual learning and chain-of-thought prompting within a four-stage prompt paradigm, leveraging large language models' (LLMs) reasoning and generalization capabilities to achieve task-level subtask sequence transfer. At the motion level, an adaptive trajectory transfer method is developed using the A* algorithm and the skill library, enabling motion-level adaptive trajectory transfer. At the physical level, we introduce an adaptive contour extraction and posture perception method based on tactile perception. This method dynamically obtains high-precision contour and posture information from visual-tactile texture data and adjusts transferred skills, such as contact positions and postures, to ensure effectiveness in new environments. Experimental results validate the effectiveness of the proposed methods. Project website:https://github.com/MingchaoQi/skill_transfer

[Arxiv](https://arxiv.org/abs/2411.11714)