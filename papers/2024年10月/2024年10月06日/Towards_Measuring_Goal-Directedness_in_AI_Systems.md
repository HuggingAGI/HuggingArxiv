# 探索 AI 系统中目标导向性的测量方法

发布时间：2024年10月06日

`LLM理论` `人工智能`

> Towards Measuring Goal-Directedness in AI Systems

# 摘要

> 深度学习的进步让我们看到了超越人类的通用 AI 系统的可能性。然而，若这些系统追求非预期目标，后果不堪设想。AI 系统是否能连贯且目标导向地行动，优化未知目标，是关键问题。尽管已有大量研究评估此类行为，但现有最严格的目标导向性定义在现实中难以计算。我们借鉴前人研究，探索了强化学习环境中的策略目标导向性，提出了一组新的定义，分析策略是否对多种稀疏奖励函数接近最优。我们在简单的 MDP 环境中测试了这一概念，并探讨了如何在大型语言模型中测量目标导向性。我们的贡献是一个更简单、更易计算的目标导向性定义，有助于探讨 AI 系统是否可能追求危险目标。基于此，我们建议进一步研究如何测量连贯性和目标导向性。

> Recent advances in deep learning have brought attention to the possibility of creating advanced, general AI systems that outperform humans across many tasks. However, if these systems pursue unintended goals, there could be catastrophic consequences. A key prerequisite for AI systems pursuing unintended goals is whether they will behave in a coherent and goal-directed manner in the first place, optimizing for some unknown goal; there exists significant research trying to evaluate systems for said behaviors. However, the most rigorous definitions of goal-directedness we currently have are difficult to compute in real-world settings. Drawing upon this previous literature, we explore policy goal-directedness within reinforcement learning (RL) environments. In our findings, we propose a different family of definitions of the goal-directedness of a policy that analyze whether it is well-modeled as near-optimal for many (sparse) reward functions. We operationalize this preliminary definition of goal-directedness and test it in toy Markov decision process (MDP) environments. Furthermore, we explore how goal-directedness could be measured in frontier large-language models (LLMs). Our contribution is a definition of goal-directedness that is simpler and more easily computable in order to approach the question of whether AI systems could pursue dangerous goals. We recommend further exploration of measuring coherence and goal-directedness, based on our findings.

[Arxiv](https://arxiv.org/abs/2410.04683)