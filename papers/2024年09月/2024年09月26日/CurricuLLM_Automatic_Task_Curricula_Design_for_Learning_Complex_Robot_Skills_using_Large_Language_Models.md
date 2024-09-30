# CurricuLLM：借助大型语言模型，自动设计复杂机器人技能学习的任务课程。

发布时间：2024年09月26日

`Agent` `机器人`

> CurricuLLM: Automatic Task Curricula Design for Learning Complex Robot Skills using Large Language Models

# 摘要

> 课程学习通过逐步增加任务难度，帮助强化学习实现复杂策略。然而，设计有效课程需大量领域知识和人工干预，限制了其广泛应用。我们提出 CurricuLLM，利用大型语言模型的高级规划和编程能力，自动生成任务课程，提升复杂任务学习效率。CurricuLLM 分三步：生成子任务序列、翻译成可执行代码、评估策略。我们在多种机器人环境中验证其有效性，并展示了其在现实世界中的应用潜力。代码已开源，详见 https://github.com/labicon/CurricuLLM。

> Curriculum learning is a training mechanism in reinforcement learning (RL) that facilitates the achievement of complex policies by progressively increasing the task difficulty during training. However, designing effective curricula for a specific task often requires extensive domain knowledge and human intervention, which limits its applicability across various domains. Our core idea is that large language models (LLMs), with their extensive training on diverse language data and ability to encapsulate world knowledge, present significant potential for efficiently breaking down tasks and decomposing skills across various robotics environments. Additionally, the demonstrated success of LLMs in translating natural language into executable code for RL agents strengthens their role in generating task curricula. In this work, we propose CurricuLLM, which leverages the high-level planning and programming capabilities of LLMs for curriculum design, thereby enhancing the efficient learning of complex target tasks. CurricuLLM consists of: (Step 1) Generating sequence of subtasks that aid target task learning in natural language form, (Step 2) Translating natural language description of subtasks in executable task code, including the reward code and goal distribution code, and (Step 3) Evaluating trained policies based on trajectory rollout and subtask description. We evaluate CurricuLLM in various robotics simulation environments, ranging from manipulation, navigation, and locomotion, to show that CurricuLLM can aid learning complex robot control tasks. In addition, we validate humanoid locomotion policy learned through CurricuLLM in real-world. The code is provided in https://github.com/labicon/CurricuLLM

[Arxiv](https://arxiv.org/abs/2409.18382)