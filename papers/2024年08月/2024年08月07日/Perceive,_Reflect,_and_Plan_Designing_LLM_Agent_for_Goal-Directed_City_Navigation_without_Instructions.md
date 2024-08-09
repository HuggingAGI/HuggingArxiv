# 设计一个能够感知、反思并规划的LLM代理，实现无需指令的目标导向城市导航。

发布时间：2024年08月07日

`Agent` `城市规划` `人工智能`

> Perceive, Reflect, and Plan: Designing LLM Agent for Goal-Directed City Navigation without Instructions

# 摘要

> 本文探讨了城市导航中的一项挑战：AI代理需根据目标位置相对于知名地标的语言描述，仅凭周围环境的观察来导航，无需任何指令。这一任务极具挑战性，因为它要求代理在复杂且地标常不可见的城市环境中，自我定位并构建空间认知。在缺乏导航指引的情况下，这些能力对代理在长距离导航中做出明智决策至关重要。尽管大型语言模型（LLMs）的推理能力为这一问题提供了新的解决思路，但直接应用这些模型作为基线效果不佳，代理常陷入重复访问同一地点和做出短视决策的困境。为此，本文提出了一种结合感知、反思和规划的新型代理工作流程。我们通过微调LLaVA-7B模型，使其能精确感知地标方向与距离，辅助城市导航。同时，通过记忆机制实现反思，整合过往经验与当前感知，优化决策过程。规划阶段则利用反思结果制定长期策略，避免短视行为。实验证明，这一设计显著提升了LLM代理的导航性能，超越了现有最佳基线。

> This paper considers a scenario in city navigation: an AI agent is provided with language descriptions of the goal location with respect to some well-known landmarks; By only observing the scene around, including recognizing landmarks and road network connections, the agent has to make decisions to navigate to the goal location without instructions. This problem is very challenging, because it requires agent to establish self-position and acquire spatial representation of complex urban environment, where landmarks are often invisible. In the absence of navigation instructions, such abilities are vital for the agent to make high-quality decisions in long-range city navigation. With the emergent reasoning ability of large language models (LLMs), a tempting baseline is to prompt LLMs to "react" on each observation and make decisions accordingly. However, this baseline has very poor performance that the agent often repeatedly visits same locations and make short-sighted, inconsistent decisions. To address these issues, this paper introduces a novel agentic workflow featured by its abilities to perceive, reflect and plan. Specifically, we find LLaVA-7B can be fine-tuned to perceive the direction and distance of landmarks with sufficient accuracy for city navigation. Moreover, reflection is achieved through a memory mechanism, where past experiences are stored and can be retrieved with current perception for effective decision argumentation. Planning uses reflection results to produce long-term plans, which can avoid short-sighted decisions in long-range navigation. We show the designed workflow significantly improves navigation ability of the LLM agent compared with the state-of-the-art baselines.

[Arxiv](https://arxiv.org/abs/2408.04168)