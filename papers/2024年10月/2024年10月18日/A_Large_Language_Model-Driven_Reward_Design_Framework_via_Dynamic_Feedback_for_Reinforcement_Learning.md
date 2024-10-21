# 基于动态反馈的强化学习奖励设计框架，由大型语言模型驱动

发布时间：2024年10月18日

`LLM应用` `人工智能`

> A Large Language Model-Driven Reward Design Framework via Dynamic Feedback for Reinforcement Learning

# 摘要

> 大型语言模型 (LLM) 在设计强化学习 (RL) 任务的奖励函数方面潜力巨大，但获取高质量奖励代码常需人工干预、多次 LLM 查询或重复 RL 训练。为此，我们提出 CARD，一个由 LLM 驱动的奖励设计框架，通过迭代生成和改进奖励函数代码。CARD 包含一个生成和验证代码的 Coder，以及一个提供动态反馈的 Evaluator，无需人工干预。此外，我们引入轨迹偏好评估 (TPE)，根据轨迹偏好评估当前奖励函数。若代码未通过 TPE，Evaluator 提供偏好反馈，避免每次迭代中的 RL 训练，使奖励函数更贴合任务目标。实证结果显示，CARD 在任务性能和令牌效率间取得有效平衡，优于或匹配所有任务的基线。在 12 个任务中的 10 个任务上，CARD 表现优于或可比于专家设计的奖励策略，甚至在 3 个任务上超越了 oracle。

> Large Language Models (LLMs) have shown significant potential in designing reward functions for Reinforcement Learning (RL) tasks. However, obtaining high-quality reward code often involves human intervention, numerous LLM queries, or repetitive RL training. To address these issues, we propose CARD, a LLM-driven Reward Design framework that iteratively generates and improves reward function code. Specifically, CARD includes a Coder that generates and verifies the code, while a Evaluator provides dynamic feedback to guide the Coder in improving the code, eliminating the need for human feedback. In addition to process feedback and trajectory feedback, we introduce Trajectory Preference Evaluation (TPE), which evaluates the current reward function based on trajectory preferences. If the code fails the TPE, the Evaluator provides preference feedback, avoiding RL training at every iteration and making the reward function better aligned with the task objective. Empirical results on Meta-World and ManiSkill2 demonstrate that our method achieves an effective balance between task performance and token efficiency, outperforming or matching the baselines across all tasks. On 10 out of 12 tasks, CARD shows better or comparable performance to policies trained with expert-designed rewards, and our method even surpasses the oracle on 3 tasks.

[Arxiv](https://arxiv.org/abs/2410.14660)