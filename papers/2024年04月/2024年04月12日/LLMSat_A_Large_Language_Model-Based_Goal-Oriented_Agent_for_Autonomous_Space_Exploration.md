# LLMSat，一款基于大型语言模型的智能代理，专为自主太空探索任务而设计。

发布时间：2024年04月12日

`Agent` `人工智能`

> LLMSat: A Large Language Model-Based Goal-Oriented Agent for Autonomous Space Exploration

# 摘要

> 随着航天器远离地球，执行更为复杂的任务，我们迫切需要更高度的自主性和智能化的系统。为了加快对太阳系的探索步伐，减少对地面任务控制的依赖变得至关重要。近期研究已经开始探索基于人工智能的目标导向系统，以提升任务执行的自主化水平。这些系统通过符号推理管理器，结合手工构建的知识库，从航天器当前状态中进行推断，实现任务的自动生成与重新规划。尽管在特定条件下这些系统表现出色，但由于它们依赖于人工构建的本体模型，使得航天器能够理解外部世界，因此实施起来颇具挑战。强化学习已被用于训练机器人代理以达成特定目标，但为了进一步提升自主性，我们需要一种全新的架构。本研究探讨了将大型语言模型（LLMs）应用于航天器高级控制系统的可能性。通过系统工程的方法，本研究设计并开发了一种航天器控制器，该控制器利用LLM作为推理引擎，以评估这种架构在提升航天器自主性方面的潜力。通过在广受欢迎的游戏引擎Kerbal Space Program（KSP）中模拟一系列深空任务场景，作为案例研究，来评估该架构的实施效果。研究显示，尽管当前的LLMs在任务复杂度提升时推理和规划能力存在局限，但通过恰当的提示框架和策略性地选择代理对航天器的控制权限，可以显著改善这一问题。本研究进一步评估了LLMs在未来机器人太空探索中增强自主决策系统的潜力。

> As spacecraft journey further from Earth with more complex missions, systems of greater autonomy and onboard intelligence are called for. Reducing reliance on human-based mission control becomes increasingly critical if we are to increase our rate of solar-system-wide exploration. Recent work has explored AI-based goal-oriented systems to increase the level of autonomy in mission execution. These systems make use of symbolic reasoning managers to make inferences from the state of a spacecraft and a handcrafted knowledge base, enabling autonomous generation of tasks and re-planning. Such systems have proven to be successful in controlled cases, but they are difficult to implement as they require human-crafted ontological models to allow the spacecraft to understand the world. Reinforcement learning has been applied to train robotic agents to pursue a goal. A new architecture for autonomy is called for. This work explores the application of Large Language Models (LLMs) as the high-level control system of a spacecraft. Using a systems engineering approach, this work presents the design and development of an agentic spacecraft controller by leveraging an LLM as a reasoning engine, to evaluate the utility of such an architecture in achieving higher levels of spacecraft autonomy. A series of deep space mission scenarios simulated within the popular game engine Kerbal Space Program (KSP) are used as case studies to evaluate the implementation against the requirements. It is shown the reasoning and planning abilities of present-day LLMs do not scale well as the complexity of a mission increases, but this can be alleviated with adequate prompting frameworks and strategic selection of the agent's level of authority over the host spacecraft. This research evaluates the potential of LLMs in augmenting autonomous decision-making systems for future robotic space applications.

[Arxiv](https://arxiv.org/abs/2405.01392)