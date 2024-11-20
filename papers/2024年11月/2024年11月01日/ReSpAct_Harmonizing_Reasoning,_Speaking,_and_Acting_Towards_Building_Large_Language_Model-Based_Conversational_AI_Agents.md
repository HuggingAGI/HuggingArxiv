# ReSpAct：致力于协调推理、表达和行动，以构建基于大型语言模型的会话式 AI 代理

发布时间：2024年11月01日

`Agent` `智能交互` `任务决策`

> ReSpAct: Harmonizing Reasoning, Speaking, and Acting Towards Building Large Language Model-Based Conversational AI Agents

# 摘要

> 以大型语言模型（LLM）为基础的智能体，已被愈发广泛地用于与外部环境（如游戏、API 等）交互并完成任务。但当下的框架无法让这些智能体与用户协作并交互，从而在任务细节上达成一致并实现用户设定的目标；相反，在情况不明时，这些智能体可能会依据假设做出决策。本研究引入了 ReSpAct（推理、说话和行动）这一全新框架，它将构建面向任务的“对话式”智能体所需的关键技能进行了协同整合。ReSpAct 满足了智能体的这一需求，是对 ReAct 方法的拓展。ReSpAct 框架使得智能体能够解读用户指令、对复杂任务进行推理、执行恰当的行动，并参与动态对话以寻求指引、澄清模糊点、理解用户偏好、解决问题，还能利用用户的中间反馈和回应来更新自身计划。我们在支持用户交互的环境（如面向任务的对话 MultiWOZ 和交互式决策 AlfWorld、WebShop）中对 ReSpAct 进行了评估。ReSpAct 具有足够的灵活性，能够纳入动态的用户反馈，并解决诸如错误传播和智能体在推理循环中停滞等常见问题。这造就了比单纯依赖推理痕迹更具可解释性、更类人的任务解决路径。在两个交互式决策基准 AlfWorld 和 WebShop 中，ReSpAct 分别以 6％和 4％的绝对成功率优于强大的仅推理方法 ReAct。在面向任务的对话基准 MultiWOZ 中，ReSpAct 使 Inform 和 Success 分数分别提升了 5.5％和 3％。

> Large language model (LLM)-based agents have been increasingly used to interact with external environments (e.g., games, APIs, etc.) and solve tasks. However, current frameworks do not enable these agents to work with users and interact with them to align on the details of their tasks and reach user-defined goals; instead, in ambiguous situations, these agents may make decisions based on assumptions. This work introduces ReSpAct (Reason, Speak, and Act), a novel framework that synergistically combines the essential skills for building task-oriented "conversational" agents. ReSpAct addresses this need for agents, expanding on the ReAct approach. The ReSpAct framework enables agents to interpret user instructions, reason about complex tasks, execute appropriate actions, and engage in dynamic dialogue to seek guidance, clarify ambiguities, understand user preferences, resolve problems, and use the intermediate feedback and responses of users to update their plans. We evaluated ReSpAct in environments supporting user interaction, such as task-oriented dialogue (MultiWOZ) and interactive decision-making (AlfWorld, WebShop). ReSpAct is flexible enough to incorporate dynamic user feedback and addresses prevalent issues like error propagation and agents getting stuck in reasoning loops. This results in more interpretable, human-like task-solving trajectories than relying solely on reasoning traces. In two interactive decision-making benchmarks, AlfWorld and WebShop, ReSpAct outperform the strong reasoning-only method ReAct by an absolute success rate of 6% and 4%, respectively. In the task-oriented dialogue benchmark MultiWOZ, ReSpAct improved Inform and Success scores by 5.5% and 3%, respectively.

[Arxiv](https://arxiv.org/abs/2411.00927)