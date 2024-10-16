# LLM2Swarm：借助 LLM 实现智能推理、协同规划与合作的机器人集群

发布时间：2024年10月15日

`Agent` `机器人` `人工智能`

> LLM2Swarm: Robot Swarms that Responsively Reason, Plan, and Collaborate through LLMs

# 摘要

> 机器人集群由众多简单机器人组成，它们通过通信和协作完成复杂任务。传统上，机器人控制器需由专家逐个编程，耗时且易错，无法应对部署中的所有情况。而大型语言模型 (LLM) 则展示了推理和规划能力，为机器交互和编程带来新思路。为此，我们提出将 LLM 与机器人集群结合，以解决上述问题，并展示其潜力。我们探索了两种集成方法：一是“间接集成”，利用 LLM 合成和验证控制器，减少开发时间和错误；二是“直接集成”，每个机器人在本地运行 LLM 实例，实现自然语言的推理、规划和协作。为推动研究，我们发布了 LLM2Swarm 系统的软件和视频：https://github.com/Pold87/LLM2Swarm。

> Robot swarms are composed of many simple robots that communicate and collaborate to fulfill complex tasks. Robot controllers usually need to be specified by experts on a case-by-case basis via programming code. This process is time-consuming, prone to errors, and unable to take into account all situations that may be encountered during deployment. On the other hand, recent Large Language Models (LLMs) have demonstrated reasoning and planning capabilities, introduced new ways to interact with and program machines, and represent domain and commonsense knowledge. Hence, we propose to address the aforementioned challenges by integrating LLMs with robot swarms and show the potential in proofs of concept (showcases). For this integration, we explore two approaches. The first approach is 'indirect integration,' where LLMs are used to synthesize and validate the robot controllers. This approach may reduce development time and human error before deployment. Moreover, during deployment, it could be used for on-the-fly creation of new robot behaviors. The second approach is 'direct integration,' where each robot locally executes a separate LLM instance during deployment for robot-robot collaboration and human-swarm interaction. These local LLM instances enable each robot to reason, plan, and collaborate using natural language. To enable further research on our mainly conceptual contribution, we release the software and videos for our LLM2Swarm system: https://github.com/Pold87/LLM2Swarm.

[Arxiv](https://arxiv.org/abs/2410.11387)