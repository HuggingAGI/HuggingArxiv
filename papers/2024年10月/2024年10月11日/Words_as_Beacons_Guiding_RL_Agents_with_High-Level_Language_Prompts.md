# 词语如灯塔，以高级语言提示引领强化学习代理前行。

发布时间：2024年10月11日

`Agent` `人工智能`

> Words as Beacons: Guiding RL Agents with High-Level Language Prompts

# 摘要

> 在强化学习中，稀疏奖励环境给探索带来了巨大挑战，常导致学习效率低下或不完整。为此，我们提出了一种师生 RL 框架，利用 LLM 作为“教师”，将复杂任务分解为子目标，指导代理学习。LLM 能基于文本描述理解环境，提供类似人类的子目标，包括位置目标、对象表示和语言指令。更重要的是，我们发现只需在训练阶段查询 LLM，代理即可在无 LLM 干预下操作。通过评估 Llama、DeepSeek 和 Qwen 在 MiniGrid 环境中的表现，实验结果显示，这种基于课程的方法显著加速了学习，复杂任务的探索效率提升了 30 到 200 倍，远超稀疏奖励环境的最新基线。

> Sparse reward environments in reinforcement learning (RL) pose significant challenges for exploration, often leading to inefficient or incomplete learning processes. To tackle this issue, this work proposes a teacher-student RL framework that leverages Large Language Models (LLMs) as "teachers" to guide the agent's learning process by decomposing complex tasks into subgoals. Due to their inherent capability to understand RL environments based on a textual description of structure and purpose, LLMs can provide subgoals to accomplish the task defined for the environment in a similar fashion to how a human would do. In doing so, three types of subgoals are proposed: positional targets relative to the agent, object representations, and language-based instructions generated directly by the LLM. More importantly, we show that it is possible to query the LLM only during the training phase, enabling agents to operate within the environment without any LLM intervention. We assess the performance of this proposed framework by evaluating three state-of-the-art open-source LLMs (Llama, DeepSeek, Qwen) eliciting subgoals across various procedurally generated environment of the MiniGrid benchmark. Experimental results demonstrate that this curriculum-based approach accelerates learning and enhances exploration in complex tasks, achieving up to 30 to 200 times faster convergence in training steps compared to recent baselines designed for sparse reward environments.

[Arxiv](https://arxiv.org/abs/2410.08632)