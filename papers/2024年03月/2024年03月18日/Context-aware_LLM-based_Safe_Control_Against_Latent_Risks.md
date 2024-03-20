# 针对隐性风险，本研究探讨了利用上下文感知的大型语言模型进行安全控制的方法。

发布时间：2024年03月18日

`Agent` `自主控制` `机器人技术`

> Context-aware LLM-based Safe Control Against Latent Risks

> 面对潜在风险时，自主控制系统完成复杂任务实属不易。为此，本文创新性地构建了一个融合LLMs、SGD与优化控制方法的整体框架。首先，该框架巧妙地将复杂任务拆解为多个包含情境信息和潜在风险考量的小型子任务链。随后，在第二阶段，通过LLMs与SGD协同运作的过程对这些子任务及其参数进行精细化调整——LLMs负责生成初步设想与失效原因分析，SGD则承担参数精密优化的任务。我们运用仿真案例，以机器人和车辆为例对该框架进行了验证，实验结果证明这个框架能够在充分考虑情境与潜在风险的前提下，有效调解并高效习得复杂行为模式。

> It is challenging for autonomous control systems to perform complex tasks in the presence of latent risks. Motivated by this challenge, this paper proposes an integrated framework that involves Large Language Models (LLMs), stochastic gradient descent (SGD), and optimization-based control. In the first phrase, the proposed framework breaks down complex tasks into a sequence of smaller subtasks, whose specifications account for contextual information and latent risks. In the second phase, these subtasks and their parameters are refined through a dual process involving LLMs and SGD. LLMs are used to generate rough guesses and failure explanations, and SGD is used to fine-tune parameters. The proposed framework is tested using simulated case studies of robots and vehicles. The experiments demonstrate that the proposed framework can mediate actions based on the context and latent risks and learn complex behaviors efficiently.

[Arxiv](https://arxiv.org/abs/2403.11863)