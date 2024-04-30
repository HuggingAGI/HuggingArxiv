# 本文探讨了如何利用深度Q-学习技术，在计算信任机制中实现推/拉动作的动态切换。

发布时间：2024年04月28日

`Agent` `多智能体系统` `机器学习`

> Using Deep Q-Learning to Dynamically Toggle between Push/Pull Actions in Computational Trust Mechanisms

# 摘要

> 近期研究在开放多智能体系统的去中心化计算信任模型方面取得了进展，特别是开发了一种名为 CA 的生物启发模型，该模型从受托人的角度出发。这一新模型针对现有信任和声誉模型中的一个难题——如何处理智能体行为的不断变化以及智能体进出系统的连续性——提供了解决方案。在先前的研究中，我们对比了 CA 与另一个著名的信任和声誉模型 FIRE，并发现在信任者群体变动时，CA 的性能更佳，而 FIRE 在受托者群体变动时更具韧性。本论文进一步探讨了信任者如何识别环境中的多个动态因素，并据此选择最合适的信任模型以优化效用。我们将这一问题设定为部分可观测环境中的机器学习挑战，信任者无法预知多个动态因素的存在。文章描述了信任者如何利用一些可测量的特征来评估环境现状，并采用深度 Q 学习（DQN）在单智能体强化学习框架下学习如何适应环境变化。通过一系列模拟实验，我们比较了适应性信任者与仅使用单一模型（FIRE 或 CA）的信任者的性能，结果表明适应性智能体确实能够学习何时应用每种模型，从而在动态环境中实现稳定的表现。

> Recent work on decentralized computational trust models for open Multi Agent Systems has resulted in the development of CA, a biologically inspired model which focuses on the trustee's perspective. This new model addresses a serious unresolved problem in existing trust and reputation models, namely the inability to handle constantly changing behaviors and agents' continuous entry and exit from the system. In previous work, we compared CA to FIRE, a well-known trust and reputation model, and found that CA is superior when the trustor population changes, whereas FIRE is more resilient to the trustee population changes. Thus, in this paper, we investigate how the trustors can detect the presence of several dynamic factors in their environment and then decide which trust model to employ in order to maximize utility. We frame this problem as a machine learning problem in a partially observable environment, where the presence of several dynamic factors is not known to the trustor and we describe how an adaptable trustor can rely on a few measurable features so as to assess the current state of the environment and then use Deep Q Learning (DQN), in a single-agent Reinforcement Learning setting, to learn how to adapt to a changing environment. We ran a series of simulation experiments to compare the performance of the adaptable trustor with the performance of trustors using only one model (FIRE or CA) and we show that an adaptable agent is indeed capable of learning when to use each model and, thus, perform consistently in dynamic environments.

[Arxiv](https://arxiv.org/abs/2404.18296)