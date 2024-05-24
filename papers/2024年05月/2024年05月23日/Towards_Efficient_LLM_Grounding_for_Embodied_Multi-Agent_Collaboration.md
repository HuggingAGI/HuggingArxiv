# 构建高效的大型语言模型基础，促进具身多智能体协同合作

发布时间：2024年05月23日

`Agent

理由：这篇论文主要讨论了在多代理协作环境中，如何通过引入强化优势反馈（ReAd）来优化大型语言模型（LLMs）的规划能力。它关注的是如何通过代理间的通信和信用分配来调整计划，以实现有效的协调。这种方法涉及到了代理（Agent）的行为和交互，因此属于Agent分类。虽然论文中使用了LLM，但其重点在于代理间的协作和优化，而不是LLM的理论或应用本身。` `多代理系统`

> Towards Efficient LLM Grounding for Embodied Multi-Agent Collaboration

# 摘要

> 大型语言模型（LLMs）在实体任务中的推理能力应用面临物理世界复杂性的挑战。特别是在多代理协作中，LLM的规划需要通过代理间通信或信用分配进行反馈，以调整计划并实现有效协调。现有方法因过度依赖物理验证或自我反思，导致对LLMs的查询效率低下。本文提出了一种创新的多代理协作框架，引入了强化优势反馈（ReAd），以高效地自我优化计划。我们通过批评回归从LLM规划数据中学习序列优势函数，并将LLM规划器作为优化器，生成最大化优势函数的动作，赋予LLM预见能力，判断动作是否有助于任务完成。理论分析表明，我们扩展了强化学习中的优势加权回归到多代理系统。实验结果显示，ReAd在成功率上优于基线，并显著减少了代理交互和LLMs查询的次数，证明了其在实现LLMs基础上的高效性。更多详情请访问 \url{https://read-llm.github.io/}。

> Grounding the reasoning ability of large language models (LLMs) for embodied tasks is challenging due to the complexity of the physical world. Especially, LLM planning for multi-agent collaboration requires communication of agents or credit assignment as the feedback to re-adjust the proposed plans and achieve effective coordination. However, existing methods that overly rely on physical verification or self-reflection suffer from excessive and inefficient querying of LLMs. In this paper, we propose a novel framework for multi-agent collaboration that introduces Reinforced Advantage feedback (ReAd) for efficient self-refinement of plans. Specifically, we perform critic regression to learn a sequential advantage function from LLM-planned data, and then treat the LLM planner as an optimizer to generate actions that maximize the advantage function. It endows the LLM with the foresight to discern whether the action contributes to accomplishing the final task. We provide theoretical analysis by extending advantage-weighted regression in reinforcement learning to multi-agent systems. Experiments on Overcooked-AI and a difficult variant of RoCoBench show that ReAd surpasses baselines in success rate, and also significantly decreases the interaction steps of agents and query rounds of LLMs, demonstrating its high efficiency for grounding LLMs. More results are given at \url{https://read-llm.github.io/}.

[Arxiv](https://arxiv.org/abs/2405.14314)