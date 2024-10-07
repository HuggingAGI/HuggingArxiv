# SELU：在未知环境中自主学习的多语言大型语言模型

发布时间：2024年10月04日

`Agent` `人工智能` `机器人`

> SELU: Self-Learning Embodied MLLMs in Unknown Environments

# 摘要

> 近期，多模态大型语言模型（MLLM）在视觉理解和决策方面表现出色，为在未知环境中自主提升 MLLM 能力提供了可能。然而，外部反馈如人类或环境反馈并非总能获取。现有方法多通过投票和评分机制提升 MLLM 的决策能力，但对提升其在未知环境中的环境理解能力关注较少。为充分挖掘 MLLM 的自学习潜力，我们提出了一种新颖的 actor-critic 自学习范式——SELU，灵感源自强化学习中的 actor-critic 范式。critic 通过自我提问和事后重新标记，从 actor 收集的交互轨迹中提取知识，增强环境理解；同时，actor 通过 critic 的自我反馈得到改进，提升决策能力。在 AI2-THOR 和 VirtualHome 环境中，SELU 通过自学习实现了 critic 约 28% 和 30% 的改进，actor 约 20% 和 24% 的改进。

> Recently, multimodal large language models (MLLMs) have demonstrated strong visual understanding and decision-making capabilities, enabling the exploration of autonomously improving MLLMs in unknown environments. However, external feedback like human or environmental feedback is not always available. To address this challenge, existing methods primarily focus on enhancing the decision-making capabilities of MLLMs through voting and scoring mechanisms, while little effort has been paid to improving the environmental comprehension of MLLMs in unknown environments. To fully unleash the self-learning potential of MLLMs, we propose a novel actor-critic self-learning paradigm, dubbed SELU, inspired by the actor-critic paradigm in reinforcement learning. The critic employs self-asking and hindsight relabeling to extract knowledge from interaction trajectories collected by the actor, thereby augmenting its environmental comprehension. Simultaneously, the actor is improved by the self-feedback provided by the critic, enhancing its decision-making. We evaluate our method in the AI2-THOR and VirtualHome environments, and SELU achieves critic improvements of approximately 28% and 30%, and actor improvements of about 20% and 24% via self-learning.

[Arxiv](https://arxiv.org/abs/2410.03303)