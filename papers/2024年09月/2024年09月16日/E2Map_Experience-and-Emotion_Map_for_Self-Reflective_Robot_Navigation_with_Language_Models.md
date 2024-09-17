# E2Map：结合语言模型的自我反思机器人导航系统，通过经验和情感地图实现导航。

发布时间：2024年09月16日

`Agent` `机器人` `人工智能`

> E2Map: Experience-and-Emotion Map for Self-Reflective Robot Navigation with Language Models

# 摘要

> 大型语言模型 (LLM) 在指导实体代理执行跨任务的语言指令方面展示了显著的潜力，包括机器人操作和导航。然而，现有方法主要设计用于静态环境，并未利用代理自身的经验来优化其初始计划。鉴于现实世界环境本质上是随机的，仅基于 LLM 的通用知识制定的初始计划可能无法实现其目标，这与静态场景不同。为了解决这一限制，本研究引入了经验与情感地图 (E2Map)，该地图不仅整合了 LLM 知识，还结合了代理的现实世界经验，灵感来自人类的情感反应。所提出的方法通过根据代理的经验更新 E2Map 来实现一次性行为调整。我们在包括模拟和真实世界场景在内的随机导航环境中进行的评估表明，与现有的基于 LLM 的方法相比，所提出的方法在随机环境中显著提高了性能。代码和补充材料可在 https://e2map.github.io/ 获取。

> Large language models (LLMs) have shown significant potential in guiding embodied agents to execute language instructions across a range of tasks, including robotic manipulation and navigation. However, existing methods are primarily designed for static environments and do not leverage the agent's own experiences to refine its initial plans. Given that real-world environments are inherently stochastic, initial plans based solely on LLMs' general knowledge may fail to achieve their objectives, unlike in static scenarios. To address this limitation, this study introduces the Experience-and-Emotion Map (E2Map), which integrates not only LLM knowledge but also the agent's real-world experiences, drawing inspiration from human emotional responses. The proposed methodology enables one-shot behavior adjustments by updating the E2Map based on the agent's experiences. Our evaluation in stochastic navigation environments, including both simulations and real-world scenarios, demonstrates that the proposed method significantly enhances performance in stochastic environments compared to existing LLM-based approaches. Code and supplementary materials are available at https://e2map.github.io/.

[Arxiv](https://arxiv.org/abs/2409.10027)